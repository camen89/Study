## ファビコンの作り方

  1. [ファビコン生成サイト](https://ao-system.net/favicongenerator/)にアクセス  
  2. ダウンロードされたフォルダには大量の.pngや.icoがあるが
    
     favicon.ico
     
     apple-touch-icon-180×180.png
     
     android-chrome-192×192.png

      だけを利用する。  
   3. htmlの`<head></head>`内に以下のコードを追加　　
        ```
        <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
        
        <link rel="apple-touch-icon" href="apple-touch-icon-180x180.png" sizes="180x180">
        
        <link rel="icon" type="image/png" href="android-chrome-192x192.png" sizes="192x192">
        ```
