# NodeJS/Express Quickstart with Codeship Pro
[ ![Codeship Status for whiteotter/nodejs-express-quickstart](https://app.codeship.com/projects/2b8b3710-bc87-0135-8951-068e83625706/status?branch=master)](https://app.codeship.com/projects/259548)

[NodeJS/Express Backend Todo app](http://todobackend.com/) configured for testing on [Codeship Pro](https://codeship.com/features/pro)

## Local Setup
- Boot up app on local machine with [Docker Compose](https://docs.docker.com/compose/gettingstarted/) -- `docker-compose up`
- Run a Codeship Pro build on your local machine with our [CLI tool](https://documentation.codeship.com/pro/builds-and-configuration/cli/) -- `jet steps`

## SCM Setup
- Initialize as a new git repo -- `rm -rf .git && git init && git add . && git commit -m 'first commit'`
- Create new repository on your SCM of choice (Github, Gitlab, Bitbucket) and push commit

## CI/CD Setup
- Sign up for a [free Codeship Pro account](https://codeship.com/features/pro)
- Once signed in, follow prompts to set up a Codeship Pro project
- Commit a change to your repo and watch as a Codeship Pro build is triggered!
