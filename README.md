# 災情ビューア (SaigaiViewer) - Auto-Update Repository

このリポジトリは **災情ビューア**（東レ労災情報共有 OneNote 閲覧・統計・AI要約アプリ）の**自動アップデート配信専用パブリックリポジトリ**です。

- アプリケーション本体およびフルインストーラー（災情ビューア-セットアップ.exe 等）やソースコードは、セキュリティおよび配布管理のため本リポジトリには配置しておりません。
- インストール済みのクライアントアプリが起動時に [updates/version.json](updates/version.json) と [updates/update_patch.zip](updates/update_patch.zip) を参照し、SHA-256 整合性検証を行った上で確認ダイアログなしで最新バージョンへ自動アップデートを適用します。