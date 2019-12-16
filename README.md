# DataExposure
Try to process the datas more readable

Data use : 房價資訊
模組運用:
1.Pandas:
  DataFrame
    -sample : 查看資料用
    -groupby : 針對某Series分類並對其餘Series的統計 argv : (columnname) + method
      -count : 出現次數
      -mean : 總體平均
    -loc : argv:(row,columnName)
    -dataframe資料篩選控制
    -corr : 相關性分析
2.matplotlib
  DataFrame+matplotlib
    -plot()
      kind : 圖型種類
      y : 對應種類y軸資料
      figsize=(10,6) : 圖形大小
      fontsize=14 : 字體大小
      title='各鄉鎮資料筆數' : 圖片名稱
      返回ax : 可用於設置圖片其他資訊
3.seaborn
  seaborn + matplotlib
  -heatmap : 熱力圖
