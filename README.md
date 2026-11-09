# 和錠（Wajō）— リリース配布

パスワード管理アプリ **和錠（Wajō）** の macOS / Windows 版の配布用リポジトリです。
アプリの説明・使い方は公式サイトをご覧ください。

- 公式サイト・取扱説明書: https://wajo.netlify.app/
- プライバシーポリシー: https://wajo.netlify.app/privacy/
- iOS / iPadOS 版: App Store で「Wajō」を検索

## ダウンロード

[Releases](../../releases/latest) から入手できます。

| ファイル | 対象 |
|---|---|
| `Wajo-mac-arm64.zip` | macOS（Apple Silicon）。Developer ID 署名・Apple 公証済み |
| `Wajo-win-x64.zip` | Windows 10/11 x64。.NET Framework 4.8 が必要 |
| `Wajo-desktop-source-<版>.zip` | 上記バイナリに対応するソースコード一式 |

> Windows 版は現在コード署名を行っていないため、初回実行時に SmartScreen の警告が
> 表示されることがあります。「詳細情報」→「実行」で起動できます。

## ライセンスとソースコード

和錠の macOS 版・Windows 版は、Dominik Reichl 氏の **KeePass 2.x** を基にした派生物で、
**GNU General Public License version 2 or later** の条件で配布しています。

- ライセンス全文と著作権表示: [`COPYING`](COPYING)
- 各リリースのソースコード: 各リリースの添付ファイル `Wajo-desktop-source-<版>.zip`
  （v0.9.1 と v0.9.2 は同一ソースのため、v0.9.2 のアーカイブが両方に対応します）

KeePass: Copyright (C) 2003-2026 Dominik Reichl.

## データについて

和錠は KeePass 互換の KDBX 形式を使用します。データが開発者のサーバーへ
送信されることはありません。
