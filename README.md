# Golang and Next.js Todo app

簡単なTodoアプリをNext.jsとGoで作成します。

インフラの構築には`AWS CDK`を使用し、 AWS Lambda に GoとNext.jsを実装します。

GoはDynamoDBにTodoアイテムを保存するためのAPIを提供します。Next.jsはバックエンドサーバにアクセスしてTodoアイテムを表示したり更新したりします。
