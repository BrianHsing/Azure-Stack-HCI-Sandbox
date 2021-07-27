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
- 登入後可以看到桌面<br>
- 