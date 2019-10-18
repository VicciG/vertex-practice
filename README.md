## Setup

In terminal run:

java -jar target/my-first-app-1.0-SNAPSHOT-fat.jar

## Postman

get all: 

request = GET http://localhost:8080/api/whiskies

delete by id: 

request = DELETE http://localhost:8080/api/whiskies/<whisky-id> 
where whisky-id is a whisky id (e.g. 1)

add: 

request = POST http://localhost:8080/api/whiskies/
body =  {
            "name": "whisky name",
            "origin": "whisky origin"
        }
            
## Web

View GUI version 
URL: http://localhost:8080/assets/
