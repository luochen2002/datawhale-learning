### Lesson 1: Introduction, why do we need Artificial Intelligence (AI).

1. （10分）在英特尔这套AI课程系统中，我们一共有几个阶段的课程：

   A.1个

   B.2个

   **C.3个**

2. (10分)计算机可以通过什么设备去感知和了解所在的环境

   A.摄像头

   B.深度距离传感器

   C.声音接收器

   **D.以上都是**

3. (10分)判断正误：在上网搜索时，AI可以为我们推荐我们感兴趣的搜索结果

   **A.正确**

   B.错误

4. (10分)智能手机中的AI能够帮我们进行什么工作

   A.人脸识别

   B.声音识别

   **C.以上均可**

5. (10分)判断正误：由于信息时代的快速发展，每天产生的数据与信息不计其数，所以人类寻求使用人工智能（AI）的方式，制造出智能系统来帮助人类自己做信息的处理与判断

   **A.正确**

   B.错误

6. (10分)AI的应用领域十分广泛，如下是AI的应用领域的是：

   A.商品零售业

   B.公共交通

   C.视频监控

   **D.ALL**

7. (10分)在构建AI产品的过程中，Intel®为我们提供了什么工具来进行支持。

   A.$OpenFino^{TM}$工具套件

   **B.$OpenVINO^{TM}$工具套件**

   C.$OneVINO^{TM}$工具套件

8. (10分)OpenVINO的全称是Open Visual inference and Nerural network Optimization，是Intel专门为AI产品推出的一套解决方案工具集

   **A.正确**

   B.错误

9. (10分)下列关于$OpenVINO^{TM}$工具套件的说法，哪个是正确的？

   A.$OpenVINO^{TM}$工具套件免费提供开发者下载与使用

   B.$OpenVINO^{TM}$工具套件提供了一个开源版本

   C.$OpenVINO^{TM}$工具套件提供云服务计算

   D.$OpenVINO^{TM}$工具套件提供了学习资料，演示示例以及具体实例

   **E.A，B & D**

   F.ALL

10. (10分)$OpenVINO^{TM}$为AI学习者提供了包括模型，demo，以及使用手册等一切相关的学习资料，而不仅仅只是一个推理加速软件。

    **A.正确**

    B.错误



### Lesson 2: What is Video, what is computer vision, how do we accelerate it on modern computers.

1. (10分)判断正误：视频是由大量的图片通过连续快速放映而产生的连续性的动作。

   **A.正确**

   B.错误

2. (10分)判断正误：在课程中看到的滑雪图片，该图片由一个像素构成的。

   A.正确

   **B.错误**

3. (10分)如果有两张图像，若他们的像素点总数量相等，则他们是两张一样的图像。

   A.正确

   **B.错误**

4. (10分)当像素中的参数（R=255，G=0，B=0）时此像素显示红色，若像素中的参数为（R=0，G=0，B=255）时，该像素显示什么颜色：

   A.白色

   B.绿色

   **C.蓝色**

5. (10分)当改变图片中每个像素值，使每一点的像素值更改为它的周围8个像素的平均值，该图片会变得

   A.更清晰

   **B.更模糊**

   C.不变

6. (10分)图片中边缘的形成是由于在边缘两侧存在像素值的巨大差距

   **A.正确**

   B.错误

7. (10分)如果想要用图像去检测一些特定目标，我们可以去获取目标的什么特征

   A.角

   B.边缘

   C.线

   D.圆形

   **E.ALL**

8. (10分)OpenCV可在Intel的硬件上进行加速，它使用Intel芯片的特定单元来加速视觉程序的运行速度。

   **A.正确**

   B.错误

9. (10分)OpenCV作为一个常用的计算机视觉工具库，它能帮助我们做如下哪些操作

   A.读取/写入图像

   B.寻找图像边缘

   C.旋转图像

   **D.以上都是**

