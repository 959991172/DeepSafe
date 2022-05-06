# DeepSocial: COVID-19大流行中的社会距离监测和感染风险评估

本教程讲述了一种监测社会距离和评估感染风险的方法。

* 在 `infer.ipynb` 中，主要介绍了监测社会距离和评估感染风险的推理过程，你可以输入一段行人视频，得到对应的社会距离监测和感染风险评估信息。


本教程主要演示了：

- 编译YOLO
- 社会距离监测和感染风险评估的推理过程


<video id="video" controls="" preload="none" >
<source id="mp4" src="/openbayes/home/darknet/DeepSOCIAL DTC.mp4" type="video/mp4">
</video>



## 代码目录

### infer：

- 准备代码环境
- 编译Yolo
- 使用Darknet的python接口
- 使用SORT来实时跟踪目标
- 输入设置
- DeepSocial参数设置和函数引入
- 推理过程
- 展示结果



> 注意事项：
> * 本教程推荐使用GPU运行

## 引用文献：

- DeepSOCIAL: Social Distancing Monitoring and Infection Risk Assessment in COVID-19 Pandemic
- Mahdi Rezaei and Mohsen Azarmi [https://www.mdpi.com/2076-3417/10/21/7514)