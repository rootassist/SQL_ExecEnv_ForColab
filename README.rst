=====================
Name
=====================
Google ColaboratoryでSQL演習環境を作る

=====================
Overview
=====================
- SQLコマンドを実行できる環境をGoogle Colaboratoryに作ります
- データベースサーバーはPostgreSQL13です
- データベースを作成するために必要なファイルは「GitHubのリポジトリから得る」「Google Driveから得る」の2パターンを用意しました

=====================
Description
=====================
- GitHubリポジトリ編ipynb:https://raw.githubusercontent.com/rootassist/SQL_ExecEnv_ForColab/main/Pagila_Env_FromGitHub_ForColab.ipynb
 - データベース「pagila」を以下リポジトリにある「pagila-schema.sql」「pagila-data.sql」で構築します
 - https://github.com/devrimgunduz/pagila

- Google Drive編ipynb:https://raw.githubusercontent.com/rootassist/SQL_ExecEnv_ForColab/main/World_Env_FromGoogleDrive_ForColab.ipynb
 - データベース「world」をGoogle Driveの「マイドライブ」フォルダの下にある「DBSample」フォルダに置いた「world.sql」で構築します。
 - 「world.sql」ファイルは以下のページからダウンロードできる「world-1.0.tar.gz」を展開したもので
 - https://www.postgresql.org/ftp/projects/pgFoundry/dbsamples/world/world-1.0/

=====================
Usage
=====================

- 詳細な説明は note () に書いています。

---------------------
GitHubリポジトリ編
---------------------

1) 以下のリンクをクリックする

https://raw.githubusercontent.com/rootassist/SQL_ExecEnv_ForColab/main/Pagila_Env_FromGitHub_ForColab.ipynb

2) ファイル上部の「Open in Colab」をクリックする

3) 「環境構築用のセル」を実行する （準備のために時間がかかります）

---------------------
Google Drive編
---------------------

1) 以下のリンクをクリックする

https://raw.githubusercontent.com/rootassist/SQL_ExecEnv_ForColab/main/World_Env_FromGoogleDrive_ForColab.ipynb

2) ファイル上部の「Open in Colab」をクリックする

3) 「環境構築用のセル」を実行する （準備のために時間がかかります）

=====================
Acknowledgments
=====================
すばらしい研修課題をご提供されている一般社団法人データサイエンティスト協会スキル定義委員の皆さまに感謝いたします。
