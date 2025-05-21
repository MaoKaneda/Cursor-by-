# ロボくんに聞いてみよう

このアプリは、FlaskとCohereを使ったチャットボットWebアプリです。  
可愛いクマさんやペンギン風のAIアイコン、Markdown対応、スマホ対応など、見やすさと親しみやすさにこだわっています。

## 主な特徴
- AI返答はMarkdown記法で見やすく表示
- オリジナルの可愛いAIアイコン
- 吹き出しやタイトルバーの色もカスタマイズ可能
- 日本語IME変換確定時のEnterで送信されない
- スマホ・PC両対応

## セットアップ手順
1. このリポジトリをクローン
2. 必要なパッケージをインストール
   ```bash
   pip3 install -r requirements.txt
   ```
3. CohereのAPIキーを取得し、プロジェクト直下に`.env`ファイルを作成
   ```
   COHERE_API_KEY=あなたのAPIキー
   ```
4. アプリを起動
   ```bash
   python3 app.py
   ```
5. ブラウザで `http://localhost:5000` にアクセス

## 使い方
- メッセージを入力し、送信ボタンまたはEnterで送信（Shift+Enterで改行）
- AIの返答がロボットアイコン付きで表示されます
- スマホ・PCどちらでも快適に利用できます

## 注意事項
- `.env`ファイルは**絶対にGitHub等に公開しないでください**
- APIキーは個人の責任で管理してください
- Cohereの無料枠や利用規約にご注意ください

## カスタマイズ例
- Markdown全対応やリスト表示など、さらに見やすくしたい場合はご相談ください
- デザインやタイトル文言も自由に変更できます

---

何か質問や要望があれば、IssueやPull Requestでご連絡ください！ 

<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script> 