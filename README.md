# takahashi_yosan
高梁川流域の市町の予算比較グラフ

##使い方
1 簡易httpサーバーを走らせる
 - python2系だと`python -m SimpleHTTPServer`
 - python3系だと`python -m http.server`

2 [ローカルホストの８０００番ポート](http://localhost:8000)へブラウザでアクセス  
3 グラフが描画される

##機能
- ソート（棒グラフをクリックすると予算額の昇順、もう一度押すと降順にソートする）
- データの切り替え（グラフの下にあるボタンをクリックすると議会費、総務費・・・と描画するグラフが変化する）

##データの引用元
* [高梁川流域圏自治体_一般会計_予算](http://catalog.dataeye.jp/dataset/33tak000001)
* [H27の国勢調査の人口速報集計](http://www.stat.go.jp/data/kokusei/2015/kekka.htm)  
[data.csv](https://github.com/piiice16/takahashi_yosan/edit/master/data.csv)は一般予算額を人口で割った値を用いている。  
[H27jinko.csv](https://github.com/piiice16/takahashi_yosan/edit/master/H27jinko.csv)は各市町の人口である。
