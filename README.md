# KanaiBiz Corporate Website

モダンなコーポレートサイトのランディングページです。レスポンシブデザインとスムーズなアニメーションを特徴とする、プロフェッショナルな企業サイトです。

## 🎯 プロジェクト概要

KanaiBizは、デジタルマーケティング、データアナリティクス、営業コンサルティングを提供する企業のコーポレートサイトです。

## ✨ 主な機能

- **レスポンシブデザイン**: モバイル、タブレット、デスクトップに対応
- **モダンなUI/UX**: 直感的で美しいインターフェース
- **スムーズアニメーション**: ホバー効果やトランジション
- **セクション構成**:
  - ヒーローセクション（グラデーションタイトル）
  - 会社概要（背景画像付き）
  - サービス紹介（3カラムレイアウト）
  - 導入事例（クライアント実績）
  - ニュース・お知らせ
  - CTA（資料請求・お問い合わせ）
  - フッター（SNSリンク・ナビゲーション）

## 🚀 セットアップ

### 必要な環境
- モダンなウェブブラウザ（Chrome、Firefox、Safari、Edge）
- HTTPサーバー（オプション、ローカル開発用）

### インストール手順

1. **リポジトリをクローン**
   ```bash
   git clone https://github.com/masakikanai-wq/sample-02.git
   cd sample-02
   ```

2. **ブラウザで表示**
   ```bash
   # 直接ファイルを開く場合
   open index.html
   
   # ローカルサーバーを使用する場合（推奨）
   python -m http.server 8000
   # または
   npx serve .
   ```

3. **ブラウザでアクセス**
   - 直接ファイル: `file:///path/to/index.html`
   - ローカルサーバー: `http://localhost:8000`

## 📁 プロジェクト構造

```
├── index.html          # メインHTMLファイル
├── css/
│   ├── style.css       # メインスタイルシート
│   ├── components.css  # コンポーネント用CSS
│   ├── responsive.css  # レスポンシブデザイン
│   └── reset.css       # CSSリセット
├── js/
│   └── main.js         # JavaScript機能
└── README.md           # プロジェクト説明
```

## 🎨 デザインシステム

### カラーパレット
- **プライマリカラー**: `#4F46E5` (インディゴブルー)
- **テキストカラー**: `#1f2937` (ダークグレー)
- **背景カラー**: `#ffffff` (ホワイト)
- **セカンダリ背景**: `#f6f6f6` (ライトグレー)

### タイポグラフィ
- **フォント**: Noto Sans JP (Google Fonts)
- **見出し**: 72px / 48px / 36px / 24px
- **本文**: 16px / 14px

### レイアウト
- **コンテナ幅**: 1200px (max-width)
- **セクション間隔**: 100px (padding)
- **カラム間隔**: 40-60px (gap)

## 🛠️ カスタマイズ

### 色の変更
`css/style.css` の `:root` セクションでカラー変数を編集：
```css
:root {
    --primary-color: #4F46E5;
    --dark-color: #333;
    --light-color: #f8f9fa;
}
```

### コンテンツの変更
`index.html` の各セクションを直接編集してください。

### 画像の追加
背景画像のURLを変更するには、CSS内の `background-image` プロパティを編集してください。

## 📱 レスポンシブ対応

- **デスクトップ**: 1200px以上
- **タブレット**: 768px - 1199px
- **モバイル**: 767px以下

## 🌐 ブラウザサポート

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 📄 ライセンス

MIT License - 詳細は [LICENSE](LICENSE) ファイルをご覧ください。

## 🤝 コントリビューション

1. フォークする
2. フィーチャーブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add amazing feature'`)
4. ブランチにプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

## 📞 お問い合わせ

プロジェクトに関する質問や提案がありましたら、Issueを作成してください。

---

**Built with ❤️ using HTML, CSS, and JavaScript**