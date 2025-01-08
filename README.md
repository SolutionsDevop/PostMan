## POSTMAN

Post man is a tool used to test APIs by generating custom HTTP requests. Think of it as an advance curl.

It has a lot of features to help simplify the process of testing APIs

- Basics of Postman
- Setting up API Demo
- Authentication in API
- Variables
- Scripts
- JWT tokens in Postman
- Environment Set-up
- https://aws.amazon.com/verification (216e0cc4f594418989aed8d99a25dabb)

# Other tools used to test API
    - CURL
    - 

## Steps for start the API

    - Install nodejs if you don't have it installed, i was using ubuntu 22-04 (https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-22-04)

    - Install npm in the project directory to download the dependencies "npm install"
    - run "node API1/index.js
    - You should see the listen on port 4000
    - You can also check using "curl localhost:4000" on your CLI. Make sure you leave the request running

## COLLECTION
- Collection is a group of requests. 
- For one specific API we can create a collectioN for it
- This will contain all the requests that we would use to test that API
