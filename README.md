# X-Window-Manager-like Dragging and Resizing for Windows  
Based on the original CodeProject article and source code

このリポジトリは、以下の CodeProject 記事で公開されている  
「X-Window-Manager-like dragging and resizing of windows」  
のソースコードを **ベースとして** 作成したものです。

Original Article:  
X-Window-Manager-like dragging and resizing of windows  
https://www.codeproject.com/articles/X-Window-Manager-like-dragging-and-resizing-of-win

Original Author: **Markus Rollmann**  
License: CodeProject Open License (CPOL)  
https://www.codeproject.com/info/cpol10.aspx

---

## 📌 About This Repository

- このリポジトリは、オリジナルのソースコードを基にしつつ、  
  **現代の開発環境で利用できるように調整・更新したバージョン** を公開するものです。  
- コードは **CPOL ライセンスの条件に従って再配布** しています。  
- オリジナルの著作権表示およびライセンス情報は保持しています。  
- CodeProject の記事本文（解説部分）は **CPOL により再配布が禁止されているため含めていません**。  
  必要な場合は上記リンクから CodeProject のページをご覧ください。

---

## 🔧 Modifications / Changes

ロジック部分はオリジナルのままですが、現代の環境でビルド・利用できるように以下の修正を行う予定です。

### ✔ Visual Studio 6.0 → Visual Studio 2026 へのプロジェクト更新
- プロジェクトファイルを VS2026 形式に変換  
- 非推奨設定の置き換え  
- 最新の Windows SDK に対応

### ✔ x64 ビルド対応
- 64bit 対応のためのプロジェクト設定追加  
- 型サイズ差による警告の修正  
- x64 で問題なく動作するよう最小限のコード調整

### ✔ その他の軽微な変更
- コメントの追加  
- ビルドエラーの解消  
- Unicode 対応の準備（必要に応じて）

---

## 📜 License

This project includes source code originally published on CodeProject and is redistributed under the  
**CodeProject Open License (CPOL)**.

You must comply with the CPOL terms when using or redistributing this code.

License details:  
https://www.codeproject.com/info/cpol10.aspx

---

## 🙏 Acknowledgements

Special thanks to **Markus Rollmann** for providing this useful implementation.  
Without his work, this project would not exist.
