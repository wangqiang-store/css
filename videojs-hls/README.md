# videojs-hls

videojs 支持 hls 直播实例
  包含功能

1.  视频播放前的高斯模糊 poster
2.  直播视频中断一定时间后提示用户刷新等操作
3.  视频卡住 3s 后不断重新尝试拉取直播流

### PS :

微信中的自动开播需要等到 wx jssdk 接口加载完毕后

    wx.ready(function(){
            myPlayer.play();
           })

详见  [参考文档](http://www.cnblogs.com/saysmy/p/6422678.html"微信中直播视频自动播放")

参考[实例演示](https://videojs.github.io/videojs-contrib-hls/)
