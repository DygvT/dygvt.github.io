# Scoreの公開サイト

アプリ紹介・プライバシーポリシー・利用規約の正本。UIと本文は英語。
アプリの実装と食い違う新しい機能やデータ利用を記載しない。

`node build.mjs` で3ページを `dist/` に生成する。外部依存なし。
ローカル表示は `python3 -m http.server --directory dist 4173`。
Sitesの静的ホスティングを使い、サイトIDは `.openai/hosting.json` に保持する。
ソースの保存・公開にはSites skillのsource helperを使う。

問い合わせ先はGoogle OAuthのsupport/developer contactと同じ本人のGmail。
Google Driveの利用範囲、直接通信、端末内トークン、削除、ログの記述は
アプリrepoの `app/PianoScore/Sync/` と `app/PianoScore/Support/AppLog.swift` に基づく。
2026-11-08にGoogleのユーザーデータポリシーとブランド設定の公式文書を確認した。
サイトには認証、フォーム、分析スクリプト、外部フォントを置かない。
