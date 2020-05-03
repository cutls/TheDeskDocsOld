# 設定のエクスポート


1. ![settings1](https://raw.githubusercontent.com/cutls/TheDeskDocs/master/media/settings1.png)を選択。
1. ![settings2](https://raw.githubusercontent.com/cutls/TheDeskDocs/master/media/settings2.png)から __環境設定__ を選択。
1. __エクスポート__ を選びます。
1. 保存先を指定します。
  
## エクスポート形式
JSON5形式で出力します。

一部設定はエクスポートされません。  
**このデータは秘密にしてください。認証情報等が含まれているため、アカウントが乗っ取られる恐れがあります。**

保存機能がOSの制約で動かない場合があります。(PWA版など)  
その時は下のテキストボックスに保存内容と同じものをテキストで表示しますので、
それをテキストエディタやメモ帳(notepad.exe)等で保存してください。

### メタ情報
エクスポートしたデータをJSON5として整形して、meta属性付近を確認してください。
```
meta: {
    date:'2020-05-03T15:11:58.559Z',
    platform:'win32',
    thedesk:'20.3.3 (Kawaii)'
},
revisons:2.1
```
`date`は作成日時を、`platform`はOS(`win32`: Windows / `linux`: Linux / `darwin`: macOS)を、
`thedesk`は作成バージョンを示します。  
また、`revisions`はエクスポートファイルのバージョンを示します。