# auth-app-practice

## 概要

COACHTECH 教材 Tutorial 10-1「認証機能 ハンズオン演習」で作成した成果物です。
登録画面、ログイン画面、認証が必要なダッシュボードを作成した。

## 使用技術

- PHP 8.x
- Laravel 10.x
- Laravel Fortify（認証）
- MySQL

## 学んだこと

- Laravel Fortify を使ったユーザー登録 / ログイン / ログアウトの仕組み
- auth ミドルウェアでルートを保護する方法
- リダイレクト設定（ログイン後の dashboard、未ログイン時の login）

## 動作確認

必要項目を入力すると登録完了の画面に行く。
ログイン、ログアウトもできる。

## 詰まったところ

DashboardController作成をする際、クラスが見つからず詰まった。
