# mp3player-speedcontroller
mp3player
Android向けMP3プレイヤーアプリ

主な機能
再生
単一再生
音量調整
速度調整
イコライザー／音響エフェクト
歌詞表示（LRC対応）
複数再生
再生単位、アルバム単位、フォルダ単位、アーティスト単位
ループ再生機能
バックグラウンド再生
ロック画面・通知欄でのメディアコントロール
Bluetooth／有線イヤホンのボタン操作対応
スリープタイマー（指定時間後に自動停止）
ライブラリ操作
端末全体検索によるMP3検索
フォルダ読み取り
タグ編集（曲名・アーティスト・アルバムアート）
ソート／絞り込み（曲名・アーティスト・追加日など）
プレイリスト
作成、編集
エクスポート／インポート
その他
音声録音機能
クラウド読み込み
ホーム画面ウィジェット
Android Auto対応
アプリ設定
プライバシーポリシー
ライセンス
ダークモード対応
多言語対応（日本語・英語など）
データベース
再生履歴を保持し、以下を表示する。

最近再生した曲
再生回数が多い曲
お気に入り
技術スタック
言語: Java
UI: XML Layout + View Binding
アーキテクチャ: MVVM
非同期処理: LiveData + ExecutorService
DI: Hilt
ローカルDB: Room
メディア再生・バックグラウンド再生: Media3 (ExoPlayer + MediaLibraryService)
画像読み込み: Glide
ナビゲーション: Navigation Component (XML)
クラウド連携: Storage Access Framework（ドキュメントピッカー）
テスト: JUnit, Espresso
CI/CD: GitHub Actions
