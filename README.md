# blog.hsin.tw

[Blog 靜態頁面備份](https://itisjoe.github.io/blog.hsin.tw)

### 備份使用到的 wordpress plugin 

#### WP2Static

[WP2Static](https://wordpress.org/plugins/static-html-output-plugin/) 可以將 wordpress 的網站轉成每篇文章是獨立一個 html ，並且讓分類、標籤可以正常運作，站內可以互相連結。

設定的部分， Deploy static website 頁籤底下的 Allow offline usage ，這個如果打勾會無法正常生成，裡面連結會亂連，我也不知道原因，所以取消打勾後，並填入 Destination URL (這邊我填入 https://itisjoe.github.io/blog.hsin.tw )，就可以正常運作了。

另外有一點比較麻煩的是，路徑有中文的話，生成後會變成 uft8 格式(就是一堆 % 跟數字)，我是手動一個一個名字再自己做轉換，才可以正常連結到 html 。

#### BackWPup

使用 [BackWPup](https://wordpress.org/plugins/backwpup/) 備份了資料庫內容。





