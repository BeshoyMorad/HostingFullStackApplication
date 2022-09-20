# Infrastructure Description

## Diagram

[Infrastructure Diagram](https://github.com/BeshoyMorad/HostingFullStackApplication/blob/main/diagrams/infrastructure.png)

<br>

# AWS Services

## 1- AWS RDS

- Used to host the postgres database
- Save or return the data given or needed by the API

## 2- AWS Elastic Beanstalk

- Used to host the node application ( API )
- Take requests from the frontend application and deal with it
- Can communicate with the database to retrieve the data
- Response with the proper data and status code to the frontend application

## 3- AWS S3 Bucket

- Used to host the frontend application
- The website that the user will interact with
- Will be used to send requests to the API and getting response back

<br>

# Circle Ci

- Used with the Github repo to trigger any change in the main branch
- After any change in the repo it will start a workflow shown in [Pipeline process](https://github.com/BeshoyMorad/HostingFullStackApplication/blob/main/docs/Pipeline%20process.md)
- Main usage for it is building, testing, and deploying the project using automation.
