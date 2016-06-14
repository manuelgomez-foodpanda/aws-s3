# mgomez/aws-s3

Fork of [convox/aws-s3](https://hub.docker.com/r/convox/aws-s3)

Uses [fakes3](https://github.com/jubos/fake-s3) to run a local S3 daemon with custom credentials and bucket name.

## Docker hub address
https://hub.docker.com/r/mgomez/aws-s3/

## Usage
    $ docker pull mgomez/aws-s3
    $ docker run -p 5000:80 mgomez/aws-s3 bash -c "/opt/fakes3/bin/fakes3-init -a <ACCESSKEY> -s <SECRETKEY> -b <BUCKETNAME>"

## License
This version: Apache 2.0 Manuel Gómez

Original version: Apache 2.0 &copy; 2015 Convox, Inc.
