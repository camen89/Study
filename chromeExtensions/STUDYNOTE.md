## chrome拡張機能自作(メモ)

- **拡張機能ファイルの構成**  
  ```
  ○○Extension  
             |- js    
             |   |-jquery3.6.0.js    
             |   |-script.js    
             |-css    
                 |-content.css   
             |-manifest.json  
  ```

- **`.json`ファイルの書き方例**  
    ```  
    {  
    "name" : "GreenTapeExtension",  
    "version" : "0.1",  
    "manifest_version" : 3,  
    "description" : "chrome extension green tape",  
    "content_scripts" : [{  
        "matches" : ["<all_urls>"],  
        "js" : [  
            "js/jquery.js",  
            "js/p5.min.js",  
            "js/script.js"  
        ]  
    }]  
    }
    ```

- **参考サイト**  
  [Chrome拡張（6）p5.jsで作る，バックグラウンドで動作するChrome拡張](https://takawo.hatenablog.com/entry/2017/11/06/214232)  
  [とほほのChrome拡張機能開発入門](https://www.tohoho-web.com/ex/chrome_extension.html#hello_world)  
  [【超基礎】Chrome拡張機能の作り方ハンズオン：version 3](https://yuki.world/how-to-develop-chrome-extension-basics/#t_Web)  
  [JSONファイルとは？基本構造からファイルの作り方、読み書き方法まで解説](https://and-engineer.com/articles/YUrUYBAAACUA2zGd)  
  [Chrome拡張機能の作り方をわかりやすく解説](https://www.dsk-cloud.com/blog/how-to-create-chrome-extension)  
  [Google Chrome拡張機能開発入門: Manifest V3対応の実践ガイド](https://neuralnetconsulting.info/google-chrome%E6%8B%A1%E5%BC%B5%E6%A9%9F%E8%83%BD%E9%96%8B%E7%99%BA%E5%85%A5%E9%96%80-manifest-v3%E5%AF%BE%E5%BF%9C%E3%81%AE%E5%AE%9F%E8%B7%B5%E3%82%AC%E3%82%A4%E3%83%89/#google_vignette)  
  [Google Chrome 拡張機能（Chrome extensions V3）の作り方](https://qiita.com/tomy0610/items/85d4e6abb1f1eefc519f)
