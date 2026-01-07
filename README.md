# Static Website Hosting using AWS S3 and AWS CloudFront

## Project Overview
This project demonstrates how to host a static website using **Amazon Web Services (AWS)**. 
The website is hosted on **AWS S3** and delivered globally using **AWS CloudFront** with HTTPS security.

## Objectives
- Host a static website using AWS S3
- Configure public access using AWS S3 Bucket Policy
- Use AWS CloudFront for fast and secure content delivery
- Enable HTTPS using AWS-managed TLS certificate

## AWS Services Used
- **AWS S3 (Simple Storage Service)** – Static website hosting
- **AWS CloudFront** – Content Delivery Network (CDN)

## Project Structure
- `index.html` – Main homepage
- `error.html` – Error page
- `screenshots/` – AWS screenshots

## Implementation Steps
1. Created an AWS S3 bucket
2. Uploaded HTML and CSS files to S3
3. Enabled static website hosting in AWS S3
4. Configured AWS S3 bucket policy for public access
5. Created AWS CloudFront distribution
6. Connected CloudFront with S3 origin
7. Enabled HTTPS and security settings
8. Tested website after CloudFront deployment

## Screenshots

### AWS S3 Bucket Created
![Bucket Created](screenshots/bucket_created_successfully.png)

### AWS S3 Static Website Hosting Enabled
![Static Hosting](screenshots/static_web_hosting_enabled.png)

### AWS S3 Bucket Policy Configuration
![Bucket Policy](screenshots/Bucket_policy(json).png)

### Website Before AWS CloudFront (Not Secure)
![Not Secure](screenshots/showing_not_secure_website_before_cloud_front.png)

### AWS CloudFront Distribution Deployed
![CloudFront Deployed](screenshots/deployed_highlight_after_completing_all_phases_of_cloud_front.png)

### Website After AWS CloudFront (HTTPS Enabled)
![HTTPS Website](screenshots/website_link_highlight_web_page_after_deploying_cloud_front.png)

## Result
The static website was successfully hosted on **AWS S3** and securely delivered using **AWS CloudFront** with HTTPS.

## Conclusion
This project proves how AWS services such as S3 and CloudFront can be used to build scalable, secure, and high-performance static websites.

## Author
**Shees Saleem**  
