# myNN-repository
Repositry for neural network

###########目录结构描述


        data                        // 数据文件
        code                        // 代码文件
            models                  // 训练好的模型文件
            results                 // 结果文件
            utils.py                // 工具代码
            reg_lstm.py             // 训练并优化lstm模型
            reg_gru.py              // 训练并优化gru模型
            reg_rnn.py              // 训练并优化rnn模型
            train.py                 // 同时训练三个模型
	      predicty.py             // 用于模型预测


### 安装环境
python环境为3.8.3 

第三方依赖
pip install torch scikit-learn pandas numpy matplotlib icecream

###实验环境
ubuntu18 64位

###数据集链接
https://aistudio.baidu.com/aistudio/datasetdetail/107857

### 使用说明
进行code中，在命令行下使用
```
python train.py 开始训练模型
python predict.py 开始预测 
```
