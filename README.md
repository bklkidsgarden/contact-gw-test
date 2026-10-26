# contact-gw-test

柏克來**聯絡簿（家長版）**新架構的**測試環境**外殼頁。正式系統不在這裡。

跟同仁用的智慧校園（`bklkidsgarden/leave-gw-test`）是兩個 App、同一套後台：家長從這裡打開，直接到聯絡簿。
頁面裡只有主機的公鑰與轉送服務的網址，沒有任何秘密或資料。

`index.html` 由「閘道」資料夾的 `shell/build.py --parent` 自動產生，請勿手動修改。
