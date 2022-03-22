# 深度學習


# Table of Contents

1 ) Importing Various Modules(匯入模組)

2 ) Preparing the Data(資料準備)

3 ) Modelling(建構模型)

4 ) Evaluating the Model Performance(評估分析)


# 匯入模組
- 

# 資料準備
- 製作函數以便從圖像中獲取訓練集和驗證集
- Splitting into Training and Validation Sets
- Setting the Random Seeds

# 建構模組
- 影像資料增補(dataaugmentation)
- Create Sequential model with using Keras
- 輸出模型摘要資訊
- reduce the learnng rate
- compile model : 選擇損失函數、優化方法及成效衡量方式
- training進行訓練, 將訓練過程會存在 history 變數中(epochs=30)

# 評估分析
-  classification  report 成果
-  Plotting learning curves

# Conclusion
- train loss 不斷下降，val loss不斷下降，說明網路仍在學習
- Accuracy rate exceeded 75% limit while in the training phase. In the same way validation accuracy return the 70%~75%. I think this is not a bad result for this datasets.
