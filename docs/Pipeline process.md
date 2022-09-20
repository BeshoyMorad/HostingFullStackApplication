# Pipeline Process

## With the help of <code> Circle Ci </code> we can automate the building, testing and deploying phases for our application

<br>

## Steps

- Developer update the code localy [ add new feature, fix a bug, ...etc ]
- Push the changes to the github repo
- Circle Ci will trigger this changes and will start the pipeline
  - Install Node
  - Install AWS Elastic Beanstalk
  - Install AWS CLI
  - Install Front-End Dependencies
  - Lint Front-End
  - Install API Dependencies
  - Build Front-End
  - Build API
  - <code> Wait for the user's approval to deploy the application </code>
  - Update API code in Elastic Beanstalk ( Deploy The API )
  - Update Front-End code in S3 Bucket ( Deploy The Front-End )
