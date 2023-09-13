# BookNow Microservices

This repository contains the following microservices:

1. [Book Administrative Service](https://github.com/Athunlal/book-administrative-service.git)
2. [BookNow API Gateway](https://github.com/Athunlal/bookNow-Api-Gateway.git)
3. [BookNow Booking Service](https://github.com/Athunlal/bookNowBooking-svc.git)
4. [BookNow Account Services](https://github.com/Athunlal/bookNow-Account-Services.git)
5. [BookNow Authentication Service](https://github.com/Athunlal/bookNow-auth-svc.git)
6. [BookNow Train Service](https://github.com/Athunlal/bookNowTrain-svc.git)

Each microservice is located in its respective submodule. Click on the links above to explore each one.

This project is written purely in Go Language. Gin (Http Web Frame Work) is used in this project. PostgreSQL Database is used to manage the data.

## To Run this project 

1. Install docker and docker-compose
2. Clone this repository
3. Navigate to the Directory
4. Run Docker Compose
```
docker-compose up
```
5. Remove the containers
```
docker-compose down
```
### API Documentation
[https://documenter.getpostman.com/view/25078744/2s9YC4Vt95](https://documenter.getpostman.com/view/25078744/2s9YC4Vt95)

## API Specification
You can test the API's using Postman. Use this [postman collection](https://lunar-flare-491559.postman.co/workspace/Team-Workspace~d4586165-a6da-4d40-88d4-f70c842c21ce/request/25078744-4141e70d-7da3-4b3e-b973-fb75b509f751) to test the API's, all the documentation you needed is provided in the following.<br>
Below is the APIs used in the application and some examples along with it. 

## Get All submodules
1. To Initialize the submodules
```
git submodule init
```
2. To Fetch the submodule from the respective repo
```
git submodule update
```
1. To Fetch the updated version of the submodule
```
git submodule update --remote
```