10. (10分)OpenCV已经包含在了OpenVINO的安装包里，因此只要安装了OpenVINO电脑里就已经完成了最新版本的OpenCV，不再需要另外单独安装。

    **A.正确**

    B.错误



### Lesson 3: How to accelerate Video processing

1. (10分)判断正误：一般来说，我们在互联网上观看一个1分钟的视频，此视频的文件大小为10GB.

   A.正确

   **B.错误**

2. (10分)为了减少视频大小，我们需要压缩视频，在视频压缩中我们需要使用冗余来替换掉视频中出现的重复性数据。视频冗余分为：

   A.时间冗余

   B.空间冗余

   C.以上都不是

   **D.A & B**

3. (10分)在被压缩后的视频中，用于存储全部像素值信息的帧是：

   **A.I帧**

   B.P帧

   C.B帧

4. (10分)I帧之间存在P帧，他们包含如何从上一个I帧生成此P帧需要的信息，通常P数据量是I帧的：

   **A.1/2**

   B.1/3

   C.1/4

5. (10分)视频中提到市面上比较主流的编解码格式H264，AVC又或者H265，HEVC，压缩速度是前一个的两倍，但是消耗的资源是三倍

   **A.正确**

   B.错误

6. (10分)Intel集成显卡Quick Sync Video技术是专为视频的加速所使用的

   **A.正确**

   B.错误

7. (10分)若需要Intel的CPU上，例如集成在Core处理器中的UHD630（GT2）集成显卡去同时解码1080p视频，以下多少路是可以实现的：

   A.10路

   B.30路

   C.50路

   **D.A & B**

8. (10分)Media-SDK位于集成显卡和VAAPI的上层，是Intel免费提供的，让你可以用c++ python在多平台上完成编解码工作，并且media-sdk也可以集成于OpenVINO工具包中。

   **A.正确**

   B.错误

9. (10分)判断正误：设定解压缩规则的是编码解码器，而视频文件实则类似于一个容器包含了视频流，音频流以及相关信息流。

   **A.正确**

   B.错误

10. (10分)Intel®的集成显卡作为视频处理的硬件，我们通过什么软件工具可以访问底层视频编解码单元以及相应的加速模块？

    A.OpenCV

    B.FFMPEG

    C.Gstreamer

    D.Intel® Media SDK

    **E.以上任意**



### Lesson 4: How to accelerate Neural Network for vision applications

1. (10分)判断正误：仅凭有4只脚和1条尾巴是不足以判断是否是一只小猫。所以用来判断小猫的是必须需要多层特征结构的神经网络

   **A.正确**

   B.错误

2. (10分)什么是训练：输入相应的数据集，应用由神经网络构成的函数，检测输出结果是否存在误差，然后从结果往回倒，并更改神经网络的权重，将结果错误率降到最低，不断重复这个过程，向神经网络输入大量的图片。更改权重并降低错误率，获得一个有特定权重的神经网络称之为训练。

   **A.正确**

   B.错误

3. (10分)向训练好的神经网络输入一张新的图像去让神经网络进行判断，并获得答案的过程称之为推理

   **A.正确**

   B.错误

4. (10分)理想情况下，当深度神经网络训练完成时，训练网络的误差将会：

   **A.趋近0**

   B.趋近1

   C.趋近100

5. (10分)深度学习模型应用于方方面面，以下是常用的模型分类是：

   A.物体分类

   B.目标追踪

   C.人脸识别

   D.图像分割

   **E.ALL**

6. (10分)计算机运行神经网络的性能取决于什么？

   A.神经网络本身的复杂度

   B.运行网络的所使用的不同性能的设备

   **C.A & B**

7. (10分)判断正误：模型优化器是一种基于Python*的工具，可将输入的训练模型从标准框架转换为统一的IR文件

   **A.正确**

   B.错误

8. (10分)英特尔®OpenVINO™DLDT最主要工作流程是怎样的？

   A.推理引擎->IR->模型优化器

   **B.模型优化器->IR->推理引擎**

   C.模型优化器->IR->模型下载器

