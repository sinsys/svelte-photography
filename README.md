- [Wedington Photography](#wedington-photography)
  - [Description](#description)
  - [Architecture](#architecture)
    - [Frontend](#frontend)
    - [Hosting](#hosting)
    - [Storage](#storage)
    - [Users](#users)
  - [Deployment](#deployment)
  - [Contribution](#contribution)
  - [Attributions](#attributions)

# Wedington Photography

## Description
This is a photography website meant to serve two purposes.  

>   
> - It is both a front end client for portfolio / marketing purposes.  
> - It is a platform to distribute photos and images to clients   
>  

## Architecture

### Frontend

Frontend is built from scratch in Svelte using minimal external dependencies.
> [Svelte](https://svelte.dev/docs)

### Hosting

AWS hosts the service using Route 53 <tbd>. It is deployed via a CI/CD process with AWS Amplify.
> [See Deployment](#Deployment)

### Storage

Amazon S3 will serve as a mechanism to store photos uploaded for clients <tbd>
> [Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/API/Welcome.html)

### Users

Cognito will serve as an authentication protocol to grant access to purchased content <tbd>
> [Cognito](https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-identity-pools.html)

## Deployment

Deployment of the application is driven through a CI/CD system to AWS Amplify. <tbd status>

## Contribution

Want to use this? Like the style? Want to work together? Contact below.

## Attributions

Author - [Nicholas Hazel](https://github.com/sinsys)