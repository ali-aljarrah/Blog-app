# Blog app

This Blog app is a simple mobile blog using react native with json server as a backend

To run this app first you need to run the command 
`npm run db` 
inside the jsonserver folder and then you need to make an ngrok url to make the app connect with the back end.
So with another terminal inside the json server folder run the command:
`npm run tunnel`

After that you need to cope the url that ngrok make and paste it inside "Blog/src/api/jsonServer.js".

Then with a new terminal run the following command to run the react native app inside the Blog folder:
`npm start`
