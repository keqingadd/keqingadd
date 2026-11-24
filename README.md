# Hi, 我是 孙玉杰 👋

[![2027 届](https://img.shields.io/badge/2027届-本科-blue)](#)
[![AI](https://img.shields.io/badge/AI-算法_·_机器视觉_·_数据分析-2ea44f)](#)
[![Location](https://img.shields.io/badge/目标城市-苏州_·_南京-orange)](#)

人工智能本科生（2027 届），方向：**计算机视觉 / 时间序列预测 / 语音信号处理**。
习惯用「基线 + 对照实验 + 指标」把问题讲清楚，而不是只报一个漂亮的数字。

## 项目

| 项目 | 一句话 | 亮点 |
|---|---|---|
| [power-load-forecasting](https://github.com/keqingadd/power-load-forecasting) | 电力负荷 15 分钟粒度多步预测（毕业设计·在研） | LSTM+Attention vs LightGBM vs 季节朴素基线；单步 MAPE 2.89%（基线 8.23%）；96 步递归+残差 MAE 6,492→4,583 kW；分位数区间 PICP 79.27% |
| [traffic-sign-recognition](https://github.com/keqingadd/traffic-sign-recognition) | GTSRB 43 类交通标志识别 | LeNet-5 测试集 **98.98%**、宏 F1 0.9897；自定义 CNN 83.20% 作对照；混淆矩阵 + 逐类 P/R/F1 |
| [sales-forecasting](https://github.com/keqingadd/sales-forecasting) | Alcohol Sales 月度销量预测 | 同管线同超参对比 LSTM(45,440) 与 GRU(43,695)，GRU 收敛更快 |
| [speech-processing](https://github.com/keqingadd/speech-processing) | 智能语音处理实验集 | **不用 librosa**，手写 Mel 滤波器组 + DCT 实现 MFCC/FBank；双门限端点检测；24bit WAV 读写与 TTS 拼接 |
| [unet-image-segmentation](https://github.com/keqingadd/unet-image-segmentation) | 传统阈值 vs U-Net 分割对比 | 全局阈值 / Otsu / 自适应 / K-means 与 U-Net 同图对比，说明"空间先验"的价值 |

## 技术栈

![Python](https://img.shields.io/badge/Python-主力-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-CNN_/_LSTM_/_U--Net-EE4C2C?logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-调参_/_Pipeline-F7931E?logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-图像处理-5C3EE8?logo=opencv&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-特征工程-150458?logo=pandas&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-基线模型-9ACD32)
![C](https://img.shields.io/badge/C-嵌入式课程-A8B9CC?logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-基础查询-4479A1)

## 正在找

2027 届校招 / 实习：**AI 算法、机器视觉、数据分析**方向，目标城市 **苏州、南京**，可全职实习。

- 简历与项目复盘：见各仓库 README 的「复现」章节，指标、数据口径、失败实验都写清楚了
- 面试可直接发上面任意仓库链接

## 其他

- 关注方向：工业视觉质检、能源时序预测、端侧推理
- 目前在做的毕设：带外生变量与区间输出的电力负荷多步预测（含 Streamlit 原型）
