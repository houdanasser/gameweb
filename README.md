# AwesomeTheSauce
Fan webpage for AwesomeTheSauce wiztuber

First, to start uploading files in repository from computer directly, have to create a readme file or something so github can take you to the page insider repository where you can upload the files (pull-request). the file can be deleted afterwards...but dont know why github does that mandatory step ...

When uploading on heroku, heroku is case sensitive (lower case) for images! also, use png images!

When deploying on heroku, make sure the PHP file is at the root of the repository, because heroku recognizes PHP not a folder as root.
this means since the app is being deployed on heroku directly from github, github must have the index file right at the root of the repository
NOT inside a folder!

To test PHP file locally, run Apache, and make sure w3svc service is stopped because PHP needs to use port 80/443:
"net stop w3svc"
once Apache starts, you can restart it "net start w3svc"

Also, every commit thats done here, if the heroku setting for automatic deployments is checked, this means every commit/edit here pushed/committed takes effects right away at the deployed webpage!
meaning no access is necessary to my heroku account, this repository can be updated to reflect new things on the webpage right from here!
