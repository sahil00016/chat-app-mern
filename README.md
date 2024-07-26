# Snappy - A Chat Application  
Snappy is chat application build with MERN Stack and a special javascript library SOCKET.IO

## Installation Guide to run and test the functionality of the project

### Requirements
- [Nodejs]
- [Mongodb]

Both should be installed and make sure mongodb is running.

#### step 1
```shell
git clone https:
```
#### step 2
rename env files from .env.example to .env


#### step 3
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

#### step 4
install the dependencies

#### step 5
```shell
cd server
yarn
cd ..
cd public
yarn
```
#### step 6
start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also we have to make sure mongodb is running in background.
```shell
cd server
yarn start
```
Done! Now open localhost:3000 in your browser.

