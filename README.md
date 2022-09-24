課題1
階層が増えれば増えるほどjoinの回数が増える
階層の深さを調べるクエリを書かないといけない
集合の全てを取得してアプリ側でデータの形成などを行わないといけないので、関心ごとが増える

課題2
別紙参照

課題３
ディレクトリ管理をするようなシステム
(マイクロソフトのシェアポイントやGoogle Driveのようなシステム)

その他
### 経路列挙
- pathが文字列が格納されるので、誤ったデータが入る可能性がある
- whereで検索時にLIKEを用いないといけない。検索に引っかからない可能性もある
- 当該のデータを取得しても、pathが文字列なのでデータの形成をした上でデータを取得しないといけいない

### 入れ子集合
- 幅を覚えておかないと両端を決めて入力しないといけないから、設計に柔軟さが欠ける
- 両端の値に溢れそうなデータ量になってきたら、改修するのが大変

