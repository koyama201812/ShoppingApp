# ECサイトをつくる

## 環境
- Docker
- CentOS7
- Laravel
- Vue

## 要件定義
### 機能一覧
- TOP・商品一覧/詳細・新規登録・ログイン画面は全ての人が閲覧することが出来る
- user
    - userはアカウントを持つ
    - userは自分の情報を編集もしくは退会出来る
    - userは商品をカートに入れ、購入出来る
    - userは商品を検索出来る
    - userは場合によっては商品を取り消すことができる
    - userがログインしていない場合は、カートに入れるを押した時ログイン画面へうつる
    - userはログアウトが出来る
- admin
    - adminはuserの全ての操作が出来る
    - adminは全userの一覧をみることが出来る
    - adminはuserの削除(または退会)が出来る
- adminは配送状況の変更が出来る
    - adminは商品の登録/編集が出来る
    - admin

### 画面設計
#### 全て
- TOP
- 新規登録
- ログイン
- 商品一覧
- 商品詳細

#### ログイン後
- admin
    - user一覧
    - 商品登録
    - 商品編集
- user
    - 詳細
    - 編集(退会)
    - 商品購入一覧(購入日/個数/配送状況/キャンセル可否)
    - カートの中身
    - 購入確認
    - 購入完了


### URL設計

### DB設計




