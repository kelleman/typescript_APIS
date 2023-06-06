Click the link below for the API Documentation
API Documentation Link: https://documenter.getpostman.com/view/21753101/2s93sZ5YeR




# Build a REST API with Node.js, Mongoose & TypeScript
Note 2: Make sure you add .env to your .gitignore before pushing any changes to your repository. You will also want to generate new public & private keys

#### Generate new keys: https://travistidwell.com/jsencrypt/demo/

#### Base64 encode the keys: https://www.base64encode.org/



## What you will need
* A running instance of MongoDB
* Postman
* An IDE or text editor (VS Code)
* A web browser
* A package manager such as NPM or Yarn
* Node.js installed

## What next?
* Testing the API with Jest
* Build a React.js user interface
* Add Prometheus metrics to the API
* Deploy the API with Caddy & Docker
* Add Google OAuth

## Concepts
* REST API principals
    * CRUD
    * HTTP methods
* JWT & refresh tokens
* Request validation
## Technologies
* Node.js
* MongoDB with Mongoose
* TypeScript
* Express.js & Express.js middleware
* Zod validation

## API structure
1. Bootstrap application
   1. Setup express JS
   2. Create routes function
   3. Setup database connection
   4. Setup logger
   5. Validate request middleware
2. Registration
   1. Create user model
   2. Create user endpoint
   3. Create user session
   4. Deserialize user middleware (refresh tokens)
   5. Get sessions
   6. Delete session
   7. Require user middleware
3. Product resource
   1. Create product model
   2. Create product
   3. Read product
   4. Update product
   5. Delete product

# Deployment

## What will we use
* Docker (image)
* docker-compose (container)
* Caddy - Web server
* DigitalOcean
