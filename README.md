# ref.inc.php
 refサムネイル対応

既存の refプラグインに、サムネイル画像の指定方法を追加しています。
新パラメータ： thumb=xxxx
第3パラメータ以降の任意位置に記述できる。xxxはサムネイル画像。サムネイル画像は当該文書に添付する必要あり。

別途公開している「サムネイル生成機能を持つAttach.inc.php https://github.com/HarukaTomose/attach.inc.php」で生成できるキャッシュデータはあえて使用していません。
サムネイルには単純に縮小した画像を使いたくない（必要な部分をトリム・変倍したものを使いたい）ケースが想定されるため。



