# Serverless Stripe Processor

Written by Eran Sandler (c) 2016  -  [@erans](https://twitter.com/erans)

Serverless Stripe processor is an AWS lamba based stripe payment processor.

Stripe requires that after you use get a token representing a credit card you need (in most cases) to send it to a server to perform the actual charge or create a subscription based on that.

The Serverless Stripe Processor (SSP) uses AWS Lamba to create an endpoint to which you can reference using Javascript to send the credit card token and process your payment without the need to configure servers, manage servers or anything else.

