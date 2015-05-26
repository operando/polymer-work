
## codelabs

* http://itshackademic.com/static/codelabs/ja/1-polymer-first-app/#1

## Chrome Dev Editor

[Chrome Dev Editor](https://chrome.google.com/webstore/detail/chrome-dev-editor-develop/pnoffddplpippgcfjdhbmhkofpnaalpg)


## HTML Import

link rel="import" 要素は HTML Import というもので、リソースをHTMLファイルに取り込む新しい方法です。

```html
<link rel="import"
  href="../components/font-roboto/roboto.html">
```


## Shadow DOM

DOM 要素内にローカルな DOM ツリーを追加する方法を提供するもので、DOM ツリーには、ウェブページの残りの部分から切り離されたローカルなスタイルとマークアップとを持たせることができます。

## <polymer-element>

Polymer において新しいカスタム要素をどのように定義するかを示す。

以下では、「post-card」という要素を作成します。

```html
<polymer-element name="post-card">
...
</polymer-element>
```

attributesの公開プロパティを定義する

```html
<polymer-element name="post-card" attributes="show">
...
</polymer-element>
```

## <template>

要素の内部の DOM 構造、つまり shadow DOM を定義します。ここに、カスタム要素のマークアップを追加します。
