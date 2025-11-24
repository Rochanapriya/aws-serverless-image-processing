# AWS Serverless Image Processing

This repository contains documentation from a cloud computing project where I built a
serverless image-processing pipeline on AWS. When an image is uploaded to an S3 bucket, an
AWS Lambda function is triggered to convert the image to grayscale using OpenCV and store
the result in an output bucket. CloudWatch is used for logging and basic monitoring.

> Note: This repository currently includes the project report only. A minimal
> reproduction of the Lambda code and deployment steps will be added later.

## Project Overview

- **Input:** Images uploaded to an S3 bucket.
- **Processing:** AWS Lambda function written in Python.
- **Libraries:** OpenCV for image processing, NumPy for array operations.
- **Output:** Processed grayscale images written to a separate S3 bucket.
- **Monitoring:** CloudWatch logs and metrics for Lambda performance.
- **Validation:** Basic load testing performed using Locust to check how the system
  behaves under concurrent requests.

## Technologies

- AWS Lambda  
- Amazon S3  
- Amazon CloudWatch  
- Python  
- OpenCV  
- NumPy  
- Locust (load testing)

## Repository Structure

- `Cloud Computing- Final Project.pdf` – original course project report describing the
  architecture, configuration and experiments.
- `README.md` – high-level overview of the project.

## Future Work

- Add a minimal Lambda example with deployment instructions.
- Provide sample images and screenshots of the CloudWatch logs.

