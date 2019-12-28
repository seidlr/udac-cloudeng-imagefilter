# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.
See the original repo here: https://github.com/udacity/cloud-developer/tree/master/course-02

## Tasks

### Setup Node Environment

1. [x] Initialize a new project: `npm i`
2. [x] run the development server with `npm run dev`

### Create a new endpoint in the server.ts file

- [x] Create new endpoint in `server.ts` file

### Deploying your system

- [x] Deployed image-filter service to elastic beanstalk

## Using the backend
You can test the micro-service by sending a GET request:
```
GET /filteredimage?image_url={{IMAGE_URL}}
```
I.e.
```
http://image-filter-project-seidlr-dev-dev.eu-central-1.elasticbeanstalk.com/filteredimage?image_url=https://www.opensourcecms.com/wp-content/uploads/wordpress-logo.png
```
should return a rescaled image.


