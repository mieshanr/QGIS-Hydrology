# QSWAT
- 主要功能：
    - 水文模擬：模擬降雨、蒸發、土壤含水量、地表徑流、河川流量和地下水補給等水文過程。
    - 土壤侵蝕和沉積物輸出：計算降雨和徑流引發的土壤侵蝕和沉積物輸送。
    - 水質模擬：模擬氮、磷等營養物質的輸送和轉化，能預測農業肥料、農藥等污染物在流域中的輸出。
    - 土地管理實施效果評估：評估不同的土地管理措施（例如輪作、減少施肥量、覆蓋作物等）對水文和水質的影響。
    - 氣候變化和土地利用變化影響評估：可以模擬和評估在不同氣候變化情境下或不同土地利用方式下對水資源的影響。
- SWAT的應用：
    - 流域水文管理：用於流域範圍內的水文預測和水資源管理，評估如何通過農業措施減少水污染。
    - 水質管理：評估農業活動、城市化等對水質的影響，並提供減少營養物質污染的解決方案。
    - 氣候變遷研究：用於分析氣候變遷對水文循環、土壤侵蝕和水質變化的影響。
    - 政策制定支持：為流域管理政策提供科學依據，如控制土壤侵蝕、減少營養物質輸出和保護水資源的政策。
- SWAT的結構：
    - 輸入數據：包括地形資料（數字高程模型 DEM）、土壤類型、土地覆蓋、氣象資料（降水、氣溫、日照、風速等）。
    - 空間單元劃分：流域劃分為子流域，再進行進一步的水文響應單元（HRUs）的劃分，以表示流域內不同的土地覆蓋、土壤類型和管理措施。
    - 過程模擬：對每個HRU進行水量、沉積物、養分和化學物質的動態模擬，並將結果匯總到子流域和主流河道。

## 操作說明

### 軟體下載
- https://swatplus.gitbook.io/docs/installation
- https://www.microsoft.com/en-us/download/details.aspx?id=105289
- [SWAT介紹](https://www.youtube.com/watch?v=dBARtcejaPM)
     ![image.png](image%200.png)
        
### 使用教學
- https://swat.tamu.edu/media/116653/qswat3-manual_v15.pdf
    
### 操作測試
- 以範例做測試：https://www.youtube.com/watch?v=MqWyJ67gnr0&list=PLK7YBpqQP_ePv-EVoWqPl_Bt2CmORifad&index=2
![image.png](image%201.png)        
- 使用數據：
![image.png](image%202.png)

- 劃定流域
    - DEM需使用.adf檔或.tif檔
    - 步驟4、6需使用.dbf檔
    ![image.png](image%203.png)
- 測試結果
    ![image.png](image%204.png)
- HRUs
    - Select landuse map使用.adf檔
    - Select soil map使用.adf檔或.tif檔
    - 步驟3使用.csv檔
    ![image.png](image%205.png)
    ![image.png](image%206.png)
- 測試結果
    ![image.png](image%207.png)
    ![image.png](image%208.png)   
- SWAT+
    - RUN SWAT+
    ![image.png](image%209.png)
    - Weather Generator
    ![image.png](image%2010.png)
    - Weather Stations
    ![image.png](image%2011.png)
    - 無影片教學中的 Simulation
    ![image.png](image%2012.png)
    ![image.png](image%2013.png)
    - RUN SWAT+ 結果
    ![image.png](image%2014.png)