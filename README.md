# Shop Angular Cloudfront

Angular version: ~12.

Repo maintainers:

- [Sergey Gultyayev](https://github.com/gultyayev)

## The purpose

The repository was created to have an Angular version of e-shop for EPAM NodeJS AWS course. At the same time we strive to make this repository follows best practices so it may be used as a starter for new projects with all the necessary toolings already set up.

## NodeJS AWS course integration

All the necessary API endpoints are in the environments files `environment.ts` (for dev builds). Also it contains feature flags to enable/disable endpoints invocations from within the app so to ensure that you don't get errors for not implemented API endpoints.

## Contribution

Create an issue with the detailed description of the improvement/issue.

If you would like to help implementing some feature, you should ask the maintainers for approval so to ensure that the feature is desired in the repository and no efforts go wasted.

## Get up and running

Prerequisites: NodeJS v14.20.x and higher

Follow the steps:

- git clone
- npm i
- ng serve

# Task 2: Serve SPA in AWS S3 and CloudFront Service

## Task 2.1
## Manual Deployment
Below are the urls that show the results of manual deployment.
- Object URL: https://chg-shop-angular-cloudfront.s3.amazonaws.com/index.html
- CloudFront distribution URL: https://d34t4gbjofyzjk.cloudfront.net

## Task 2.2 + Additional tasks
## Automated Deployment
Below are the urls that show the results of automated deployment of the task 2.2 and Additional tasks,
using serverless-finch, serverless-single-page-app-plugin, serverless-build-client.
- Object URL: https://js-cc-cloudfront-s3-sls.s3.amazonaws.com/index.html
- CloudFront distribution URL: https://d452lnzqkf712.cloudfront.net
