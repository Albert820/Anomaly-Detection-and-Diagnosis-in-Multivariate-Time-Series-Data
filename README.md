# A Deep Neural Network for Unsupervised Anomaly Detection and Diagnosis in Multivariate Time Series Data

這是使用PyTorch實作MSCRED

論文原文： http://in.arxiv.org/abs/1811.08055

我參照的程式網址: https://github.com/Zhang-Zhi-Jie/Pytorch-MSCRED
我是參照該網址的程式碼，做了些修改，可以將合成資料的異常點順利偵測出來。

此項目具體流程如下：

先將時間序列資料轉換為 image matrices

執行 ./utils/matrix_generator.ipynb

然後訓練模型並對測試集產生對應的reconstructed matrices

執行 main.ipynb

最後評估模型，結果存在outputs資料夾中

執行 ./utils/evaluate.ipynb
