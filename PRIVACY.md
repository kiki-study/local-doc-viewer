# Local Doc Viewer プライバシーポリシー

最終更新日: 2026 年 9 月 26 日

Local Doc Viewer（以下「本拡張機能」）は、ユーザーの情報を収集・送信しません。

## 扱う情報

- **ユーザーが選んだフォルダの中のファイル**: 一覧・検索・表示のために、ユーザーのパソコンの中で読み取ります（読み取り専用で、書き換えません）。
  読み取った内容は保存せず、画面を閉じると消えます。
- **登録したフォルダへの参照**: 次に開いたときに同じフォルダを読めるように、ブラウザの中（IndexedDB）に保存します。ファイルの中身は保存しません。
- **画面の設定**: 配色や列の幅などの好みを、ブラウザの中（localStorage）に保存します。
- **アドレスバーの検索語**（`md` + 語句）: 本拡張機能の中で検索に使うだけです。
- **Chrome で直接開いた .md ファイル**（ユーザーが「ファイルの URL へのアクセスを許可する」を ON にした場合のみ）: そのページの中で表示を整えるだけです。

これらはすべてユーザーのパソコンの中だけで扱い、開発者や第三者のサーバーを含め、外部には一切送信しません。
本拡張機能には通信する機能がなく、インターネット上の画像やスクリプトも読み込みません。

## 第三者への提供

ユーザーの情報を第三者に販売・提供することはありません。

## 保存した情報の削除

ビューアーの画面でフォルダを「一覧から外す」と、そのフォルダへの参照を削除します。
本拡張機能をアンインストールすると、ブラウザの中に保存したすべての情報が削除されます。

## 変更

このポリシーを変更する場合は、このページを更新し、最終更新日を改めます。

---

# Local Doc Viewer Privacy Policy

Last updated: September 26, 2026

Local Doc Viewer ("the extension") does not collect or transmit any user data.

- **Files in folders you choose** are read locally on your computer (read-only) to list, search, and display them. Their contents are not stored and are discarded when you close the viewer.
- **References to registered folders** are stored in your browser (IndexedDB) so the viewer can reopen them. File contents are not stored.
- **Display preferences** (color scheme, column widths) are stored in your browser (localStorage).
- **Search terms typed in the address bar** (`md` + terms) are used only for searching inside the extension.
- **.md files opened directly in Chrome** (only if you enable "Allow access to file URLs") are formatted in place on that page.

All of this stays on your computer. Nothing is sent to the developer or any third party. The extension has no networking features and does not load images or scripts from the internet.

User data is never sold or shared with third parties. Removing a folder from the list deletes its reference, and uninstalling the extension deletes everything it stored in your browser.
If this policy changes, this page will be updated along with the date above.
