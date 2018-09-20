# What is it for?
Its a full fledge mocked api proxy service, that allow intercept of all available apis used by the application and produce fresh mock and store into json file to load as the service is activated.

# Prodution Stages

## basic setup
1. basic nodejs api service setup
0. 1 end point - get
0. 1 set of mock
0. mock generator service manual triggered
1. endpoint instruction file
0. basic deploy

## scaling up - expand end points
1. end point - post
2. end ponit - with login header
3. end point mapper service
3. mock generator scheduler service

## stablize
1. create unit tests for existing services

