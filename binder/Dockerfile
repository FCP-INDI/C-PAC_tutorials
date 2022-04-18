FROM python:3.9-slim

COPY . .

# install the notebook package & Docker and local requirements
RUN pip install --no-cache --upgrade pip && \
    pip install --no-cache notebook jupyterlab && \
    apt-get update && \
    apt-get install \
      apt-utils \
      ca-certificates \
      curl \
      gcc \
      git \
      gnupg \
      libfreetype6-dev \
      lsb-release \
      pkg-config -y && \
    pip install -r ./requirements.txt && \
    python -m bash_kernel.install && \
    curl -fsSL https://download.docker.com/linux/debian/gpg | gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg && \
    echo \
      "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/debian \
      $(lsb_release -cs) stable" | tee /etc/apt/sources.list.d/docker.list > /dev/null && \
    apt-get update && \
    apt-get install docker-ce docker-ce-cli containerd.io -y

# create user with a home directory
ARG NB_USER
ARG NB_UID
ENV USER ${NB_USER}
ENV HOME /home/${NB_USER}

RUN adduser --disabled-password \
    --gecos "Default user" \
    --uid ${NB_UID} \
    ${NB_USER}
WORKDIR ${HOME}
USER ${USER}
