# baseApp
To run the app you will need to have npm installed.

Step by step guide on how to run the app:

Create a directory:
mkdir basicApp

Put application files in that directory

go to directory folder:

cd basicApp

run:
npm init

npm install @inrupt/solid-client @inrupt/solid-client-authn-browser @inrupt/vocab-common-rd

npm install parcel-bundler

Start the application. (You can pass the port as a parameter, e.g : -p 1111, if no parameter is passed port 1234 will be used)
npx parcel index.html

go to http://localhost:1234/ or http://localhost:{the port that you chose} to see the application in work.
