覚えてる限りで書く
#### Application の仕様
* Twitter垢連携して投稿できるようにする
* 何か一つ文章を入れると、前に誰かが入れた文章が出て来る
  * 強制Tweet or preview出来る？
    * 強制で、なんのApplicationからTweetされたかはヘッダで出す方がドキドキはする

#### 開発環境 
* 言語はPython
* 基本はAWSのManaged service をフル活用
  * Web interface : API Gateway?
  * 実処理 : lambda?
  * アカウント連携 : Amazon Cognito?
  * Data store : SQS? DynamoDB? S3でファイル書き出しでも良いかも
