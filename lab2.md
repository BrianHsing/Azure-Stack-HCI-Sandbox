# Lab2 - 使用桌面 New-AzSHCISandbox 一鍵式佈署

## 透過桌面 New-AzSHCISandbox 一鍵式佈署
- 佈署完成後，遠端登入虛擬機器 `ASHCIHost001`，登入桌面後會看到 New-AzSHCISandbox 的執行程式 <br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy12.png)<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy13.png)<br>
- 請點選右鍵並且 Powershell 執行，<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy14.png)<br>
- 跳出視窗後會詢問您是否要改變執行原則，這邊輸入 `a`，會開始執行佈署<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy15.png)<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy16.png)<br>
> **Tips.這個步驟大約需要 3 個小時才會完成** <br>

## 透過 Windows Admin Center 新增 Azure Stack HCI 叢集

- 完成後就可以看到桌面出現一個遠端桌面的捷徑 `AdminCenter`，登入帳號是 contoso\Administrator，密碼則是 Password01<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy17.png)<br>
- 登入後看到桌面有一些系統工具以及瀏覽器 Google Chrome<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy18.png)<br>
- 開啟 Google Chrome 網址列輸入 https://admincenter.contoso.com，並且輸入帳號是 contoso\Administrator，密碼則是 Password01，輸入後點選 Sign in 按鈕<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy19.png)<br>
- 點選 Add，右邊會出現功能視窗，往下拖拉看到 Server clusters，點選 Add 按鈕<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy20.png)<br>
- 在 Cluster name 欄位輸入 `azstackcluster`，並且勾選 Manage Software-Defined Networking(if set up)，在 Specify the Network Controller REST URI 的欄位中輸入 `https://nc01.contoso.com`，完成後點選 Validate 按鈕<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy21.png)<br>
- 完成驗證後會出現 Install RSAT-NetworkController 按鈕，點選執行<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy22.png)<br>
- 完成安裝後，請再次點選 Validate 按鈕，最後點選最下方 Add 按鈕，即可完成<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy23.png)<br>
![GITHUB](https://github.com/BrianHsing/Azure-Stack-HCI-Sandbox/blob/main/images/deploy24.png)<br>
