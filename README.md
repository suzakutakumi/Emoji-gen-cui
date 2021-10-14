# Emoji-gen-cui
絵文字ジェネレータをターミナル上から使えるコマンドです。

## インストール方法

```bash
curl -s https://raw.githubusercontent.com/suzakutakumi/Emoji-gen-cui/master/install.sh|bash
```

上記のコマンドによってインストールできる

## 使い方

### 基本

```shell
emojigen 文字の色(RGB) 生成したい文字
```

このコマンドによって"**生成したい文字.png**"が生成されます  
改行したい場合は改行場所に"_"を入れてください

### 例

```shell
emojigen ff00ff Emoji_GenCli
```

![Emoji_GenCli](https://user-images.githubusercontent.com/71514776/137248113-5c63266a-c483-4036-8a1d-84e099307025.png)

## オプション

### randomオプション

--random|-rを使うことで色をランダムにすることができます

```shell
emojigen -r 生成したい文字
```

## 偉大なる絵文字ジェネレータ様
[Webページ](https://emoji-gen.ninja/)  
[GitHub](https://github.com/emoji-gen/web-main)  
[Twitter](https://twitter.com/emoji_gen)  
