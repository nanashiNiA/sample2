# Markdownサンプル集

このドキュメントは、Markdownの主要な構文とメディアの埋め込み方法を示すサンプル集です。

---

# h1 見出し
## h2 見出し
### h3 見出し
#### h4 見出し
##### h5 見出し
###### h6 見出し

## 強調表現

**太字テキスト**
**太字テキスト（別記法）**
*斜体テキスト*
*斜体テキスト（別記法）*
~~取り消し線~~

## 引用

> 引用はネストすることもできます...
>> ...大なり記号を隣り合わせで使うことで...
> > > ...または矢印の間にスペースを入れて記述します。

## 画像

Markdown技法を利用し、画像を入れる例：

![Snow Miku 2025](image)

![Minion](https://octodex.github.com/images/minion.png)

![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

## 動画

Markdown技法を利用し、動画を入れる例：

### YouTube Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/QcHZdiVD0Ww"
title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write;
encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## リスト

### 順序なしリスト
+ `+`、`-`、または `*` で始める行でリストを作成
+ サブリストは2スペースでインデント:
  - マーカー文字の変更で新しいリスト開始:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ とても簡単！

### 順序ありリスト
1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

1. 連続した番号を使用することもできます...
1. ...または全ての番号を `1.` のままにすることも可能

オフセット付きの番号開始:
57. foo
1. bar

## コード

インライン `code`

インデントされたコード

    // コメント
    line 1 of code
    line 2 of code
    line 3 of code

コードブロック「フェンス」

```
ここにサンプルテキスト...
```

シンタックスハイライト

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## テーブル

| オプション | 説明 |
| ------ | ----------- |
| data | テンプレートに渡されるデータを提供するデータファイルへのパス |
| engine | テンプレート処理に使用されるエンジン。Handlebarsがデフォルト |
| ext | 宛先ファイルに使用される拡張子 |

右揃えの列

| オプション | 説明 |
| ------:| -----------:|
| data | テンプレートに渡されるデータを提供するデータファイルへのパス |
| engine | テンプレート処理に使用されるエンジン。Handlebarsがデフォルト |
| ext | 宛先ファイルに使用される拡張子 |

## リンク

[リンクテキスト](http://dev.nodeca.com)

[タイトル付きリンク](http://nodeca.github.io/pica/demo/ "タイトルテキスト!")

自動変換されるリンク https://github.com/nodeca/pica （linkifyを有効にすると表示されます）

### [脚注](https://github.com/markdown-it/markdown-it-footnote)

脚注1のリンク[^first]。

脚注2のリンク[^second]。

インライン脚注^[インライン脚注のテキスト]の定義。

重複した脚注参照[^second]。

[^first]: 脚注には**マークアップを含める**ことができ、
複数の段落も可能です。

[^second]: 脚注のテキスト。

---

このサンプルは、Markdownの基本構文から高度な機能まで、メディアの埋め込みを含めて包括的にカバーしています。
