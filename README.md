# A* Pathfinding Visualizer (Single File)

単一ファイル（外部依存なし）の A* 可視化ツールです。ヘッダーの操作群と中央キャンバスで、壁の配置や斜め移動の有無を切り替えながら、A* の探索を視覚的に確認できます。

## デモ（GitHub Pages）
公開URL: 後述の GitHub Pages 有効化後に反映されます。

## 使い方（概要）
- 壁の描画: モードを「Draw Walls」にしてグリッド上をドラッグ。
- 消去: 「Erase」で壁を消す。
- Start/Goal: モード「Move Start/Move Goal」で開始/終了を移動。
- 実行: Run（一時停止: Pause、1手進める: Step）。
- オプション: Speed/Rows/Cols 変更、Diagonal（斜め移動）切替、Save/Load（ローカル保存）。
- フルスクリーン: 右上の「Fullscreen」で切替。

## 開発
- 単一ファイル: `index.html`（HTML/CSS/JS）。
- 主要関数: `initGrid()`, `runAStar()`, `reconstructPath()`, `draw()`, `saveToLocalStorage()`, `loadFromLocalStorage()`。
- パフォーマンス: Open集合は二分ヒープで管理、フレーム時間を~12msに抑制。

## ローカルで開く
そのままブラウザで `index.html` を開いて動作します（ビルド不要）。

## ライセンス
明示されていません。このリポジトリの意図に合わせて必要に応じて追加してください。
