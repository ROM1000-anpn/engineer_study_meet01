# 2021.04.30 エンジニアゼミ<br>LINEbotを作ろうRTA

<br>

## 事前準備編

1. [LINE Developers](https://developers.line.biz/ja/)にログインする<br>
   自分のLINEアカウントで登録できます<br><br>
2. Developers consoleを使用するアカウントの必要情報を入力して送信<br><br>
3. botをホストするサーバーを用意する<br>
   これについてはFirebaseでもHerokuでもなんでもokです！<br>
   ※今回のハンズオンでは、Firebaseを使用します(無料枠で済みそうなので)<br><br>
4. **準備完了！**<br>
   LINE Developersコンソール画面からプロバイダをつくるところから、ハンズオンスタートしていきます🐰

<br><br>

## Q&A
当資料を公開した際に受けた質問をここに随時追記していきます<br>
わからないことがあったときに参考にしてみてくださいね<br>

<details>
<summary>Q. 「Developers consoleを使用するアカウントの必要情報を入力して送信」 これってなんのことですか？</summary>
   
<div>
   
<br>A. ログインすると、<br>LINE Developersのアカウントを作成する画面に遷移するので、入力欄埋めて登録してください！<br>

<br>

</div>
</details>

<details>
<summary>Q. データは日本のサーバに保存されてますか？</summary>
   
<div>
   
<br>A. 現状テキストは日本ということなので大丈夫そうです<br>画像をbotから送る際は、他国に一時保存されてても問題ない画像を選択するようにしてくださいね<br>

<br>

参考：https://www.watch.impress.co.jp/img/ipw/docs/1313/941/html/l03_o.jpg.html<br>

<br>

</div>
</details>

<details>
<summary>Q. Firebaseの場合、登録するだけでFirebase Hostingが使えるのでそれでいいですか？ローカルにCLIいれる必要ありますか。</summary>
   
<div>
   
<br>A. cli必要です！<br>あと、生成したurlでhookされる感じにするのでFirebase Hosting使用で問題ないです！<br>

<br>
</div>
</details>

<br><br>


### それでは、今月のエンジニアゼミをお楽しみに！

当日のエンジニアゼミでは、対話形式の自動応答を一緒に作ります！<br>
**事前準備の中でなにか不明な点や、詰まったりしたらお気軽にご相談ください！**

