# Lambda in Go

## About

This lambda is written using the AWS native Go support. Go version 1.x

## Use

You will write your go code locally. For simple function like the http request in this repo, you can simply create your function with the AWS handler function in mind.

You will need to then compile and zip your code. You can then upload to the lambda.

Alternatively, you can install [SAMS](https://github.com/awslabs/serverless-application-model) and the AWS CLI on your local machine. Then upload back to AWS.