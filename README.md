## Running

You'll need to install Docker and Docker compose to be able to spin up the DBs instances, after that run:
- docker-compose up -d
- npm ci
- npm run seed
- npm start

## Errors?

In case you got an error of too many processes open, try decreasing the const [CLUSTER_SIZE] variable