9. (10分)判断正误：英特尔®OpenVINO™工具套件分发版专注于深度学习推理，而非训练

   **A.正确**

   B.错误

10. (10分)DLDT是OpenVINO的核心组件，它包括了什么组件？

    A.构建与执行AI解决方案与所需的一切资源

    B.可随时使用的实例与实用程序

    C.模型下载器

    **D.ALL**



### Lesson 5: Video Analytics pipeline

1. (10分)判断正误：在视频每帧图像处理流程中，在解码部分进行图像的缩放以及重定义大小操作。

   A.正确

   **B.错误**

2. (10分)解码的视频流可以通过什么途径获取？

   A.摄像头

   B.RTSP

   C.视频文件

   **D.ALL**

3. (10分)判断正误：Intel® Media SDK可以用于视频中图像的推理

   A.正确

   **B.错误**

4. (10分)实际应用中，当我们发现输入图片的质量不够好的时候，我们应该在哪个阶段进行相应的锐度和亮度调整：

   A.解码

   **B.前处理**

   C.编码

5. (10分)英特尔® OpenVINO™工具套件支持以下操作系统：

   A.CentOS*

   B.Ubuntu*

   C.Window® 10

   D.macOS*

   **E.以上全部**

6. (10分)判断正误：英特尔® OpenVINO™工具套件不支持传统的计算机视觉库，包括OpenCV和OpenVX*。

   A.正确

   **B.错误**

7. (10分)在OpenVINO™工具套件中，主要用于推理加速神经网络模型的模块是：

   **A.Deep learning Deployment toolkit**

   B.OpenCV

   C.Intel® Media SDK

   D.以上都是

8. (10分)实际上，每一帧的视频正确处理流程是什么？

   **A.解码，前处理，推理，后处理，编码**

   B.编码，解码，前处理，推理，后处理

   C.解码，前处理，后处理，编码，推理

9. (10分)跟踪行为是一个跨帧行为，需要在连续帧确认追踪的目标为同一个，并且同一个目标不需要再次检测以节约计算资源。

   **A.正确**

   B.错误

10. (10分)若要检测输入图片中的目标的特征，如目标的颜色，种类。可以先大致地从这一帧图片中分割出目标，再进行目标检测的推理。

    **A.正确**

    B.错误



### Lesson 6: Demos, OpenVINO at work

1. (10分)在视频中我们使用什么工具进行模型拓扑结构的查看？

   **A.Netron**

   B.GDB

   C.模型优化器

2. (10分)在视频的示例演示中，-i后面标记的是视频流的输出源位置，那么如果我们使用-i cam表示什么？

   A.文件输入视频

   B.互联网输入视频

   **C.摄像头输入视频**

3. (10分)如果要从使用CPU推理切换到使用集成显卡推理，我们需要修改哪个参数？

   A.-i

   **B.-d**

   C.-o

4. (10分)OpenVINO支持多通道，多路视频同时输入，并且可以进行同时解码同时推理的操作。

   **A.正确**

   B.错误

5. (10分)同样一台计算机上，实例分割演示运行速度较慢原因是计算机内存太小

   A.正确

   **B.错误**

6. (10分)视频演示中读入的模型文件是什么格式？

   **A..xml文件**

   B..h5文件

   C..bin文件

   D.h5和.xml文件

7. (10分)推理引擎允许开发人员使用哪些设备用于推理？

   A.CPU

   B.GPU

   C.VPU

   D.FPGA

   **E.以上全部**

   F.以上都不是

8. (10分)OpenVINO™预训练模型主题包括：

   A.面部检测

   B.行人检测

   C.车辆特征识别

   D.B 和 C

   **E.以上全部**

9. (10分)判断正误：一个计算机视觉应用中允许使用两个或者更多个模型

   **A.正确**

   B.错误

