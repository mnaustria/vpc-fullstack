# VPC Reference Architecture: Infrastructure as Code

The architecture we deploy is a very simple VPC with presets parameters that you can choose from
to orchestrate your network architecture design automagically.

## Running the example

#### 1. Fork the GitHub repository

[Fork](https://help.github.com/articles/fork-a-repo/) the [Amazon VPC sample
template](https://github.com/w3dotmakinadotnull/vpc-fullstack) GitHub repository into
your GitHub account.

From your terminal application, execute the following command (make sure to
replace `<your_github_username>` with your actual GitHub username):

```console
git clone https://github.com/<your_github_username>/vpc-fullstack
```

This creates a directory named `vpc-fullstack` in your current
directory, which contains the code for the Amazon VPC template(s).

#### 2. Create the CloudFormation stack

Deploy | Region Name | Region | Launch Types
:---: | ------------ | ------------- | -------------
[🚀][us-east-1] | US East (N. Virginia) | us-east-1 | VPC
[🚀][us-east-2] | US East (Ohio) | us-east-2 | VPC
[🚀][us-west-1] | US West (N. California) | us-west-1 | VPC
[🚀][us-west-2] | US West (Oregon) | us-west-2 | VPC
[🚀][eu-west-1] | EU (Ireland) | eu-west-1 | VPC
[🚀][eu-west-2] | EU (London) | eu-west-2 | VPC
[🚀][eu-central-1] | EU (Frankfurt) | eu-central-1 | VPC
[🚀][ap-southeast-1] | Asia Pacific (Singapore) | ap-southeast-1 | VPC
[🚀][ap-southeast-2] | Asia Pacific (Sydney) | ap-southeast-2 | VPC
[🚀][ap-northeast-1] | Asia Pacific (Tokyo) | ap-northeast-1 | VPC
[🚀][ap-northeast-2] | Asia Pacific (Seoul) | ap-northeast-2 | VPC
[🚀][ca-central-1] | Canada (Central) | ca-central-1 | VPC

This reference architecture can only be deployed to Regions which have all
necessary services available. See the [Region
Table](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/)
for information about service availability.
## License

This reference architecture sample is [licensed][license] under Apache 2.0.

[license]: LICENSE
[launch-types]: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/launch_types.html
[us-east-1]: https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
[us-east-2]: https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
[us-west-1]: https://console.aws.amazon.com/cloudformation/home?region=us-west-1#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
[us-west-2]: https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
[eu-west-1]: https://console.aws.amazon.com/cloudformation/home?region=eu-west-1#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
[eu-west-2]: https://console.aws.amazon.com/cloudformation/home?region=eu-west-2#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
[eu-central-1]: https://console.aws.amazon.com/cloudformation/home?region=eu-central-1#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
[ap-southeast-1]: https://console.aws.amazon.com/cloudformation/home?region=ap-southeast-1#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
[ap-southeast-2]: https://console.aws.amazon.com/cloudformation/home?region=ap-southeast-2#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
[ap-northeast-1]: https://console.aws.amazon.com/cloudformation/home?region=ap-northeast-1#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
[ap-northeast-2]: https://console.aws.amazon.com/cloudformation/home?region=ap-northeast-2#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
[ca-central-1]: https://console.aws.amazon.com/cloudformation/home?region=ca-central-1#/stacks/create/review?stackName=VPC-Fullstack&templateURL=https://s3.amazonaws.com/w3kp-public-templates/vpc-fullstack.yaml
