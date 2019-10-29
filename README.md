# aws-kvs-consumer-opencv
amazon kinesis video stream consumer with python opencv

## Requirment packages
```
pip install opencv-python
pip install numpy
```

## How to Get HLS Streaming Session URL for Kinesis Video Stream
```shell 
$ aws kinesisvideo get-data-endpoint --stream-name Raspberry1 --api-name GET_HLS_STREAMING_SESSION_URL
```
it returns below

```shell
"DataEndpoint": "https://<blahblah>.kinesisvideo.us-west-2.amazonaws.com"
```

---
refer to : https://stackoverflow.com/questions/50061634/boto3-kinesis-video-getmedia-and-opencv
