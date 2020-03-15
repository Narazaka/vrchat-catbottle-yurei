# vrchat-catbottle-yurei

VRChat用の2Dアバターです。

[猫ボトル(ボトル猫さん)の伺かフリーシェル](http://catbottle.sakura.ne.jp/souko_fs.html)をざっくり2Dアバター化したものです。

## アバターとしてのアップロード方法

1. git cloneまたはzipダウンロードしてUnityで開く
2. VRCSDKを入れる
3. 多分アップロードできる

## 作り方

1. （規約上問題の無い）フリーシェルをてきとうにダウンロード
2. 伺かの透過関係が特殊なsurface0.pngとかを一般に読めるpngにするツール [ukagaka-surface-to-standard-png](https://www.npmjs.com/package/ukagaka-surface-to-standard-png)を使ってUnityで普通に扱える透過PNGにする
3. 諸々設定してアップロード

## ライセンス

部分部分でライセンスが異なりますが、基本的にその中で一番厳しいMITライセンスに従っておくと大体オッケーな気がします。

### Reflex Shader 2（Assets/Reflex Shader 2）

[MIT License](Assets/Reflex%20Shader%202/LICENSE)

### シェルデータ（Assets/g01-normalize）

[ボトル猫製作のフリーシェルについての適当なガイドライン](http://catbottle.sakura.ne.jp/shell_memo.txt)

```
ボトル猫製作のフリーシェルについての適当なガイドライン。

＊やってもいいことの一例

・相方のみなど一部を抜き出しての使用

・色変更

・表情合成などの切り張り

・完全に別物への改変

・反転して\0、\1逆の使用

・他のシェルと組み合わせて使用

・見た目を似せた別のシェルの作成

・再配布

・改変して再配布

・ゴースト以外での使用

・使用ゴーストの二次創作絵や同人での使用

・暫定のシェルとしての使用

・一発ネタゴーストで使用

・有償の媒体での使用

・年齢制限付きのコンテンツで使用

・会員制コンテンツでの使用

・製作者表記無しでの使用


＊禁止事項

・違法な行為への使用
```

### Assets/AvatarBase.fbx

```
Copyright (c) 2020 Narazaka

This software is provided 'as-is', without any express or implied warranty. In no event will the authors be held liable for any damages arising from the use of this software.
Permission is granted to anyone to use this software for any purpose, except commercial applications, and to alter it and redistribute it freely, subject to the following restrictions:
1. The origin of this software must not be misrepresented; you must not claim that you wrote the original software. If you use this software in a product, an acknowledgment in the product documentation would be appreciated but is not required.
2. Altered source versions must be plainly marked as such, and must not be misrepresented as being the original software.
3. This notice may not be removed or altered from any source distribution.

このソフトウェアは、"as-is (現状のまま)" で、明示であるか暗黙であるかを問わず、何らの保証もなく提供されます（著作者はバグを含めたあらゆる改修義務を負いません）。
著作者は、それが利用されることによって起こりうるいかなる損害に対しても責任を負いません。
商用利用でない場合にのみ、ソフトウェアの改変・配布は以下の制限のもとで許可されます。
1. ソフトウェアの原著作者であると詐称してはなりません。（著作者の表示義務はありません）
2. ソフトウェアを改変した場合はオリジナルのままだと勘違いされないようにしなければなりません。
3. ライセンス表示をソフトウェアそのものの配布物（blendファイル・fbxファイル・unitypackageなど）から削除してはなりません。（ソフトウェアを利用した著作物に含める義務はありません）
```

### その他の部分

[NYSL](http://www.kmonos.net/nysl/)

```
A. 本ソフトウェアは Everyone'sWare です。このソフトを手にした一人一人が、
   ご自分の作ったものを扱うのと同じように、自由に利用することが出来ます。

  A-1. フリーウェアです。作者からは使用料等を要求しません。
  A-2. 有料無料や媒体の如何を問わず、自由に転載・再配布できます。
  A-3. いかなる種類の 改変・他プログラムでの利用 を行っても構いません。
  A-4. 変更したものや部分的に使用したものは、あなたのものになります。
       公開する場合は、あなたの名前の下で行って下さい。

B. このソフトを利用することによって生じた損害等について、作者は
   責任を負わないものとします。各自の責任においてご利用下さい。

C. 著作者人格権は Narazaka に帰属します。著作権は放棄します。

D. 以上の３項は、ソース・実行バイナリの双方に適用されます。
```
