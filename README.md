# LMSCode_AMV_Convert<br>LMS代码团队 AMV格式转换器

支持从任何流行的视频格式转换至AMV格式。

AMV格式是许多品牌的MP4播放器使用的视频播放格式；使用本工具可以将您的视频转换为AMV视频格式。

## 开始使用

1. 您需要一台Windows8以上系统的电脑。
2. 从[本仓库的Releases](https://github.com/LMSLuos/LMSCode_AMV_Convert/releases/latest/)或[LMSOFSv3](https://files.lms.cn.eu.org/v3/Software/LMSCode_AMV_Convert/InstallTool/)下载最新的版本并安装。
>本工具的安装依赖7-Zip，本质上是绿色软件，安装操作不会像您的计算机添加多余的文件，更不会有病毒。
3. 双击文件夹内的程序，立即开始使用！

## 使用问题

一些常见问题的集合。
在遇到问题的时候，请先检查您使用的版本是否是最新的！

### 安装失败
检查磁盘的空间是否充足（一般需要120MB左右），目录是否正确、拥有读写权限。

### 打不开软件
看看任务栏是否有新的窗口打开，。

### 提示“Code:Err2” 
拖拽功能加载时出错。使用“添加文件”的按钮来添加文件。

### 进度条不动
V1.2.1之后修复了该问题；如果之后的版本也出现了，请将日志（单击“展开控制台”，复制下方窗口中的一切文字）与截图发送到[LMSLuos的邮箱：LMSLuos@LMS.CN.eu.org](mailto:LMSLuos@LMS.CN.eu.org)，有空时会联系您解决。

### 转换出错
检查源文件是否损坏，转换途中是否操作了软件；大部分有弹窗提示您的错误都是您的文件或环境的问题；或者是您的杀毒软件误杀了，暂时关闭您的杀毒软件并重试。

### 转换出的文件模糊不清
默认的输出视频的分辨率为160x128，这是主流的MP4播放器的分片率。压缩视频的分辨率是为了节约您的存储空间（AMV格式因为历史问题，体积异常的大），模糊不清为正常现象；如果您的视频的竖版视频，您可以将画面旋转90°后再转换；后续更新会添加更改分辨率的功能，以适配更多型号的播放器。

### 更多
请将日志（单击“展开控制台”，复制下方窗口中的一切文字）与截图发送到[LMSLuos的邮箱：LMSLuos@LMS.CN.eu.org](mailto:LMSLuos@LMS.CN.eu.org)，有空时会联系您解决。

## 关于软件

本软件由[LMSCodeLuos](https://pre.lms.cn.eu.org/lmsluos)开发，使用Python语言。

软件支持Windows8以上的操作系统。

本软件[开源](https://files.lms.cn.eu.org/v3/Software/LMSCode_AMV_Convert/SourceCode/)；调用了[FFmpeg](https://ffmpeg.org)。

更新日志均发布在[LMSOnlineBolg](https://blog.lms.cn.eu.org)。
