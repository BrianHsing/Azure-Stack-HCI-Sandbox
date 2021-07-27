# Azure-Stack-HCI-Sandbox

在 [Azure Stack HCI Simple](https://github.com/BrianHsing/Azure-Stack-HCI-Simple) 說明文件中，您學會簡單佈署 Azure Stack HCI & Arc 的基本設定，但其實還有一個重要功能 SDN 沒有體驗，本篇會說明如何使用由 Michael Godfrey 所提供的實戰演練 [AzStackHCISandbox](https://github.com/microsoft/AzStackHCISandbox) 中文步驟說明，您也可以透過連結直接參考原文步驟，使用 AzStackHCISandbox，提供極少的操作步驟，讓讀者能夠完整體驗 Azure Stack HCI 完整服務。<br>

在開始之前，您必須知道的幾件事情：<br>
- 您必須擁有 Azure Subscription，使用者帳號權限至少是參與者<br>
- 稍後您將透過一鍵式按鈕進行佈署，佈署之前必須複製原作者寫好的 Json file<br>
- 完成 AzStackHCISandbox 佈署大約需要花費 3 小時的時間，每小時花費大約為 $ 24.70 台幣<br>
- 您也可以參考原文的[影片](https://www.youtube.com/watch?v=nmQ12Ma1pD4)進行操作<br>

## 使用 Deploy to Azure 按鈕在 Azure 入口網站佈署

- 點選連結  [AzStackHCISandbox](https://github.com/microsoft/AzStackHCISandbox) 會看到 Deploy to Azure 的按鈕<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy1.png)<br>
- 點選後就會跳到 Azure 入口網站從自訂範本佈署的畫面<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy2.png)<br>
- 回到 [AzStackHCISandbox](https://github.com/microsoft/AzStackHCISandbox) 進入 json 資料夾，並且開啟 `azuredeploy.parameters.json` 檔案