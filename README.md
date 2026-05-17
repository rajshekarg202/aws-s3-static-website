# AWS S3 Static Website Hosting

This project demonstrates how to host a static website using Amazon S3 service in AWS cloud platform.

---

## Project Overview

A static website was created using HTML and CSS and hosted publicly using Amazon S3 static website hosting feature.

This project helps understand:
- Amazon S3 bucket creation
- Static website hosting
- Bucket policy configuration
- Public access permissions
- Website deployment in AWS cloud

---

## Technologies Used

- HTML
- CSS
- Amazon S3
- AWS Management Console
- GitHub

---

## AWS Services Used

### Amazon S3
Amazon S3 (Simple Storage Service) is used to:
- Store website files
- Enable static website hosting
- Provide public access to website content

---

## Project Files

```text
aws-s3-static-website/
│
├── index.html
├── style.css
├── README.md
│
└── images/
      ├── screenshot1.png
      └── screenshot2.png
```

---

## Steps Performed

1. Created an S3 bucket
2. Disabled block public access settings
3. Uploaded HTML and CSS files
4. Enabled static website hosting
5. Added bucket policy for public access
6. Accessed website using S3 endpoint URL
7. Uploaded project to GitHub

---

## Bucket Policy Used

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicReadGetObject",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::rajshekarg20/*"
    }
  ]
}
```

---

## Website Features

- Static webpage hosting
- Publicly accessible website
- HTML and CSS integration
- Cloud-based deployment
- Beginner-friendly AWS project

---

## Output

Successfully hosted a static website using Amazon S3 with public access enabled.

---

## Screenshots

### Website Output
![Website Screenshot](images/screenshot1.png)

### AWS S3 Bucket Configuration
![AWS Screenshot](images/screenshot2.png)

---

## Learning Outcome

Through this project, learned:
- Basics of AWS cloud services
- S3 bucket configuration
- Static website deployment
- Cloud storage concepts
- GitHub project hosting

---

## Author

Rajshekar.G
