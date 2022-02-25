# Used-car-valuation
## 程式簡介
### 簡述
* 使用「類神經網路」實作 [Kaggle](https://www.kaggle.com/) - [100,000 UK Used Car Data set](https://www.kaggle.com/adityadesai13/used-car-dataset-ford-and-mercedes) 資料集，目的是「二手車價格」之回歸預測。
  > 本專案只使用「Audi」、「BMW」、「Ford」這三個車款來實作
* 各廠牌的csv檔中：
  * 第 1 ~ 2、4 ~ 9 欄是訓練資料的特徵
 
    * model: 車種

    * year: 註冊年份
    
    * transmission: 變速器類型
     
    * mileage: 里程數
    
    * fuelType: 發動機燃料
    
    * tax: 路稅
    
    * mpg: 每加侖英里
    
    * engineSize: 引擎尺寸( 升 )
    
  * 第 3 欄表示二手價，代表Label

* 同時透過 matplotlib 實作資料分析

> 類神經網路 與 資料前處理 在其他文章介紹過，此篇不會詳細介紹，可直接觀看程式碼

### 範例圖
* **Partial Dataset ( After standardization )**  
  ![](https://i.imgur.com/P3CCkPz.png)

* **Data Analysis**
  *  「二手價格」與「里程數」之關係  
    ![](https://i.imgur.com/4XZHZQP.png)
    
  *  「二手價格」與「註冊年份」之關係  
    ![](https://i.imgur.com/JsKVYs4.png)
    
  *  「二手價格」與「路稅」比較  
    ![](https://i.imgur.com/ahie5A6.png)
    
  *  「二手價格」與「每加侖英里」比較  
    ![](https://i.imgur.com/4wct4ZT.png)

* **Neural Network output**  
  ![](https://i.imgur.com/axT3TAP.png)
