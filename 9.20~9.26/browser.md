## browser

個人目前是先傾向，把問題聚焦在打了網址後，網頁會發生什麼事情（有滿多資料是說，整個網頁rendering的過程，但個人覺得這部分比較偏向是前端工程師的問題，不過聯結有留在下面）。

當在url上按下enter後，前面會發生的事情是DNS的運作，我們的網址通常不可能是IP位址，所以會去觸發DNS的查詢，當查到正確的IP位址後，下一步就是送出HTTP請求（好比像是google、yahoo、cathay......等），這時接收請求的那一塊，會有一個server幫忙把請求轉化成另一端開發人員開發的程式語言的物件（以Java來說是HttpServletRequest），由程式語言那端去進行實作，接著就會回傳一整個html頁面回來，讓browser去進行解析。

> https://medium.com/@monica1109/what-happens-when-i-type-any-url-in-the-browser-3719c6357da2
> https://medium.com/@monica1109/how-does-web-browsers-work-c95ad628a509
