Fake API for testing

Install JSON Server

npm install -g json-server Create a db.json file with some data

{ "notification": [ { "status": "0", "id": 1 } ] }

Start JSON Server

json-server --watch db.json Now if you go to http://localhost:3000/lookbook you see the data

https://my-json-server.typicode.com/vinhx3/TestAPI for use of online fake API