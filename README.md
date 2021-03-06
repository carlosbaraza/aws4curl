# aws4curl [![Build Status](https://travis-ci.org/carlosbaraza/aws4curl.svg?branch=master)](https://travis-ci.org/carlosbaraza/aws4curl)

curl, but with AWS Signature Version 4

# Installation

```
npm i -g aws4curl
```

# Usage

```
usage: aws4curl [aws4curl options] [curl options]

aws4curl options:
  --aws-region AWS Region to sign requests with (required)
  --aws-service AWS Service (required)

AWS Credentials:
Environment variables AWS_ACCESS_KEY and AWS_SECRET_KEY must be defined.
If AWS_SESSION_TOKEN is available, it will be used to generate the header
"X-Amz-Security-Token"

curl options:
  Every flag and argument will be passed to your installed curl
```

# Contributing

Thank you for checking this project out! The project is MIT licensed
and every contribution is welcomed.
