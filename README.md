# スキルシート

## 基本情報

- **名前**: 高橋 俊
- **所在**: 東京
- **外部リンク**: [Zenn](https://zenn.dev/ikuraikura), [GitHub](https://github.com/suguruTakahashi-1234), [X](https://twitter.com/ikuraikuraaaaaa), [Wantedly](https://www.wantedly.com/id/suguru_takahashi_m)

## スキルセット

### iOS アプリ開発

- **Swift**
  - SwiftUI, Combine, Swift Concurrency, Swift Package Manager といった Swift の最新技術を用いた実装経験。
  - Swift の言語機能に関する数多くのブログの投稿。→ [Zenn](https://zenn.dev/ikuraikura)
- **リードエンジニア**
  - 0 → 1 フェーズでの iOS アプリ開発のリードエンジニアの経験。
  - アーキテクチャやライブラリの選定を含むプロジェクト立ち上げにおける技術選定の経験。
- **アーキテクチャ**
  - Clean Architecture, VIPER, MVVM, Redux などの様々なアーキテクチャパターンの適用経験。
  - Swift Package Manager でのマルチモジュールアプリ構成の設計と実装経験。
- **ライブラリの組み込み**
  - ドローンなどのハードウェア機器の制御や、インカメラを使った視線分析、感情分析といった高度な実装スキルを要するライブラリの組み込みの実装経験。
- **mBaaS 連携**
  - **Firebase**
    - Authentication, Firestore, Storage, Analytics, Crashlytics などの Firebase の各種サービスの利用/実装経験。
  - **AWS Amplify**
    - AppSync (GraphQL), Cognito, S3, Pinpoint などの AWS の各種サービスの利用/実装経験。
- **CI/CD**
  - Xcode Cloud, Bitrise などを用いた自動テスト、自動デプロイ環境の構築経験。

### チーム開発

- **チーム間コミュニケーション**
  - PdM、デザイナーと連携し、アプリケーションの仕様/デザインの調整経験。
  - サーバーサイドチームと連携し、API インターフェースの調整経験。
- **アジャイル開発**
  - Jira, Confluence, GitHub Projects, Trello, Zenhub を含む多様なプロジェクト管理ツールを活用した数多くのアジャイル開発プロセスの経験。
- **Scrum Master**
  - Scrum Master として、チームのスプリント計画、実行、レトロスペクティブのファシリテーション、スクラムボードの設計を経験。

### その他の技術

- **Flutter**
  - Flutter による iOS/Android クロスプラットフォームでのアプリ開発経験。
- **サーバーサイドエンジニア**
  - PHP での API の設計/開発、DB (MySQL) のテーブル設計、OAuth2.0 での認証/認可の設計/実装。
  - OpenAPI (Swagger) での API インターフェース提供。
  - Postman を用いた API テストの自動化、JMeter での負荷テストのテストの設計/実施。

## 案件経歴

| No. | 期間                  | 案件名                                    |
|-----|-----------------------|-----------------------------------------------------------|
| 1   | 2023年4月 - 2023年10月 | マーケティングリサーチアプリ開発 - iOS リードエンジニア（Swift）          |
| 2   | 2022年8月 - 2022年12月 | アーティストファンクラブアプリ開発 - iOS エンジニア（Swift）                           |
| 3   | 2021年7月 - 2022年5月  | ドローン制御アプリ開発 - iOS エンジニア（Swift）                        |
| 4   | 2021年2月 - 2021年4月  | ショッピングアプリ開発 - Flutter エンジニア（Flutter）                    |
| 5   | 2021年1月 - 2021年3月  | 飲食店管理アプリ開発 - iOS リードエンジニア（Swift）                    |
| 6   | 2018年9月 - 2020年12月 | クレジットカードアプリ iOS アプリ開発 - iOS エンジニア（Swift）                     |
| 7   | 2018年9月 - 2020年12月 | クレジットカードアプリ API 開発 - サーバーサイドエンジニア（PHP） |

各案件の詳細は以下のプルダウンから表示できます。

---

<details><summary>No1. マーケティングリサーチアプリ開発 - iOS リードエンジニア（Swift）</summary>

#### 期間

2023年4月 - 2023年10月（7カ月間）

#### チーム体制

- 案件全体人数 : 約15名
  - iOS エンジニア : 3名（リードエンジニア担当）

#### 案件概要・担当業務

- スタートアップ企業の 0 → 1 フェーズでのマーケティングリサーチサービスの立ち上げ案件。
- toC 向けのコンテンツ配信アプリと、そのアプリ利用者のデータを用いた toB 向けの Web での BI ツールの 2 つサービスで構成されており、その iOS アプリのリードエンジニアを担当した。

#### 新たな習得スキル

- **Swift**
  - iOS16 以上を対象 OS とした SwiftUI での画面開発
  - Clean Architecture x Swift Package Manager でのマルチモジュール構成の構築
  - Xcode Cloud での CI/CD 環境の構築
  - Protocol Buffers に対応した SwiftProtobuf のライブラリを用いたデータ連携
  - async/await, AsyncStream, TaskGroup, actor などを用いた Swift Concurrency による非同期処理のハンドリング
  - AWS の Amplify SDK を用いた Cognito での認証/認可、AppSync による GraphQL 疎通、Pinpoint によるログイベント送信、S3 とのデータ連携
  - SMS 二要素認証の実装
  - デザインシステムを活用した画面実装
  - AVFoundation を用いた動画の再生
  - ReplayKit を用いた画面のレコーディング
  - 視線や感情の時系列データの Combine を用いたハンドリング
  - JavaScript を用いたアプリ内 WebView のイベントハンドリング
- **開発体験向上の取り組み**
  - GitHub Actions によるリリース tag の生成、リリースノートの作成、PR のレビューワー追加、マイルストーン追加、ラベル追加の自動化の Workflow の実装
  - Renovate によるライブラリの自動更新 PR の作成の環境構築
  - Periphery による Swift コードの不要なコードの静的解析
  - Swift-DocC による iOS アプリのドメイン層のドキュメント化
  - Mockolo によるテスト用の Mock の自動生成
  - GitHub Copilot, ChatGPT の活用

#### 経験できたこと・貢献できたこと

- iOS リードエンジニアとして、0 → 1 フェーズのアプリ開発における、アーキテクチャ・ライブラリの選定、ブランチの戦略の設計、リリース手順の確立、CI/CD 環境の構築、iOS チームのスクラムボードの運用の設計を行った。
- AWS Amplify SDK や SwiftProtoBuf のライブラリは、チームとしても経験者がいなかったが、先行して挙動を確認するサンプルアプリを作成して、それをチームに展開することで、それらのライブラリを採用することができた。
- 視線分析、感情分析の SDK を組み込み、それらの SDK の入れ替えがあっても、影響範囲を最小限にするようなアーキテクチャを検討して、それを実装した。
- PdM、デザイナー、サーバーサイド、データ分析チームとコミュニケーションをとって、アプリの仕様の調整や、データ連携のインターフェースの調整を行った。
- iOS チーム内の issue チケットの運用管理を担当し、チームメンバーのタスク状況を常に把握して、他のメンバーがタスクを途切れさせないように先回りして行動し続けた。

### 技術スタック

#### Swift

- **アーキテクチャ:**
  - VIPER ベースの Clean Architecture x Swift Package Manager でのマルチモジュール構成
- **Swift 標準 SDK & API:**
  - SwiftUI, Swift Package Manager, Swift Concurrency, Combine, Swift-DocC, AVFoundation, Core ML, WebKit, ReplayKit, Logger
- **サードパーティ製 SDK:**
  - SwiftProtobuf, Firebase, Amplify, Nimble/Quick, LicensesPlugin, PhoneNumberKit, DeviceKit, SwiftFormat, SwiftGen, Lottie, Mockolo, Mint, Periphery

#### mBaaS

- **AWS Amplify:**
  - AppSync (GraphQL), Cognito, S3, Pinpoint
- **Firebase:**
  - Crashlytics

#### CI/CD

- Xcode Cloud, GitHub Actions, Renovate

#### プロジェクト管理

- GitHub Projects, Notion, Backlog

#### インターフェース共有

- Protocol Buffers, Swagger

#### デザインツール

- Figma

</details>

---

<details><summary>No2. アーティストファンクラブアプリ開発 - iOS エンジニア（Swift）</summary>

#### 期間

2022年8月 - 2022年12月（4カ月間）

#### チーム体制

- 案件全体人数 : 約30名
  - iOS エンジニア : 5名（担当）

#### 案件概要・担当業務

- アーティストファンクラブアプリにおけるスタンプラリー機能および景品交換の機能の開発を行なった。
- デザイナーとの仕様の調整、見積もり、実装、レビュー、バグ修正を行なった。

#### 経験できたこと・貢献できたこと

- Redux ベースのアーキテクチャライブラリを使った開発が経験できた。
- デザイナー、Android、Web フロントのエンジニアとコミュニケーションを取りながら、プラットフォーム間で仕様に大きな差がでないように開発することができた。
- デザイナーが定義したデザインシステムに沿ったUIの実装を経験できた。

### 技術スタック

#### Swift

- **アーキテクチャ:**
  - Redux ベースのアーキテクチャ
- **Swift 標準 SDK & API:**
  - UIKit, AVFoundation
- **サードパーティ製 SDK:**
  - Carbon, VueFlux, ReactiveSwift, XcodeGen, Quick/Nimble, APIKit, CocoaPods, Carthage, Lottie

#### mBaaS

- **Firebase:**
  - Crashlytics

#### CI/CD

- CircleCI, Fastlane

#### プロジェクト管理

- Wrike, Kibela

#### インターフェース共有

- Protocol Buffers, Swagger

#### デザインツール

- Figma

</details>

---

<details><summary>No3. ドローン制御アプリ開発 - iOS エンジニア（Swift）</summary>

#### 期間

2021年7月 - 2022年5月（11カ月間）

#### チーム体制

- 案件全体人数 : 約15名
  - iOS エンジニア : 6名（担当）

#### 案件概要・担当業務

- BtoB 向けドローン制御アプリの iOS アプリの開発におけるドローンの飛行の安定性改善、複数社のドローンの対応、画面の開発などを行なった。
- アーキテクチャの検討、見積もり、実装、レビュー、バグ修正を行なった。

#### 新たな習得スキル

- **Swift**
  - アーキテクチャの検討
  - Clean Architecture での実装
  - SwiftUI/UIKit x Combine を用いた画面実装
  - Swift Concurrency を用いた非同期処理の実装
  - Firebase Crashlytics、Xcode Organizer を用いたバグの原因調査
  - Logger API を用いたログ出力
  - Quick/Nimble ライブラリを用いた可読性の高いテストコードの記述
  - Mock を活用したテストコードの記述
  - iPad サイズ対応のアプリの実装
- **IoT**
  - 外部ライブラリを用いたドローンの制御の Swift での実装
  - PID 制御などの制御工学の理解と適切な制御モデルの Swift での実装
  - RoS(Robot Operating System) 環境の活用

#### 経験できたこと・貢献できたこと

- Clean Architecture を採用したことによって、UI実装を全く変更せずに外部ライブラリの差し替えができたこと。
- 各レイヤーごとに依存しないテストコードの記述ができたこと。
- UIKit や delegate パターンでの既存実装を、SwiftUI、Combine、Swift Concurrency といった新しい技術でのリファクタリングを経験。

- チームの運用の改善に積極的に取り組んだことで、プロジェクト管理や開発プロセスの最適化に寄与。

### 技術スタック

#### Swift

- **アーキテクチャ:**
  - VIPER ベースの Clean Architecture
- **Swift 標準 SDK & API:**
  - SwiftUI, UIKit, Combine, Swift Concurrency, Logger, MetricKit
- **サードパーティ製 SDK:**
  - Realm, Quick/Nimble, APIKit, CocoaPods, Carthage

#### mBaaS

- **Firebase:**
  - Crashlytics, Analytics

#### CI/CD

- Bitrise, Fastlane

#### プロジェクト管理

- Zenhub

#### デザインツール

- Figma

</details>

---

<details><summary>No4. ショッピングアプリ開発 - Flutter エンジニア（Flutter）</summary>

#### 期間

2021年2月 - 2021年4月（3カ月間）

#### チーム体制

- 案件全体人数 : 2名
  - Flutter エンジニア : 1名（担当）
  - デザイナー : 1名

#### 案件概要・担当業務

- Flutter での iOS/Android クロスプラットフォーム開発を採用したショッピングアプリのデモアプリの開発を担当。
- Flutter でのフロントエンド実装から Firebase の mBaaS を活用したバックエンド実装まで、すべて一人で行った。

#### 新たな習得スキル

- **Flutter**
  - Provider による状態管理
- **Firebase**
  - Authentication による認証
  - Firestore によるデータの永続化、NoSQL DB 設計
  - Storage への画像データの永続化
  - Crashlytics によるクラッシュ報告管理
  - App Distribution による iOS/Android のアプリ配布
  - Analytics による KPI 指標の集計
  - Google Maps API での地図活用
- **CI/CD**
  - Codemagic での iOS/Android のアプリ配布の自動化
  - Fastlane から App Distribution への配布

#### 経験できたこと・貢献できたこと

- Firebase の mBaaS サービスを活用して、サーバーレスな構成でモバイルバックエンドサービスの設計・実装ができた。
- Flutter を採用したことで、Android の画面仕様、マテリアルデザイン、Google Play ストアでの配信などの経験をした。

### 技術スタック

#### Flutter

- Provider

#### mBaaS

- Firebase:
  - Authentication, Firestore, Storage, Crashlytics, App Distribution, Analytics
- Google Maps API

#### CI/CD

- Codemagic, Fastlane

#### デザインツール

- Adobe XD

</details>

---

<details><summary>No5. 飲食店管理アプリ開発 - iOS リードエンジニア（Swift）</summary>

#### 期間

2021年1月 - 2021年3月（3カ月間）

#### チーム体制

- 案件全体人数 : 約10名
  - iOS エンジニア : 3名（リードエンジニア担当）

#### 経験できたこと・貢献できたこと

- BtoB 向け飲食店管理モバイルアプリの MVP アプリの作成。
- iOS リードエンジニアとして、要件の調整やサーバーサイドチームとの API インターフェースの検討などを行った。
- Scrum Master も兼任。

#### 新たな習得スキル

- **Swift**
  - SwiftUI での画面実装
  - Codable プロトコルを用いた JSON の変換
  - TestFlight によるアプリ配信
  - アーキテクチャ、ディレクトリ構成の検討
- **Scrum Master**
  - スクラムボードの設計
  - 会議のファシリテーション

#### 経験できたこと・貢献できたこと

- SwiftUI での画面実装を経験することができた。
- 決められた要件をただ実装するだけではなく、お客様やデザイナーによりよい仕様やデザインを提案することができた。
- Scrum ボードのレーンの扱い、コードレビュー方法、issue の起票方法などについて、レトロスペクティブの場でなくても、チーム内で相談し、常に運用の改善を行うことができた。

### 技術スタック

#### Swift

- **アーキテクチャ:**
  - MVVM
- **Swift 標準 SDK & API:**
  - SwiftUI
- **サードパーティ製 SDK:**
  - SwiftLint

#### プロジェクト管理

- Zenhub, Trello

#### デザインツール

- Adobe XD

</details>

---

<details><summary>No6. クレジットカードアプリ iOS アプリ開発 - iOS エンジニア（Swift）</summary>

#### 期間

2018年9月 - 2020年12月（2年4カ月間）

#### チーム体制

- 案件全体人数 : 約20名
  - iOS エンジニア : 4-5名（担当）

#### 案件概要・担当業務

- BtoC 向けのクレジットカードアプリの iOS アプリの開発を担当。
- iOS アプリ開発における見積もり、実装、テスト、レビュー、バグ修正を担当。
- メインは上記のサーバーサイドチームの担当であったが、作業の手が空いたり、iOS チームの負荷が上がったときに iOS チームを担当した。

#### 新たな習得スキル

- UIKit での画面実装
- API 疎通
- Realm でのデータ永続化
- XCTest でのテストコード実装
- MVVM での実装
- Delegate パターンの実装
- Human Interface Guidelines に基づいた UI 実装
- Moneytree LINK SDK といったサードパーティー製のライブラリの組み込み

#### 経験できたこと・貢献できたこと

- iOSアプリ開発の基本的なスキル習得。

### 技術スタック

#### Swift

- **アーキテクチャ:**
  - MVVM
- **Swift 標準 SDK & API:**
  - UIKit
- **サードパーティ製 SDK:**
  - CocoaPods, Carthage, Realm, Moneytree LINK SDK

#### 通信キャプチャ

- mitmproxy

#### プロジェクト管理

- Jira, Confluence, Trello

#### デザインツール

- Sketch, InVision

</details>

---

<details><summary>No7. クレジットカードアプリ API 開発 - サーバーサイドエンジニア（PHP）</summary>

#### 期間

2018年9月 - 2020年12月（2年4カ月間）

#### チーム体制

- 案件全体人数 : 約20名
  - サーバーサイドエンジニア : 4名（担当）

#### 案件概要・担当業務

- BtoC 向けクレジットカード明細管理アプリのリニューアルに伴い、API やバッチの開発。
- サブリードディベロッパーとして、お客様向け説明資料の作成、設計、見積もり、実装、テスト、レビューを担当。
- アジャイル開発を採用しており、サーバーサイドチーム結成から約 2 年半に渡り、リリースしたシステムについて継続的にアップデートを行なった。

#### 新たな習得スキル

- **API 設計/開発**
  - PHP での API 設計/開発
  - MySQL での DB 設計/開発
  - OAuth2.0 での認証/認可の実装
- **バッチ設計/開発**
  - Java でのバッチの設計/開発
- **テスト**
  - API の単体/結合テストの設計と実装
  - Postman での API テストの自動化
  - JMeter での負荷テスト
- **ドキュメンテーション**
  - OpenAPI (Swagger) でのインターフェース設計/提供
  - PlantUML での設計

#### 経験できたこと・貢献できたこと

- モバイルアプリケーションのバックエンド開発における設計、実装、テスト、リリース、運用までのフルライフサイクルを経験できた。
- iOS チームと兼任していたため、モバイルアプリからの視点を API のインターフェースの設計に取り込むことができた。
- API の結合テストを Postman によって自動化することで、少ない工数で網羅的に繰り返しテストを実施することができ、品質を担保することができた。

### 技術スタック

#### 使用言語

- Java
- PHP (CodeIgniter)

#### プロジェクト管理

- Jira, Confluence, Trello

#### テストツール

- Postman, JMeter

#### ドキュメンテーション

- OpenAPI, PlantUML, draw.io

</details>

---

## 自己PR

iOS エンジニアの高橋 俊です。

BtoC、BtoB にかかわらず、金融、メディア/エンタメ、ドローンといった幅広い業種でのアプリの開発経験があります。

リードエンジニアの経験もあり、アーキテクチャやライブラリの選定や、他チームとの仕様の調整の経験も豊富です。

iOS 開発だけでもなく、サーバーサイドエンジニアとしても開発経験があり、API 設計や BD のテーブル設計といったことにも知見があります。

参画した案件のほぼすべてはアジャイルでの開発であり、Scrum Master も担当したことがあります。

業務外でも、新しい技術を試してみることに興味があり、それらについての技術発信も積極的に行っています。発信している内容も Swift に限らず、Flutter、AWS、Docker、Node.js など幅広く扱っております。→ [Zenn](https://zenn.dev/ikuraikura) (2023/09/28 現在 114件 投稿)

どうぞ、よろしくお願いいたします。
