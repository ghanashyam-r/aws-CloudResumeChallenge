Cloud Resume Challenge

My portfolio website
Website-https://ghanashyam-cloud.tech/ (Temporarily Full functionality Unavailable See the last line of the Readme File to see the working video)

The Challenge :

Certification:
So the challenge involved getting a AWS Cloud Certified Practitioner Certification which is the introductory industry grade cloud certification.With the help of resources like Stephane Mareek’s Cloud Practitioner prep course, I prepared for the exam and successfully obtained the certification.

HTML/CSS and Static Website Deployment:
I built a static website using HTML/CSS and deployed it as a static website on Amazon S3. This involved uploading the HTML and CSS files to an S3 bucket and configuring it to serve the files as a static website

HTTPS and DNS:
To ensure the security of my portfolio website, I set up an Amazon CloudFront distribution to serve the content via HTTPS. I registered a custom domain name for my portfolio website and configured it to point to the CloudFront distribution. 

JavaScript and Database:
One of the requirements of the Cloud Resume Challenge was to implement a visitor counter on my portfolio webpage using JavaScript. To achieve this, I used Amazon DynamoDB to store and update the visitor count. With a bit of JavaScript, I was able to display the visitor count dynamically on my resume website, providing visitors with real-time engagement metrics.

API and Python:
To interact with the DynamoDB database, I created an API using AWS API Gateway and AWS Lambda. This API, written in Python using the boto3 library, handled requests from the frontend web app to update the visitor count in the database.

Infrastructure as Code (IaC):
I used Terraform to set up a configuration with an S3 bucket with basic website hosting capabilities, allowing it to serve static web content like HTML files and assets. The configuration also ensured that the bucket had appropriate ownership controls, public access settings, and ACLs configured for web hosting.

Source Control and CI/CD:
Version control was essential throughout the Cloud Resume Challenge, so I set up GitHub repositories for my frontend website code. Utilising GitHub Actions, I implemented CI/CD pipelines to automate the deployment process. This ensured seamless deployment and minimal downtime.

![CLoud Resume challenge (1)](https://github.com/ghanashyam-r/aws-CloudResumeChallenge/assets/138144872/f4064b6c-06f5-4f89-87e3-4053d3dbfb5d)


https://github.com/user-attachments/assets/0b7934cb-7453-4210-af84-2e3c9580e58f



