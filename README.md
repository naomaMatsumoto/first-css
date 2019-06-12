# cssの説明

### 前のおさらい
HTMLとは文字を表示するもの
CSSは装飾を行うもの

### CSSはどうやって書くのか
タグの中にstyle="color:red"とかく
あとはCSSにclassを付けて適用させる。

### 文字の色を変えてみよう！
```
<h1 style="clolor:red;"l>見出し１</h1>
```

### 文字の大きさを変えてみよう！
```
<h1 style="font-size:40px;"l>見出し１</h1>
```

### 色と大きさを複合させてみよう！
```
<h1 style="clolor:red;font-size:40px;">見出し１</h1>
```

### このように複合させることで綺麗にすることができます。
```
<h1 class=”font-midashi”>
<style>
.font-midashi {
	color: red;
	font-size: 40px; 
}
</style>
```

### 最後に！
htmlのタグにstyleで文字の装飾を定義することも可能！

classという所に名前を付けてcssを定義することも可能！

いろんな事ができるので調べて試してみましょう！

次のパートではレイアウトについてお話をしていきます！
