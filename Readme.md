# Cloudformation Template for Infra Set up #

1. Create a S3 bucket of your choice of name
2. Download the [lambda-cleanup-snapshot.zip](https://github.com/SatishNaidi/cf-template-infrasetup/blob/master/lambda-cleanup-snapshot.zip) and [lambda-create-snapshot.zip](https://github.com/SatishNaidi/cf-template-infrasetup/blob/master/lambda-create-snapshot.zip) files for from this repo
3. Upload the [lambda-cleanup-snapshot.zip](https://github.com/SatishNaidi/cf-template-infrasetup/blob/master/lambda-cleanup-snapshot.zip) and [lambda-create-snapshot.zip](https://github.com/SatishNaidi/cf-template-infrasetup/blob/master/lambda-create-snapshot.zip) files to newly created s3 Bucket
4. Run the Cloud Formation Template [Main-CF-Template.json](https://github.com/SatishNaidi/cf-template-infrasetup/blob/master/Main-CF-Template.json)
  * For Cloud Formation Template Input Parameters under "Lambda Configuration" section
      * BucketForLambdaCode use `newly created S3 Bucket Name`
      * Lambda1FileName use `lambda-cleanup-snapshot.zip`
      * Lambda1FileName use `lambda-create-snapshot.zip`

