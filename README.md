t
# AWS Static Website 

A personal portfolio website hosted on **Amazon S3** 
and delivered globally via **AWS CloudFront**.

##  Live Demo
[View Live Website](http://my-aws-website-raghvendra.s3-website.eu-central-1.amazonaws.com)

##  Architecture
User → CloudFront (CDN + HTTPS) → S3 Bucket (eu-central-1 Frankfurt)
##  AWS Services Used
| Service | Purpose |
|---|---|
| Amazon S3 | Stores and hosts static website files |
| AWS CloudFront | CDN for fast global delivery and HTTPS |
| S3 Bucket Policy | IAM policy to allow public read access |

##  What I Learned
- How to host a static website on AWS S3
- How CloudFront CDN improves performance and adds HTTPS
- How to configure S3 bucket policies for public access
- AWS region selection strategy (eu-central-1 Frankfurt)
- Git version control and GitHub workflow

##  Project Structure
aws-static-website/
├── index.html      # Main webpage
├── style.css       # Styling
└── app.js          # JavaScript

##  Author
Raghvendra Yadav — Aspiring AWS Solutions Architect
Currently learning AWS | Moving to Berlin 🇩🇪 | Open to internships
