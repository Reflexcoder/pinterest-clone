# Installing
## Create a new directory and initialize Git:

mkdir Pinterest-Clone
cd pinterest-clone
git init
## Clone the repository and install packages:

git pull https://github.com/Reflexcoder/pinterest-clone.git
npm install
## Run MongoDB locally with Docker:

In the root folder, run:

docker-compose up mongodb
Alternatively, you can get a connection string from MongoDB Atlas after setting up your own database.

Create .env file:



npm run dev


## Using Docker
If you have Docker installed and a .env file with the contents from above, then from the root directory:

## Build and run the images:

docker-compose up

Note: MONGOLAB_URI is already incorporated in the local Docker setup and is not needed in your .env file if fully running with Docker.

# Testing & Build
## Testing
npm test
npm run coverage
## Lint
npm run lint
## Compile TypeScript
npm run compileTS
## Build
npm run build_server && npm run build_client
## Run
npm start
## Built With
Node.js - JavaScript runtime
React - A JavaScript library for building user interfaces
MongoDB - Database
Express - Node.js web application framework
Material UI - A library of React UI components that implements Google's Material Design
OpenAI - AI-based image generation
...and more
## Authors
Mayur Pal



