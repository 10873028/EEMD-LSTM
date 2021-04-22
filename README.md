# 總體經驗模態分解結合長短期記憶

流程：  
eemd.py -> preprocessing.py -> model.py -> main.py -> retrain.py <-> Predict.py  
  
|檔案             | 內容                                   | 
|-----------------|----------------------------------------|
|eemd.py          | 總體經驗模態分解                       |  
|preprocessing.py | 資料預處理，標準化、切割、打亂         |  
|model.py         | 模型架構及正向傳播流程                 |  
|main.py          | 進行訓練，並儲存模型                   |  
|retrain.py       | 透過修改各項超參數，對模型再次進行訓練 |  
|Predict.py       | 預測未來數天，儲存圖表及誤差數據       |  
  
結論：  
單天預測  
![Mode00](https://github.com/10873028/EEMD-LSTM/blob/master/train/Mode00-predict.jpeg?raw=true)  
![Mode01](https://github.com/10873028/EEMD-LSTM/blob/master/train/Mode01-predict.jpeg?raw=true)  
![Mode02](https://github.com/10873028/EEMD-LSTM/blob/master/train/Mode02-predict.jpeg?raw=true)  
![Mode03](https://github.com/10873028/EEMD-LSTM/blob/master/train/Mode03-predict.jpeg?raw=true)  
![Mode04](https://github.com/10873028/EEMD-LSTM/blob/master/train/Mode04-predict.jpeg?raw=true)  
![Mode05](https://github.com/10873028/EEMD-LSTM/blob/master/train/Mode05-predict.jpeg?raw=true)  
![Mode06](https://github.com/10873028/EEMD-LSTM/blob/master/train/Mode06-predict.jpeg?raw=true)  
![Mode07](https://github.com/10873028/EEMD-LSTM/blob/master/train/Mode07-predict.jpeg?raw=true)  
![Mode08](https://github.com/10873028/EEMD-LSTM/blob/master/train/Mode08-predict.jpeg?raw=true)  
![Mode09](https://github.com/10873028/EEMD-LSTM/blob/master/train/Mode09-predict.jpeg?raw=true)  
![Mode10](https://github.com/10873028/EEMD-LSTM/blob/master/train/Mode10-predict.jpeg?raw=true)  
連續多天預測  
![Mode00](https://github.com/10873028/EEMD-LSTM/blob/master/test/Mode00-future299.jpeg?raw=true)  
![Mode01](https://github.com/10873028/EEMD-LSTM/blob/master/test/Mode01-future299.jpeg?raw=true)  
![Mode02](https://github.com/10873028/EEMD-LSTM/blob/master/test/Mode02-future299.jpeg?raw=true)  
![Mode03](https://github.com/10873028/EEMD-LSTM/blob/master/test/Mode03-future299.jpeg?raw=true)  
![Mode04](https://github.com/10873028/EEMD-LSTM/blob/master/test/Mode04-future299.jpeg?raw=true)  
![Mode05](https://github.com/10873028/EEMD-LSTM/blob/master/test/Mode05-future299.jpeg?raw=true)  
![Mode06](https://github.com/10873028/EEMD-LSTM/blob/master/test/Mode06-future299.jpeg?raw=true)  
![Mode07](https://github.com/10873028/EEMD-LSTM/blob/master/test/Mode07-future299.jpeg?raw=true)  
![Mode08](https://github.com/10873028/EEMD-LSTM/blob/master/test/Mode08-future299.jpeg?raw=true)  
![Mode09](https://github.com/10873028/EEMD-LSTM/blob/master/test/Mode09-future299.jpeg?raw=true)  
![Mode10](https://github.com/10873028/EEMD-LSTM/blob/master/test/Mode10-future299.jpeg?raw=true)  
![Total](https://github.com/10873028/EEMD-LSTM/blob/master/test/Total-future299.jpeg?raw=true)  
