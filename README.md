# linux 指令整理

# 切換介面

* 切換至文字介面Shell

  * ctrl + alt + F2~F6 

* 切換回圖形介面

  * ctrl + alt + F1

* 登出

  * exit or logout

# linux系統目錄

* /home:家目錄  

* /root:root目錄

* /bin:存放系統常用基本指令的地方

* /sbin:僅供系統管理者執行的指令

* /lib:存放基本的共用函式庫檔案以及核心模組驅動

* /usr:全文為Unix Software Rescouse 目錄包含主要程序、圖形介面所需檔案、自行安裝的軟體、系統文件等等

* /tmp:存放暫存檔案，所有使用者對該目錄都具有讀寫權限

* /dev:鍵盤、滑鼠、硬碟、USB等設備皆以檔案或目錄方式存放於此，方便管理

* /etc:存放系統設定檔，如使用者帳戶資訊、主機名稱等等

* /var:存放長度可變的檔案，ex:伺服器LOG檔

* /sys:內涵檔案用來檢視及設定系統硬體資訊

* /mnt:光碟或其他媒體設備掛載點的地方 (系統透過掛載存取光碟or USB)

* /opt:作為OPTIONAL檔案漢城式的存放目錄，例如非預設安裝的外來軟體常會安裝於此


# 基本指令操作

* 以 . 表示當前目錄 .. 表示上層目錄

* 印出當前帳號

`whoami`

* 印出當前所在目錄

`pwd`

* 顯示當月月曆

`cal`

* 顯示當月月曆 (每周從星期一開始)

    cal -m

* 顯示2019年 1月的月曆 (每周從星期一開始)

    cal -m 2019
    ```js
    這邊是程式碼
    ```

















