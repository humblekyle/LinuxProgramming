## Linux用戶及組

[TOC]

用戶
---
系統的使用者的邏輯名稱, 對應有一個UID, 系統的/etc/passwd文件中以一行資訊對其進行定義, 包含以下訊息

* 組ID: 用戶加入的第一個組
* home目錄: 用戶登入後的初始目錄
* 登入Shell: 用來解釋用戶命令的Shell名稱

![etc/passwd實例](https://github.com/humblekyle/LinuxProgramming/blob/master/%E5%9C%96%E5%BA%AB/etc_passwd%E5%AF%A6%E4%BE%8B.png)

組
---
將用戶組成一個群組, 對應有一個GID, /etc/group 文件中以一行來定義, 包含以下訊息

* 組名: 組的唯一名稱
* 組ID: 與該組相關聯的ID數值
* 用戶列表: 逗號分隔的用戶登錄名列表

![etc/group實例](https://github.com/humblekyle/LinuxProgramming/blob/master/%E5%9C%96%E5%BA%AB/etc_group%E5%AF%A6%E4%BE%8B.png)


超級用戶
---
通常UID = 0, 名稱為root, 可以繞過所有權限檢查訪問任何文件。系統管理員使用超級用戶來管理系統。



*Ref:  
[Linux User&Group實戰教學]
(https://www.runoob.com/linux/linux-user-manage.html)

