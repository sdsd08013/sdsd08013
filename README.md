# Sky Iwasaki

Mobile Engineer

📄 Resume: https://sdsd08013.github.io/sdsd08013/

Androidを中心に、モバイルアプリケーションの設計・開発に10年以上携わっています。

Kotlin / Kotlin Multiplatform（KMP）を用いたモバイル基盤開発を得意とし、大規模サービスからスタートアップまで、アーキテクチャ設計、技術選定、開発、レビュー、チームリードを経験しています。

近年は、Claude CodeをはじめとしたAIエージェントを前提とした開発プロセス・アーキテクチャの設計にも取り組んでいます。

[LinkedIn](https://www.linkedin.com/in/sky-iwasaki-4a821a159)

---

## Experience

### LinQ Inc.

**Mobile Engineer**
2024年1月 – 現在

位置情報共有サービスのモバイルアプリ開発に従事。Androidチーム最大約10名の開発リードを担当。

* Androidアプリのアーキテクチャ設計、技術選定、コードレビュー
* Androidエンジニアの採用面接
* Google MapsのAdvanced Marker相当となる、任意Viewを利用したマーカー描画機構を独自実装
* Android / iOSで共通利用する位置情報計測基盤をKotlin Multiplatformで設計・開発
* 各OSで収集した位置情報データをBigQueryへ連携し、位置情報共有精度の集計・可視化まで一貫して構築
* Claude Codeをチーム開発へ導入し、ほぼすべての実装コードをAIエージェント経由で生成する開発フローへ移行
* `CLAUDE.md`、開発Workflow、10種類以上のレビューエージェントを整備し、チーム運用へ導入
* AIエージェントが扱いやすいことを前提に、アーキテクチャや使用技術を見直し

**主な技術**

`Kotlin` `Kotlin Multiplatform` `Android` `iOS` `Google Maps` `BigQuery` `Claude Code`

---

### Freelance

**Software Engineer**
2023年1月 – 2023年12月

モバイルアプリおよびバックエンド開発に従事。

* Androidアプリの機能開発
* Ruby on Railsによる決済機能の開発

**主な技術**

`Kotlin` `Android` `Ruby on Rails`

---

### PayPay Corporation

**Mobile Application Developer**
2021年4月 – 2022年12月

後払い・キャリア決済などの決済機能および、モバイルアプリ共通基盤の開発に従事。

SDK・Featureチームを合わせて約20名規模の開発組織で、Android / iOS双方から利用するKotlin Multiplatform SDKを開発。

* 後払い機能の開発
* キャリア決済機能の開発
* Kotlin Multiplatformによるモバイル共通SDKの開発
* Feature Flag、多言語化処理などAndroid / iOS共通ロジックの実装
* 多国籍チームにて、ミーティング、設計議論、Slack、コードレビュー、ドキュメント作成を英語で実施

**主な技術**

`Kotlin` `Kotlin Multiplatform` `Android`

---

### Jiraffe Inc.

**Mobile Application Developer**
2019年2月 – 2021年3月

フリマアプリのモバイル開発を担当。

* Androidアプリの設計・機能開発
* クラッシュフリーレートを約90%から99%へ改善
* React Native / Vue Nativeを利用したクロスプラットフォーム開発

**主な技術**

`Java` `Kotlin` `Coroutines` `Android Architecture Components`
`LiveData` `ViewModel` `Koin` `Spek2`
`React Native` `Vue Native` `TypeScript`

---

### DeNA

**Mobile Application Developer**
2017年6月 – 2019年1月

オートモーティブ事業におけるモバイルアプリ開発に従事。

* 車載アプリケーションの開発
* 乗務員向けAndroidアプリの開発
* AWS IoT / MQTTを利用したリアルタイム通信機能の開発

**主な技術**

`Kotlin` `Coroutines` `AWS IoT` `Firebase`
`RxJava` `Dagger2` `Eclipse Paho MQTT`
`JUnit4` `Robolectric`

---

### Slogan Inc.

**Web / Mobile Application Developer**
2015年4月 – 2017年5月

Webサービスおよび新規モバイルアプリの開発に従事。

**主な技術**

`CakePHP 2` `Ruby on Rails 4` `Swift 2` `Kotlin`

---

## Expertise

### Mobile Engineering

`Android` `Kotlin` `Kotlin Multiplatform`
`Coroutines` `Mobile Architecture`

Androidアプリの設計・実装から、Android / iOS間で共有するモバイル基盤の設計まで経験しています。

### Technical Leadership

アーキテクチャ設計、技術選定、コードレビュー、採用を含め、最大約10名規模のAndroidチームをリード。

仕様やドキュメントだけでは明示されていないプロダクト上の意図を汲み取り、品質と開発速度を両立しながらリリースまで進めることを重視しています。

### AI-assisted Software Engineering

Claude CodeなどのAIエージェントを個人利用に留めず、チームの標準的な開発プロセスへ組み込む取り組みを行っています。

AIエージェント向けのWorkflow、レビューエージェント、コンテキスト設計に加え、AIが安全かつ効率的にコードを変更できることを考慮したアーキテクチャ設計にも取り組んでいます。

---

## Education

### 東京大学

**修士（工学） / 機械工学**
2012年 – 2015年

### 豊田工業大学

**学士（工学） / 電気・電子工学**
2008年 – 2012年

---

## GitHub Pages（Resume サイト）について

このリポジトリは GitHub Pages + Jekyll で職務経歴サイトとしても公開しています。
ベースは公式テーマ [architect](https://github.com/pages-themes/architect) で、`_layouts/default.html` と `assets/css/style.scss` で Resume 向けにカスタマイズしています。

```text
/
├── _config.yml            # サイト設定（名前・肩書き・専門領域・リンク・baseurl）
├── index.md               # ページ本文（About / Experience / Expertise / Education / Links）
├── _layouts/default.html  # Hero（名前・肩書き）とフッターを含むレイアウト
├── assets/css/style.scss  # Resume 向けスタイル
└── Gemfile                # ローカル確認用
```

### 1. GitHub Pages で公開する

1. `master` ブランチに push する
2. 下記の Settings → Pages を設定する
3. 数十秒〜数分後に https://sdsd08013.github.io/sdsd08013/ で公開される（Actions タブでビルド状況を確認できる）

### 2. Settings → Pages で必要な設定

- **Source**: `Deploy from a branch`
- **Branch**: `master` / `/(root)` を選択して Save

補足:

- `_config.yml` の `baseurl` はリポジトリ名に合わせて `/sdsd08013` にしてあります。リポジトリ名を `sdsd08013.github.io` に変える場合は `baseurl: ""` にしてください。
- 独自ドメインを使う場合は Pages 設定の Custom domain を設定し、`_config.yml` の `url` も合わせて変更します。

### 3. ローカルで Jekyll を確認する

Ruby 3.x と Bundler が必要です（macOS なら `brew install ruby`）。

```sh
bundle install
bundle exec jekyll serve --livereload
```

`http://localhost:4000/sdsd08013/` で確認できます（`baseurl` が付くので末尾のパスに注意）。

`Gemfile` は `github-pages` gem を使っており、GitHub Pages 本番と同じ Jekyll / プラグイン構成で動作します。
