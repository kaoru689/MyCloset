# README
アプリケーション名:
　〜My Closet〜
アプリケーション概要と制作背景:
 自分のクローゼットの中身を外出先でも見れるようにしました。自分の持っている洋服の画像を貼り付けて一覧で見ることができ、アイテム別に表示、季節別に表示だったりの絞り込み機能も付けました。
 洋服が好きなのですが、洋服をお店に買いに行った時、例えはこのトップスと合う家にあるスカートは何だろう？と思うことがあり、コーディネートを想像するよりも実際に写真で見て選べたら良いなと思い、このアプリを作りました。
 似たような洋服もうっかり買わずに済むはずです。

本番環境：

工夫したポイント:

使用技術(開発環境):

課題や今後実装したい機能:


# テーブル設計

## items テーブル

| Column           |  Type      | Options                        |
| --------------   | ------     | ---------------------          |
| image            | string     | null: false                    |
| memo             | text       |                                |
| type_id          | integer    | null: false                    |
| season1_id       | integer    | null: false                    |
| season2_id       | integer    |                                |
| season3_id       | integer    |                                |

