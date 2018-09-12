# face-recognition-brain-api

 An API built to be used in conjunction with the [face-recognition-brain application](https://github.com/vtam2012/face-recognition-brain). This was a final project for the Udemy course (The Complete Web Developer in 2018: Zero to Mastery) taught by Andrei Neagoie (https://github.com/aneagoie)

## How to use:

1. Clone this repo
2. Run npm install
3. Run npm start

### Note:
You must add your own API key in the controllers/image.js file to connect to Clarifai API. (Replace 'process.env.API_CLARIFAI' with your own apiKey)

You can generate a Clarifai API key [here](https://www.clarifai.com/)

** Make sure you use postgreSQL instead of mySQL for this code base.
Furthermore, you must also configure the connection to your database in the
server.js file.
