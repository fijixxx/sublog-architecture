# sublog-architecture v2.0

[sublog](https://github.com/fijixxx/sublog) の環境構成図です。

![v2.0環境構成図](sublog-architecture-v2.01.svg)

## レイヤー別技術スタック一覧

### **FrontEnd**

<div>
 <img src="assets/typescript-icon.svg" style="max-width: 120px;"> <img src="assets/nextjs.svg" style="max-width: 120px;"> <img src="assets/graphql.svg" style="max-width: 120px;"> <img src="assets/apollostack.svg" style="max-width: 120px;">
   <p>TypeScript/ Next.js/ GraphQL/ Apollo Client</p>
</div>
<div>
 <img src="assets/google-analytics.svg" style="max-width: 120px;"> <img src="assets/aws-s3.svg" style="max-width: 120px;"> <img src="assets/aws-cloudfront.svg" style="max-width: 120px;"> <img src="assets/aws-lambda.svg" style="max-width: 120px;">
   <p>Google Analytics/ Amazon S3/ Amazon CloudFront/ Lambda@Edge</p>
</div>

### **API**

<div>
 <img src="assets/typescript-icon.svg" style="max-width: 120px;"> <img src="assets/graphql.svg" style="max-width: 120px;"> <img src="assets/apollostack.svg" style="max-width: 120px;"> <img src="assets/docker-icon.svg" style="max-width: 120px;"> <img src="assets/google-cloud-run.svg" style="max-width: 120px;">
   <p>TypeScript/ GraphQL/ Apollo Server/ Docker/ Cloud Run</p>
</div>

### **Infra**

<div>
 <img src="assets/aws-dynamodb.svg" style="max-width: 120px;"> <img src="assets/aws-lambda.svg" style="max-width: 120px;"> <img src="assets/aws-sqs.svg" style="max-width: 120px;"> <img src="assets/aws-s3.svg" style="max-width: 120px;">
   <p>Amazon DynamoDB/ AWS Lambda/ Amazon SQS/ Amazon S3</p>
</div>

<div>
 <img src="assets/aws-route53.svg" style="max-width: 120px;"> <img src="assets/AWS-Cloud-Development-Kit.svg" style="max-width: 120px;"> <img src="assets/github-icon.svg" style="max-width: 120px;"> <img src="assets/discord.svg" style="max-width: 120px;">
   <p>Amazon Route53/ AWS CDK/ GitHub, GitHub Actions, GitHub Apps)/ Discord</p>
</div>

<div>
 <img src="assets/typescript-icon.svg" style="max-width: 120px;"> <img src="assets/python.svg" style="max-width: 120px;">
   <p>TypeScript/ Python</p>
</div>
