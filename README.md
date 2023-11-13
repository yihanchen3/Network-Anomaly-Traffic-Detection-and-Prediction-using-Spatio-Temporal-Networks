# Detection and Prediction of Network Anomaly Traffic using Spatio-Temporal Hybrid Networks
- `requirements.txt`: Environment libraries required to run the code.

## Anomaly Traffic Detection Model
- `traffic_detect.ipynb`: Code for classifying traffic anomalies, with results stored in the `train` folder.
- `Dataset`: Raw data used for model training.
- `dataframe.xlsx`: Preprocessed raw data, can be directly read.
- `train`: Folder containing files generated after training, organized by date. Includes training results (`result.txt`), the trained model (`trained_model.h5`), and intermediate images.

## Future Traffic Prediction Model
- `traffic_predict.ipynb`: Code for predicting traffic, with results stored in the `predict` folder.
- `Dataset`: Raw data used for model training.
- `predict`: Folder containing files generated after training, organized by date. Includes training results (`result.txt`), the trained model (`trained_model.h5`), and intermediate images.


# 基于时空混合网络的数据中心网络攻击流量实时检测方法
- requirement.txt: 运行代码文件所需要的环境库
## 异常流量检测模型
- traffic_detect.ipynb: 对流量进行异常分类的代码，结果保存在train文件夹下
- Dataset: 该文件夹下为模型训练所使用的原始数据
- dataframe.xlsx: 预处理后的原始数据，可以直接读取
- train: 该文件夹下按日期保存训练后生成的文件，包括训练结果result.txt，模型trained_model.h5以及中间图片
## 未来流量预测模型
- traffic_predict.ipynb: 对流量进行预测的代码，结果保存在predict文件夹下
- Dataset: 该文件夹下为模型训练所使用的原始数据
- predict: 该文件夹下按日期保存训练后生成的文件，包括训练结果result.txt，模型trained_model.h5以及中间图片
