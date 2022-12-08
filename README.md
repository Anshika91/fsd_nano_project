# Lambda Gmail Sender
Lambda function that sends Gmail emails

## Setup
1. Create a `config.yml` file in the root folder
2. Copy & paste the content from `config.example.yml` to `config.yml`
3. Replace the values with your data

## Deploy
1. Setup credentials for AWS lambda: https://serverless.com/framework/docs/providers/aws/guide/credentials/
2. Run `serverless deploy`

## Usage

Request a POST method to the lambda's endpoint with the following JSON format:

```
{
  "subject": "My email",
  "text": "email content"
}
```
