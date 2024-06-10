

### What was done?
- Created and configured an S3 bucket for hosting the React app.
- Manually uploaded the app to the S3 bucket.
- Created a CloudFront distribution for the S3 bucket.
- Automated the deployment using AWS CDK.
- Configured S3 bucket creation, website deployment, CloudFront distribution, and invalidation using AWS CDK.
- Added npm scripts for automated build, deployment, and CloudFront invalidation.

### Links
Outputs:
-ShopStack.BucketURL = http://shopstack-myshopbucket3363d19f-vtvugygaezmg.s3-website-us-east-1.amazonaws.com
-ShopStack.CloudFrontURL = d3etj67o53goqy.cloudfront.net
- S3 Website: https://rsschool-module2.s3.amazonaws.com/index.html
- CloudFront URL: https://d1rm5rfiej03jr.cloudfront.net

### Additional Information
- The app is built and deployed automatically using CDK scripts.
- CloudFront cache invalidation is handled via npm scripts.
