# docker-grokdebug
The lovely grokdebug tool (https://grokdebug.herokuapp.com) in a Docker container.

Since the original location for the application seems heavy loaded, why not bring up your own instead? It does of course have some other advantages as well running your own container as the grok patterns are executed on the server.

Big thanks to Nick Ethier (nickethier) and others for the original work.

How to build:

docker-compose build
or
docker build . -t <your preferred tag>

How to start:

docker-compose up -d

or

docker run -d lunderhage/grokdebug
