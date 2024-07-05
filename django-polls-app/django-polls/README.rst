=====
Polls
=====

Polls is a Django app to conduct web-based polls. For each question,
visitors can choose between a fixed number of answers.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "polls" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...,
        "polls",
    ]

2. Include the polls URLconf in your project urls.py like this::

    path("polls/", include("polls.urls")),

3. Run ``python manage.py migrate`` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/polls/ to participate in the poll.


------------------------以下は日本語です------------------------
=================
投票アプリ（Polls）
=================
投票アプリ（Polls）は、Webベースの投票を行うためのDjangoアプリです。各質問に対して、訪問者は固定された選択肢から1つを選ぶことができます。

詳細なドキュメントは "docs" ディレクトリにあります。

クイックスタート
"polls" を INSTALLED_APPS 設定に追加します。以下のように記述します：

INSTALLED_APPS = [
    ...,
    "polls",
]

プロジェクトの urls.py に投票アプリのURLconfを追加します。以下のように記述します：

path("polls/", include("polls.urls")),

python manage.py migrate を実行して、投票アプリのモデルを作成します。

開発サーバーを起動し(python manage.py runserver)、http://127.0.0.1:8000/admin/ にアクセスして投票を作成します（管理アプリが有効である必要があります）。

http://127.0.0.1:8000/polls/ にアクセスして、投票に参加します。