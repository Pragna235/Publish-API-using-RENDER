# Publishing our OWN API to cloud using RENDER

## Playbook

* Create an account and login to your account in `render.com`
* Select `Create a new web service`
* Copy the github `repository url` you want to deploy your `api` to, or connect an existing github repository.
* Fill the details of your API - name, branch, build command : default, start command : `node index` (index.js)
* This is because, we are just deploying an API
* IF we are deploying a frontend app or a full project, then
  - Build Command : `npm install`
  - Start Command : `npm start`

# Work In Progress...
