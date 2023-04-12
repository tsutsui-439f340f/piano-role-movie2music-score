# piano-role-movie2music-score
YouTubeなどに存在しているピアノロール動画使用して、楽譜の復元を行います。
本来ピアノロール動画はDTMソフトウェア上で作成したmidiファイルを使用して作成されるものですが、本プロジェクトではその逆を行うことで、音楽データの抽出を試みます。

# 更新
2023/04/12:動画のピアノロールの場所を指定すると、自動解析をし音符の抽出に成功

# サンプル
![image](https://user-images.githubusercontent.com/55880071/231452391-93a9b7a7-7804-4735-a103-4751af9d3af3.png)

\\\
1つ目の要素は観測時間、2つ目は音、3つ目は音の長さ(1が四分音符, 4が全音符, 0.5は八分音符)
```
[[1.1344666666666667, 'F_3', 0.25],
 [1.1845166666666667, 'A#_3', 0.25],
 [1.1344666666666667, 'G#_2', 0.25],
 [1.4014000000000002, 'A#_3', 0.25],
 [1.35135, 'G#_3', 0.5],
 [1.7017000000000002, 'D#_4', 0.5],
 [1.7517500000000004, 'A#_3', 0.5],
 [1.7517500000000004, 'G#_3', 0.5],
 [2.2022, 'A#_3', 0.5],
 [2.15215, 'D_4', 0.5],
 [2.2022, 'G#_3', 0.5],
 [2.8194833333333333, 'D#_4', 1.25],
 [2.8695333333333335, 'A#_3', 1],
 ...
 ```
