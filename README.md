# Vanity-Number-Generator-AWS-Connect
Generate top vanity numbers based on user phone number

- [Overview](#overview)
- [Documentations](RUNPYTHONAPP.md)
- [CloudFormation Instructions](CLOUDFORMATION.md)
- [Contact Flow Instructions](CONTACTFLOW.md)
- [Managing The Project (Trello Board)](https://trello.com/b/MtaGkEdG/voicefoundry-code-challenge)
- [Blockers (Trello Board)](https://trello.com/b/MtaGkEdG/voicefoundry-code-challenge)

## Overview:
Implementation of mid-level assignment on vanity number generator.

### To test:
Call: +441143921064

### Checklist:
- Git Repo with all code and documentation
- Working Amazon Connect phone number to test in your environment :-)
- Create a Lambda that converts phone numbers to vanity numbers and save the best 5 resulting vanity numbers and the caller's number in a DynamoDB table.
- Create an Amazon Connect contact flow that looks at the caller's phone number and says the 3 vanity possibilities that come back from the Lambda function.
- Build a deployment package to deploy your solution into reviewers own AWS Account/Amazon Connect instance.
- A web app that displays the vanity numbers from the last 5 callers.
- Documentation
- Architecture diagram.

#### Tech Stack
- AWS Lambda
- AWS DynamoDB
- AWS Connect
- AWS Amplify
- API Gateway
- SQS
- SNS
- Python (for the lambda function)
- NLTK

