/* 全体の背景色を黒に設定 */
body {
  background-color: #000; /* 黒色 */
  color: #fff; /* 文字色を白に */
  font-family: Arial, sans-serif; /* フォント設定 */
}

/* スライドショーコンテナのスタイル */
.slideshow-container {
  position: relative;
  max-width: 100%;
  margin: auto;
  background-color: #000; /* 黒色 */
}

/* 各スライドのスタイル */
.slide {
  display: none;
  position: absolute;
  width: 100%;
  height: 100%;
  background-color: #000; /* 黒色 */
}

/* スライド画像のスタイル */
.slide img {
  width: 100%;
  height: auto;
}

/* 前後ボタンのスタイル */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: #fff; /* ボタン文字色を白に */
  background-color: rgba(0, 0, 0, 0.5); /* 半透明の黒背景 */
  border: none;
  border-radius: 0 3px 3px 0;
  font-weight: bold;
  font-size: 18px;
  transition: background-color 0.3s ease;
}

/* 左側のボタン */
.prev {
  left: 0;
  border-radius: 3px 0 0 3px;
}

/* 右側のボタン */
.next {
  right: 0;
  border-radius: 3px;
}

/* ボタンのホバー時のスタイル */
.prev:hover, .next:hover {
  background-color: rgba(0, 0, 0, 0.8); /* ホバー時の背景色をダークに */
}

/* ドットナビゲーションのスタイル */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #fff; /* ドットの色を白に */
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

/* アクティブなドットのスタイル */
.active {
  background-color: #717171; /* アクティブなドットの色 */
}
