## AWS视频服务

### 概览

  - [Amazon Elastic Transcoder](https://amazonaws-china.com/cn/cloudwatch/?nc2=h_m1)
  - [Amazon Kinesis Video Streams](https://amazonaws-china.com/cn/kinesis/video-streams/?nc2=h_m1)
  - [AWS Elemental MediaConnect](https://amazonaws-china.com/cn/mediaconnect/?nc2=h_m1)
  - [AWS Elemental MediaConvert](https://amazonaws-china.com/cn/mediaconvert/?nc2=h_m1)
  - [AWS Elemental MediaLive](https://amazonaws-china.com/cn/medialive/?nc2=h_m1)
  - [AWS Elemental MediaPackage](https://amazonaws-china.com/cn/mediapackage/?nc2=h_m1)
  - [AWS Elemental MediaStore](https://amazonaws-china.com/cn/mediastore/?nc2=h_m1)
  - [AWS Elemental MediaTailor](https://amazonaws-china.com/cn/mediatailor/?nc2=h_m1)
  - [AWS Elemental Device&Software](https://amazonaws-china.com/cn/elemental-appliances-software/?nc2=h_m1)

### 服务适用场景

| 服务名称 | 应用场景 | 匹配程度 |
| ------|------|------|
| Elastic Transcoder |视频源格式(RAW)转码成其他格式，以便支持在智能手机、平板电脑或PC上播放|NO|
| Kinesis Video Streams |获取、处理和存储视频流用于分析和机器学习|YES|
| MediaConnect |安全可靠的直播视频传输|NO|
| MediaConvert |广播级文件视频处理服务|NO|
| MediaLive |广播级实时视频处理服务|NO|
| MediaPackage |轻松准备和保护视频，以传送到 Internet 设备|NO|
| MediaStore |实时存储分发|NO|
| MediaTailor |视频中间定制广告|NO|
| Device&Software | 视频硬件部署 |NO|

### 实施方案

前端录制好的视频，使用[Amazon S3](https://amazonaws-china.com/cn/s3/?nc2=h_m1)服务来进行视频存储  
使用开源机器学习框架，根据预设条件构建视频分析结果  
使用[Kinesis Video Streams](https://amazonaws-china.com/cn/kinesis/video-streams/?nc2=h_m1)的HTTP实时流(HLS)功能将视频流式传输给企业端，提供人工审核
## Aliyun视频服务

### 概览
 
  - [媒体转码](https://www.aliyun.com/product/mts?spm=a2c4g.11186623.5.3.6bf276fasM9coQ)
  - [视频截图](https://www.aliyun.com/product/mts?spm=a2c4g.11186623.5.3.6bf276fasM9coQ)
  - [视频画质重生](https://www.aliyun.com/product/mts?spm=a2c4g.11186623.5.3.6bf276fasM9coQ)
  - [智能审核](https://www.aliyun.com/product/mts?spm=a2c4g.11186623.5.3.6bf276fasM9coQ)
  - [内容理解](https://www.aliyun.com/product/mts?spm=a2c4g.11186623.5.3.6bf276fasM9coQ)
  - [视频编辑](https://www.aliyun.com/product/mts?spm=a2c4g.11186623.5.3.6bf276fasM9coQ)
  - [视频版权保护](https://www.aliyun.com/product/mts?spm=a2c4g.11186623.5.3.6bf276fasM9coQ)

### 服务适用场景

阿里云端使用场景描述较少，需要进一步深入的去看文档。
