# Anki Web Template

## What's Anki Web Template

"Anki" means memorization in Japanese. In Japanese study, they sometimes do "Anki" in order to get high score in the exam and to get into the prestigious university.

They do "Anki" using textbooks and other materials that allow them to hide important words and phrases. For example, the way to using a red translucent membrane and the textbook on which important words and phrases are written in red is the popular way of "Anki". (Because you can hide the words and phrases by using the translucent membrane.)

By using this template, you can make the website to do "Anki" with HTML. the website developed from this will be the websites with interfaces similar to the way we do things with red membranes and textbooks.

## How to Use

### CSS and JavaScript

The CSS file (`css/style.css`) sets up the various designs of the website. And the JavaScript file (`js/app2.js`) enable the words and phrases visible and invisible.

Then by making "Anki" website, you need to load these file in `<head>` tag.

### How to make the blank with "important words and phrases"

If you put the important words and phrases and make it possible to hide and show, you need to wrap important words and phrases with `<span>` tags. The `<span>` have to have `id` in order be recognized as an important phrase in the JavaScript file. 

The syntax (HTML) is as follows below,
```
<span id="a[NUMBER]"> [Important Words and Phrases] </span>
```
`[NUMBER]` have to be a natural number, and there cannot be two identical `[NUMBER]` in one HTML file. The number should be from 1 to 899.

## Used Icons

We used *Microsoft Fluent UI System Icons* ([GitHub](https://github.com/microsoft/fluentui-system-icons)) as icons on the button (at header and footer).

## Additional Comment

`index.html` is the sample file of "Anki" website. Feel free to watch it, and let us make your own "Anki" website by using this template.

Sorry about the difficulty in reading English.

This repository is licensed under MIT License.

# Anki Web Template

## Anki Web Templateとは

我々はしばしば, 赤シートと重要語句が赤色で書かれたテキストを使って「暗記」を行う。

Anki Web Templateはその赤シートとテキストのような使い心地の, 「暗記」ができるようなサイトを作るためのものである。

## つかいかた

### CSSとJavaScript

`css/style.css`に, ウェブページのデザインについて書かれている。 また, `js/app2.js`に, 重要語句を隠すなどができるような実装がかかれている。

すなわち暗記サイトを作るためには, 両ファイルを`<head>`タグ内で読み込む必要がある。

### 重要語句を隠す

重要語句を隠すためには, HTMLファイルにおいて, 重要語句を`<span>`タグでくくる必要がある。 `<span>`タグにはJavaScriptファイルがその部分を重要語句と認識できるように, `id`を割り当てる必要がある

文法(HTML)は以下の通り
```
<span id="a[NUMBER]"> [Important Words and Phrases] </span>
```
`[NUMBER]`は, 1から899までの自然数である必要があり, 同一HTMLファイルに同じ数字は1つしか含んではいけない

## 使ったアイコン

*Microsoft Fluent UI System Icons* ([GitHub](https://github.com/microsoft/fluentui-system-icons))というところのアイコンを, ボタンのUIアイコンとして利用しています。

## 追加情報

`index.html`を, 暗記サイトのサンプルとして置いてあります。ご自由にご覧ください

上の英語の文章のミスがあったら教えてください。

本リポジトリは MIT License でライセンスされています