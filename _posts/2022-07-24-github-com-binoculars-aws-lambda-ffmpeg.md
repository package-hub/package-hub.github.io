---
title: aws-lambda-ffmpeg
categories: ['typescript', 'ffmpeg', 'aws-lambda']
---
## [aws-lambda-ffmpeg](https://github.com/binoculars/aws-lambda-ffmpeg)

### An S3-triggered Amazon Web Services Lambda function that runs your choice of FFmpeg 🎬 commands on a file  🎥 and uploads the outputs to a bucket.

1. A video file is uploaded to the source storage location
1. A notification event triggers the function
1. The function downloads the video file from the source location
1. Streams the video through FFmpeg
1. Outputs a scaled video file and a thumbnail image
1. Uploads both files to the destination bucket
