# SHIFT説明文
## 1. オブジェクトの説明
|<img src="./.data/images/Field/player.GIF" width=100>|
|:-:|
|プレイヤー|
|**WASD**で操作できます|


|<img src="./.data/images/Field/goal.GIF" width=100>|
|:-:|
|ゴール|
|**プレイヤー**がゴールのマスにいればクリアです<br>手数を超えると王冠が割れてしまいます。|

|<img src="./.data/images/Field/structure.GIF" width=100>|
|:-:|
|障害物|
|プレイヤーはこのマスに**進むことができません。**|


|<img src="./.data/images/Field/reverse.GIF" width=100>|
|:-:|
|リバース|
|踏むと操作が**上下左右それぞれ反転**します|


|<img src="./.data/images/Field/warp.GIF" width=100>|
|:-:|
|ワープ|
|踏むと**もう一つのワープマスまでワープ**します|

## 2. ゲームルール
2つの盤面で**同時に**プレイヤー<img src="./.data/images/Field/player.GIF" width=15>がゴールマス<img src="./.data/images/Field/goal.GIF" width=15>にいればクリアです。<br>
画面上部に書かれた**0/4**は手数を表しています。このステージでは**4回の操作**でクリアする必要があります。

![rule](./.img/rule1.png)

## 3. 操作方法
|操作|キー|
|:-:|:-:|
|移動|WASD|
|最初から|R|
|一手戻る|Backspace|
|ゲームを終了する|esc|

## 4. メニュー画面
遊ぶステージを選べます。表示は**world-stage**で書かれています。各worldごとに大まかなstageの特徴があります。
|world|特徴|
|:-:|:-:|
|0|チュートリアル|
|1|障害物<img src="./.data/images/Field/structure.GIF" width=15>|
|2|リバース<img src="./.data/images/Field/reverse.GIF" width=15>|
|3|ワープ<img src="./.data/images/Field/warp.GIF" width=15>|
|4|すべて|
|5|サイズ違い|

- **操作方法**

|操作|キー|
|:-:|:-:|
|world選択|WS|
|stage選択|AD|
|あそぶ|Enter|


- **表示される色の意味**
<span style="color: yellow;background-color:#dddddd;">手数以内にクリア</span>
<span style="color: red;background-color:#dddddd;">手数は超えているがクリア</span>

![rule](./.img/rule2.png)
