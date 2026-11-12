# Scoreの公開サイト

アプリ紹介・プライバシーポリシー・利用規約の正本。UIと本文は英語。
アプリの実装と食い違う新しい機能やデータ利用を記載しない。

`node build.mjs` で3ページを `dist/` に生成する。外部依存なし。
ローカル表示は `python3 -m http.server --directory dist 4173`。
正本はGitHubの `DygvT/dygvt.github.io`。`main` へのpushでGitHub Pagesが
`dist/` をビルド・公開する。公開URLは https://dygvt.github.io/ 。
アプリ本体や楽譜、認証tokenをこの公開repoへ追加しない。

2026-11-08：Sitesでは現在のworkspaceのインターネット公開が無効だったため、
GitHub Pagesへ切替えた。Sites側 `appgprj_6aef48fecc588191930e10c70ada3b63` の
version 1は未公開の古い下書きで、以後の更新先ではない。

問い合わせ先はGoogle OAuthのsupport/developer contactと同じ本人のGmail。
Google Driveの利用範囲、直接通信、端末内トークン、削除、ログの記述は
アプリrepoの `app/PianoScore/Sync/` と `app/PianoScore/Support/AppLog.swift` に基づく。
2026-11-08にGoogleのユーザーデータポリシーとブランド設定の公式文書を確認した。
サイトには認証、フォーム、分析スクリプト、外部フォントを置かない。

Google Search Consoleの所有権確認ファイルは `google326ad673a918c396.html`（2026-11-12に同じGoogleアカウントで取得）。
ビルドで公開ルートへコピーする。所有権の確認後も残す必要がある。確認結果とGoogle OAuthのブランド審査の状態は
アプリrepoの `notes/public_release_plan.md` を参照する。
