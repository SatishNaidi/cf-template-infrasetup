# Cloudformation Template for Infra Set up #


[root](https://github.com/SatishNaidi/cf-template-infrasetup/blob/master/lambda-cleanup-snapshot.zip)

1. Create a S3 bucket of your choice of name
2. Download the `snaphot_deletion_lambda.zip` and `lambda_snapshot.zip` files for from this repo
3. Upload the `snaphot_deletion_lambda.zip` and `lambda_snapshot.zip` files to newly created s3 Bucket
4. Run the Cloud Formation Template `Main-CF-Template.json`
  * For Cloud Formation Template Input Parameters under "Lambda Configuration" section
      * BucketForLambdaCode use `newly created S3 Bucket Name`
      * Lambda1FileName use `snaphot_deletion_lambda.zip`
      * Lambda1FileName use `lambda_snapshot.zip`

