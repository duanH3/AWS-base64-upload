var s3 = AWS.S3(awsCredentials);
s3.deleteObject({
  Bucket: MY_BUCKET,
  Key: 'some/subfolders/nameofthefile1.extension'
},function (err,data){})
