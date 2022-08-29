# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

The project is split into three parts:
1. [The Simple Frontend](https://github.com/evans-manyala/cloud-dev/tree/master/course-02/exercises/udacity-c2-frontend) A basic Ionic client web application which consumes the RestAPI Backend.
2. [The RestAPI Backend](https://github.com/evans-manyala/cloud-dev/tree/master/course-02/exercises/udacity-c2-restapi), a Node-Express server which can be deployed to a cloud service.
3. [The Image Filtering Microservice](https://github.com/evans-manyala/cloud-dev/tree/master/course-02/project/image-filter-starter-code), An Image filter Application running in the cloud.

## Tasks

To perform the tasks below, go to the Github link =>> https://github.com/evans-manyala/cloud-dev/ and clone the project repo from here before your can begin to work with it.

### Setup Node Environment

You'll need to create a new node server. Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`

### Create a new endpoint in the server.ts file

The starter code has a task for you to complete an endpoint in `./src/server.ts` which uses query parameter to download an image from a public URL, filter the image, and return the result.

### Deploying your system

Follow the process described in the course to `eb init` a new application and `eb create` a new environment to deploy your image-filter service! Don't forget you can use `eb deploy` to push changes.


### Custom Domain Name

Add your own domain name and have it point to the running services (try adding a subdomain name to point to the processing server)
> !NOTE: Domain names are not included in AWS’ free tier and will incur a cost.

# Original Picture URL Unfiltered Image

https://unsplash.com/photos/g3esK1uXCjM

## Resulting Link Tom Filtered Image

http://image-filter-evans.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://images.unsplash.com/photo-1509610696553-9243c1e230f0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1500&q=80

