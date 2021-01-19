# sublog-architecture v2.0

[sublog](https://github.com/fijixxx/sublog) の環境構成図です。

![v2.0環境構成図](sublog-architecture-v2.05.png)

## レイヤー別技術スタック一覧

svg アイコンは https://svgporn.com/ よりお借りしました

### **FrontEnd**

<div>
 <img src="assets/typescript-icon.svg" width="80">
 <img src="assets/nextjs.svg" width="80">
 <img src="assets/graphql.svg" width="80">
 <img src="assets/apollostack.svg" width="80">
</div>
 <p>TypeScript/ Next.js/ GraphQL/ Apollo Client</p>

<div>
 <img src="assets/google-analytics.svg" width="80">
 <img src="assets/cloudinary.svg" width="80">
 <img src="assets/aws-s3.svg" width="80">
 <img src="assets/aws-cloudfront.svg" width="80">
 <img src="assets/aws-lambda.svg" width="80">
</div>
 <p>Google Analytics/ Cloudinary/ Amazon S3/ Amazon CloudFront/ Lambda@Edge</p>

### **API**

<div>
 <img src="assets/typescript-icon.svg" width="80">
 <img src="assets/graphql.svg" width="80">
 <img src="assets/apollostack.svg" width="80">
 <img src="assets/docker-icon.svg" width="80">
 <img src="assets/google-cloud-run.svg" width="80">
</div>
 <p>TypeScript/ GraphQL/ Apollo Server/ Docker/ Cloud Run</p>

### **Infra**

<div>
 <img src="assets/aws-dynamodb.svg" width="80">
 <img src="assets/aws-lambda.svg" width="80">
 <img src="assets/aws-sqs.svg" width="80">
 <img src="assets/aws-s3.svg" width="80">
</div>
<p>Amazon DynamoDB/ AWS Lambda/ Amazon SQS/ Amazon S3</p>

<div>
 <img src="assets/aws-route53.svg" width="80">
 <img src="assets/aws-cloudformation.svg" width="80">
 <img src="assets/github-icon.svg" width="80">
 <img src="assets/slack.svg" width="80">
</div>
<p>Amazon Route53/ AWS CloudFormation(AWS CDK)/ GitHub, GitHub Actions, GitHub Apps/ Slack</p>

<div>
 <img src="assets/typescript-icon.svg" width="80">
 <img src="assets/python.svg" width="80">
</div>
<p>TypeScript/ Python</p>
