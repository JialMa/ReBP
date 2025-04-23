# ReBP
项目简介
ReBP项目中上传的数据集为实验采集的原始数据及预处理结果，旨在为后续信号处理、特征提取及建模研究提供支持。

数据说明
本项目的数据文件格式为 .mat，每个 .mat 文件中包含以下四类数据：

rawdata
初步处理的毫米波雷达信号数据。

wavedata
经过自适应滤波处理后的毫米波雷达信号，用于后续特征提取与分析。

ppgdata
同步采集的光电容积描记（PPG）信号数据。

name
字符串类型，标识文件名，编码包含血压参考值：

S 后为收缩压（Systolic Blood Pressure, SBP）值

D 后为舒张压（Diastolic Blood Pressure, DBP）值
