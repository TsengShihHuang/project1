項目名稱：jsp+serlvet+mysql+spring+hibernate+github 實作pizza網站

成品效果：

商品瀏覽：分類顯示商品；顯示商品詳情，提供購買連結；可以對商品進行模糊查詢。瀏覽商品時不要求用戶登錄，但下訂單前用戶必須登錄，對於瀏覽過的商品有歷史記錄。

購物車管理：欲購買商品可以增添到購物車；也可以從購物車退回商品，清空購物車；對於同一件商品的多次購買只能在原來的商品上增添數量，還可以修改購物車中某個商品的數量，統計商品總額。

註冊管理：能夠對用戶名，密碼的簡單驗證；能夠對電子郵箱，Email進行有效性驗證；能夠防止利用頁面刷新重複註冊，以及已經註冊的用戶不能重複註冊。

訂單管理：只有登錄的用戶可下訂單；用戶可以查看自己的訂單。管理員可以修改訂單的狀態。

商品管理：管理員可以增刪商品；修改商品基本信息。

用戶信息管理：用戶登陸後可以修改個人信息

設計思路：

網上購物系統，由前台商品展示及銷售、後台管理2部分組成。前台商品展示及銷售：商品瀏覽、購物車、訂單查詢、商品查詢等後台管理：該部分主要對商城內的一些基礎數據進行有效管理，包括商品管理、管理員管理、訂單管理等



本系統結構如下：

（1）商品瀏覽模塊：

實現瀏覽最新商品

實現按商品名稱瀏覽商品

實現根據商品分類瀏覽商品

（2）購物車：

登錄後可以將商品加入購物車，或從購物車移除商品

（3）登錄、註冊：

購物前需要登錄，如果沒有帳號則可以先註冊

（4）提交、查詢訂單：

商品加入購物車後可以提交訂單，也可以查看自己的所有訂單

(5) 後台管理員模塊

用戶登錄功能：通過帳號登錄系統。

商品分類管理功能：可以查詢所有商品分類，添加新的商品分類，刪除已有的分類

商品管理功能：可以查詢所有商品，添加新商品，刪除已有商品

訂單管理功能：可以查詢所有訂單，對未發貨的訂單進行發貨處理

用戶管理功能：可以查詢所有用戶，查詢指定用戶，刪除用戶

修改登錄密碼功能：修改管理員的登錄密碼






