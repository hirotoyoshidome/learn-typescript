## install

* install latest nodejs

```
sudo apt install -y nodejs npm
sudo npm install n -g
sudo n stable
sudo apt purge -y nodejs npm
exec $SHELL -l
node -v
```

* install Typescript

```
sudo npm install -g typescript ts-node
```

## exec
* compile and exec

```
tsc hello.ts
node hello.js
```

※↑tscでtsファイルをjsファイルにトランスコンパイルできるらしい

* ts-node exec

```
ts-node hello2.ts
```
※プリコンパイルなしで実行もできる

## description

* 基本型
  * number ： 整数 、浮動小数点数
  * string ： 文字列
  * boolean ： 真偽値
  * symbol ： シンボル型
  * any ： 任意の型（型の制約がなくなる）

* 文字列リテラル
  * シングルクォート
  * ダブルクォート
  * バッククォート（${…}で変数埋め込み可能、複数行表現可能）

それ以外はだいたいJSと一緒な感じ
→JS, nodejs, Solidityの勉強後、再度勉強する
