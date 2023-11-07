
# Hosting an Website using AWS S3, Cloudfront and code Pipeline

Hosting a website using Amazon S3, CloudFront, and CodePipeline is a streamlined and efficient way to deliver a highly available and scalable web application. This setup leverages the services provided by Amazon Web Services (AWS) to ensure a reliable and performant web hosting environment. 



# steps to create this project

Amazon S3 (Simple Storage Service):

Create an S3 bucket: Start by creating an S3 bucket to store your website's static assets (HTML, CSS, JavaScript, images, etc.). Ensure that the bucket name matches your website's domain name 
Upload your website content: Upload all your website files and assets to the S3 bucket.

![Screenshot (199)](https://github.com/sunilkurthakoti/simple_aws_project/assets/131526336/cc3278d1-d116-4131-805b-c8c27e57afb5)


Amazon CloudFront:

Create a CloudFront distribution: CloudFront is a content delivery network (CDN) that will help speed up content delivery and enhance security. Create a distribution and configure it to use your S3 bucket as the origin.
Configure custom domains: Associate your website's domain with your CloudFront distribution by setting up CNAME records in your DNS settings.
Enable SSL: Use AWS Certificate Manager (ACM) to provision an SSL certificate for your domain and associate it with your CloudFront distribution to enable HTTPS.

![Screenshot (200)](https://github.com/sunilkurthakoti/simple_aws_project/assets/131526336/aa2d8807-5d07-4c6d-8af2-71476abf7118)


AWS CodePipeline:

Create an AWS CodePipeline.
Source Stage: Connect to your version control system (e.g., GitHub) or an S3 bucket as the source.
Deploy Stage: Configure the deployment to the S3 bucket containing your website content.
These steps create a workflow where updates to your website's code trigger an automated deployment process. The website is hosted on S3, accelerated by CloudFront, and updates are managed through CodePipeline for continuous integration and delivery.

![Screenshot (202)](https://github.com/sunilkurthakoti/simple_aws_project/assets/131526336/3d7864af-6df2-4af7-9526-62f28e30d849)


Finally the website is up and running

![Screenshot (203)](https://github.com/sunilkurthakoti/simple_aws_project/assets/131526336/d8e6b21b-ffd2-44ed-9377-c794d87eea4d)



## Feedback

If you have any feedback, please reach out to us at sunilkurthakoti06@gmail.com

