# [![AWS CDK Examples Banner](./icons/github-title-banner.png)](https://towardsthecloud.com)

# AWS CDK Examples

A collection of AWS CDK code samples crafted in TypeScript, featured on my blog at https://towardsthecloud.com/blog

<!-- TIP-LIST:START -->
> [!TIP]
> **[Towards the Cloud](https://towardsthecloud.com/about) eliminates AWS complexity so you ship faster with confidence, cut costs by 30%, and become compliant.**
>
> Sounds too good to be true? We'll assess your AWS account for free and report exactly where you stand. You'll receive a report with security findings and cost optimization opportunities. After that you can decide whether to fix these findings yourself or let us handle it. No strings attached.
>
> <a href="https://cal.com/towardsthecloud/aws-account-review"><img alt="Book a Free AWS Account Review" src="https://img.shields.io/badge/Book%20A%20Free%20AWS%20Account%20Review-success.svg?style=for-the-badge"/></a>
>
> <details>
> <summary>☁️ <strong>Discover how we cut AWS costs by 30% and accelerate SOC 2 compliance...</strong></summary>
> <br/>
>
> ### AWS complexity builds faster than you realize
>
> What starts as simple deployment quickly spirals into inefficient architectures costing 40-60% more than needed, security blind spots risking customer data, and team burnout from operations instead of product development.
>
> **Traditional consultancies prioritize billable hours over outcomes, then disappear after setup. We do the opposite...**
>
> ---
>
> ### We provide a complete package, so you deploy faster with confidence on AWS Cloud
>
> - ✅ **[Compliant multi-account Landing Zone](https://towardsthecloud.com/services/aws-landing-zone)**:
>   - Provisions AWS accounts with security guardrails out of the box - 100% [CIS benchmark compliant](https://docs.aws.amazon.com/securityhub/latest/userguide/cis-aws-foundations-benchmark.html)
>   - Secure Single Sign-On (SSO) for clean user access management
>   - Everything is built using AWS CDK ensuring consistency, version control, and repeatable deployments
>   - See what features are already included in our landing zone on our [public roadmap](https://github.com/towardsthecloud/aws-cdk-landing-zone-roadmap?tab=readme-ov-file#features)
> - ✅ **Off-the-shelf compliant CDK components**: Develop secure infra quicker without reinventing the wheel
> - ✅ **Complete CI/CD with easy rollbacks**: Deploy more frequently because of IaC safety
> - ✅ **Quarterly checks**: Proactively receive [Cost Optimization assessments](https://towardsthecloud.com/services/aws-cost-optimization) + [Security Reviews](https://towardsthecloud.com/services/aws-security-review)
> - ✅ **Fractional Cloud Engineer**: On-demand access to a decade of AWS Cloud experience to help you use best practices
>
> ---
>
> ### What results can you expect when you partner with us:
>
> - **30% Lower AWS Bill**: Proactive quarterly reviews catch overspending before it happens [(30-60% documented savings)](https://towardsthecloud.com/services/aws-cost-optimization#case-study)
> - **Accelerate SOC 2/HIPAA compliance**: Our Landing Zone automatically sets up security guardrails on your AWS accounts with 100% CIS compliance from day one
> - **Easily stay compliant**: Our automated monitoring and proactive quarterly security reviews give you control so yearly audits are smooth, not stressful
> - **Your Team Ships Faster**: Our Pre-built secure infrastructure components let your team focus on product, not AWS
> - **Save on hiring costs**: Access expert Cloud knowledge through our [flexible retainer](https://towardsthecloud.com/pricing) instead of committing to a full-time Cloud Engineer
>
> **Proof:** Y Combinator startup Accolade's founder on how our Landing Zone [accelerated their SOC 2 certification](https://towardsthecloud.com/blog/aws-landing-zone-case-study-accolade):
>
> *"Danny's solution and AWS expertise stood out with comprehensive accelerators, documentation, and clearly articulated design principles. **We achieved a perfect security score in days, not months.**"* — Galen Simmons, CEO
>
> </details>
<!-- TIP-LIST:END -->

## How to run the code from the examples

To run a Typescript example, execute the following:

```
$ npm install -g aws-cdk
$ cd EXAMPLE_DIRECTORY
$ npm install
$ cdk synth
$ cdk deploy
```

Then, to dispose of the stack/s afterwards

```
$ cdk destroy
```

## Table of Contents

| AWS CDK Example                                                                                    | Description                                                           | Blogpost link                                                                                            |
| -------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| [application-load-balanced-fargate-service](./application-load-balanced-fargate-service/README.md) | Create an Application Load Balanced Fargate Service in AWS CDK        | [Click here](https://towardsthecloud.com/aws-cdk-application-load-balanced-fargate-service)              |
| [cloudfront-s3-origin](./cloudfront-s3-origin/README.md)                                           | Create a CloudFront distribution with an S3 bucket as origin          | .                                                                                                        |
| [custom-role-lambda-function](./custom-role-lambda-function/README.md)                             | Create a custom IAM role for an AWS Lambda function                   | [Click here](https://towardsthecloud.com/aws-cdk-custom-role-lambda-function)                            |
| [aws-cdk-dependson-relation](./custom-role-lambda-function/README.md)                              | Create a DependsOn relation between resources in AWS CDK              | [Click here](https://towardsthecloud.com/aws-cdk-dependson-relation)                                     |
| [openid-connect-bitbucket](./openid-connect-bitbucket/README.md)                                   | Create a Bitbucket OpenID Connect (OIDC) provider in AWS CDK          | [Click here](https://towardsthecloud.com/aws-cdk-openid-connect-bitbucket)                               |
| [openid-connect-github](./openid-connect-github/README.md)                                         | Create a GitHub OpenID Connect (OIDC) provider in AWS CDK             | [Click here](https://towardsthecloud.com/aws-cdk-openid-connect-github)                                  |
| [rds-with-cloudwatch-alarms](./rds-with-cloudwatch-alarms/README.md)                               | Create an Amazon RDS instance with custom CloudWatch alarms           | .                                                                                                        |
| [scheduled-fargate-task](./scheduled-fargate-task/README.md)                                       | Create a Scheduled Fargate Task example in AWS CDK                    | [Click here](https://towardsthecloud.com/aws-cdk-scheduled-fargate-task)                                 |
| [scheduled-rds-stop-and-start](./scheduled-rds-stop-and-start/README.md)                           | Create a Scheduled stop and start function for an Amazon RDS Instance | [Click here](https://aws.amazon.com/blogs/database/schedule-amazon-rds-stop-and-start-using-aws-lambda/) |
| [share-resources-across-stacks](./share-resources-across-stacks/README.md)                         | Create a stack where you share resources to another stack             | [Click here](https://towardsthecloud.com/share-resources-across-stacks-aws-cdk)                          |

---

## Author

[Danny Steenman](https://towardsthecloud.com/about)

[![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/towardsthecloud)
[![](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/dannysteenman)
[![](https://img.shields.io/badge/GitHub-2b3137?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dannysteenman)
