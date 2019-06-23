# docker-aws-s3-sync
A container that simply runs the aws s3 sync AWS cli command.

## Usage
docker run -d -e "SOURCE_BUCKET=bucketname" -e "DESTINATION_BUCKET=bucketname" -e "SYNC_OPTIONS=--dry-run" phr3nzii/aws-s3-sync
