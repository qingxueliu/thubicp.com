# thubicp.com
Tsinghua University Brain-Inspired Computing Research Center
BICPT SBPU-C4 Platform Open Source Project documentation and Code

=================SBPU-C4 ======================
SBPU-C4是天机的pcie类型的板卡，是当前主力推送的形态，该形态已建立完整的文档和工具链说明，如下内容包括：加速卡手册说明、deb格式的driver包、deb格式的sdk、resnet50命令行验证、resnet50 GUI验证、后期将同步更多的原生云相关的材料

01 SBPU集成环境资料包目录结构.
├── 00 天机Sbpu-demo环境搭建全流程文档---d.pdf
├── 01 pcie驱动
│   ├── drv
│   ├── intel_fpga_pcie_ip_params.h
│   ├── PCIE
│   ├── prt
│   └── user
├── 01 pcie驱动安装文档.pdf
├── 02 pcie传输层接口
│   ├── pcie_recog719(725)(811)(复件)
│   ├── pcie_recog719(725)(stable)
│   └── Readme.txt
├── 02 pcie传输层接口启动.pdf
├── 03 ros框架dvpp运行流程.pdf
├── 03 ros框架下dvpp包catkin_ws
│   ├── 1.txt
│   ├── dvpp.launch
│   └── src
├── 04 qt工程启动流程.pdf
├── 04 qt 显示工程包
│   ├── build-img_show-Desktop_Qt_5_12_6_GCC_64bit-Debug
│   ├── build-img_show-Desktop_Qt_5_12_6_GCC_64bit-Release
│   ├── img_show
│   └── img_show 0826--17_25.zip
├── 05 SBPU逻辑
│   └── sbpu_sof_两版工程
└── 请先看Readme.txt



=================EBPU ======================
02 Ebpu集成环境资料包目录结构.EBPU是面向嵌入式应用的平台，其主力接口是千兆以太，目前传输速率可达700Mbps，如下内容包括：EBPU手册说明、UDP-Driver等
├── 00 天机Ebpu-demo环境搭建全流程文档---d.pdf
├── 01 UDP驱动
│   ├── drv
│   ├── intel_fpga_UDP_ip_params.h
│   ├── UDP
│   ├── prt
│   └── user
├── 01 UDP驱动安装文档.pdf
├── 02 UDP传输层接口
│   ├── UDP_recog719(725)(811)(复件)
│   ├── UDP_recog719(725)(stable)
│   └── Readme.txt
├── 02 UDP传输层接口启动.pdf
├── 03 ros框架dvpp运行流程.pdf
├── 03 ros框架下dvpp包catkin_ws
│   ├── 1.txt
│   ├── dvpp.launch
│   └── src
├── 04 qt工程启动流程.pdf
├── 04 qt 显示工程包
│   ├── build-img_show-Desktop_Qt_5_12_6_GCC_64bit-Debug
│   ├── build-img_show-Desktop_Qt_5_12_6_GCC_64bit-Release
│   ├── img_show
│   └── img_show 0826--17_25.zip
├── 05 Ebpu逻辑
│   └── Ebpu_sof_两版工程
└── 请先看Readme.txt

=================BICM Toolkit工作栈-Bitorm======================
（1）. BICM Toolkit基于单纯linux平台或者ros平台；
（2）. BICM Toolkit提供EBPU版本的UDP和SBPU(CBPU)版本的pcie的SDK包
（3）. BICM Toolkit将模型获取、模型测试和初始化、模型部署分成解耦的三个部分，使得不同领域的小伙伴能够独立工作；
（4）. BICM Toolkit提供QT口，方便用户按照自有场景参与实际部署；
（5）. BICM Toolkit具备完成的视频等格式的处理包、针对不同层次的天机控制器的编程包、以及适应多用户的中间件；
（6）. BICM Toolkit能够嵌入ROS生态，进行移动平台的部署形式
（7）. BICM组件众多，满足相应要求；
（8）. BICM具有丰富的调试组件和调试方案，提供动态调试方案；
（9）. BICM目标是实现的案例包括resnet、mnist、dvs-net、snn-net、mtn-net网络，满足不同部署者的参考需求；
（10）.  以上总结，使用BICM Toolkit，能够加速天机类脑平台的部署速度。

