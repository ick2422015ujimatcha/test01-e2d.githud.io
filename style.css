/* ====================
 * 0. 基本リセット
 * ==================== */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Hiragino Kaku Gothic ProN', 'Meiryo', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f9f9; /* 明るい背景色 */
}

/* ====================
 * 1. ヘッダー / ナビゲーション
 * ==================== */
header {
    background: #004d40; /* 深い緑色 */
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin-bottom: 5px;
    font-size: 2.5em;
}

header p {
    margin-bottom: 15px;
}

nav ul {
    list-style: none;
    padding-top: 10px;
    border-top: 1px solid rgba(255, 255, 255, 0.2);
}

nav ul li {
    display: inline-block;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    padding: 5px 10px;
    border-radius: 5px;
    transition: background-color 0.3s;
}

nav ul li a:hover {
    background-color: #00796b; /* ホバー時の色 */
}

/* ====================
 * 2. メインコンテンツのレイアウト
 * ==================== */
main {
    padding: 20px;
    max-width: 1200px;
    margin: 0 auto;
}

section {
    padding: 40px 20px;
    margin-bottom: 30px;
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #004d40; /* メインカラーに統一 */
    border-bottom: 3px solid #ffb300; /* アクセントカラー: 黄色 */
    padding-bottom: 10px;
    margin-bottom: 20px;
    font-size: 2em;
}

/* キャッチコピーのスタイル */
.catch-copy {
    display: block;
    margin-top: 20px;
    padding: 10px 20px;
    border-left: 5px solid #00796b;
    background-color: #e0f2f1;
    font-style: italic;
    color: #004d40;
}

/* ====================
 * 3. 観光スポットのグリッドレイアウト
 * ==================== */
.grid-container {
    display: grid;
    /* 画面サイズに応じて自動で列数を調整 (最小300px) */
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

.card {
    background: #e8f2f1;
    padding: 0; /* 画像を端まで見せるため一旦0に */
    border-radius: 8px;
    overflow: hidden; /* 角丸に合わせて画像もクリップ */
    text-align: left;
    transition: transform 0.3s, box-shadow 0.3s;
}

/* ホバーで少し浮き上がらせるアニメーション */
.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
}

/* カード内のテキスト部分 */
.card h3 {
    color: #004d40;
    margin-bottom: 10px;
    padding: 0 20px;
    margin-top: 15px;
}

.card p {
    padding: 0 20px 20px 20px;
}

/* 画像のスタイル */
.image-placeholder {
    width: 100%;
    height: 200px; /* 画像の標準的な高さ */
    overflow: hidden;
}

.content-body-img {
    max-width: 100%;
    height: 100%;
    object-fit: cover; /* 画像がコンテナを覆うように調整 */
    display: block;
    margin: 0;
    border-radius: 0; /* カードの上端なので角丸は不要 */
}

/* ====================
 * 4. イベントリスト
 * ==================== */
#event-list {
    list-style: disc inside;
    padding-left: 20px;
}

#event-list li {
    margin-bottom: 10px;
    padding: 5px 0;
    border-bottom: 1px dotted #ccc;
}

#event-list li:last-child {
    border-bottom: none;
}

/* ====================
 * 5. フッター
 * ==================== */
footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: white;
    margin-top: 30px;
}

/* ====================
 * 6. アニメーション用CSS (JavaScriptと連携)
 * ==================== */
.fade-in {
    opacity: 0;
    transition: opacity 1s ease-out, transform 0.8s ease-out; /* transformも追加 */
    transform: translateY(20px); /* 最初は少し下に配置 */
}

.fade-in.is-visible {
    opacity: 1;
    transform: translateY(0); /* 表示されたら元の位置へ */
}

/* ====================
 * 7. レスポンシブデザイン
 * ==================== */
@media (max-width: 768px) {
    /* グリッドを1列表示に切り替え */
    .grid-container {
        grid-template-columns: 1fr;
    }

    /* パディングを調整 */
    section {
        padding: 30px 15px;
    }

    /* メインタイトルを小さく */
    header h1 {
        font-size: 2em;
    }
}
