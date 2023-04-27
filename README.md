# home-assistant
A Complete Smart Home Solution

### 本项目对应于《HomeAssistant智能家居实战篇》系列内容中的文档。
[home-assisant.msly.cn](https://home-assisant.msly.cn)

## 目录
1. [home assisant project-install home assisant core 2022.3.0 on Raspberry Pi3b+](https://github.com/freemsly/home-assistant/blob/main/home-assisant-core-install.MD)
	- 硬件环境准备——安装树莓派
	- 系统环境设置——树莓派基础配置
	- 安装Samba和JupyterNotebook
	- 基于树莓派安装HomeAssistant
	- [HomeAssistant配置、文件结构、升级]
	  - [Home Assistant Core upgrage](https://www.msly.cn/boards/topic/57/installing-home-assistant-core-on-raspberry-pi-3b/page/2#3590)
        - [HomeAssistant自启动如何配置]
	- [HomeAssistant core 20221102配置、文件结构、升级]
	  - [change Home Assistnant Core default port](https://www.msly.cn/boards/topic/13395/quick-start#18747)
	- [Other]
	  - [How to Install Home Assistant core 2022.3.0 on Ubuntu 20.04（vultr VPS） Step by Step](https://www.iaspnetcore.com/Blog/BlogPost/624b26f5bc7b674a02f93b86/how-to-install-home-assistant-core-202230-on-ubuntu-2004vultr-vps-step-by-step)
	  - [How to Get the correct Debian ISO](https://www.matterxiaomi.com/boards/topic/36/debian-11-bullseye-installation#63)
	
	
	
	
2. 组件接入基础篇
	- 让设备发声——朗读文字
	- 让设备看到——使用手机摄像头做监控
	- 将消息发送给你的邮箱
	- 接入硬件产品——小米多功能网关
	- 接入自定义组件-和风天气
3. 操作进阶篇
	- 配置目录、hass命令与升级
	- 操作界面与Lovelace
	- 设置地理位置与界面语言
	- 实体显示属性自定义
	- 手机访问HA
	- StatesUI界面优化——分组与分页
4. [home assisant project-remote access on Raspberry Pi3b+](https://github.com/freemsly/home-assistant/blob/main/home-assisant-remote.MD)
	- 申请Amazon免费云主机
	- [buy a domain from www.namesilo.com](https://www.iaspnetcore.com/Blog/BlogPost/5eb9e65e775d020216dbe009/wwwnamesilocom-registration-and-domain-name-purchase-operation-manual)
	- frp隧道构建
	- 免费为HA配上域名与HTTPS网站证书
	- nginx代理
	- [Install Let’s Encrypt Client Certbot](https://www.iaspnetcore.com/blogpost-619a0dbd5b26cb0202ae5bf1-how-to-secure-nginx-with-lets-encrypt-on-ubuntu-1804vultr#mcetoc_1g3p82cte53)		
5. 设备位置追踪篇
	- 设备定位准备知识与Ping检测
	- nmap网络扫描、黑客、小米wifi路由器
	- [home assisant project-Play audio on a Bluetooth speaker with Raspberry Pi3b+](https://github.com/freemsly/home-assistant/blob/main/home-assisant-bluetooth-speaker.MD)
	- 使用iCloud随时定位苹果手机
6. 自动化篇
	- 编写简单脚本——执行系列动作
	- 编写简单自动化规则
	- 模板——嵌入配置文件中的程序
	- 事件与事件消息接收
	- 前端输入组件+packages配置
	- 语音+音乐+灯光闹钟
7. 设备接入篇(1)
	- 太阳、月亮、季节和潮汐
	- 天气与预报——yr、DarkSky、……
	- 红外遥控——博联RM系列产品
	- 红外遥控——小米万能遥控器
	- 文件夹监测——FolderWatche
8. 设备接入篇(2)   aqara 
	- [aqara hub M1s](https://www.msly.cn/boards/topic/5278/aqara-gatewayhub-g2h-m1s-cn-p3-cn-m2-cn-h1-cn-e1-cn-g3-cn-g2h-pro-integration-for-home-assistant#18735)
	
	
8. 各种摄像头接入篇
	- 支持MJPEG的摄像头与图片抓取
	- RTSP协议摄像头与ffmpeg
	- ONVIF协议摄像头
	- 有线树莓派CSI与USB摄像头
	- 小米的大方摄像头
	- 天气预报与交通状况图——另类摄像头
9. 人脸识别篇
	- DLib配置与pip安装
	- 本地DLib人脸探测
	- 本地DLib人脸识别
	- 微软人脸特征检测
	- 微软人脸识别与验证
	- Facebox-在docker中运行人脸识别
10. 设备接入篇（2）
	- YeeLight智能灯
	- 云端的自动化——IFTTT(1)
	- 云端的自动化——IFTTT(2)
	- 系统性能监控——SystemMonitor
	- 以不同的音色播报文字——百度tts
11. 使用苹果设备语音控制篇
	- 通过Homekit与苹果Siri连接(1)
	- 通过Homekit与苹果Siri连接(2)
	- 捷径与HA的接口调用
	- 在HA中完成语音文字处理——chrome语音控制
	- 苹果设备语音控制全自由定制
12. 数据记录篇
	- 历史数据基础概念
	- 数据组件的配置、mysql数据库及其它
13. AppDaemon与DashBoard
	- 安装、配置与初步运行
	- DashBoard配置(1)
	- DashBoard配置(2)
	- 制作App——一个最简单的样例
	- 制作App——应用callback
14. Node-RED篇
	- Node-RED安装与初体验
	- Node-RED配置
	- HomeAssistant节点(1)
	- HomeAssistant节点(2)
	- 一些样例：闹钟、自动湿度控制、门铃
15. 树莓派GPIO口设备连接篇
	- 直连树莓派的LED(1)——NodeRED接入/HA中rpi_gpio_pwm组件
	- 直连树莓派的LED(2)——HA 中的shell_command/binary_sensor.command_line/light.template
	- 直连树莓派的温湿度传感器
16. MQTT篇
	- 服务器安装与最简单的智能灯
	- 主题格式、状态反馈、调试……
	- QoS、retain、last_will、自动配置……
17. DIY智能硬件ESP8266篇
	- ESP8266——固件烧录与连接
	- ESP8266上的MicroPython使用
	- 连接ESP8266的DHT温湿度传感器
	- ESP8266完成各种功能
	- 典型样例讲解：光照传感器与智能灯
	- ESPHome——不编程，集成ESP8266
18. 成为HomeAssistant开发者
	- 组件的工作原理
	- 程序样例：二维码识别组件
	- Python程序员的成长与代码规范
	- 把你的代码贡献给组织
19. IOS App的使用
	- IOS App——连接、定位与通知消息
	- iBeacon定位
	- 多媒体通知与静态文件Web服务
20. Lovelace定制界面
	- 理解Lovelace页面的结构
	- Lovelace中的卡片
	- 使用自定义lovelace卡片
21. 抓取Internet信息作为传感器
	- 即时股票行情——使用sensor.rest
	- 各种网站页面元素——sensor.scrape组件
22. 自己动手做一个智能音箱
	- DIY智能音箱（1）——整体架构、硬件安装
	- DIY智能音箱（2）——snowboy、speech_recognition
	- DIY智能音箱（3）——完成主程序架构
	- DIY智能音箱（4）——与HomeAssistant交互
	- 完善（1）——更好的音色、更多的指令
	- 完善（2）——准确回答任意问题
	- 完善（3）——自定义唤醒词与敏感度
	- 完善（4）——使用微软语音识别服务
	- 最后一课——积木构建智慧空间
23. 音乐灯带
	- 音乐灯带——硬件连接与基本使用
	- 音乐灯带——接入ESPHome(1)
	- 音乐灯带——接入ESPHome(2)
	- Arduino与ESP硬件
	- 音乐灯带——音频处理过程与Arduino平台编译
24. 远程麦克风
	- 声音信号的采集与播放
	- 接入HomeAssistant的远程麦克风
	- 使用远程麦克风——监听与录音
	- 给智能音箱配上远程麦克风
25. 485总线
	- 实现485总线通讯
	- 接入自定义ascii码指令集的设备
	- 接入modbus设备
	- 自定义二进制命令设备的接入
26. KNX
	- 家庭总线部署方案与KNX
	- 使用IPRouter接入HomeAssistant
	- 使用ncn5120模块-USB连接模式
	- 使用ncn5120模块-WIFI连接模式
27. 室外物联网
	- 全球卫星定位
	- NB-IOT
	- 车载定位(1)—traccar安装与配置
	- 车载定位(2)—车载设备diy
28. docker
	- docker基础(1)
	- docker基础(2)
	- HomeAssistant的docker安装
	- HomeAssistant docker容器的典型使用
	- HomeAssistant docker容器的非典型使用
28. DIY红外与433转发设备
	- 使用红外与无线模块(1)——红外接收
	- 使用红外与无线模块(2)——红外发射
	- 使用红外与无线模块(3)——无线收发
	- 硬件制作(1)——画电路图
	- 硬件制作(2)——画PCB板
	- 硬件制作(3)——元器件与焊接
- 补充篇章
	- Linux下的常用命令
	- Linux下的文本编辑
	- YAML文件格式
	- Python虚拟环境
- 加餐
	- 使用TensorFlow进行物体识别
	- 使用NFC识别不同的ID卡
	- ESPHome中的自动化
	- 制作树莓派镜像文件(1)
	- 制作树莓派镜像文件(2)
- 学员成果秀
	- 语音播报床头灯(by Espoir)
	- 感应伴随灯带(by ZackXu)
	- 屏幕感应背光灯带(by ZackXu)
	- HA实时直播画面(by Bobo)
- 精彩众创教程
	- 魔镜系列——魔镜安装(by JonnyWong)
	- 魔镜系列：天气组件openweather(by JonnyWong)
	- 魔镜系列：第三方组件WeeklySchedule(by JonnyWong)
	- 魔镜系列：获取HomeAssistant中实体状态(by JonnyWong)
	- 魔镜系列：联动智能音箱(by JonnyWong)
	- 在群晖中安装ESPHome(by Bobo)
	- ESPHome-SonoffBasic完整接入过程(by Bobo)
	- ESPHome-接入SonoffRF(by Bobo)
	- ESPHome-接入SonoffPow(by Bobo)
	- ESPHome-接入Sonoff4CH4路继电器(by Bobo)
	- ESPHome-H801玩转RGB+冷暖光(by Bobo)
	- Esphome-空气质量传感器(by Bobo)
	- EspHome-DIY小屏幕(by Bobo)
	- 设计与制作PCB板(by Zack-Xu)
	- 树莓派安装HASS.IO(by Zack-Xu)
	- HASSIO.IO与常规运行环境区别(by Zack-Xu)
	- x86下ubuntu虚机及HomeAssistant安装（by 猛将兄）
4. matterxiaom
	- [create vps on vultr](https://www.iaspnetcore.com/Blog/BlogPost/6199ff495b26cb0202ad6ce8/how-to-deploy-a-new-instance-on-vultr-step-by-step)
	- [Install xshell7 on windows 10](https://www.iaspnetcore.com/Blog/blogpost/635d3024da4aea5b6ab5891e)
	- [How to Install and uninstall reinstall  upgrade .NET on Ubuntu 18.04 64](https://www.iaspnetcore.com/Blog/BlogPost/618a75d3635c733c81dc77c3/how-to-install-and-uninstall-reinstall-upgrade-net-6x-on-ubuntu-180464-step-by-step)
	- [How to Deploying Real World ASP.NET Core  on Ubuntu 18.04 step by step](https://www.iaspnetcore.com/Blog/BlogPost/5d9833c672c1772b244aa228/how-to-deploying-real-world-aspnet-core-3x-on-ubuntu-1804-step-by-step)
	- [How To Install and uninstall reinstall Nginx on Ubuntu 18.04（aliyun/vultr）](https://www.iaspnetcore.com/Blog/BlogPost/5d9865cc72c1772b244afe0f/how-to-install-and-uninstall-reinstall-nginx-on-ubuntu-1804aliyun)
	- [Firewall Setup on vultr](https://www.iaspnetcore.com/Blog/BlogPost/6199ff495b26cb0202ad6ce8/how-to-deploy-a-new-instance-on-vultr-step-by-step#mcetoc_1g2gdbgp550)
	- [www.namesilo.com](https://www.iaspnetcore.com/Blog/BlogPost/5eb9e65e775d020216dbe009/wwwnamesilo-operation-manual-for-com-registration-and-domain-name-purchase)
	- [CloudFlare](https://www.iaspnetcore.com/Blog/BlogPost/5ee3a43a1c73d43127f113a1/cloudflare-free-cdn-website-acceleration-practice-tutorial#mcetoc_1g37gn9lf11)
	- Basic Firewall Setup
	- [How To Install and uninstall reinstall Mysql on Ubuntu 18.04（vultr）](https://www.iaspnetcore.com/blogpost-6449555969967f028d52f122-how-to-install-and-uninstall-reinstall-mysql-on-ubuntu-1804vultr)	
		

## Useful links
1. 真实<br>
https://github.com/sl041400/Home-assistant

2. 小米有品<br>
https://www.xiaomiyoupin.com/

3. 快节奏<br>
重点展现实践操作过程。如果不是仅追求效果的话，需要自己补充对应的知识。实践——思考——学习

4. 精心选择的实践与操作内容<br>
全面、避免不成熟的技术方向、避免陷入超出知识体系范畴之外的坑中

5. 便宜、实用<br>
几百元的硬件投入，就可以实践几乎所有的视频内容
