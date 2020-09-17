# LimeleAPI
短縮URLのAPIになります。
最新版はv3です。v1,v2はベータ版なのでリファレンスを作っておりません。
## APIではなくご利用になりたい場合
公式サイトで使用できるようになっております。
https://limu.ml でご使用できます
## API v2の利用方法
> API v3がまもなくリリースされますのでそちらを使うことを推奨します  
>API URLが突然変わる可能性があります。
<br/>

```
https://riyblog.shop/limele/api/v2/
```

上記のURLに `url` パラメータをつけてリクエストをすると下記のようなJSONをレスポンスします

```json
{ "ver":"v2", "msg":"200", "url":"https://limu.ml/XXXXX" }
```

正常に作成できた場合は `msg` キーに `200` がレスポンスされます。
また、エラーやパラメータに値が存在しない場合は `msg` キーに `404` がレスポンスされます
