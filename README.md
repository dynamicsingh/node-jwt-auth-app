# node-jwt-authentication-app

Demonstrating authentication by verifying a token using Express route middleware.

## Requirements

- node, npm, express and mongoose

## Usage

1. Clone the repo
2. Install dependencies: `npm install`
3. Change SECRET in `config.js`
4. Add your own MongoDB database to `config.js`
5. Start the server: `node server.js`
6. Create sample user by visiting: `http://localhost:3000/setup`

Once everything is set up, we can begin to use our app by creating and verifying tokens.

### Getting a Token

Send a `POST` request to `http://localhost:3000/api/authenticate`. 

### Verifying a Token and Listing Users

You can also send the token as a URL parameter: `http://localhost:3000/api/users?token=YOUR_TOKEN_HERE`
