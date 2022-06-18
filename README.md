# Goal
>運用Kaggle競賽APTOS2019公開資料集，訓練模型EfficientNetB3/B5，將眼底鏡圖片糖尿病視網膜病變程度區分成五種程度：  
>>0 – No DR  
>>1 – Mild  
>>2 – Moderate  
>>3 – Severe  
>>4 – Proliferative DR  
  
# Dataset
>Kaggle APTOS 2019 Blindness Detection "https://www.kaggle.com/c/aptos2019-blindness-detection" 中的「Train」資料集(3662)  
>將資料使用0.15的比例切分成：
>>Training set：3112  
>>Validation set：550  

# DeployModel
>使用訓練後的最佳化模型套用在Kaggle Diabetic Retinopathy Detection 2015 "https://www.kaggle.com/competitions/diabetic-retinopathy-detection/data" 中「train」其中20張照片，看模型表現結果。
