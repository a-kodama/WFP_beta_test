# 🌳 [WFP] [β - 5] チュートリアルを初回だけではなく、何度も見たい

## 不具合・要望の原文

> 最初にログインした時に表示される使い方の説明をもう１回見たいけど見れないので、いつでも見れるようにして欲しい。

## カテゴリー

<span style="color: blue;">要望</span>



## 対応方針

### 解決策・解決案

開発者ツール（F12）を立ち上げ、 `[Application]` - `[Local Storage]` から `http://10.145.11.35:3000/` を選択し、 `vuex` をキーに登録されている値を右クリックから削除することでアプリ再起動後にチュートリアルが表示されるようになります。

![Local Strage 削除](https://user-images.githubusercontent.com/19407009/83709358-4d747780-a659-11ea-8ae0-283ee326c6fa.png)

### コメント

チュートリアルはアプリ起動のたびに表示されると、（最初はよくても）邪魔くさくなるので手動で再表示させる方法を記載しています。

## 対応状況

完了