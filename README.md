# [![AWS CDK Examples Banner](./icons/github-title-banner.png)](https://towardsthecloud.com)

# AWS CDK Examples

A collection of AWS CDK code samples crafted in TypeScript, featured on my blog at https://towardsthecloud.com/blog

> [!TIP]
> **Launch Faster on AWS and Become Fully Secure From Day One!** Our AWS Landing Zone Foundation service helps B2B companies achieve SOC 2 compliance 90% faster,  redirect 30% of engineering time back to product development all while eliminating the six-figure cost of specialized cloud engineers. so you can focus on shipping your product, instead of worrying about managing your infrastructure on AWS.
>
> [Schedule a free introduction call](https://towardsthecloud.com/contact) to discover how we can deliver 10x the value of securing and building your infrastructure on AWS for a fraction of the cost of a full-time cloud engineer.

<details><summary>☁️ <strong>Learn more about our unique AWS Foundation Service</strong></summary>

<br/>

Is AWS complexity draining your engineering resources? Most B2B startups and growing businesses struggle with overwhelming configuration options, time-consuming compliance requirements, and diverting valuable developer talent away from core product development. Without specialized AWS expertise, you risk security vulnerabilities, mounting technical debt, and delayed time-to-market. All while your competitors race ahead.

Traditional AWS consultancies only compound this problem. They're incentivized to bill by the hour, extending projects indefinitely rather than focusing on your business outcomes. We take the opposite approach. Our fixed-price subscription model proves how confident we are in delivering results, not just billable hours. We succeed when you succeed, aligning our incentives with your growth rather than your AWS complexity.

## Our Solution: Enterprise-Grade AWS Foundation

We deliver an enterprise-grade AWS Landing Zone built entirely in AWS CDK coupled with a support and consultacy foundation that grows with your business needs. Here's what we'll deliver to you:

### We deploy a [Secure and Compliant Landing Zone](https://towardsthecloud.com/services/aws-landing-zone)
- Multi-account architecture with proper security boundaries
  - Achieves a **100% score on the industry-standard [CIS AWS Foundation Benchmark](https://docs.aws.amazon.com/securityhub/latest/userguide/cis-aws-foundations-benchmark.html)**
  - **Achieves a 96% rating on AWS's own [foundational security best practices](https://docs.aws.amazon.com/securityhub/latest/userguide/fsbp-standard.html)**
- Setup entirely using AWS CDK (Infrastructure as Code)
- Budget monitoring and notifications across all accounts
- Deploy changes quickly through GitHub Actions
- We're continuously adding new features as listed on our [Roadmap](https://github.com/towardsthecloud/aws-cdk-landing-zone-roadmap)

### We upskill and accelerate your Developers
- They gain access to our library of ready-to-use, security-hardened AWS CDK components
- They receive guidance on how to utilize AWS best practices for your architecture so you avoid technical debt later on

### We monitor and maintain the multi-account setup & provide ongoing support
- Gain new Landing Zone features once they're released and get free maintenance and security updates
- Get priority support through Slack/Teams whenever you need assistance with infrastructure challenges
- We proactively do quarterly [security](https://towardsthecloud.com/services/aws-security-review) and [cost optimization](https://towardsthecloud.com/services/aws-cost-optimization) assessments to verify AWS account compliance and provide advice to reduce your AWS bill

### What This Means For Your Business
- **30% Lower TCO**: Cut your Total Cost of Ownership (TCO) by up to 30% through right-sized resources and architectural optimization while eliminating the $150K+ annual cost of a specialized AWS hire
- **Close Enterprise Deals Faster**: Win enterprise clients with SOC2 compliance ready in weeks instead of months - our clients report 50% faster sales cycles with security-conscious customers
- **Unleash Your Development Team**: Redirect up to 30% of engineering time from infrastructure back to revenue-generating product features with our pre-built, compliant components
- **Scale Without Infrastructure Headaches**: Grow from startup to enterprise without ever rebuilding your foundation - our architecture scales seamlessly from your first customer to your millionth

We deliver all of this as a [simple subscription service](https://towardsthecloud.com/pricing). No large upfront costs, no lock-in. You'll essentially get a solid and secure landing zone foundation + a decade of AWS expertise without having to hire a full-time Cloud Engineer.

<a href="https://towardsthecloud.com/contact"><img alt="Schedule a free introduction call" src="https://img.shields.io/badge/schedule%20a%20free%20introduction%20call-success.svg?style=for-the-badge"/></a>
</details>

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
