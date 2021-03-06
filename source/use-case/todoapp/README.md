---
author: azu
---

# ユースケース: Todoアプリ {#todo-app}

ここではブラウザで動作するウェブアプリケーション（以下アプリ）のユースケースとして、Todoアプリを作成していきます。
ここで作成するTodoアプリは、タスクを入力しそのタスクの完了状態をチェックボックスで管理するというアプリです。

[Ajax通信][]のユースケースではGitHubからデータを取得し表示するだけであったため状態を管理する部分は殆どありませんでした。
しかし、このTodoアプリはタスクの状態管理をするためアプリとしての状態を管理する必要があります。
このユースケースを通して、どのように状態を管理し、表示や処理を変更するかといったアプリに作るにあたり必要になる設計や考え方についてを見ていきます。

作成するアプリは次の要件を満たすものとします。

- Todoアイテムを追加できる
- Todoアイテムの完了状態を更新できる
- Todoアイテムを削除できる

[Ajax通信]: ../ajaxapp/README.md