10. (10分)当某一开发者想要去设计一个统计商场人流的计算机视觉应用，通过课程中提到的行人追踪示例，将此示例应用于商场中摄像头上，每当此商场摄像头出现一个相同的人，则人流量数据统计总数加一。若只有一个摄像头，那么这个摄像头置于商场哪个位置会比较合适？

    A.卫生间

    B.停车场

    **C.商场行人进出大门**



### Lesson 7: The full flow, from Data to a product using Intel tools-Part 1.

1. (10分)在构建AI应用的流程中，哪一步是关键

   A.评测模型

   **B.选择系统**

   C.编解码测试

2. (10分)不论是前一代CPU apolloca-lake还是目前最新一代Tiger-lake都可以运行OpenVINO进行深度学习推理。

   **A.正确**

   B.错误

3. (10分)AI应用系统通过支持尽可能多的摄像头，尽可能多的视频流，来降低系统的整体成本

   **A.正确**

   B.错误

4. (10分)在实际的AI系统中，解码编码推理不是一起进行的

   A.正确

   **B.错误**

5. (10分)判断正误：英特尔® OpenVINO™工具套件对于深度学习推理，相比于不使用OpenVINO，同一个设备上运行性能会有较大提升

   **A.正确**

   B.错误

6. (10分)判断正误：推理引擎提供了一个API，你的应用可以使用该API定位特定的硬件

   **A.正确**

   B.错误

7. (10分)判断正误：使用Intel的CPU的推理效果一定比它的集成显卡性能好

   **A.错误**

   B.正确

8. (10分)判断正误：OpenVINO™不支持最新的Intel智能硬件，比如第二代神经电脑棒（NCS2）

   A.正确

   **B.错误**

9. (10分)在推理前必须准备好一个训练好的模型，构建这个模型的框架可以是：

   A.TensorFlow

   B.Caffe

   C.MXNet

   D.Kaldi

   E.A，B & D

   **F.ALL**

10. (10分)判断正误：在AI产品落地前，必须经过本地测试来确保实际推理性能满足理论设置的推理性能要求。

    **A.正确**

    B.错误



### Lesson 8: The full flow, from Data to a product using Intel tools-Part 2.

1. (10分)视频中提到检测分类分割的模型用什么工具进行标注

   **A.CVAT**

   B.AVCT

   C.CATV

2. (10分)模型优化器会对模型进行一定程度的修改，比如说：

   A.水平垂直融合

   B.添加删除层

   C.添加归一化，缩放

   D.调整输入大小尺寸

   **E.以上都是**

3. (10分)基准性能测试程序（benchmarApp）只要输入模型转换好的IR模型文件就可以进行性能测试

   **A.正确**

   B.错误

4. (10分)Devcloud是提供了各种型号的Intel硬件包括CPU，VPU，FPGA等等硬件，注册之后远程链接就可以进行使用。

   **A.正确**

   B.错误

5. (10分)DLworkbench是一款web端的模型OpenVINO推理性能评测工具，它在生成模型性能报告时有什么特点？

   A.拓扑可视化

   B.模型性能对比

   C.模型逐层分析

   **D.以上都是**

6. (10分)使用GSTREAMER可以将OpenVINO变成流程中的元素来快速构建视频分析流程，模拟实际情况的发生。

   **A.正确**

   B.错误

7. (10分)判断正误：英特尔® OpenVINO™工具套件提供了一个实用程序“模型下载器”，用于从互联网下载公开可用的预训练模型

   **A.正确**

   B.错误

8. (10分)在模型训练进行之前，必须准备好送入模型的数据集，以下4个对数据集的准备操作：（A-数据清洗，B-裁剪分离目标区域，C-收集数据，D-数据标注），正确的顺序是：

   A.B->C->A->D

   B.D->A->B->C

   **C.C->A->B->D**

   D.A->B->C->D

