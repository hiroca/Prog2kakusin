# Prog2kakusin
プログラミング２の　google colab ためのリポジトリ
## プログラム１について
1. プログラムの概要
  * このプログラムは自らデータフレームを入力し、また不明なデータフレームの要素１つを同じ行の要素から推測するというプログラムです。
2. 役に立つ状況
  * まずこのプログラムは自分でデータフレームを作成できるという面で優れています。そのうえでもしデータを入力する際に不明なデータがあるときに都合の良いデータをさくせいすることができるので未完成なデータフレームを無理やり完成させることができます。
3. 入力と出力
    1. 行数を入力
    2. 行名を入力
    3. 列数を入力
    4. 列名を入力した後その要素を行数分入力
    5. ４を列数分繰り返すその際不明な要素の部分にNoneと入力
    6. Noneと入力した要素のある行のその他の要素が同じ列にあるその他の行の要素とどれくらいまでの差がある要素を参考にNoneを埋めるのかを決める「基準値」を入力
    7. Noneに基準値をもとに推測された値を代入してデータフレームを出力
4. 工夫した点
  * データフレームを作成する際間違った値を入力した際に00と入力すると１つ前に戻ることができる
