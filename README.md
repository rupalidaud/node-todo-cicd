# node-todo-cicd

Run these commands:


`sudo apt install nodejs`


`sudo apt install npm`


`npm install`

`node app.js`



step 1 - fork node-todo-cicd repo
step 2 - open jenkins 
step 3 - create new freestyle job for node-todo-cicd app
step 4 - for configuration setting give describtion and give github URL
step 5 - click on execute Build step and execute code and save and apply
step 6 - click on Build now and project build successfully.
step 7 - Again go to the configuration part and click on the "GitHub hook trigger for GITScm polling" to set a job.
step 8 - After all that, just let GitHub know that it has to notify your Jenkins server every time there is a commit. To do this, go to GitHub repository > settings > Webhooks > Add webhook
step 9 - In Payload URL place the Jenkins server URL with this format
step 10 - Select the content type.
step 11 - Configure when GitHub should send events to this webhook
step 12 - Check the “Active” box.
step 13 - Done! The Jenkins server will build according to how you configured the GitHub webhook.
step 14 - In the Execute shell run the application using Docker compose
step 15 - Build the job and it execute successfully
step 16 - then run you aws Public IPv4 address and it run successfully.
