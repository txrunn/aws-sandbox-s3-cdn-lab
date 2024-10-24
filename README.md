# AWS Sandbox Lab: Deploying a Static Website with S3 and CloudFront

This repository contains files and instructions for deploying a static website using AWS S3 and CloudFront in the **AWS Academy Cloud Foundations** sandbox environment.

## Lab Objectives
- Understand how to host a static website using S3.
- Configure CloudFront to serve website content globally.
- Learn the basics of using CloudShell and the AWS CLI.

## Repository Structure
- `luci-portfolio/`: Contains the static website files (HTML, CSS, image) to be placed in S3.
- `lab-walkthrough/`: Detailed instructions for the live lab session.

## Prerequisites
- Access to the AWS Academy Cloud Foundations sandbox environment.
- Basic knowledge of AWS services like S3 and CloudFront.
  
## Quick Start
1. Clone this repository or download the zip file.
2. Follow the steps in `lab-walkthrough/lab-instructions.md` to deploy your static website.
3. If you would like to preview the website with the javascript functionality, clone the directory and run the following command: 
```
cd luci-portfolio && python3 -m http.server
```

## License
This project is open-source and licensed under the MIT License.