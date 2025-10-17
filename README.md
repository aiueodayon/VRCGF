#  VRChat Group Finder (VRC_GF)

![License](https://img.shields.io/github/license/yourname/finder?style=flat-square)
![Version](https://img.shields.io/github/v/release/yourname/finder?style=flat-square)
![Issues](https://img.shields.io/github/issues/yourname/finder?style=flat-square)
![Stars](https://img.shields.io/github/stars/yourname/finder?style=flat-square)

> 🛰️ Discover, track, and share VRChat worlds effortlessly.

---

**Languages:** 🇯🇵 日本語 | [🇬🇧 English](README.en.md)

---

## 🪐 Overview

**VRC_GF** は、VRChatの世界探索をより便利で楽しくするためのツールです。  
タグ・カテゴリ別のおすすめ表示やスケジュール管理、テーマカスタムなどを備え、  
あなたの「次に行くワールド」を見つける体験をサポートします。

---

## ✨ Features

| カテゴリ | 内容 |
|-----------|------|
| 🧭 **ワールド探索** | タグ・カテゴリ別のおすすめ表示、カスタムおすすめアルゴリズム |
| 🗓️ **スケジュール管理** | カレンダー表示モードでイベント・訪問予定を視覚的に管理 |
| 📊 **統計ダッシュボード** | プレイ時間や訪問傾向を自動集計 |
| ❤️ **お気に入り保存** | よく行くワールドをブックマーク・フォルダ分類 |
| 🎨 **テーマ＆カスタマイズ** | プラグイン・拡張・テーマ機能でUIや動作を自由に変更 |
| 🌐 **ワールドリンク連携** | VRChatワールドURLを直接開いたり共有可能 |
| 🕒 **タイムゾーン対応** | 世界中のフレンドの予定をローカル時間で表示 |

---

## 🧩 Extensibility

- **🔌 Plugin API**：サードパーティ製プラグインを簡単に追加可能  
- **🎨 Theme Engine**：CSSライクなテーマで外観を自由に変更  
- **🌍 Finder Hub**：人気プラグイン・テーマを共有できる仕組み（開発予定）  

---

## 📸 Screenshots

> UIプレビュー（追加予定）  
> ![](./screenshots/main-ui.png)  
> ![](./screenshots/dashboard.png)

---

## 🗺️ Roadmap

- [ ] モバイル対応UI  
- [ ] VR内ブラウザ対応  
- [ ] フレンド共有機能  
- [ ] Finder Cloud Sync（ローカル + クラウドオプション）

---

## 🧠 Architecture

```mermaid
graph TD
  A[Finder Core] --> B[UI Layer]
  A --> C[Plugin API]
  C --> D[Theme Engine]
  C --> E[Recommendation System]
````

---

## 🤝 Contributing

Pull Request・Issue 大歓迎です！
特に **プラグイン開発** や **おすすめアルゴリズム改善** に興味のある方はぜひご参加ください。

```bash
# Clone the repository
git clone https://github.com/aiueodayon/VRC_GF.git

# Install dependencies
npm install

# Start development
npm run dev
```

---

## 📜 License

Licensed under the [MIT License](./LICENSE) © 2025 [Astral](https://github.com/aiueodayon)

---

## 💫 Links

* 🌐 **Website:** [finder.astraldao.shop](https://finder.astraldao.shop)
* 👤 **Author:** [Astral (aiueodayon)](https://github.com/aiueodayon)

---

<div align="center">
  <img src="/docs/banner.png" width="600" alt="VRCGF Banner"><br><br>
  <strong>VRChat_GroupFinder</strong> — *“Find your next favorite world — faster, smarter, and together.”*  
  <br><br>
  <sub>© 2025 Astral | Designed for the VRChat Community</sub>
</div>
