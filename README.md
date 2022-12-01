# How_to_write_README
## README.mdの書き方とその例に関するリポジトリ

### 表の書き方 例
|  番号 | 日付  |  空行 | 値 |
| ----- | ----- | ---- | -- |
| 1     | 04/10 |      | 10 |
| 2     | 04/10 |      | 20 |
| 3     | 04/11 |      |    |
| 4     | 04/12 |      | 40 |

<!--
this is a comment.
コメントはこのように書く
複数行にも対応可能
-->

### リスト
- list1
- list2
- list3
  - list3-1
  - list3-2
- list4

### 改行
これだと
改行できない

これと<br>
これは  
改行できる

    これだと
    改行できない
    
    これと<br>
    これは  
    改行できる

    説明
    <br>
      (半角スペース×2)
    で改行可能

### 強調表現
比較用
 
**強調1**
 
__強調2__

### リンク
この[リンク](https://github.com/Sakkyun71Gray/How_to_write_README)はこのページへのリンクです


### 画像の挿入
![サンプル画像](pic/sample.png)

### コードの挿入
```bash
git clone https://github.com/Sakkyun71Gray/How_to_write_README
cd --
java Hello.java
```

### 複合
画像にリンクを埋め込む(以下の画像はこのページへのリンク)

[![サンプル画像](pic/Link.png)](https://github.com/Sakkyun71Gray/How_to_write_README)

### 複合2
|  　　 | 　　  |
| ----- | ----- |
|[![サンプル画像](pic/sample.png)](https://github.com/Sakkyun71Gray/How_to_write_README)|![サンプル画像](pic/Link.png)|
|![サンプル画像](pic/Link.png)|![サンプル画像](pic/sample.png)|

### その他
[参考ページ](https://omrilotan.medium.com/rich-html-in-github-readme-bfb3de791441#:~:text=Rich%20HTML%20in%20GitHub%20README%201%20TL%3BDR.%20Jump,Enter%20foreignObject.%20...%204%20Put%20it%20together.%20)