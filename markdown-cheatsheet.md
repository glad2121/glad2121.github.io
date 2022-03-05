---
layout: slate-custom
title: Markdown チートシート
---

[ホームページ](./)

---
## 1. 見出し

見出し1 {#header1-1}
=======

```
見出し1 {#header1-1}
=======
```

# 見出し1 {#header1-2}

```
# 見出し1 {#header1-2}
```

<h1 id="header1-3">見出し1</h1>

```html
<h1 id="header1-3">見出し1</h1>
```

見出し2
-------
{: #header2-1}

```
見出し2
-------
{: #header2-1}
```

## 見出し2
{: #header2-2}

```
## 見出し2
{: #header2-2}
```

<h2 id="header2-3">見出し2</h2>

```html
<h2 id="header2-3">見出し2</h2>
```

### 見出し3

```
### 見出し3
```

<h3>見出し3</h3>

```html
<h3>見出し3</h3>
```

#### 見出し4

```
#### 見出し4
```

<h4>見出し4</h4>

```html
<h4>見出し4</h4>
```

##### 見出し5

```
##### 見出し5
```

<h5>見出し5</h5>

```html
<h5>見出し5</h5>
```

###### 見出し6

```
###### 見出し6
```

<h6>見出し6</h6>

```html
<h6>見出し6</h6>
```

---
## 2. 水平線

### Markdown (ハイフン3個以上)

---

```
---
```

### Markdown (アスタリスク3個以上)

***

```
***
```

### Markdown (アンダースコア3個以上)

_ _ _

```
_ _ _
```

### HTML

<hr>

```html
<hr>
```

---
## 3. 段落

### Markdown

1つめの段落です。

2つめの段落です。

```
1つめの段落です。
(空行)
2つめの段落です。
```

### HTML

<p>1つめの段落です。</p>

<p>2つめの段落です。</p>

```html
<p>1つめの段落です。</p>

<p>2つめの段落です。</p>
```

---
## 4. コードブロック

### Markdown (バッククォート3個以上)

```
Hello, World!
```

````
```
Hello, World!
```
````

### Markdown (チルダ3個以上)

~~~
Hello, World!
~~~

````
~~~
Hello, World!
~~~
````

### Markdown (インデント)

    Hello, World!

```
    Hello, World!
```

### HTML

<pre>Hello, World!</pre>

```html
<pre>Hello, World!</pre>
```

### Markdown (シンタックスハイライト)

```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

````
```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
````

---
## 5. 引用

### Markdown

> これは引用文です。
> > 二重引用文です。

```
> これは引用文です。
> > 二重引用文です。
```

### HTML

<blockquote>
  これは引用文です。
  <blockquote>
    二重引用文です。
  </blockquote>
</blockquote>

```html
<blockquote>
  これは引用文です。
  <blockquote>
    二重引用文です。
  </blockquote>
</blockquote>
```

---
## 6. 順序つきリスト

### Markdown

1. 項目1
1. 項目2
    1. 項目2-1
    1. 項目2-2
1. 項目3

```
1. 項目1
1. 項目2
    1. 項目2-1
    1. 項目2-2
1. 項目3
```

### HTML

<ol>
  <li>項目1</li>
  <li>項目2
    <ol>
      <li>項目2-1</li>
      <li>項目2-2</li>
    </ol>
  </li>
  <li>項目3</li>
</ol>

```html
<ol>
  <li>項目1</li>
  <li>項目2
    <ol>
      <li>項目2-1</li>
      <li>項目2-2</li>
    </ol>
  </li>
  <li>項目3</li>
</ol>
```

---
## 7. 順序なしリスト

### Markdown (ハイフン)

- 項目1
- 項目2
    - 項目2-1
    - 項目2-2
- 項目3

```
- 項目1
- 項目2
    - 項目2-1
    - 項目2-2
- 項目3
```

### Markdown (アスタリスク または プラス)

* 項目1
* 項目2
    + 項目2-1
    + 項目2-2
* 項目3

```
* 項目1
* 項目2
    + 項目2-1
    + 項目2-2
* 項目3
```

### HTML

<ul>
  <li>項目1</li>
  <li>項目2
    <ul>
      <li>項目2-1</li>
      <li>項目2-2</li>
    </ul>
  </li>
  <li>項目3</li>
</ul>

```html
<ul>
  <li>項目1</li>
  <li>項目2
    <ul>
      <li>項目2-1</li>
      <li>項目2-2</li>
    </ul>
  </li>
  <li>項目3</li>
</ul>
```

### Markdown (タスクリスト)

- [x] タスク1
- [ ] タスク2

```
- [x] タスク1
- [ ] タスク2
```

---
## 8. 定義リスト

### Markdown

用語1
: 説明1

用語2
: 説明2
: 説明3

用語3
用語4
: 説明4

```
用語1
: 説明1

用語2
: 説明2
: 説明3

用語3
用語4
: 説明4
```

### HTML

<dl>
  <dt>用語1</dt>
  <dd>説明1</dd>
  <dt>用語2</dt>
  <dd>説明2</dd>
  <dd>説明3</dd>
  <dt>用語3</dt>
  <dt>用語4</dt>
  <dd>説明4</dd>
</dl>

```html
<dl>
  <dt>用語1</dt>
  <dd>説明1</dd>
  <dt>用語2</dt>
  <dd>説明2</dd>
  <dd>説明3</dd>
  <dt>用語3</dt>
  <dt>用語4</dt>
  <dd>説明4</dd>
</dl>
```

---
## 9. テーブル

### Markdown

|ヘッダー1| 左寄せ      |中央寄せ | 右寄せ |
|--------|:-----------|:-----:|------:|
|長い行   |いろはにほへと|ABCDEFG|1234567|
|短い行   |あいうえお    |abc    |    123|
{: #mytable .mytable}

```
|ヘッダー1| 左寄せ      |中央寄せ | 右寄せ |
|--------|:-----------|:-----:|------:|
|長い行   |いろはにほへと|ABCDEFG|1234567|
|短い行   |あいうえお    |abc    |    123|
{: #mytable .mytable}
```

### HTML

<table>
  <thead>
    <tr>
      <th rowspan="2" style="vertical-align: middle">ヘッダー1</th>
      <th colspan="3" style="text-align: center">整列</th>
    </tr>
    <tr>
      <th style="text-align: center">左寄せ</th>
      <th style="text-align: center">中央寄せ</th>
      <th style="text-align: center">右寄せ</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>長い行</td>
      <td style="text-align: left">いろはにほへと</td>
      <td style="text-align: center">ABCDEFG</td>
      <td style="text-align: right">1234567</td>
    </tr>
    <tr>
      <td>短い行</td>
      <td style="text-align: left">あいうえお</td>
      <td style="text-align: center">abc</td>
      <td style="text-align: right">123</td>
    </tr>
  </tbody>
</table>

```html
<table>
  <thead>
    <tr>
      <th rowspan="2" style="vertical-align: middle">ヘッダー1</th>
      <th colspan="3" style="text-align: center">整列</th>
    </tr>
    <tr>
      <th style="text-align: center">左寄せ</th>
      <th style="text-align: center">中央寄せ</th>
      <th style="text-align: center">右寄せ</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>長い行</td>
      <td style="text-align: left">いろはにほへと</td>
      <td style="text-align: center">ABCDEFG</td>
      <td style="text-align: right">1234567</td>
    </tr>
    <tr>
      <td>短い行</td>
      <td style="text-align: left">あいうえお</td>
      <td style="text-align: center">abc</td>
      <td style="text-align: right">123</td>
    </tr>
  </tbody>
</table>
```

---
## 10. 改行

### Markdown

1行目です。  
2行目です。

```
1行目です。(空白2つ)
2行目です。
```

### HTML

1行目です。<br>
2行目です。

```html
1行目です。<br>
2行目です。
```

---
## 11. 画像

### Markdown

![I am GLAD!!](images/IamGLAD!!.png "タイトル")

```
![I am GLAD!!](images/IamGLAD!!.png "タイトル")
```

### HTML

<img src="images/IamGLAD!!.png" alt="I am GLAD!!" title="タイトル">

```html
<img src="images/IamGLAD!!.png" alt="I am GLAD!!" title="タイトル">
```

---
## 12. リンク

### Markdown

[ホームページ](./index.html "タイトル")

```
[ホームページ](./index.html "タイトル")
```

### HTML

<a href="./index.html" title="タイトル">ホームページ</a>

```html
<a href="./index.html" title="タイトル">ホームページ</a>
```

### Markdown (自動リンク)

ホームページ: <https://glad2121.github.io/>

```
ホームページ: <https://glad2121.github.io/>
```

---
## 13. 注釈

### 略語

Markdown から HTML を生成します。

*[HTML]: Hyper Text Markup Language

```
Markdown から HTML を生成します。

*[HTML]: Hyper Text Markup Language
```

<abbr title="Cascading Style Sheets">CSS</abbr> でスタイルを指定します。

```html
<abbr title="Cascading Style Sheets">CSS</abbr> でスタイルを指定します。
```

### 脚注

脚注付きの文章です[^1]。

[^1]: 脚注です。

```
脚注付きの文章です[^1]。

[^1]: 脚注です。
```

---
## 14. 文字修飾

### 強調1

*Itaric*

```
*Itaric*
```

_Itaric_

```
_Itaric_
```

<em>Itaric</em>

```html
<em>Itaric</em>
```

### 強調2

**太字**

```
**太字**
```

__太字__

```
__太字__
```

<strong>太字</strong>

```html
<strong>太字</strong>
```

### コード

`code`

```
`code`
```

<code>code</code>

```html
<code>code</code>
```

### 取消

~~取消~~

```
~~取消~~
```

<del>取消</del>

```html
<del>取消</del>
```

---
## 15. 属性指定

### id 指定

**id 指定**{: #myid}

```
**id 指定**{: #myid}
```

<span id="myid2">id 指定</span>

```html
<span id="myid2">id 指定</span>
```

### class 指定

**class 指定**{: .myclass}

```
**class 指定**{: .myclass}
```

<span class="myclass">class 指定</span>

```html
<span class="myclass">class 指定</span>
```

### style 指定

**style 指定**{: style="color: red;"}

```
**style 指定**{: style="color: red;"}
```

<span style="color: red;">style 指定</span>

```html
<span style="color: red;">style 指定</span>
```

---
## A. 参考文献・URL

- kramdown Quick Reference  
  <https://kramdown.gettalong.org/quickref.html>
- GitHub Pages themes  
  <https://github.com/pages-themes>

---
