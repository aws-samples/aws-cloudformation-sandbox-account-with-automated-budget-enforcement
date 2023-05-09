## AWS CloudFormation template for creating a sandbox account with automated budget enforcement

This AWS CloudFormation template creates resources in an existing account to create a sandbox account with managed access based on a monthly budget.

When you deploy this stack it will create:
A VPC with 2 public subnets, 2 private subnets, vpc flow logs, an internet gateway, a NAT gateway, and a no ingress security group. A monthly budget will be created in AWS Budgets, along with a SandboxDeveloper IAM role and 2 Lambda functions to govern access to the account based on the budget.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

