# コードリーフ — Windows配布版

Salesforce開発を学ぶローカル学習アプリです。入門・Apex・LWC・Visualforce・Aura・実務/設計の全77単元、Developer I/II向け模試240問、総合4課題を収録しています。

## ダウンロード

**[最新版の codeleaf-windows.zip をダウンロード](https://github.com/cfn0eft/codeleaf-downloads/releases/latest/download/codeleaf-windows.zip)**

[変更内容・各バージョン](https://github.com/cfn0eft/codeleaf-downloads/releases) / [導入・更新の手順](SETUP.md)

GitHubの自動生成する「Source code」ZIPではなく、Releaseに添付された`codeleaf-windows.zip`を使用してください。

## はじめ方

1. ZIPを新しい書き込み可能なフォルダーへすべて展開します。
2. 「必要環境を確認.bat」を実行します。不足があれば公式ダウンロードページをご案内します。
3. 「コードリーフを起動.bat」を実行します。初回は採点用依存のダウンロード・検証・展開が完了するまでお待ちください。

Windows、Node.js 24以上、公式Salesforce CLI、Microsoft EdgeまたはGoogle Chromeが必要です。Git演習にはGit for Windowsも必要です。Salesforceの実採点にはインターネットと学習専用Developer Editionが必要です。

0.1.4以降は小型版のみを提供します。初回起動または必要環境確認で、固定版の`codeleaf-dependencies.zip`を自動取得し、SHA-256を検証します。初回はGitHub添付ファイルへの接続と依存展開用の空き容量が必要です。準備後は同じフォルダーでの起動時に依存を再ダウンロードしません。新しいフォルダーへ更新した場合は、そのフォルダーで依存を再取得します。

## 保存と更新

履歴・下書き・学習用認証はPC内の`.local`へ保存します。クラウド同期はありません。
アプリの「環境・バックアップ」→「更新を確認」から最新版を確認できます。更新確認は手動で、学習履歴・認証情報は送信しません。

## 確認範囲

この配布版は学習レビュー用です。教材全体の学習効果や資格合格を保証しません。会社PCでの実行・ダウンロードの許可は会社のルールに従ってください。Sophos環境の貸与PCや、利用者の最新版CLI・別組織での実採点は個別確認が必要です。

各ReleaseにZIPのSHA-256を添付しています。同梱依存の版は`dependencies.json`、ライセンスは`THIRD_PARTY_NOTICES.txt`と各パッケージ内を参照してください。
