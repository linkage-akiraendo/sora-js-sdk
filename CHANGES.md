# 変更履歴

- UPDATE
    - 下位互換がある変更
- ADD
    - 下位互換がある追加
- CHANGE
    - 下位互換のない変更
- FIX
    - バグ修正


## 1.5.0
- [CHANGE] Signaling 時の WebSocket onerror では reject しないようにする
- [UPDATE] パッケージの更新

## 1.4.1
- [FIX] Signaling message の metadata が旧仕様(access_token)のままだったので修正する

## 1.4.0
- [ADD] Signaling notify 用の callback を追加できるように変更する

## 1.3.0
- [UPDATE] Safari に対応する

## 1.2.0
- [ADD] Subscriber の multistream に対応する
- [CHANGE] iceServers が指定されていない場合に 'stun:stun.l.google.com:19302' を使用していたのをやめる

## 1.1.0

- [UPDATE] Microsoft Edge に対応する

## 1.0.0

- [CHANGE] PeerConnection まで含めた処理を SDK で実行するように変更する
- [CHANGE] multistream をパラメーターに追加する
- [CHANGE] videoSnapshot をパラメーターに追加する
- [CHANGE] videoBitRate をパラメーターに追加する
- [CHANGE] audioCodecType をパラメーターに追加する
- [CHANGE] codecType を videoCodecType に変更する

## 0.5.0

- [CHANGE] codecType のチェックをしないようにする
- [UPDATE] シグナリングメッセージのキー名を変更する

## 0.4.2

- [UPDATE] ドキュメントを修正する

## 0.4.1

- [UPDATE] ドキュメントを修正する

## 0.4.0

- [UPDATE] codecType が選択できるように修正する
- [UPDATE] パッケージの更新
- [UPDATE] ビルドの仕組みを変更する

## 0.3.2

- [UPDATE] パッケージの更新

## 0.3.1

- [UPDATE] signaling 時に WS が切断した場合、ステータスコードが 440x だったら Promise.reject するように変更する

## 0.3.0

- [ADD] disconnect を追加する

## 0.2.0

- [CHANGE] constructor の引数に URL 文字列を受け取る用に修正する
- [CHANGE] package name を sora.js から sora-js-sdk に変更する
- [CHANGE] Promise 化する
- [FIX] PeerConnection Object が GC の対象にならないように修正する

## 0.1.0

**0.1.0 リリース**

