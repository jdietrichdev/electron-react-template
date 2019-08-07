# electron-react-template
Template for desktop applications using Electron and React

## Getting Started

Clone this repo and install dependencies with the command `npm install`.

## Running the Project

### Run React Project Locally

To run the React part of the project locally to work on the UI, run the command `npm run-script start-react`. This will start the project on your local machine and you can access it through the browser at `localhost:3000`.

### Run Electron Project locally

To start your Electron app, run the command `npm run-script start-project`, which will in turn run two commands, one to build the React application and one to start your Electron app on your local desktop.

### Build Electron App for Deployment

To build the project, you must first install `electron-forge` to help with packaging and building the final product. To do this, run `npm install -g @electron-forge/cli`. Once this has completed, you can run the command `npm run-script build-project`. This will build a final verion of your product and place it in the `out/` directory of your project.
