## 项目仓库介绍
介绍本新手的一些代码仓库，主要是一些学习demo、论文代码复现、实习项目、课程作业、日常刷题的代码备份. 

### [Func-Loop-Profiler](https://github.com/meton-robean/Func-Loop-Profiler)  
基于PIn动态插桩框架的函数-循环嵌套关系分析工具,可以分析程序执行的函数-循环的嵌套关系、找出程序中耗时并且有优化潜力的循环、提供类似gprof的终端显示和可视化流图显示.    

![工具分析结果](/images/callgraph1.png)


### [goDeviceServer](https://github.com/meton-robean/goDeviceServer)  
项目参与的一个基于golang的物联网后台项目. 该后台用于对接响其他前继的java服务发来的设备控制请求、以及管理控制lora物联网网关设备集群.基于这两个明确的需求，该系统也清晰的分为WechatAPI和DeviceServer两部分，以实现维护上的功能解耦.  

![系统架构](/images/lockserver.png)  


### [CFG-DFG-generator](https://github.com/meton-robean/CFG_DFG_generator)  
generating DFG and CFG from source code (using LLVM ) or from binary (using LLVM and Mcsema)  
基于LLVM PASS分析的二进制或者源码转CGF& DFG 工具,支持可视化绘制. 二进制逆向需要Mcsema支持.    

![DFG-CFG](/images/f3_dfg.png)    

### [chipyard_accelerators]()  
基于rocketchip开发的一些加速器和generators部件集合,目前该项目仍在开发中，处于私有仓库管理中.   



### [Vector_MulAdd_Accelerator](https://github.com/meton-robean/Vector_MulAdd_Accelerator)  
  基于Rocketchip RoCC的向量乘法累加加速器简单demo,支持浮点运算. 使用chisel3(一个scala的子集语言)开发.  


### [Multi-Gans-Deraining](https://github.com/meton-robean/Multi-Gans-Deraining)  
机器学习课程的一个作业, 基于多个GANs的层次化single image deraining 的探究.  

### [ICanSeeClearyNow_unofficial](https://github.com/meton-robean/ICanSeeClearyNow_unofficial)  
论文复现: I Can See Clearly Now : Image Restoration via De-Raining  unofficial code implementation(pytorch)


### [Xposed_ActivityLaunchingHooking_Analysis](https://github.com/meton-robean/Xposed_ActivityLaunchingHooking_Analysis)  
利用Xposed分析Android Activity组件启动底层细节与生命周期.  


### [BZTools](https://github.com/meton-robean/BZTools) 
用于测试Lora终端节点与[LockServer](https://github.com/meton-robean/LockServer)后台系统通信是否正常的Android App工具. 实现在手机App中与管理后台通信即可进行测试，方便线下测试安装工作.  

### [FaceDetect](https://github.com/meton-robean/FaceDetect)  
人脸登录人脸检测App demo: 基于第三方SDK实现刷脸登陆、 基于android 自带的人脸检测库支持前后摄像头动态实时人脸捕捉 以及静态导入图片进行检测. 

### [32bits_MIPS_CPU](https://github.com/meton-robean/32bits_MIPS_CPU)  
基于logisim实现的单周期MIPS CPU仿真：32 bits MIPS CPU processor based on logisim


### [mavlink_rc_override_mannual_input](https://github.com/meton-robean/mavlink_rc_override_mannual_input)  
使用mavlink指令，通过树莓派开发板间接控制来对无人机进行姿态控制. 支持pixhawk飞控固件. 

### [SPO-BPNN-PID](https://github.com/meton-robean/SPO_BPNN_PID)  
基于粒子群优化的神经网络PID控制. 粒子群智能算法主要用于神经网络训练前的网络权重参数进行预搜索,以达到比随机初始化更好的效果.  

### [CommandLine_ChatRoom](https://github.com/meton-robean/CommandLine_ChatRoom)  
命令行聊天室，支持群聊，私聊，踢人下线，用户注册；chatroomv1.0没有公共聊天室群聊功能； chatroomV2.0添加了公共聊天室功能;  chatroomV3.0在此基础上改成Websocket版本


## **其他**：  
### [HandOnLeetcode](https://github.com/meton-robean/HandOnLeetCode)  
### [simple_algo_c++](https://github.com/meton-robean/simple_algorithm_test)  
### [calculation_method_matlab](https://github.com/meton-robean/calculation_method_matlab)  
一些算法刷题记录. 包括：算法、数据结构、数值方法. 