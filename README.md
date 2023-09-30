# GCP_Study_Notes
###GCP 學習筆記

---
注意事項：本筆記僅用來學習GCP服務
參考文章：https://ithelp.ithome.com.tw/articles/10261758

---

# 安裝 Google Cloud SDK
Cloud SDK 提供語言專屬的 Cloud 用戶端程式庫，支援每種語言的自然慣例與風格。這樣一來，您就能更輕鬆地使用自選語言與 Google Cloud API 互動。此外，用戶端程式庫也會處理驗證工作、減少所需的樣板程式碼、提供輔助函式分頁大型資料集，並以非同步的方式處理長時間執行的作業。

windows 用戶可以打開 PowerShell ( Win+R 輸入 PowerShell) 輸入以下命令

```
(New-Object Net.WebClient).DownloadFile("https://dl.google.com/dl/cloudsdk/channels/rapid/GoogleCloudSDKInstaller.exe", "$env:Temp\GoogleCloudSDKInstaller.exe")

& $env:Temp\GoogleCloudSDKInstaller.exe
    
```


###### 官方文件：https://cloud.google.com/sdk/docs/install-sdk?hl=zh-cn
###### 來源：[Cloud SDK](https://cloud.google.com/sdk?hl=zh-tw)。
---




