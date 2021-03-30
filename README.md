# AWS-SNS-SMS with NodeJS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)

> Send SMS using AWS SNS and Node.js

This tutorial showcase how to send an SMS by using AWS SNS and Node.js

### Clone this repository

`git clone https://github.com/codecventer/AWS-SNS-SMS-Nodejs.git`

`$ cd aws-sns-sms-nodejs`

`$ npm install`

### Create a specific AWS IAM user and add to group 'AmazonSNSFullAccess'

Rename the `.env.example` file to `.env` and enter your correct AWS access key, secret and region.

`$ npm start`

Open browser and visit something like,

`http://localhost:3000/?message=[The Message]&number=[The Number]&subject=[The Subject]`

The mobile number should be E.164 format but without the + character.

### For example:

You want to send a message to a number

The country code is 27

The mobile number is 082 345 6789

The E.164 format would be +27823456789

Remove the '+' character

### Author: [Christiaan Venter](https://github.com/codecventer)
