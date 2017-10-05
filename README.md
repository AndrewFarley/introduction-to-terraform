# Introduction to Terraform
This introduces terraform to people unfamiliar with it and its concepts.

## Author
Created by Farley  <br>
<farley@olindata.com> <farley@neonsurge.com>

## Presentation / Slides
Please view the slides / presentation in the [Intro To Terraform](Intro_to_Terraform.pdf)

## What this sample/demo does
All it does is creates a S3 bucket, and uploads an index file to it

## How-to
Simply run `terraform apply` and it'll do the magic, then visit the URL that it generates to see it work!  If this fails, you probably don't have an AWS CLI profile setup.  You'll probably need to do that first.  Please see: [Setup your AWS CLI credentials or profile](https://serverless.com/framework/docs/providers/aws/guide/credentials/)

## Remove
S3 won't cost you anything, but when you're done you should `serverless remove` so it deletes that S3 bucket.