9. (10分)关于推理的性能评估，Intel®为开发者准备了多个工具，包括了：

   A.OpenVINO™工具套件中的Benchmark App

   B.Dev-Cloud

   C.DL Workbench

   **D.ALL**

10. (10分)判断正误：在AI开发的过程中，合理运用已经集成好的软件工具能减小开发工作量。例如，使用Gstreamer+OpenVINO™的组合，可以完整提供图像处理流程中的包括编解码，图像处理，以及图像推理的功能。

    **A.正确**

    B.错误



### Lesson 9: Summary, intro to next course (200)

1. (10分)视频的压缩目的是为了解决视频过大过多消耗资源的问题

   **A.正确**

   B.错误

2. (10分)视频是当今互联网传输的主要数据类型

   **A.正确**

   B.错误

3. (10分)像素 图片 视频之间的关系是怎样的？

   **A.像素组成图片，图片组成视频**

   B.像素组成视频，视频组成图片

4. (10分)Intel®的集成显卡可以用于加速视频的编解码，以及加速对于视频的相关操作

   **A.正确**

   B.错误

5. (10分)简单来说，什么是OpenVINO™？

   A.一种编程语言

   B.一种操作系统

   **C.一种工具套件**

   D.一家云服务提供商

6. (10分)OpenVINO提供了AI应用的一系列解决方案以及资源。

   **A.正确**

   B.错误

7. (10分)关于OpenVINO™工具套件的说法，以下正确的是：

   A.OpenVINO™工具套件能够进行模型的搭建以及模型的训练

   B.OpenVINO™工具套件针对提升的领域是模型的推理

   C.在使用OpenVINO™工具套件前，必须搭建并训练好自己的模型或者下载好已经训练好的模型

   D.OpenVINO™工具套件的意义在于能让开发者在使用Intel®任何硬件进行模型推理的时候，提高它的推理性能

   **E.B，C & D**

   F.ALL

8. (10分)OpenVINO™工具套件提供了许多Demo和示例供开发者进行初步学习，这些示例使用的开发语言有：

   A.C++

   B.Python

   C.Basic

   **D.A & B**

   E.ALL

9. (10分)OpenVINO的出现，有效的帮助了开发者在部署深度学习模型的时候，充分利用各种Intel的推理硬件来实现异构系统。

   **A.正确**

   B.错误

10. (10分)为了构建出一个成熟的AI产品，流程中包含什么步骤：

    A.模型评估

    B.性能评估

    C.硬件选择

    D.完整工作流程搭建

    E.A，C & D

    **F.ALL**



### Lesson 10: Introduction to the use of Intel DeCloud

1. (10分)Intel® DeCloud是一个在线沙盒平台，可以提供Intel物理硬件供用户远程登录使用。

   **A.正确**

   B.错误

2. (10分)Intel® DeCloud允许用户上传自己的数据集和模型到DevCloud云端进行推理

   **A.正确**

   B.错误

3. (10分)Intel® DeCloud的使用流程是怎样的？

   A.网页登陆--->推理任务部署--->链接至DevCloud服务器--->返回推理结果

   **B.网页登陆--->链接至DevCloud服务器--->推理任务部署--->返回推理结果**

   C.本地客户端登陆--->链接至DevCloud服务器--->推理任务部署--->返回推理结果

   D.本地客户端登陆--->推理任务部署--->链接至DevCloud服务器--->返回推理结果

4. (10分)判断：用户需要付费购买DevCloud的使用权限

   A.正确

   **B.错误**

5. (10分)Intel® DeCloud支持以下哪些功能？

   A.运行OpenVINO推理示例

   B.测试模型性能

   C.推理性能对比分析

   D.获取现成的AI解决方案

   **E.以上全部**

6. (10分)以下哪些推理硬件，用户可以在DevCloud中使用？

   A.英特尔® 至强® 处理器

   B.英特尔® Movidius™ 视觉处理器

   C.英特尔® 酷睿™ 处理器

   D.英特尔凌动® 处理器

   **E.以上全部**

