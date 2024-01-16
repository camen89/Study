## Node.jsのメモ(備忘録)
[Zenn記事_Node.jsによるwebアプリケーション作成入門](https://zenn.dev/wkb/books/node-tutorial)を参考にした

- **Node.jsの操作方法**  
  1. `windows` + `R`  
  2. ファイル名を指定して実行が表示されるので、検索欄に「node」と入力。   
  3. コマンドプロンプトの黒い画面が表示されnode.jsが操作できるようになる。

- **Node.jsでjsファイルを実行する方法**   
  1. Vscodeでjsファイルを作成する(ex. hello.jsを作成する)。   
  2. どこかに保存する(ex. デスクトップに保存する)。   
  3. コマンドプロンプトを開く   
  4. `cd` + `半角スペース`のあとにjsファイルが入っているフォルダをドラッグアンドドロップ(ex. 今回はデスクトップとドラッグアンドドロップ)。   
  5. node 名前.jsで実行(ex. 今回はnode hello.js)。

- **Node.jsのバージョン確認**  
  以下のコマンドを実行  
  `node -v`  

  ![エビフライトライアングル](http://i.imgur.com/Jjwsc.jpg "サンプル")
- **curlコマンドの使い方**   
  1. コマンドプロンプトを立ち上げる   
  2. Curlのインストールの確認   
    コマンドプロンプトで以下のコマンド入力 + Enter
    ```
    curl --version
    ```
  3. `curl` + `半角スペース` + `url` (ex. `curl https://tonari-it.com`)  
- **MySQLのパスの設定**
  1. MySQLのパスの設定  
     コンピュータにプログラムの場所を認識させ、プログラム名で実行可能にする  
  2. `「PC」->「ローカルディスク(C:)」->「Program Files」->「MySQL」->「MySQL Server8.0」->「bin」`の順にフォルダクリック  
  3. パスをコピー  
  4. `「スタートメニュー」-> 「設定」`で「設定の検索」に環境変数と入力。「環境変数の編集」をクリック  
  5. `Path`の行をクリック→編集→新規→パスをペースト
     
- **MySQLにログイン**
  1. MySQLにrootユーザでログインする。コマンドプロンプトで以下のコマンドを実行する。  
     `mysql -u root -p`
  2. ログアウトのコマンド  
     `mysql> exit`
     
- **参考記事**   
   [Node.js公式ページ_ダウンロード](https://nodejs.org/en/download/)   
   [MySQL公式ダウンロードページ](https://dev.mysql.com/downloads/file/?id=523568)   
   [Zenn記事_Node.jsによるwebアプリケーション作成入門](https://zenn.dev/wkb/books/node-tutorial)   
   [Node.jsをつかってjsファイルを実行する方法](https://q-az.net/node-js-pursue/)   
   [node.jsの利用シーン、メリットの解説記事](https://www.kagoya.jp/howto/it-glossary/develop/nodejs/)   
   [とほほのnode.js入門](https://www.tohoho-web.com/ex/nodejs.html)   
   [curlの使い方](https://tonari-it.com/windows-curl/)   
   [Express.js完全入門](https://qiita.com/ryome/items/16659012ed8aa0aa1fac)   
   
  



  



