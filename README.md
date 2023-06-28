# DEMO说明
本DEMO用于演示内置编解码SDK的使用，DEMO接收来自服务器指定位置的码流、解码、渲染。<br>

可通过DEMO配置文件设置服务器IP、房间号、接收位置、文件录制开关等进行设置。


```js
[Config]
;服务器IP
ServerIp=47.106.195.225
;域ID
DomainId=3
;房间号
RoomId=888
;播放位置
DownPosition=1
;音频渲染参数
AudioSampleRate=44100
AudioChannel=2
;播放接收缓存毫秒
JitterBuffTimeMs=200
;是否录制文件
CaptureDownStreamTs=0
CaptureDownStreamRaw=0


```
<br>

SDK API的调用集中在SDClient.cpp中

<br>
测试工程使用VS2010或更高版本编译



---

# 相关资源
跟多文档、代码资源见：https://mediapro.apifox.cn

SDK 商用及定制化、技术支持服务可联系：[http://www.mediapro.cc/](http://www.mediapro.cc/)

