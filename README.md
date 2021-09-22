# auto_learn
### 功能
江苏职称继续教育系统的自动挂科脚本。

### 制作原因
继续教育系统里有视频课程，每隔10分钟会自动暂停，影响(观看)体验，所以做了一个脚本跳过检测机制。

### 尝试的方案
* 每隔一段时间检测是否有窗口弹出，有的话点掉窗口
  * 未采用的原因：视频区有两个，有一个是点掉窗口之后要点一下视频再播放，另外一个是点掉窗口直接播放，机制不统一
* 每隔5分钟暂停/播放一次（目前的方案）

### 使用方法
 1.安装需要的环境
 chrome 版本93.0.4577.82
 python
 selenium
 2.执行run.bat脚本
 3.登录系统
 4.打开学习视频，关闭其他标签页
 5.视频播放完毕后，打开其他视频，并关闭其他标签页
