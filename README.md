#28DC

This sample provides an example of how to compile TypeScript files while
deploying to App Engine.

The `gcp-build` NPM script is used to trigger the TypeScript compilation
process. This step happens automatically when deploying to App Engine, but must
be performed manually when developing locally.

## Setup

Install dependencies:

   npm install

## Running locally

1. Perform the build step:

    npm run gcp-build

1. Run the completed program

    npm start

## Deploying to App Engine

Deploy your app:

    npm run deploy


