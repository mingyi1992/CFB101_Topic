在作資料比對時建議要先轉為英文，比較容易對上目標。

轉英文可以用selenium爬蟲或採用google內建的檔案翻譯系統。

由於檔案翻譯系統不支援csv檔，可執行change fileformat來把檔案格式轉為excel

亦可直接採用下面的API來執行翻譯工作，但由於他無法承受大量數據，因此還是比較建議上面的方法。
https://github.com/lushan88a/google_trans_new