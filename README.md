# React live-reload with Docker

This repo shows how to setup live-reloading for a React App (generated via create-react-app) using Docker and docker-compose and Volumes. 

## Running
Run `docker-compose up`. Any file changes will reload the React application which is accessible via [http://localhost:3000](http://localhost:3000) 


## Setup
You will need Docker installed. 

To use Volumes locally, you'll need to give Docker some permissions. To add your base directly to Docker:

- Open your Docker settings via the Docker GUI
- Navigate to "Resources" -> "File Sharing" 
- Add the directory or root directory of your code, e.g. `C:\repos`

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
