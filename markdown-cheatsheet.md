---
layout: slate-custom
title: Markdown チートシート
---

---
## 1. 見出し

見出し1
=======

```
見出し1
=======
```

# 見出し1

```
# 見出し1
```

<h1>見出し1</h1>

```html
<h1>見出し1</h1>
```

見出し2
-------

```
見出し2
-------
```

## 見出し2

```
## 見出し2
```

<h2>見出し2</h2>

```html
<h2>見出し2</h2>
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
## 2. 段落

1つめの段落です。

2つめの段落です。

```
1つめの段落です。
(空行)
2つめの段落です。
```

<p>1つめの段落です。</p>

<p>2つめの段落です。</p>

```html
<p>1つめの段落です。</p>

<p>2つめの段落です。</p>
```

---
## 3. 水平線

---

```
---
```

***

```
***
```

_ _ _

```
_ _ _
```

<hr>

```html
<hr>
```

---
## 4. コードブロック

```
Hello, World!
```

````
```
Hello, World!
```
````

~~~
Hello, World!
~~~

````
~~~
Hello, World!
~~~
````

    Hello, World!

```
    Hello, World!
```

<pre>Hello, World!</pre>

```html
<pre>Hello, World!</pre>
```

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

> これは引用文です。
> > 二重引用文です。

```
> これは引用文です。
> > 二重引用文です。
```

---
## 6. 順序つきリスト

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

---
## 7. 順序なしリスト

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

- [x] タスク1
- [ ] タスク2

```
- [x] タスク1
- [ ] タスク2
```

---
## 8. 定義リスト

用語1
: 説明1
: 説明2

用語2
用語3
: 説明3

```
用語1
: 説明1
: 説明2

用語2
用語3
: 説明3
```

---
## 9. テーブル

|ヘッダー1|左寄せ|中寄せ|右寄せ|
|-------|:----|:---:|----:|
|長い行|いろはにほへと|ABCDEFG|1234567|
|短い行|あいうえお|abc|123|
{: #mytable .mytable}

```
|ヘッダー1|左寄せ|中寄せ|右寄せ|
|-------|:----|:---:|----:|
|長い行|いろはにほへと|ABCDEFG|1234567|
|短い行|あいうえお|abc|123|
{: #mytable .mytable}
```

---
## 10. リンク

[ホームページ](./index.html)

```
[ホームページ](./index.html)
```

ホームページ: <https://glad2121.github.io/>

```
ホームページ: <https://glad2121.github.io/>
```

---
## 11. イメージ

---
## 12. 文字修飾

*Itaric*

```
*Itaric*
```

<em>Itaric</em>

```html
<em>Itaric</em>
```

**太字**

```
**太字**
```

<strong>太字</strong>

```html
<strong>太字</strong>
```

`code`

```
`code`
```

<code>code</code>

```html
<code>code</code>
```

~~取消~~

```
~~取消~~
```

<del>取消</del>

```html
<del>取消</del>
```

**id 指定**{: #myid}

```
**id 指定**{: #myid}
```

<span id="myid2">id 指定</span>

```html
<span id="myid2">id 指定</span>
```

**class 指定**{: .myclass}

```
**class 指定**{: .myclass}
```

<span class="myclass">class 指定</span>

```html
<span class="myclass">class 指定</span>
```

**style 指定**{: style="color: red;"}

```
**style 指定**{: style="color: red;"}
```

<span style="color: red;">style 指定</span>

```html
<span style="color: red;">style 指定</span>
```

## A. 参考 URL

- kramdown Quick Reference  
  <https://kramdown.gettalong.org/quickref.html>
- GitHub Pages themes  
  <https://github.com/pages-themes>
