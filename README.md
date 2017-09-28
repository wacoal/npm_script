### Overview ###

* https://fatey.net/
* モコトーク 本家ページとwebview用

### Description ###
* S3にホスティングしています。
* SSLはCloudFrontとACM(SNI)で対応。
* https://s3.console.aws.amazon.com/s3/buckets/fatey.net/?region=us-east-1
 の/public/以下をDocumentRootとしています。

### Deploy ###
* master に merge or pushでS3にデプロイされます。（BitBucket Pipelineを使用）

