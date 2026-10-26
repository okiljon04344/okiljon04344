# 開発経歴書（新卒採用向け ポートフォリオ補足資料）

## 基本情報

**最終更新日:** 2026年10月25日  
**氏名:** NABIEV OKILJON ASROR UGLI（ナビエフ・オキルジョン・アスロル・ウグリ）※在留カード表記  
**呼び名:** オキルジョン（Okiljon）  
**生年月日:** 2004年生まれ  
**居住地:** 日本・北海道（出身: ウズベキスタン ナマンガン州）  
**学歴:** 岩谷学園 ひがし北海道IT専門学校 地域未来情報テクノロジー科（2027年3月卒業見込）  
**連絡先:** [okiljonnabev@gmail.com](mailto:okiljonnabev@gmail.com)  
**ポートフォリオ:** [https://okiljon04344.github.io/](https://okiljon04344.github.io/)  
**GitHub:** [https://github.com/okiljon04344](https://github.com/okiljon04344)

---

## 1. 概要

専門学校で学びながら、Flutter と Firebase を中心にモバイル・Web・Android TV 向けのアプリを開発してきました。  
在学中に4名のチームで企業（韓国で事業展開）からの依頼を受けたECアプリ「**Million Halal (MILLION MARKET)**」を開発・納品し、PMとして要件の整理やタスクの進行管理を担当しました。  
個人開発では、Firebase Cloud Functions と Google Gemini API を連携させた学習管理アプリ「**EduPlanner AI**」を制作し、静的解析（`flutter analyze` 0 issues）とユニット・ウィジェットテスト（118テスト全通過）まで行っています。  
入社後は、テストとレビューを大切にしながら、品質の高いアプリ開発に貢献したいと考えています。

---

## 2. 学習歴

- **高校2年生:** Java の独学を開始
- **2023年頃:** Dart / Flutter の独学を開始
- **専門学校在学中:** 授業に加えて、Flutter・Firebase・Gemini API を使った個人開発に継続的に取り組んでいます

---

## 3. 技術スキル

| 分野 | 技術要素 | 使用経験（何を、どこで使ったか） |
| :--- | :--- | :--- |
| **開発言語** | Dart, Python, Java, SQL, HTML5 / CSS3 / JavaScript | Java は高校在学中に独学開始、Dart は2023年頃から独学（個人開発・チーム開発1件） |
| **フレームワーク** | **Flutter** (Mobile, Web, Desktop, Android TV 10-foot UI) | 2023年頃から独学（設計・状態管理・テスト）。チーム開発1件と個人開発で使用 |
| **状態管理** | Riverpod, Provider, StateNotifier | 個人開発で feature 単位のレイヤー分割（UI / Provider / Repository）を実践 |
| **バックエンド・BaaS** | Firebase (Auth, Firestore, Cloud Functions, FCM, Realtime DB), Supabase | 個人開発でセキュリティルール・クエリ最適化に取り組み |
| **AI / LLM 連携** | Google Gemini API (`google_generative_ai`), REST API, Function Calling | EduPlanner AI でプロンプト設計、構造化出力、自動テストを実施 |
| **CI / CD・ツール** | Git, GitHub, GitHub Actions, Firebase Emulator, Android Studio, VS Code, Figma | 個人開発で静的解析・ユニット／ウィジェットテストを GitHub Actions で自動実行 |
| **語学力** | **日本語: JLPT N2**、ウズベク語: ネイティブ、英語: 技術ドキュメント読解・会話 | 多国籍チームでのコミュニケーションを経験 |

---

## 4. 開発実績

### チーム開発

#### Million Halal (MILLION MARKET)
* **概要:** 在学中に4名のチームで、企業（韓国で事業展開）からの依頼を受けて開発・納品したハラール食品ECアプリケーション
* **リポジトリ:** コードは非公開（Private Repository）
* **開発体制:** 4名チーム（**役割: プロジェクトマネージャー（PM）& Flutter開発**）
* **開発期間:** 約6か月
* **担当工程:** 要件定義、基本設計、UI設計、タスク配分・スケジュール管理、Flutterアプリ実装、API連携、納品
* **主な機能:** 商品検索・カテゴリ絞り込み、カート・注文管理、セール・ポイント還元、卸売業者登録機能
* **工夫した点・成果:**
  - 多言語・多国籍チーム間の認識ズレを防ぐため、Figmaを用いたプロトタイプとNotionによるチケット管理を徹底。納期遅延ゼロでクライアントへの納品を達成。
  - 商用資産保護のためソースコードは非公開ですが、PMとしてのタスク設計、アーキテクチャ、画面設計、課題解決のプロセスについては面談時に詳細をご説明可能です。

---

### 個人開発

#### EduPlanner AI (エデュプランナーAI)
* **リポジトリ:** [https://github.com/okiljon04344/eduplaner_ai](https://github.com/okiljon04344/eduplaner_ai)
* **使用技術:** Flutter 3.x, Dart, Riverpod, `go_router`, Firebase, Cloud Functions, Google Gemini API
* **役割:** 企画・設計・開発・テスト（個人開発）
* **主な機能:**
  - 時間割・講義管理、課題提出・リマインダー通知
  - 週間学習時間・成績推移のインタラクティブグラフ可視化
  - **Gemini API 連携:** 弱点分野に基づいた学習アドバイス、および多肢選択式理解度テスト問題の自動生成
* **技術的成果:**
  - APIキーをクライアント側に露出させないセキュアな Cloud Functions バックエンド設計。
  - **118件のユニット・ウィジェットテスト**を作成し、`flutter test` 100% 通過、`flutter analyze` 0 warnings を達成。

#### Universal Restaurant App (QR テーブルオーダー & 飲食店舗管理システム)
* **リポジトリ:** [https://github.com/okiljon04344/restoranapp](https://github.com/okiljon04344/restoranapp)
* **使用技術:** Flutter, Riverpod, `go_router`, Cloud Firestore, Firebase Auth, i18n
* **主な機能:**
  - 来店客用: テーブルQRコード読み取り、リアルタイム注文・カート管理
  - キッチン用（KDS）: 新規注文のリアルタイム受信と調理ステータス更新（受付 → 調理中 → 提供準備完了）
  - 管理者用: メニュー・カテゴリ管理、在庫（食材・最小在庫アラート）管理、テーブル状況、売上・注文ダッシュボード
  - 日本語・英語・ウズベク語の3言語対応（ARB によるローカライズ）
* **セキュリティ・品質:**
  - 管理者権限は Firestore の `admins/{uid}` ドキュメントの有無で判定（セキュリティルールとアプリで同じ判定）
  - Firestore セキュリティルールで役割ごとの読み書き権限を制御し、GitHub Actions で `flutter analyze`・`flutter test` を自動実行

#### Smart TV Streaming App (Android TV 動画配信プラットフォーム)
* **リポジトリ:** [https://github.com/okiljon04344/smart_tv_app](https://github.com/okiljon04344/smart_tv_app)
* **使用技術:** Flutter, Android TV 10-foot UI, D-Pad Remote Navigation, Firebase Realtime Database, Firebase Auth, `video_player`, `youtube_player_flutter`
* **主な機能:**
  - **リモコン操作 (`tv_key_helper.dart`):** 決定キー・戻るキーの KeyDown / KeyUp 二重発火を防止し、KeyUp のみ届くリモコンにも対応。画面ごとに `FocusScope` でフォーカス移動を管理。
  - 動画再生: YouTube 動画は `youtube_player_flutter`、それ以外はアプリ同梱の動画を `video_player` で再生。10秒スキップと再生位置の保存に対応。
  - カタログは Realtime Database を購読し、取得できない場合はアプリ内サンプルデータにフォールバック。お気に入りはログイン時に Realtime Database と同期。
  - ログイン不要で操作を試せる **TV Demo / ゲストモード**。多言語 UI（ウズベク語・ロシア語・英語）。
  - ユニットテスト（キー判定・二重発火防止、Realtime Database データ変換）を作成し、GitHub Actions で `flutter analyze`・`flutter test` を自動実行。
  - 管理者は Realtime Database の `admins` ノードで管理し、Database ルールで書き込みを制限。

---

## 5. 自己PR

### ① チームをまとめ、最後までやり抜く推進力
留学生として日本語でのコミュニケーション（JLPT N2）を磨きながら、在学中に多国籍メンバー4名のチームで企業向けECアプリの開発に取り組み、PMとして納期通りに納品しました。「技術的に可能か」だけでなく「依頼元の事業にどう役立つか」を考え、要件の優先順位付けと課題解決を進めることを心がけています。

### ② 生成AIや新しい技術をプロダクトに取り入れる実装力
ただAPIを呼び出すだけでなく、Cloud Functions を介したセキュアな設計や、Gemini API のストリーミング生成、構造化JSONレスポンスのパースなど、実用的なAI機能の組み込みに取り組んできました。

### ③ 保守性・セキュリティとテスト自動化へのこだわり
「動けばいい」コードではなく、Riverpod を用いた feature 単位の保守しやすいディレクトリ構成を心がけています。主要リポジトリ（EduPlanner AI・Restaurant App・Smart TV App）には GitHub Actions を導入し、静的解析（`flutter analyze`）とユニット／ウィジェットテストを自動実行しています。
開発では AI コーディング支援ツールも活用していますが、設計・コードレビュー・テスト・最終的な判断は自分で行っています。

---

## 6. 受賞・資格

- **国際ビジネスアイデアコンテスト チーム第1位**（4か国参加・メンタルヘルス×医師連携アプリの企画・プロトタイプ提案）
- **日本語能力試験 (JLPT) N2 認定**
- **日本普通自動車第一種運転免許 取得済**

---

## 7. 入社後に挑戦したいこと

- Flutter・モバイル開発の経験を活かし、品質の高いプロダクトづくりに貢献したいです。
- チーム開発やコードレビューの文化から学び、チームで成果を出せるエンジニアに成長したいです。
- 生成AIを活用した開発に取り組み、アプリの価値を高めたいです。
