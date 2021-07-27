# 使用 Deploy to Azure 按鈕在 Azure 入口網站佈署

- 點選連結  [AzStackHCISandbox](https://github.com/microsoft/AzStackHCISandbox) 會看到 Deploy to Azure 的按鈕<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy1.png)<br>
- 點選後就會跳到 Azure 入口網站從自訂範本佈署的畫面<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy2.png)<br>
- 回到 [AzStackHCISandbox](https://github.com/microsoft/AzStackHCISandbox) 進入 json 資料夾，並且開啟 `azuredeploy.parameters.json` 檔案<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy3.png)<br>
- 點選檔案後會看到參數相關設定，點選 Raw 複製所有內容<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy4.png)<br>
- 回到 Azure 入口網站從自訂範本佈署的畫面，點選編輯參數<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy5.png)<br>
- 將 `azuredeploy.parameters.json` 複製的內容覆蓋至此，完成後點選儲存<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy6.png)<br>
- 回到 Azure 入口網站從自訂範本佈署的畫面，您在這邊只需要輸入 3 個欄位<br>
  - 新增資源群組<br>
  - 選擇區域<br>
  ![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy7.png)<br>
  - 輸入 Admin Password<br>
  ![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy8.png)<br>
  > **Tips.其餘欄位請不要更動** <br>
- 填入完成後，請點選檢閱 + 建立的按鈕，再按下建立執行佈署<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy9.png)<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy10.png)<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy11.png)<br>