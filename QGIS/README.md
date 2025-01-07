# QGIS
QGIS是一套地圖資料管理系統，使用者可透過蒐集、處理、分析及整合地理空間資料，以繪製主題式地圖，呈現地理現象和資訊型態的分佈；而其常用的數據格是為.shp、.dbf、.grd、.tif、.csv檔案。

## 數據蒐集
| **分析數據** | **資料名稱** | **檔案格式**| **教學參考** |
| --- | --- | --- | --- |
| 臺灣地圖<br>環境底圖 |  [國土測繪圖資網路地圖服務系統WMS服務](https://www.nlsc.gov.tw/NLSC_Content.aspx?n=11987&s=183190)<br>[使用插件 QuickMapServices](https://plugins.qgis.org/plugins/quick_map_services/) | --- | [link](https://www.youtube.com/watch?v=w94r1mE6Jz0) |
| 數值地形模型 | [內政部20公尺網格數值地形模型資料](https://data.gov.tw/dataset/35430) | .grd/.tif | [link](https://www.youtube.com/watch?v=XpN0tO5wA3A) |
| 淹水潛勢 | [淹水潛勢圖](https://data.gov.tw/dataset/25766) | .dbf | [link](https://www.youtube.com/watch?v=IXHbmR7Is-Y&list=PL-6GgAT7_AUS2EqA0Bf9L35Ku0aGSkfYC&index=5) |
| 河川河道 | [河川河道](https://data.gov.tw/dataset/25781) | .dbf | --- |
| 河川流域範圍圖 | [河川流域範圍圖](https://data.gov.tw/dataset/9823) | .dbf | --- |
| 土地使用分區 | [非都市土地使用分區圖（112年）](https://data.gov.tw/dataset/169538)<br>[高雄市政府都市發展局 都市計畫圖資供應開放平台](https://urbangisdata.kcg.gov.tw/ODA/web_page/ODA020100.jsp) | .dbf | --- |
| 人口統計 | [行政區三段年齡組性別人口統計](https://segis.moi.gov.tw/STATCloud/QueryInterfaceView?COL=XnZR4EL%252b%252bEUW829GivKzQQ%253d%253d&MCOL=wmufPLtELxnT0Qc7RnrIIw%253d%253d) | .csv | --- |
| 活動中心分佈 | [高雄市里活動中心](https://data.gov.tw/dataset/47063) | .csv(座標) | --- |
| 公車站與路線 | [交通部 GIS-T交通網路地理資訊倉儲系統](https://gist.transportdata.tw/gist_web/MapDataService/Retrieval) | .dbf | --- |
| 消防局分佈 | [高雄市消防分隊駐地位置圖](https://data.kcg.gov.tw/dataset/team-sites) | .csv(座標) | --- |
| 超商分佈 | [全國5大超商資料集](https://data.gov.tw/dataset/32086?fbclid=IwAR1-5ekeNM6TZSC-1jyXoVrbAR8fPlnnLaXGPUrETnzMR9CujVtdzku81OM) | .csv(座標) | --- |

## 操作注意事項
- 資料數據庫推薦：
    - [社會經濟資料服務平台](https://segis.moi.gov.tw/STATCloud/Index)
    - [政府資料開放平台](https://data.gov.tw/)
- 檔案格式：
    - 在QGIS加入向量圖層中，若.shp檔案格式無法讀取，可嘗試選擇使用.dbf檔。