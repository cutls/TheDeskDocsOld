# SpotifyとNowPlayingの設定(Spotify)

## Spotifyアカウントとの連携

1. ![settings1](https://raw.githubusercontent.com/cutls/TheDeskDocs/master/media/settings1.png)を選択。
1. ![settings2](https://raw.githubusercontent.com/cutls/TheDeskDocs/master/media/settings2.png)から __SpotifyとNowPlayingの設定__ を選択。
1. Windowsの場合、「接続」を押した後一旦アプリが閉じ、  
![account7](https://raw.githubusercontent.com/cutls/TheDeskDocs/master/media/account7.png)  
が表示されます。  
その他のOSの場合、認証キーが表示されるので入力します。

## テンプレートの編集
説明通り入力して、 __設定__ を押して保存してください。  
標準の、  
`#NowPlaying {song} / {album} / {artist}`  
`{url}`  
の場合、  
`#NowPlaying 庭師KING / 救済の技法 / Susumu Hirasawa`  
`https://open.spotify.com/track/1GOFmfWEXFnOG52PhnIuJG`  
と入力されます。

## アルバムワークを添付する
1. ![settings1](https://raw.githubusercontent.com/cutls/TheDeskDocs/master/media/settings1.png)を選択。
1. ![settings2](https://raw.githubusercontent.com/cutls/TheDeskDocs/master/media/settings2.png)から __SpotifyとNowPlayingの設定__ を選択。
1.  __アルバムワークを添付する__ 値を変更します。クリックすると更新・保存されます。

## アルバムアートワークが無い時補完する(macOS)
上の「アルバムアートワークを添付する」がはいのとき限定。

macOSでNowPlayingしているとき、もしアルバムアートワークがない場合、Apple MusicのAPIを使用して
アルバムアートワークを添付します。もしかしたら適当でない画像が添付されるかもしれません。また、Apple Musicにない曲は添付できません。

これをはいに設定しておくと、アルバム情報が楽曲に無い場合もApple MusicのAPIで補完します。