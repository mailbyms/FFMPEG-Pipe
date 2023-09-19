# FFMPEG-Pipe
使用管道进行ffmpeg音视频开发
> https://batchloaf.wordpress.com/2017/02/12/a-simple-way-to-read-and-write-audio-and-video-files-in-c-using-ffmpeg-part-2-video/

【原理】建立 2 个管道（ffmpeg 作为管道），从输入管道读数据，处理后 flush 到输出管道
