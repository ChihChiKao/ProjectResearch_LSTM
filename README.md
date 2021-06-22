# 摘要
空間軌跡為一個物體在地理空間中移動生成的軌跡，會受到環境、身分、交通等影響，造成軌跡有不同的型態。現今行動裝置與許多社交網路都能獲取使用者位置，並且記錄連續時間的歷史座標，這些連續性的位置資料反映了使用者在空間上的移動行為，而過去許多研究也發現空間軌跡與使用者的興趣相關。本研究利用產學合作公司的專利技術收集到行動裝置使用者位置資料來進行移動目的地預測，由於台北市為經濟產業發展重要地帶，使用行動裝置需求更多，所以本研究以台北市為例，根據行動裝置使用者歷史軌跡資料歸納軌跡特徵，並利用使用者移動特性和手機內安裝的APP，統整出使用者軌跡規律性及使用者的興趣，最後結合社會經濟資料庫的POI資料，將軌跡資料轉換成環境條件軌跡，結合兩種深度學習長短期記憶 (LSTM)的預測，來改善預測結果，將預測誤差改善30%~60%，提高準確率。
# 本研究資料來源
### (一)	 數據資料來源
##### 本研究資料來源為產學合作L科技公司利用行動數據基地台接收行動裝置使用者位置，資料收集的主要來源為交通資訊查詢類APP，這些大數據都是去識別化(無個資)的空間資料，為了將大數據的空間資料進行分析與整合，故將空間資料建立資料表欄位，存取與統整在PostGIS空間資料庫，並利用Python程式語言進行資料分析。
### (二)	 POI資料
##### POI資料為使用社會經濟資料庫平台最小統計區工商家數為依據，此資料為分類好土地使用類型的資料，總共有20個類別
