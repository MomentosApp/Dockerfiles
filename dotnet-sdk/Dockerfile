FROM mcr.microsoft.com/dotnet/sdk:7.0
RUN curl -fsSL https://deb.nodesource.com/setup_18.x | bash - &&\
apt-get install -y nodejs &&\
npm install -g npm@latest &&\
npm install -g yarn
RUN apt-get install -y build-essential
RUN npm install -g nx@latest
LABEL org.opencontainers.image.source="https://github.com/MomentosApp/Dockerfiles/tree/main/dotnet-sdk"
