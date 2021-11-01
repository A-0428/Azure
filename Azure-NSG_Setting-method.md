# Azure VM的NSG規則要如何調整?
1.點選您的資源所在的訂用帳戶 <br>
2.點選資源群組 <br>
3.點選您的資源所在的資源群組 <br>
![GITHUB](https://github.com/A-0428/Azure-Common-isuss/blob/main/AzureVM-firewall-settings/AzureNSG01.jpg) <br>
4.點選要更改**NSG**規則的**Virtual Machine**
![GITHUB](https://github.com/A-0428/Azure-Common-isuss/blob/main/AzureVM-firewall-settings/AzureNSG02.jpg) <br>
5.選擇左側的**網路** <br>
6.選擇要變更**輸入(輸出)連接埠規則**，這邊使用**輸入連接埠規則**作為範例 <br>
7.點擊**新增輸入連接埠規則** <br>
![GITHUB](https://github.com/A-0428/Azure-Common-isuss/blob/main/AzureVM-firewall-settings/AzureNSG03.jpg) <br>
![GITHUB](https://github.com/A-0428/Azure-Common-isuss/blob/main/AzureVM-firewall-settings/AzureNSG04.jpg) <br>
8.設定要開放的port規則(這邊範例為開啟443 port)，設定好後點選**新增** <br>
![GITHUB](https://github.com/A-0428/Azure-Common-isuss/blob/main/AzureVM-firewall-settings/AzureNSG05.jpg) <br>
* 完成後就會直接顯示出來剛剛所設定的規則 <br>
![GITHUB](https://github.com/A-0428/Azure-Common-isuss/blob/main/AzureVM-firewall-settings/AzureNSG06.jpg) <br>

**微軟官方文件-使用安全性規則 : https://docs.microsoft.com/zh-tw/azure/virtual-network/manage-network-security-group#work-with-security-rules**
