#Install newman

npm install -g newman

#Run tests collection with this command 

newman run TestingAPI_reqres.json

#For installing html report 

npm install -g newman-reporter-htmlextra

#Run with html report

newman run TestingAPI_reqres.json -r htmlextra