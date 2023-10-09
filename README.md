# chatwork-chatgpt

## はじめに
OpenAI社が提供するChatGPTのWebアプリやスマホアプリは、設定を間違えると入力内容が将来の学習に使われてしまうので、社員の方に簡単に利用を許可することはできません。一方、OpenAI社やMicrosoft社の提供するChatGPTのAPIであれば、入力内容が学習などの用途に使われることはありませんが、APIなので、それを利用したアプリの開発が面倒です。そこで、お手軽に使えるGoogle Apps Scriptを利用し、ChatGPTのAPIをラップしたChatworkのチャットボットを作ってみました。Chatworkに登録したチャットボットへ話かけると、ChatGPTが答えてくれる形です。

## 必要な環境
- Chatworkの利用環境
- Google Apps Script（GAS）を使うためのGoogleアカウント
- OpenAI社のAPIまたはMicrosoft Azure OpenAI ServiceのAPIを利用するためのアカウントがあり、実際にOpenAIのPlaygroundやAzure OpenAI StudioのプレイグラウンドでChatGPTのチャットを試すことができる方

## 構築方法や制限事項の詳細
詳細はQiitaの記事「[ChatworkとGoogle Apps ScriptでChatGPTをセキュアに使ってみよう！](https://qiita.com/segavvy/items/84f3b4817543aa5bb939)」をご参照ください。
