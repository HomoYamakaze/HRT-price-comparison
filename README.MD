
# 這裏是哪裏

如你所見, 這裏是藥商價格比對和記錄騙子藥商的倉庫  
此倉庫是由[HomoYamakaze/HRT-price-comparison](https://github.com/HomoYamakaze/HRT-price-comparison) fork而得, 由於HomoYamakaze可能已經放棄更新則elihuso/英風莊和其他協助人員接管後續更新.  
由於某些原因只能更新騙子藥商的名單, 所以藥商價格比對可能仍是2022年4月的數據, 此間發生的事情(例如壟斷香香雪的日雌)等事件沒有記錄在內.  

# FAQ

1. 如果我發現了新的騙子藥商, 該怎麼辦?  
    如果您發現了新的騙子藥商並且確定, 請發送pr或者發送一封郵件到[Elihuso@outlook.com](mailto:Elihuso@outlook.com)  
    如果您是發送的電子郵件, 則請詳細說明整個事件, 相關人員的聯繫方式, 以及涉案金額等, 我們將有人員進行分析.  
2. 我被已經記錄的騙子藥商再次騙了
    首先, 我們很抱歉聽到此事. 畢竟能力有限, 我們無法將這個repo進行大衆公開處理.  
    如果您想要記錄, 那麼您可以發送一封郵件到[Elihuso@outlook.com](mailto:Elihuso@outlook.com), 詳細說明事件的過程, 我們將添加更多關於那些騙子藥商的信息並感謝您.  
3. 如何使用?  
    首先, 在根目錄中的`騙子藥商肅反名單.csv`是一個彙總表, 在內部可以使用瀏覽器的查詢功能快速查找人員以確認您正在聯繫的藥商是否爲假藥商或騙子;  
    其次, 在分類表中可以查詢已經被記錄的騙子藥商從而在指定的聯繫方式裏避免受騙.  

# 如何貢獻

您所需要做的是:  
1. 收集信息, 將確認後的信息拉取一個新的branch以open pull request.  
2. 將詳細過程在新open的pr中以圖片/文字的形式說明.  
3. 如果您有多個藥商需要上報, 請分多個commit完成; 您可以只在一個pr中上報多個藥商.  

# Feather

在此之後, 我們將添加`可信任的藥商.csv`一表, 裏面記錄可以信任的藥商及ta們的聯絡方式.  

可以看到, 這個repo已經不是標準的`HRT-PRICE-COMPARISON`了, 它已經被用作記錄各種於用藥相關的人和事  
當然, 這雖然不是咱的初心但仍然很高興看到這個  

# Details

**如果您只是想要查閱, 或者沒有需求進行修改/commit, 可以忽略本節**

本倉庫的文件結構如下(2022/9/17):  
``` text
HRT-PRICE-COMPARISON
    騙子藥商肅反名單(分類)/
        qq.csv
        Telegram.csv
        Twitter.csv
        WeChat.csv
    .gitignore
    README.MD
    在線藥商價格比對表
    騙子藥商肅反名單
```

所有表格全部使用csv文件格式, 編碼爲UTF-8(所以不要使用Excel或者轉化爲GB2312後再轉化回來)  

`.gitignore`用於防止在使用vscode編輯時上傳不必要的文件; 當然, 您正在閱讀`README.MD`.  

# 聯絡我們

郵箱: [Elihuso@outlook.com](mailto:Elihuso@outlook.com)  
Twitter: [@ElihusoQ](https://twitter.com/ElihusoQ)(只是英風莊的twitter, 其他人不在此說明)  