# Cloudformation Template for Infra Set up #



1. Create a s3 bucket of your choice of name
2. Download the Lambda1.zip and Lambda2.zip files for from this repo
3. Upload the Lambda1.zip and Lambda2.zip files to newly created s3 Bucket
4. Run the Cloud Formation Template `Main-CF-Template.json`
  * For Cloud Formation Template Input Parameters under "Lambda Configuration" section
      * BucketForLambdaCode `newly created S3 Bucket Name`
      * Lambda1FileName `Lambda1.zip`
      * Lambda1FileName `Lambda2.zip`

