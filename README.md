# KK跑--痛快淋漓的跑步叭
#### ————From Noah Yu（于彦宽）
#### ——如果您需要运行此小程序，请记得在微信小程序编译器编译之前删除screenshot文件夹，这个文件夹无实际意义，其中均为程序运行截图，微信小程序编译器编译有包大小限制，请注意——
***
## **说明：** 
### 这是一款微信小程序的Demo，主要功能是记录位置，将位置信息获取下来并且标记，并在地图上画点，用于可视化显示行走路径。
### 主要功能
- [x] 初始页面
  - [x] 设计图标
  - [x] 宣传标语
  - [x] 点击模块：开始跑步按钮
- [x] 进入页面
  - [x] 打开位置模块
  - [x] 开始跑步模块
  - [x] 暂停跑步模块
  - [x] 数值数据显示模块（里程数、所用时间）
  - [x] 可视化数据显示模块（地图、路径可视化显示）
***
***
# ***使用方法及功能展示***
### 首先打开微信，下拉最近使用小程序或者搜索栏搜索“散步轨迹”
![搜索栏](https://github.com/yuyankuan/WeChatRunning/blob/main/screenshot/sousuolan.jpg) 
***
### 点击打开此微信小程序，即可到达初始界面(首页)
![首页](https://github.com/yuyankuan/WeChatRunning/blob/main/screenshot/shouye.jpg)
***
### 点击“开始跑步”按钮即可进入功能区
![功能页面](https://github.com/yuyankuan/WeChatRunning/blob/main/screenshot/gongnengye.jpg)
***
### 点击“打开位置”，通过您的位置信息授权，即可获取您的当前位置
#### （这里的地图调用的是微信小程序开发自带的腾讯公开地图API）
![位置授权](https://github.com/yuyankuan/WeChatRunning/blob/main/screenshot/huoquweizhi.jpg)
![粗略定位](https://github.com/yuyankuan/WeChatRunning/blob/main/screenshot/dingwei2.jpg)
![精细定位](https://github.com/yuyankuan/WeChatRunning/blob/main/screenshot/dingwei1.jpg)
***
### 返回之后点击“开始跑步”即可开始记录您的“里程数（单位km）”、“所用时间”，以及地图上的“路径数据可视化”

#### （本次测试路经我校区实验楼三号楼，穿插崇学路途径图书馆北侧，最终到达男生宿舍楼9号楼。共计0.55km，用时7分47秒）
![数据可视化](https://github.com/yuyankuan/WeChatRunning/blob/main/screenshot/guijikeshihua.jpg)
***
### 如需暂停使用本小程序功能，可以点击“暂停跑步”按钮，即可使后台程序停止获取您的位置信息

***
### 后台获取具体数据如下图所示
![调试概览](https://github.com/yuyankuan/WeChatRunning/blob/main/screenshot/tiaoshi1.JPG)
![数据结构](https://github.com/yuyankuan/WeChatRunning/blob/main/screenshot/tiaoshi2.JPG)
