#### Three main services : client , server(api) , worker

- Build a `Dockerfile.dev` for each app services in their related folders
- Run command `docker build -f Dockerfile.dev .`

#### Two dbs : redis & postgres

- latest versions from docker hub

#### environment variables

#### nginx

- build default.conf file
- include in dockerfile

#### Put together all in docker-compose
- Run command `docker-compose up --build`
- you might need to re-run to make sure db connection is built
- websocket should be open for dev env

#### Build .travis.yml for pipeline

#### Build Dockerrun.aws.json for pipeline
