# Python数据分析项目实战

这是一个基于技术指标与时间序列建模的股票价格预测研究项目，采用Python进行数据分析和建模。项目使用了多种技术指标与时间序列模型，如ARIMA、Prophet、LSTM和LightGBM，来预测股票价格，并进行比较和评估。

## 环境配置

在开始之前，确保您的计算机已安装以下环境和库。

### 1. 安装 Python

确保您已安装 Python 3.x 版本。可以通过以下命令检查您的 Python 版本：

```bash
python --version
```

### 3. 安装依赖库

安装以下依赖

```
pandas
numpy
matplotlib
seaborn
scikit-learn
statsmodels
prophet
tensorflow
lightgbm
yfinance
tushare
pandas-ta
ta-lib
```

## 使用说明

​		首先先运行python数据处理-数据获取与预处理代码，获取数据并进行预处理，本项目使用 `yfinance` 和 `Tushare` 库来获取股票数据。

​		然后在模型训练前，我们首先通过 `pandas-ta` 和 `ta-lib` 库计算技术指标，包括但不限于：MA（移动平均）、MACD（指数平滑异同移动平均线）、RSI（相对强弱指数）、BOLL（布林带）

再进行模型训练与预测，本项目包含多个预测模型：ARIMA模型、Prophet模型、LightGBM模型。分别使用不同的时间序列建模方法和机器学习模型。