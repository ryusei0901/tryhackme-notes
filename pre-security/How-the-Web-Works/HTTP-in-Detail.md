HTTPの詳細

##概要
HTTPの詳細


##タスク
１．HTTP(S)とは
２．リクエストとレスポンス
３．HTTPメソッド
４．HTTPステータスコード
５．ヘッダー
６．クッキー
７．リクエストの作成


##学んだこと
HTTPとは
HTTPSとは
URLとは（スキーム、ユーザー、ホスト、ポート、パス、クエリ文字列、フラグメント）
リクエストの作成
HTTPメソッドの種類（GETリクエスト、POSTリクエスト、PUTリクエスト、DELETEリクエスト）
共通リクエストヘッダー（HOST、User-Agent、Content-Length、Accept-Encoding、Cookie）
共通レスポンスヘッダー（Set-Cookie、Cache-Control、Content-Type、Content-Encoding）
クッキーの表示




##クイズ
Q.HTTPは何の略か
A.HyperText Transfer Protocol

Q.HTTPSとは何の略化
A.Secure

Q.模擬ウェブページの問題を見つける（実践）

Q.どのHTTPプロトコルが使用されているか
A.HTTP/1.1

Q.どのくらいの量のデータが予想されるかをブラウザに伝える応答ヘッダーは何ですか?
A.Content-Length

Q.新しいユーザー アカウントを作成するにはどのような方法を使用しますか?
A.POST

Q.電子メール アドレスを更新するにはどのような方法を使用しますか?
A.PUT

Q.アカウントにアップロードした写真を削除するにはどのような方法がありますか?
A.DELETE

Q.ニュース記事を閲覧するにはどのような方法を使用しますか?
A.GET

Q.新しいユーザーまたはブログ投稿記事を作成した場合、どのような応答コードを受け取る可能性がありますか?
A.201

Q.存在しないページにアクセスしようとした場合、どのような応答コードが返される可能性がありますか?
A.404

Q.Web サーバーがデータベースにアクセスできず、アプリケーションがクラッシュした場合、どのような応答コードを受け取る可能性がありますか?
A.503

Q.最初にログインせずにプロフィールを編集しようとすると、どのような応答コードが表示されるでしょうか?
A.401

Q.どのヘッダーが Web サーバーに使用されているブラウザを通知しますか?
A.User-Agent

Q>返されるデータの種類をブラウザに伝えるヘッダーは何ですか?
A.Content-Type

Q.どのヘッダーが、どの Web サイトが要求されているかを Web サーバーに伝えるのでしょうか?
A.Host

Q.コンピュータにクッキーを保存するために使用されるヘッダーはどれですか?
A.Set-Cookie

実践
Q./room ページへのGETリクエストを実行する

Q>blogページへのGETリクエストを作成し、 idパラメータを1に設定します。注: URIパラメータを管理するには、右側の歯車ボタンを使用します。

Q./user/1ページにDELETEリクエストを発行する

Q.ユーザー名 パラメータをadminに設定して、/user/2ページにPUTリクエストを送信します。注: ボディパラメータを管理するには、右側の歯車ボタンを使用します。

Q./loginページにユーザー名thm 、パスワードletmeinでPOSTリクエストを送信します。注: ボディパラメータを管理するには、右側の歯車ボタンを使用します。
