# Parcel Core App

## About

This app is configured to use postcss, posthtml, and react. It creates a local dev server that is meant to be a base for creating prototypes.

### Starting Locally

- `yarn`
- `yarn start`

### Starting Docker container

- From the base directory of the app
- `docker build -t core .`
- `docker run --name core -d -p 80:80 core`
