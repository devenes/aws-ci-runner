<div align="center" id="top"> 
  <img src="./.github/ci.jpeg" alt="Aws Ci Runner" />

&#xa0;

  <!-- <a href="https://awscirunner.netlify.app">Demo</a> -->
</div>

<h1 align="center">AWS CI Runner</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/devenes/aws-ci-runner?color=orange">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/devenes/aws-ci-runner?color=orange">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/devenes/aws-ci-runner?color=orange">
  <img alt="License" src="https://img.shields.io/github/license/devenes/aws-ci-runner?color=orange">
  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/devenes/aws-ci-runner?color=orange" /> -->
  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/devenes/aws-ci-runner?color=orange" /> -->
  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/devenes/aws-ci-runner?color=orange" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center">
	🚧  Aws Ci Runner 🚀 Under construction...  🚧
</h4>

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/devenes" target="_blank">Author</a>
</p>

<br>

## :dart: About

You can use GitHub Actions pipeline for deploying your application to the AWS EC2 instances. And you can test or deploy the automated process on the AWS EC2 instances as runners.

Used docker images to register the AWS EC2 instances as runners.

## :sparkles: Features

:heavy_check_mark: Start runner\
:heavy_check_mark: Deploy your code\
:heavy_check_mark: Run your code\
:heavy_check_mark: Stop runner

## :rocket: Technologies

The following tools were used in this project:

- [AWS](https://aws.amazon.com/)
- [AWS CLI](https://aws.amazon.com/cli/)
- [GitHub Actions](https://github.com)
- [Docker](https://www.docker.com/)

## :white_check_mark: Requirements

- Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Docker](https://www.docker.com) installed on your EC2 instance. And any other software you need to run or test the project.
- After finished setting up your EC2 instance take an image (AMI) of it and use it for the runner. You will add its AMI ID in the GitHub Actions workflow.
- For your safety, you need to have a separate EC2 instance for the runner.
- For your safety, you need to use GitHub Actions Secrets to store your AWS credentials that you will use to connect to the AWS EC2 instances.

## :checkered_flag: Starting

| Key                     | Value    | Description                              |
| :---------------------- | :------- | :--------------------------------------- |
| `ec2-image-id`          | `string` | The ID of the EC2 instance AMI           |
| `github-token`          | `string` | The GitHub token                         |
| `aws-region`            | `string` | The region of the EC2 instance           |
| `ec2-instance-type`     | `string` | The type of the EC2 instance             |
| `aws-access-key-id`     | `string` | The AWS access key                       |
| `aws-secret-access-key` | `string` | The AWS secret key                       |
| `subnet-id`             | `string` | The ID of the subnet                     |
| `security-group-id`     | `string` | The ID of the security group             |
| `iam-role-name`         | `string` | The name of the IAM role for EC2 service |
| `aws-resource-tags`     | `string` | The AWS resource tags                    |

## :memo: License

This project is under license from MIT. For more details, see the [LICENSE](LICENSE) file.

Made with :heart: by <a href="https://github.com/devenes" target="_blank">devenes</a>

&#xa0;

<a href="#top">Back to top</a>
