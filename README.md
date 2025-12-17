# terraform-aws-s3-bucket

A simple Terraform module to create an AWS S3 bucket...

## Usage

```hcl
module "s3_bucket" {
  source      = "mytest/s3-bucket-jmc/aws"
  bucket_name = "my-bucket"
}
``` 