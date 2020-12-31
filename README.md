# Amazonの在庫をチェックして、在庫があった場合にツイートするボットを作成します
なお、処理は極力クラス化して、クラス外への記述は最小限にしてください。<BR>
設定ファイルは.envファイルとして管理して、load_dotenvを使って呼び出すようにしてください。<BR>
seleniumは使用せずにrequestsモジュールを使用してください。

## １
TwitterAPIキーを取得してください<BR>
https://www.itti.jp/web-direction/how-to-apply-for-twitter-api/

## ２
Amazonの在庫チェックを実装してください<BR>
在庫チェックは以下のような商品ページで「カートに入れる」ボタンの有無で判断してください<BR>
https://www.amazon.co.jp/%E3%82%B7%E3%83%A3%E3%83%BC%E3%83%97-SHARP-SJ-AF50G-R-%E3%83%97%E3%83%A9%E3%82%BA%E3%83%9E%E3%82%AF%E3%83%A9%E3%82%B9%E3%82%BF%E3%83%BC-%E3%82%B0%E3%83%A9%E3%83%87%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%83%AC%E3%83%83%E3%83%89/dp/B08KJ85RJ5?ref_=fspcr_pl_dp_2_2272928051

## ３
任意の文のTweetを実装してください<BR>

## ４
Amazonの在庫が見つかったらツイートするようにしてください

## ５
一度ツイートした商品は、再度在庫切れになるまではツイートしないようにしてください

## ６
無限ループのプログラムとして、起動したら一定間隔で指定したURLを監視して、在庫が見つかったらツイートするようにしてください
