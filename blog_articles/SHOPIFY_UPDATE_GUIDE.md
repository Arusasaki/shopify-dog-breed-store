# Shopifyブログ記事更新ガイド

## 問題
記事内のテーブルがマークダウン記法のまま表示されている。
例：`| 項目 | 詳細 | |------|-----|`

## 解決方法
HTMLテーブルに置き換える

---

## 更新手順

### Step 1: Shopify管理画面にアクセス
1. https://admin.shopify.com/ にログイン
2. 左メニューから「オンラインストア」>「ブログ記事」を選択

### Step 2: 記事を編集モードで開く
1. 「ジャックラッセルテリアは初心者向き？飼育の現実と覚悟すべき5つのこと」をクリック
2. または検索で「jack-russell」と検索

### Step 3: HTML編集モードに切り替え
1. 記事エディタ内で「</>」ボタンまたは「HTMLを表示」をクリック
2. これにより、記事の生のHTMLコードが表示される

### Step 4: コンテンツを置き換え
1. **既存の内容をすべて選択**（Cmd+A または Ctrl+A）
2. **削除**
3. **`jack-russell-care-guide.html`の内容をコピー**して貼り付け
   - ファイルの場所: `blog_articles/jack-russell-care-guide.html`
   - GitHub: https://github.com/Arusasaki/shopify-dog-breed-store/blob/master/blog_articles/jack-russell-care-guide.html

### Step 5: プレビューと保存
1. 「プレビュー」をクリックして表示を確認
2. テーブルが正しく表示されていることを確認
3. 「保存」をクリック

---

## 修正済みHTMLファイル
- `jack-russell-care-guide.html` - ジャックラッセルテリア飼育ガイド

## 修正内容
以下のマークダウン記法をHTMLに変換：
- 4つのテーブル（基本情報、運動量、問題行動、病気）
- 3つのcallout（NOTE、WARNING、CAUTION、IMPORTANT）
- リストとヘッダー構造

## 注意事項
- 他の犬種記事も同様の問題がある場合は、同じ手順でHTMLファイルを作成できます
- テーブルスタイルはインラインCSSで設定されているので、どのテーマでも動作します
