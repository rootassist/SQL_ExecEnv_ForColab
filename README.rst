=====================
Name
=====================

Google ColaboratoryでSQL演習環境を作る

=====================
Overview
=====================

- SQLコマンドを実行できる環境をGoogle Colaboratoryに作ります
- データベースサーバーはPostgreSQL13です
- データベースを構築するために必要なファイルは「GitHubのリポジトリから得る」「Google Driveから得る」の2タイプを用意しました

=====================
Description
=====================

---------------------
'GitHub Repository' type ipynb:
---------------------

https://raw.githubusercontent.com/rootassist/SQL_ExecEnv_ForColab/main/Pagila_Env_FromGitHub_ForColab.ipynb

- データベース「pagila」を以下リポジトリにある「pagila-schema.sql」「pagila-data.sql」で構築します

 https://github.com/devrimgunduz/pagila

---------------------
'Google Drive' type ipynb
---------------------

https://raw.githubusercontent.com/rootassist/SQL_ExecEnv_ForColab/main/World_Env_FromGoogleDrive_ForColab.ipynb

- データベース「world」をGoogle Driveの「マイドライブ」フォルダの下にある「DBSample」フォルダに置いた「world.sql」で構築します
- 「world.sql」ファイルは以下のページからダウンロードできる「world-1.0.tar.gz」を展開したものです

 https://www.postgresql.org/ftp/projects/pgFoundry/dbsamples/world/world-1.0/

=====================
Usage
=====================

- 詳細な説明は note (https://note.com/nmt_rootassist/n/na8ace92f452c) に書いています。

---------------------
'GitHub Repository' type
---------------------

1) 以下のリンクをクリックする

https://raw.githubusercontent.com/rootassist/SQL_ExecEnv_ForColab/main/Pagila_Env_FromGitHub_ForColab.ipynb

2) ファイル上部の「Open in Colab」をクリックする

3) 「環境構築用のセル」を実行する （準備のために時間がかかります）

---------------------
'Google Drive' type
---------------------

1) 以下のリンクをクリックする

https://raw.githubusercontent.com/rootassist/SQL_ExecEnv_ForColab/main/World_Env_FromGoogleDrive_ForColab.ipynb

2) ファイル上部の「Open in Colab」をクリックする

3) 「環境構築用のセル」を実行する （準備のために時間がかかります）
