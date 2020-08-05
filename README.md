# CRUDWebApiApp
NorthwindデータベースサンプルからリバースエンジニアリングしたWebAPIサンプルです

# 事前準備
以下の手順に従い、SQL Server上にNorthwindサンプルデータベースを作成してください。  
https://github.com/Microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs

# 実行手順
サンプルプロジェクトを開き、`appsettings.json`の`Connection`に作成したNorthwindデータベースの接続文字列を設定します。

`launchSettings.json`を開き、`applicationUrl`を環境にあわせて変更します。

実行します。