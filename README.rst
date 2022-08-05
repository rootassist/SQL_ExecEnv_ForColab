=====================
Name
=====================

Google ColaboratoryでSQLの演習環境を作る

=====================
Overview
=====================

- SQLを実行できる環境として、Google Colaboratoryで動作するNoteBookを提供します
- データベースサーバーはPostgreSQLとMySQLです
- 以下の3種類のパターンを用意しています。適宜組み合わせてご利用下さい。
1) PostgreSQL: データベースを構築に必要なファイルを「GitHubのリポジトリ」から得る
2) PostgreSQL: データベースを構築に必要なファイルを「Google Drive」から得る
3) MySQL: データベースを構築に必要なファイルを「サイト」から得る

=====================
Description
=====================

---------------------
PostgreSQL 'GitHub Repository' type ipynb:
---------------------

https://github.com/rootassist/SQL_ExecEnv_ForColab/blob/main/Pagila_Env_FromGitHub_ForColab.ipynb

- データベース「pagila」
- 以下リポジトリにある「pagila-schema.sql」「pagila-data.sql」で構築します

 https://github.com/devrimgunduz/pagila

---------------------
PosgreSQL 'Google Drive' type ipynb
---------------------

https://github.com/rootassist/SQL_ExecEnv_ForColab/blob/main/World_Env_FromGoogleDrive_ForColab.ipynb

- データベース「world」
- Google Driveの「マイドライブ」フォルダの下にある「DBSample」フォルダに置いた「world.sql」で構築します
-「world.sql」ファイルは以下のページからダウンロードできる「world-1.0.tar.gz」を展開したものです

 https://www.postgresql.org/ftp/projects/pgFoundry/dbsamples/world/world-1.0/

---------------------
MySQL 'Site' type ipynb
---------------------

https://github.com/rootassist/SQL_ExecEnv_ForColab/blob/main/Sakila_Env_FromGitHub_ForColab.ipynb

- データベース「Sakila」
- MySQL公式ホームページの以下のURLから/tmp/dataの下にダウンロードして展開して得られた「sakila-schema.sql」「sakila-data.sql」で構築します

  http://downloads.mysql.com/docs/sakila-db.zip

=====================
Usage
=====================

- 詳細な説明は note (https://note.com/nmt_rootassist/n/na8ace92f452c) に書いています

1) それぞれ該当するNoteBookのリンクをクリックする

PostgreSQL 'GitHub Repository' type ipynb:
https://github.com/rootassist/SQL_ExecEnv_ForColab/blob/main/Pagila_Env_FromGitHub_ForColab.ipynb

PosgreSQL 'Google Drive' type ipynb
https://github.com/rootassist/SQL_ExecEnv_ForColab/blob/main/World_Env_FromGoogleDrive_ForColab.ipynb

MySQL 'Site' type ipynb
https://github.com/rootassist/SQL_ExecEnv_ForColab/blob/main/Sakila_Env_FromGitHub_ForColab.ipynb

2) ファイル上部の「Open in Colab」をクリックする

3) 「環境構築用のセル」を実行する （準備のために時間がかかります）。

4) Google Driveからダウンロードする場合には、Google Driveへのアクセス権を求めてくるので許可する。
