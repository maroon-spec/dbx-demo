# dbx-demo

こちらは dbxを使ったDatabricksのリモートクラスター実行のためのサンプルコードです。お使いのIDEと連携してお使い頂けます。
詳細はこちらもご覧ください。
https://learn.microsoft.com/ja-jp/azure/databricks/dev-tools/dbx

# Setup
1. install dbx in local compute. 
```$ pip install dbx```

2. Configure databricks workspace information
```$ databricks configure --token```

3. Clone this code both local laptop and Databricks workspace.
```
$ git clone https://github.com/maroon-spec/dbx-demo.git
$ cd dbx-demo
```
4. create dbx project
``` $ dbx configure```

5. Create Cluster in Databricks workspace.  

6. Run code in local IDE
```dbx execute --cluster-name <cluster-name> dbx-demo-job --no-package```
