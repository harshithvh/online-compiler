# online-compiler
Application is an online compiling services for languages like Java , Haskell, Python.

## Java SpringBoot Microservices
* Microservices hosted on Kubernetes pods for scalability and fault tolerance.
* User code stored in GCP Bucket and User record saved in MYSQL database
* User has access to saved files
* Each compiler microservice compiles and sends response back to caller service with success or failure response.

## Kubernetes Cluster
* GKE cluster is used to deploy microservices
* Modified GKE auto pilot mode for starting a cluster on click of a button
* Front-end application deployed on an nginx webserver.
* Separate pods created for each microservice

## Architecture
![Screenshot 2023-11-14 174850](https://github.com/harshithvh/online-compiler/assets/91654378/027c0a86-8ba4-439b-9ddd-c2b199fc285f)


## Built With
* Google Cloud Platform
* Kubernetes
* Docker
* React


