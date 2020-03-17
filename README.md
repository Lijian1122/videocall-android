# videocall-android

简介
本Demo展示了怎么使用环信SDK创建一个简易多人音视频Demo，可以进行音频、视频会话，上麦、下麦互动。

demo运行
1.安装 Android Studio ,配置好 

sudo gem install cocoapods
2.安装成功后, 运行Podfile

cd ./VideoCallDemo/EMiOSVideoCallDemo

pod install

3.点击iOSVideoCallDemo.xcworkspace进入Demo

代码结构
多人音视频Demo主要包含的类如下：

RoomJoinViewController 加入房间页面

ConferenceViewController 视频展示页面

AccountSettingViewController 个人设置页面

RoomSettingViewController 房间设置页面

SpeakerListViewController 主播列表页面

KickSpeakerViewController 选人下麦页面

EMStreamView 视频小窗口类

EMDemoOption 会议管理类

集成文档
多人音视频集成文档参见官方文档：http://docs-im.easemob.com/im/ios/basics/multiuserconference
