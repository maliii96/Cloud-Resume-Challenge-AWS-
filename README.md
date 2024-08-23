# 🌥️ Cloud Resume Challenge

Welcome to my Cloud Resume Challenge repository! This project showcases how I built and deployed a personal resume website using key AWS services such as S3, CloudFront, Route 53, and Certificate Manager. The project demonstrates my ability to create a secure, globally distributed static website, leveraging the power of AWS.

## 🚀 Overview

The **Cloud Resume Challenge** is a hands-on project that allows you to build and deploy a personal resume site using cloud technologies. In this project, I focused on the following:

- 🖥️ **Building a Static Website**: Hosting a personal resume site on AWS S3.
- 🌐 **Global Distribution**: Using AWS CloudFront as a CDN to ensure fast and secure content delivery.
- 🔒 **SSL/TLS Security**: Securing the website with HTTPS using AWS Certificate Manager.
- 🌍 **Custom Domain Management**: Configuring a custom domain with Route 53.

## 🏗️ Architecture

Here’s a breakdown of the architecture I used:

- **S3**: Serves as the storage for the static website files (HTML, CSS, JS). The bucket is configured for static website hosting.
- **CloudFront**: A Content Delivery Network (CDN) that caches content at edge locations around the world, providing low-latency access to the website.
- **Route 53**: Manages the DNS, pointing the custom domain to the CloudFront distribution.
- **AWS Certificate Manager (ACM)**: Provides an SSL/TLS certificate to secure the website with HTTPS.

## 📝 Steps to Completion

### 1. **Design and Build the Static Website**

- Developed a responsive, mobile-friendly resume site using HTML, CSS, and JavaScript.
- The site includes sections like About Me, Skills, Work Experience, and Projects.
- Uploaded the static files to an S3 bucket configured for static website hosting.

### 2. **Set Up S3 Bucket for Website Hosting**

- Created an S3 bucket with a name matching the custom domain (e.g., `yourdomain.com`).
- Enabled static website hosting in the S3 bucket settings.
- Configured the bucket policy to allow public read access to the website files.

### 3. **Secure the Website with SSL/TLS**

- Used AWS Certificate Manager (ACM) to request a public SSL/TLS certificate for the custom domain.
- Validated the domain ownership using DNS validation through Route 53.

### 4. **Distribute Content Globally with CloudFront**

- Created a CloudFront distribution with the S3 bucket as the origin.
- Configured CloudFront to use the SSL/TLS certificate from ACM to secure the content.
- Enabled caching and compression in CloudFront to optimize delivery speed.

### 5. **Configure DNS with Route 53**

- Created a hosted zone in Route 53 for the custom domain.
- Added an A record in the hosted zone to point the domain to the CloudFront distribution.
- Verified that the domain correctly resolves to the CloudFront distribution, and the website is served over HTTPS.

## 🛠️ Technologies Used

- **Amazon S3**: For static website hosting.
- **Amazon CloudFront**: For global content delivery.
- **Amazon Route 53**: For DNS management and domain registration.
- **AWS Certificate Manager (ACM)**: For SSL/TLS certificate management.

## 🔍 Lessons Learned

- **Infrastructure Setup**: Gained hands-on experience with setting up a fully functional, secure, and globally distributed website on AWS.
- **DNS Configuration**: Learned to configure DNS settings in Route 53 to point a custom domain to a CloudFront distribution.
- **Security Best Practices**: Implemented SSL/TLS certificates to secure the website, ensuring data is encrypted in transit.



## 📫 Contact

For any questions or feedback, feel free to reach out via [LinkedIn](https://linkedin.com/in/MalikStevenson) 
