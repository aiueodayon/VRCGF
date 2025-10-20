# 🤝 Contributing to VRChat_GroupFinder (VRCGF)

まずはこのプロジェクトに関心を持っていただきありがとうございます！  
VRChat_GroupFinder（以下 VRCGF）は、VRChatのグループやイベントをより見つけやすくするためのオープンソースプロジェクトです。  
開発、翻訳、デザイン、ドキュメントなど、どのような形でも貢献を歓迎します。

---

## 🪄 貢献の方法

### 1. バグ報告（Bug Reports）

バグを見つけた場合は、次の情報を [Issues](https://github.com/aiueodayon/VRCGF/issues) に投稿してください。

- ✅ 発生した状況（例：イベント検索中にクラッシュした）  
- ✅ 再現手順（できるだけ簡潔に）  
- ✅ 期待する動作  
- ✅ 使用環境（OS・ブラウザ・バージョン など）  
- ✅ スクリーンショットやログ（あれば）

---

### 2. 機能提案（Feature Requests）

新しい機能の提案や改善アイデアも歓迎です。  
投稿時は次のテンプレートを参考にしてください：

**タイトル:** `[Feature] カレンダーとの連携をもっと自動化してほしい`  
**内容:**  
- 機能の概要  
- どんな課題を解決できるか  
- 想定する利用シナリオ  

---

### 3. コードへの貢献（Code Contributions）

Pull Request（PR）を送る前に、以下を確認してください：

1. **`main` ブランチ**を最新にしてからブランチを切ってください。  
```bash
   git checkout main
   git pull origin main
   git checkout -b feature/my-feature
```

2. **コードスタイル**は既存のフォーマットに合わせてください。

   * JavaScript / TypeScript: [Prettier](https://prettier.io/) 準拠
   * コミットメッセージは簡潔に（例: `fix: event card not loading`）

3. PR の説明には、

   * 変更内容の概要
   * 影響範囲
   * スクリーンショット（UI変更がある場合）
     を含めてください。

4. レビューが通ったら、`main` ブランチにマージされます。

---

### 4. 翻訳・ドキュメント貢献

* 英語版・日本語版のREADMEやUIテキストの翻訳を歓迎します。
* 翻訳ファイルは `/locales` ディレクトリに配置してください。
* ドキュメント修正（README、Wikiなど）は直接PRでもOKです。

---

### 5. デザイン・UI/UX 改善

* カードレイアウトやテーマデザインの改善提案を歓迎します。
* `mockup/` または `design/` ディレクトリにデザイン案を追加してください。
* Figmaや画像での提案もOKです。

---

## 🧩 コーディングガイドライン

* コンポーネント名・変数名は英語で明確に。
* コメントは日本語または英語どちらでもOK。
* PRを送る前にLintを通してください。

  ```bash
  npm run lint
  ```
* 新しい機能を追加する場合は、テストまたはデモデータも添付してください。

---

## 🔐 倫理・安全性について

* ユーザーのプライバシーを尊重し、個人情報を収集しない設計を心がけてください。
* VRChatの利用規約やAPIポリシーに反する実装は行わないでください。
* 不正アクセスや追跡行為につながるコードは即時却下されます。

---

## 🧠 コミュニティのマナー

* 意見の違いを尊重し、相手を攻撃しないこと。
* 初心者の質問にはやさしく対応しましょう。
* issueやPRでの議論は建設的に。

---

## 💌 連絡先

* **公式サイト:** [astraldao.shop](https://astraldao.shop)
* **バグ報告・提案:** [GitHub Issues](https://github.com/aiueodayon/VRCGF/issues)
* **開発に関する質問:** Discussions または DM にてご相談ください。

---

## 🙏 Thank You!  

VRCGF の開発に関わってくださった皆さんに感謝します。  

<div align="center">

<a href="https://github.com/KawaiiAstral" target="_blank">
  <img src="https://github.com/KawaiiAstral.png?size=64" width="64" height="64" alt="username1" style="border-radius:50%;" />
</a>

</div>

---

<div align="center">
<sub>このプロジェクトは VRChat に公式に関連するものではありません。<br>
VRChat およびそのロゴは VRChat Inc. の登録商標です。</sub>
</div>
