# Unity Font Tool v1.0.0

<p align="center">
  <img src="images/screenshot.png" alt="Unity Font Tool Screenshot" width="900">
</p>

<p align="center">

**Unity TextMeshPro Font Asset Creator向け文字抽出支援ツール**

TXT・DOCX・フォルダー一括読み込み対応
必要な文字だけを抽出してフォントアセット作成を効率化

</p>

---

## ✨ 概要

**Unity Font Tool** は、Unityの **TextMeshPro Font Asset Creator** 用に必要な文字だけを抽出・整理できるWindows向け支援ツールです。

ゲーム制作では、シナリオやUIテキストが増えるにつれてフォントアセットへ登録する文字数も膨大になります。

本ツールは実際に使用する文字だけを抽出することで、

* フォントアセット作成の効率化
* 無駄な文字登録の削減
* 作業時間の短縮

をサポートします。

---

# 🚀 主な機能

* 📄 TXTファイル読み込み
* 📝 DOCXファイル読み込み
* 📂 フォルダー内ファイル一括読み込み
* 📋 テキスト貼り付け入力
* 🔤 全使用文字抽出
* 漢字のみ抽出
* 重複文字自動削除
* 空白・改行自動除去
* 出現順を維持
* UTF-8形式で保存
* シンプルで使いやすいGUI

---

# 📷 スクリーンショット

<p align="center">
  <img src="images/screenshot.png" width="900">
</p>

---

# 💻 動作環境

| 項目     | 内容                      |
| ------ | ----------------------- |
| OS     | Windows 10 / Windows 11 |
| Unity  | TextMeshPro対応           |
| Python | 不要（Release版）            |

---

# 📥 ダウンロード

最新版は **Releases** よりダウンロードしてください。

👉 **https://github.com/akihito8702-glitch/Unity-Font-Tool/releases**

---

# 🛠 使用方法

### ① ファイルを読み込む

対応形式

* TXT
* DOCX
* フォルダー一括読み込み
* テキスト貼り付け

---

### ② 抽出モードを選択

* 全使用文字
* 漢字のみ

---

### ③ 抽出

以下を自動で処理します。

* 重複文字削除
* 空白除去
* 改行除去
* 出現順維持

---

### ④ 保存

UTF-8形式のテキストとして保存します。

---

### ⑤ Unityへ貼り付け

保存した文字列を

**TextMeshPro → Font Asset Creator**

の

**Custom Characters**

へ貼り付けるだけです。

---

# 💡 開発のきっかけ

現在制作中の東方Project二次創作恋愛シミュレーションゲーム

## **東方恋華録**

の制作中、

TextMeshPro Font Asset Creatorへ登録する文字の整理に多くの時間がかかっていました。

「もっと簡単に、もっと早く。」

そんな思いから、このツールを開発しました。

---

# 👨‍💻 開発者

50代からAIを補助ツールとして活用し、ゲーム制作を始めた非エンジニアです。

現在はUnityで

**東方Project二次創作恋愛シミュレーションゲーム**

## **東方恋華録**

を制作しています。

また、AIを活用しながらUnity開発を便利にするツールの制作も行っています。

---

# 🗺 今後のアップデート予定

* UI改善
* 抽出精度向上
* 対応ファイル形式追加
* 新機能追加

---

# 🐞 バグ報告・ご要望

不具合や改善案は **Issues** よりお気軽にお知らせください。

皆さまのフィードバックをお待ちしております。

---

# 📜 ライセンス

MIT License

---

# ⭐ 応援していただける方へ

このツールが役に立ったら、

ぜひ **GitHubの Star ⭐** を付けていただけると、とても励みになります！

ご利用・ご感想・改善提案も大歓迎です。

---

<p align="center">

**Made with ❤️ using Python + PySide6**

</p>
