# Amazon S3 Bucket VersioningConfiguration<a name="aws-properties-s3-bucket-versioningconfig"></a>

Describes the versioning state of an [ AWS::S3::Bucket](aws-properties-s3-bucket.md) resource\. For more information, see [PUT Bucket versioning](https://docs.aws.amazon.com/AmazonS3/latest/API/RESTBucketPUTVersioningStatus.html) in the *Amazon Simple Storage Service API Reference*\.

## Syntax<a name="w4ab1c21c10d180c13d174b5"></a>

### JSON<a name="aws-properties-s3-bucket-versioningconfig-syntax.json"></a>

```
{
  "[Status](#cfn-s3-bucket-versioningconfig-status)" : String
}
```

### YAML<a name="aws-properties-s3-bucket-versioningconfig-syntax.yaml"></a>

```
[Status](#cfn-s3-bucket-versioningconfig-status): String
```

## Properties<a name="w4ab1c21c10d180c13d174b7"></a>

`Status`  <a name="cfn-s3-bucket-versioningconfig-status"></a>
The versioning state of an Amazon S3 bucket\. If you enable versioning, you must suspend versioning to disable it\.   
Valid values include `Enabled` and `Suspended`\. The default is `Suspended`\.  
*Required*: Yes  
*Type*: String