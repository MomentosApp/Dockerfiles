FROM google/cloud-sdk:slim
RUN curl -fsSL https://deb.nodesource.com/setup_18.x | bash - &&\
apt-get install -y nodejs &&\
npm install -g npm@latest &&\
npm install -g yarn
RUN apt-get install -y build-essential
LABEL org.opencontainers.image.source="https://github.com/MomentosApp/Dockerfiles/tree/main/npm-gcloud"
