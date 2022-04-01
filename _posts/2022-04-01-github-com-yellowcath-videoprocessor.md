---
title: VideoProcessor
categories: ['java']
---
## [VideoProcessor](https://github.com/yellowcath/VideoProcessor)

### process video(cut & scale & increase & decrease & reverse) with mediacodec


[VideoProcessor](https://github.com/yellowcath/VideoProcessor)使用Android原生的MediaCodec实现视频压缩、剪辑、混音、快慢放及倒流的功能（快慢放及倒流支持音频同步变化），在支持MediaCodec的手机上优于使用FFmpeg的方案

- **体积小** ：编译后的aar只有262K，ffmpeg一个so就7、8M，精简之后也差不多还有一半大小
- **速度快** ：在huaweiP9上压缩(1080P 20s 20000k -> 720p 2000k)

lib | 耗时
------ | ------
VideoProcessor| 13.3s
ffmpeg | 172s
ffmpeg(ultrafast) | 74s
