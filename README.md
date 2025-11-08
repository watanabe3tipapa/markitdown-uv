# 📂 markitdown-uv

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-0.1.0-green.svg)

## Microsoft Office ドキュメントを マークダウンファイルに変換します

### ⚙️ *ローカルでの使い方*

1. 必要なもの（導入方法省略）
- Python
- Flask
- markitdown
- uv （事前にインストールしていること）
  
2. このリポジトリをクローンしてください（詳細省略）  

3. ワーキングディレクトリで　`uv add -r requirements.txt` を実行  

4. 続いて `uv run server.py` を実行  

5. ブラウザで http://localhost:5555/ にアクセス  


## 🚀

===

ライブラリ markitdown は office ドキュメントを Markdown に変換することに特化しており、クライアントサイドのブラウザで動作する JavaScript ライブラリではないため、ブラウザ上でのファイル選択や直接的なダウンロード処理はできません。このプロジェクトでは単純なWEBアプリーションを用いることで当該ライブラリを有効利用しようというものです。

[markitdown リポジトリ](https://github.com/microsoft/markitdown)


===

⚓️ ライセンスは　MIT です。

===

.&- @toolsmith# markitdown-uv

