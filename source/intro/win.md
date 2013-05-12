% 競技プログラミングのためのWindows入門
% Tomoki Imai
% 2013/05/12

# イントロダクション
この記事は、競技プログラミングに必要な開発環境をWindows上で整えようという人をサポートするために書かれました。
MacやLinuxユーザーは自分でなんとかしてください。

# 開発環境を入れよう

## 開発環境の選択
WindowsでC++をやろうとすると、いくつかの選択肢がある。パッと思いつくのはこれくらい。

- VisualStudioを使う : 登録しなきゃだけど、無料
- MinGW + エディタ(NotePad++とか) : 無料

ここでは、VisualStudioを使うことにするけど、他の選択をしたいという人のためにいくつかリンクを貼っておくね。

- [Mingw Getting Started](http://www.mingw.org/wiki/Getting_Started) 英語の本家
- トーラスさんの記事

## VisualStudioを入れよう
[VisualStudio Express 2012 for Windows Desktop ](http://www.microsoft.com/visualstudio/jpn/downloads)をダウンロード&インストールしよう。
まぁ入れ方についてはそれほど難しくない(クリックするだけ)なので、がんばってね。
バージョンが変わったら入れ方も変わると思うから。


# 最後に
これでとりあえずは戦えるかなという感じなんだけれど、最後にいくつか。

## Windowsを使うこと
Windowsを扱うのは大変だ。今回だけでも、コンパイラのいれかたとか、すごく大変だった。
もしも、君が情報科学/工学の人だったりするのであれば、Linuxを使うことをお勧めしておく。
VirtualBoxとか、VMWareとかでWindows上でLinuxを扱うこともできるからね。

## Linuxを使うメリット
ぼくも普段はLinuxしか使ってない。Linuxを使う最大のメリットは、開発がしやすいことにある。
Cygwinとかいろいろあるけれど、Linuxの足元にも及ばない。