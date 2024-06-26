# gacha-pull-plan

原神や崩壊スターレイルなどのゲームのガチャでピックアップ星5キャラクターを当てるまでの計画に利用するためのプログラムです。

### Google Colab での実行
このリポジトリのコードを Google Colab 上で実行することも可能です。
| Colab name | Colab Page |
| --- | --- |
face_features.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yhotta240/face_features/blob/main/face_features.ipynb)  

remaining_days:  残りの日数<br>
current_stones:  所持している石の数<br>
current_tickets:  所持しているチケットの数<br>
current_pulls:  すでに引いている回数<br>
slip_through:  すり抜けしたかどうか<br>
isDaily:　デイリーミッションを毎日やるかどうか<br>

を入力することにより<br>

・天井まで必要な回数<br>
・天井まで必要な石の数<br>
・残りの日数で獲得できる石の数<br>
・毎日獲得目標とする石の数<br>
・不足している石の数<br>
・追加の石が必要か不要か<br>

の結果を得ることができる
