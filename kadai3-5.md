## 自動販売機（データ構造と各種処理）のミニレポート
### Q5-1. 自動販売機の商品データついて説明せよ。
* データ構造（各項目とその説明）
  id 商品番号
 name　商品名
  price　金額
  stock　在庫
  
* 連想配列の配列として定義するメリット
  商品情報の管理が容易
  
  
### Q5-2. showItemListの処理内容について説明せよ。
* 配列の繰り返し処理
  for分でitems配列の全要素を順に取り出し各情報を一つずつ表示
  
* 連想配列の参照方法
  繰り返しで各商品データを個別に参照
  
### Q5-3. buyItemの処理内容について説明せよ。
* 商品購入の可否判定
* 商品在庫を減らす処理
* 商品番号のエラー処理

番号が有効か確認→在庫があれば購入・減算、なければ「在庫なし」を表示

### Q5-4. プログラムの考察
* データ構造について
* 商品一覧表示と購入処理を関数化したメリット
  
  関数化で処理の再利用と見通しがよくなった。配列＋連想配列で柔軟なデータ管理が可能。
### Q5-5. 感想
* 今回の課題で苦労したこと
* 演習を通して理解できたこと
* この自動販売機プログラムの追加機能や課題など

  在庫や番号の処理が少しややこしかったが、配列とオブジェクトの使い方が理解できた。今後は金額入力なども加えてみたい。
