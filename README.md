# electron-react-template
Template for desktop applications using Electron and React

## Getting Started

Clone this repo and install dependencies with the command `npm install`.

## Running the Project

### Run React Project Locally

To run the React part of the project locally to work on the UI, run the command `npm run start-react`. This will start the project on your local machine and you can access it through the browser at `localhost:3000`.

### Run Electron Project locally

To start your Electron app, run the command `npm run start-project`, which will in turn run two commands, one to build the React application and one to start your Electron app on your local desktop.

### Build Electron App for Deployment

To build the application for deployment, run the command `npm run build-project`, which will first build the react project so that it can be accessed from the Electron application, then it will build the Electron app so that it is ready for publishing/deployment.
