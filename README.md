Memories

mkdir memories 
cd memories 
mkdir client 
cd client 
npx npx create-react-app .
cd ../server 
touch index.js 
npm init -y 
npm install body-parser cross express mongoose nodemon
code ../.

body-parser : enable us to send post requests
cross : enable cross origin requests
express : for creating the routing of our application
mongoose : to create models for our posts 
nodemon : to do not manually reset the server every time we make a change