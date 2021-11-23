# Azure Active Directory 新增主要網域
# (一) 新增主要網域<br>
1. 已全域管理員身分帳號登入Azure Portal，進入**Azure Active Directory** <br>
![GITHUB](https://github.com/A-0428/Azure/blob/main/Azure%20Virtual%20Desktop/Virtual%20Desktop%20image/image1.jpg) <br>
2. 進入Azure Active Directory->自訂網域名稱->新增自訂網域 <br>
![GITHUB](https://github.com/A-0428/Azure/blob/main/Azure%20Virtual%20Desktop/Virtual%20Desktop%20image/image2.jpg) <br> 
3. 前往該網域的DNS新增一筆TXT或者MX紀錄 <br>
4. 驗證網域 <br>
![GITHUB](https://github.com/A-0428/Azure/blob/main/Azure%20Virtual%20Desktop/Virtual%20Desktop%20image/image3.jpg) <br> 
![GITHUB](https://github.com/A-0428/Azure/blob/main/Azure%20Virtual%20Desktop/Virtual%20Desktop%20image/image4.jpg) <br>
![GITHUB](https://github.com/A-0428/Azure/blob/main/Azure%20Virtual%20Desktop/Virtual%20Desktop%20image/image5.jpg) <br>

# (二) 建立Azure Active Directory使用者<br>
1. 回到AzureAD中點選**使用者** <br>
![GITHUB](https://github.com/A-0428/Azure/blob/main/Azure%20Virtual%20Desktop/Virtual%20Desktop%20image/image6.jpg) <br>
2. 點擊**新增使用者** <br>
![GITHUB](https://github.com/A-0428/Azure/blob/main/Azure%20Virtual%20Desktop/Virtual%20Desktop%20image/image7.jpg) <br>
3. 建立新的使用者並套用剛剛新增的網域名稱，這裡範例為:**user1~user3** <br>
![GITHUB](https://github.com/A-0428/Azure/blob/main/Azure%20Virtual%20Desktop/Virtual%20Desktop%20image/image8.jpg) <br>
4. 這是剛剛建立的AzureAD使用者
![GITHUB](https://github.com/A-0428/Azure/blob/main/Azure%20Virtual%20Desktop/Virtual%20Desktop%20image/image9.jpg) <br>
