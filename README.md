# encrypt-s3fs
CSC4420 Final Project

An implementation of the s3fs file system using rc4 encryption.

The purpose of the project is to create a stackable file system on Linux using Amazon S3 as the back end storage that will accomplish the following:

-On Mount, a bucket from S3 appears as part of the file directory on your Linux machine.

-Any updates will be reflected on both the local directory and the corresponding s3 bucket.

-All files in the file system are automatically encrypted using rc4 with salt, 
and applications can transparently operate on the files without explicit decryptions.
