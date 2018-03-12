Requirements
Configuration
make a copy of a previous backend project (not sluggram) that uses authorization in the /lab-<yourname>/something-backend directory
make a copy of a previous frontend project (not sluggram) in the /lab-<yourname>/something-frontend directory
Feature Tasks
backend
create an app on the google dev console
configure oauth credentials to support a client app on http://localhost
configure oauth credentials to support a server redirect uri to http://localhost:3000/oauth/google/code
create a backend route GET /oauth/google/code for handling google oauth
frontend
create an index.html with an anchor tag pointing to the google authorization page
configure the query string with correct key value pairs
Documentation
Write a description of the project in your README.md, including detailed instructions for how to build your app. In your frontend README.md add a code block with your frontend .env vars, and in your backend README.md add a code block with your backend .env vars.

env:

PORT=3000
API_URL=http://localhost:3000
CLIENT_URL=http://localhost:3000
GOOGLE_OAUTH_ID=897059426867-g7r7vph68ov2n6kevt88ccdbpb7lkdqa.apps.googleusercontent.com
GOOGLE_OAUTH_SECRET=4pX2fgMsIxA0EwZVwkCSwk5p

