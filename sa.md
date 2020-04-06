Restoring an object from Glacier.

$ aws s3api restore-object --bucket awsexamplebucket --key dir1/example.obj --restore-request '{"Days":25,"GlacierJobParameters":{"Tier":"Standard"}}'
