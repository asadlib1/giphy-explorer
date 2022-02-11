# Giphy Explorer

With this giphy explorer you can see trending gifs and search for any desirable gifs present in giphy.
To leverage the data I am using GiphyAPI https://github.com/Giphy/GiphyAPI
Selecting a still gif image at home page will open a modal in which you can see various renditions of a gif, referred from https://developers.giphy.com/docs/api/schema/#image-object.

## Running application locally

Installing dependencies using:
`npm install`

Run app using: 
`npm start`
(app will start running at port 3001)

## Testing the project
You can use given commands for testing:

Updating snapshot:
`npm run test:update-snapshot`

Running unit tests:
`npm run test`

Running e2e tests:
- First run the app using:
`npm start`
- Then run end to end tests using:
`npm run e2e`

Unit tests and e2e tests have been added to cover most cases in different work flows of this app.

## Create Production build

`npm run build:prod`
This generates a dist folder which can be used for deployments on a web server.
