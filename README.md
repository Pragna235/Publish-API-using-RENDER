# Publishing our OWN API to cloud using RENDER

## Playbook

* Create an account and login to your account in `render.com`
* Select `Create a new web service`
* Copy the github `repository url` you want to deploy your `api` to, or connect an existing github repository.
* Fill the details of your API - name, branch, build command : default, start command : `node index` (index.js)
* This is because, we are just deploying an API
* If we are deploying a frontend app or a full project, then
  - Build Command : `npm install`
  - Start Command : `npm start`
* Click on Create Web Service
* After the deployment, Click on the url obtained.

## API URL - https://publish-api-using-render-2.onrender.com/api/users

## Live Project Page - https://pragna235.github.io/Publish-API-using-RENDER/

* Open this link in the browser and add an extension `/api/users` to get the users data.
* `/api/users/2` or give any id used in place of 2 to get the particular id details.
* Your api is successfully deployed in `render.com`

* Go to `POSTMAN` and test your api.

## API_URL - https://publish-api-using-render.onrender.com
## API_URL - https://publish-api-using-render.onrender.com/api/users/table  (index2.js)



