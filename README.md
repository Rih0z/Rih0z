# Hello, I'm Riho
**ITインフラから生成AIまで、行動力でカタチにするエンジニア。**  
「思いついたら即実行」をモットーに、**クラフトビールブログで検索1位を継続**しながら、**AI × Webアプリ開発**で新しい価値を生み出しています。
- 「**クラフトビール ブログ**」で**Google検索1位を1年以上継続**  
- **業務効率化アプリ**や**アフィリエイトサイト構築**の実績あり  
- **Azureを活用したAIソリューション開発**や**技術トレンド調査**にも取り組み中  
- アメリカ・シアトルからリモートで活動中

**👥 現在、[PintHop](https://github.com/Rih0z/PintHop)プロジェクトの共同開発者を募集中です！試してみませんか？詳細はリポジトリをご確認ください。**

---
## About Me
- **Role**: ITエンジニア / コンサルタント  
- **Location**: 日本出身、現在はアメリカ・シアトル在住  
- **Company**: NEC  
  - Windows Server保守  
  - Active Directory関連  
  - ダンプファイル解析  
  - 最新技術のトレンド調査  
  - Azureリソースを活用したAIソリューションのPoC・実装支援  
- **Tech Stack**:  
  - **インフラ系**: Windowsサーバー, Active Directory  
  - **Web開発**: Node.js, Python, WordPress, Swift  
  - **AI技術**: テキスト生成 / 画像生成 / GPT API連携  
  - **クラウド**: Netlify（Webデプロイ）、Azure OpenAI, Azure AI Document Intelligence など  
- **What I Offer**:  
  - サーバー保守と障害対応に関する支援  
  - Web/AIアプリケーション開発（PoC〜実運用まで）  
  - WordPressサイト構築・SEO対策・運営サポート  
  - AI導入に向けた技術選定と実装の伴走支援

### 1. [portfolio-manager](https://github.com/Rih0z/portfolio-manager)
- **概要**: 投資ポートフォリオ管理と革新的なAIプロンプト自動生成機能を備えたWebアプリケーション  
- **背景と課題**:  
  従来の投資管理では毎月の投資配分計算が手作業で非効率だった上に、**AIの分析能力を活用しようとしても効果的なプロンプト設計が複雑で専門知識が必要**という二重の課題があった。そこで株価情報の自動取得と最適配分計算に加え、**ポートフォリオデータを自動的にAI分析用プロンプトに変換する革新的な機能**を実装。
- **革新的なAIプロンプト自動生成**:
  - **現在の資産構成、目標配分、総資産額**など、ユーザー固有の投資データを自動的にプロンプトに組み込み
  - 最新の市場動向や世界情勢を調査するよう指示を含む**プロフェッショナル品質のAIプロンプト**を生成
  - 生成したプロンプトは**Claude、ChatGPT、Geminiなど好きなAIで利用可能**（特定AIに依存しない）
  - **AIプロンプト設計の専門知識不要**で、誰でも高度な投資分析を受けられる革新的なシステム
  - **ボタン1つ**でクリップボードにコピーされるため、3クリックで専門家レベルの投資分析が可能
  - **プライバシーとセキュリティを最重視**: アプリはユーザーの資産データを一切保存・管理せず、AIによる分析もユーザー自身の環境で実行されるため、センシティブな金融情報を守りながら安全に分析できます（アプリ自体にAI分析機能を組み込まない主な理由です）
- **ポイント**:  
  - Netlifyでホストされるブラウザ動作型アプリ（モバイル対応）  
  - 複数のデータソースから株価を取得し、資産配分の視覚化やリバランス計算をサポート  
  - 手数料・配当の分析機能を搭載  
  - 複数通貨（円/ドル）対応の資金配分シミュレーション
- **スクリーンショット**:  
  **ポートフォリオ管理画面**  
  ![資産状況管理プログラム](https://github.com/Rih0z/portfolio-manager/blob/main/images/IMG_0007.jpeg?raw=true)

  
　**試してみませんか？** [こちらのサンプルプロンプト](https://github.com/Rih0z/portfolio-manager/blob/main/sample-prompt.md)をClaudeやGemini ChatGPTなどのAIに貼り付けるだけで、このアプリが目指している投資分析がどのようなものか確認できます。実際に使用する際は、プロンプト内の「現在の総資産額」と「毎月の新規投資予定額」の数値を自分の状況に合わせて変更するだけで、あなた専用の投資分析が即座に得られます。

  **AIプロンプト実行結果例**  
  ![現在比率と理想比率の分析](https://github.com/Rih0z/portfolio-manager/blob/main/images/Invest-prompt/IMG_0206.jpeg?raw=true)  
  *AIがユーザーのポートフォリオデータを分析し、現在の資産配分と理想配分の差異や改善点を提案*
  
  ![理想比率に近づけるための投資プラン](https://github.com/Rih0z/portfolio-manager/blob/main/images/Invest-prompt/IMG_0207.jpeg?raw=true)  
  *理想的な資産配分に近づけるための、具体的な銘柄ごとの投資計画を提案*

### 2. [PintHop](https://github.com/Rih0z/PintHop)
- **概要**: クラフトビール愛好家のためのブルワリー探索・レビュープラットフォーム
- **背景と課題**:  
  クラフトビールの新しい発見や体験共有を簡単にできるプラットフォームが必要とされていたため開発。旅行者がローカルブルワリーを見つけやすく、ビール愛好家がお気に入りを記録・共有できる環境を提供。
- **ポイント**:  
  - 位置情報ベースのブルワリー検索機能
  - ユーザーレビュー・評価システム
  - パーソナライズされたビールおよびブルワリーのレコメンデーション
  - ソーシャル共有機能
- **スクリーンショット**:  
  <table>
    <tr>
      <td><img src="https://github.com/Rih0z/PintHop/blob/main/Document/Design/prototypes/Beer-review/IMG_0115.jpeg?raw=true" alt="フレーバープロファイル" width="250" /></td>
      <td><img src="https://github.com/Rih0z/PintHop/blob/main/Document/Design/prototypes/Beer-review/IMG_0116.jpeg?raw=true" alt="ホップ構成" width="250" /></td>
      <td><img src="https://github.com/Rih0z/PintHop/blob/main/Document/Design/prototypes/Beer-review/IMG_0117.jpeg?raw=true" alt="評価スコア" width="250" /></td>
    </tr>
    <tr>
      <td>フレーバープロファイル</td>
      <td>ホップ構成分析</td>
      <td>評価スコア記録</td>
    </tr>
  </table>
- **開発状況**:  
  開発中 - 共同開発者募集中！ご興味のある方はお気軽にご連絡ください

### 3. [Job-Automate](https://github.com/Rih0z/Job-Automate)
- **概要**: 日常業務を効率化するためのAIプロンプトテンプレート集
- **背景と課題**:  
  AIの実践的な活用方法がわからないビジネスパーソンのために、すぐに業務で使える実用的なプロンプト例を提供。単なるプロンプト集ではなく、使い方の解説や実際の出力例も含めた総合的なリソース。
- **ポイント**:  
  - クリエイティブ系：アイデア発想、コンセプト設計プロンプト
  - ドキュメント作成系：企画書からプレゼンスライド自動生成プロンプト
  - 開発支援系：コード規則テンプレート、実装サポートプロンプト
  - 今後も各種業務カテゴリのプロンプトを継続的に追加予定
- **コンセプト**:  
  「AIと共に、もっと効率的に、もっとクリエイティブに」をモットーに、様々な業務シーンでAIを効果的に活用する方法を提供。実務経験に基づく実践的なプロンプトで、AIツールの本格活用をサポート。

### 4. [SoundMixer](https://github.com/Rih0z/SoundMixer)
- **概要**: 発達障害を持つ子どもや人のためのiPad向け音刺激提示アプリ
- **背景と課題**:  
  2017年にNPO法人 EdTech Tokushima youthの代表として、活動していた際に作成。2名のチームメンバーを率いて、リーダーとして開発を推進。発達障害を持つ子どもや人がパニックや興奮状態にあるときに、適切な音刺激で落ち着きを促す支援ツールが必要とされていた。
- **ポイント**:  
  - 科学研究費助成事業（課題番号：２６５９０２６６）の支援を受けた「発達障害児へ提示する音刺激によるカームダウン誘発条件」研究プロジェクトの成果物
  - 複数音源の同時再生と音量・音程・再生位置の個別調整機能
  - メトロノーム機能による視覚的なアニメーションでのリズム表現
  - 脳波センシングヘッドバンドや心拍計測デバイスとの連携機能
  - Swift/iOSでの開発経験
- **研究成果**:  
  - 特定のノイズキャンセリングヘッドフォンの効果検証
  - 自然音の提示による落ち着き促進効果の検証
  - 個人差に対応したカスタマイズ機能の実装
- **スクリーンショット**:  
  ![メトロノーム画面](https://github.com/Rih0z/SoundMixer/blob/master/images/IMG_0019.jpeg)  
  ![音楽選択画面](https://github.com/Rih0z/SoundMixer/blob/master/images/IMG_0020.jpeg)

### 5. [beer-affiliate-engine](https://github.com/Rih0z/beer-affiliate-engine)
- **概要**: ビールに関するアフィリエイトサイト構築エンジン  
- **背景と課題**:  
  ブログの中で最も収益性が高かったのは旅行ジャンルだったため、**記事内容から自動的にアフィリエイトリンクを生成**することで、**収益性を最大化**する仕組みを開発。
- **ポイント**:  
  - 商品データの集約やリンク生成を効率化  
  - サイト運営者向けにアフィリエイト連携を簡素化
- **スクリーンショット**:  
  ![ブログのスクリーンショット](https://github.com/Rih0z/beer-affiliate-engine/blob/main/Images/IMG_0010.png?raw=true)  
  ![ブログ内容を読み込み自動広告挿入](https://github.com/Rih0z/beer-affiliate-engine/blob/main/Images/IMG_0011.png?raw=true)
---
## My Website
- **[rihobeer.com](https://rihobeer.com)**  
  クラフトビールに特化したWordPressメディア  
  - WordPressの設計・デプロイ・記事作成・レンタルサーバー管理を一貫して担当  
  - **「クラフトビール ブログ」でGoogle検索1位を1年以上キープ**（2024年4月〜）  
  - **記事の執筆は自ら行い、AIを活用して以下を自動化・最適化**：  
    - 誤字脱字の修正  
    - ファクトチェック  
    - SEO対策（検索流入分析・キーワード最適化）  
    - サムネイル画像の自動生成  
  - 運営の原動力は「**ビール業界に貢献したい**」という想い
---
## Future Vision
今後、以下のような領域にチャレンジしていきたいと考えています：
- **生成AI × ノーコード**を組み合わせた開発支援エージェントの構築  
- 自作アプリのユーザー拡大と**収益化モデルの確立**（portfolio-managerの一般公開など）  
- **クラフトビール × AI**での新規コンテンツ生成や**自動広告挿入アルゴリズムの高度化**  
- **グローバルチームと連携したAI活用プロジェクト**への参画（英語でのコミュニケーションも可能）

**👨‍💻 共同開発者・協力者募集：** PintHopプロジェクトをはじめ、クラフトビール業界やAI活用に興味のある方、一緒に価値を創造していきましょう！
---
## AI実践プロジェクト

AIの実践的な活用と普及に向けて、以下の取り組みを行っています：

### マイクロソフト責任あるAIへの準拠
すべてのAI開発・活用において、[Microsoftの責任あるAI原則](https://learn.microsoft.com/ja-jp/azure/machine-learning/concept-responsible-ai?view=azureml-api-2)に準拠しています。公平性、包括性、信頼性、安全性、透明性、プライバシーとセキュリティ、説明責任の各原則を遵守し、AIの責任ある開発と展開を心がけています。

### ブルワー向けAI活用支援
クラフトビール業界のブルワー向けに、実践的なAI活用事例の紹介を始めました。[ブログ内の専用カテゴリー](https://rihobeer.com/category/beer/ai%e3%83%bbdx/)では、マーケティング強化、レシピ開発支援、顧客コミュニケーション向上など、具体的なAI活用方法を定期的に更新しています。ブルワリーの個性と職人技を最大限に活かしながら、業務効率化とブランド価値向上を支援します。

### 業務効率化プロンプト集
日々の業務効率化に役立つAIプロンプト集「[Job-Automate](https://github.com/Rih0z/Job-Automate)」をGitHubで公開しています。文書作成、データ分析、コード生成、アイデア発想など、様々な業務シーンで活用できるプロンプトテンプレートを無料で提供。実務経験に基づいた実践的なプロンプトで、AIツールの効果的な活用をサポートします。

---
## 資格・スキルセット
- **Microsoft認定資格**  
  - AZ-104: Azure Administrator Associate  
  - AI-102: Azure AI Engineer Associate  
- **英語力**: TOEIC 800点以上、アメリカ在住中の実務経験あり  
- **技術領域**:  
  - サーバー保守（Windows Server / AD）  
  - Web開発（Node.js / Python / WordPress）  
  - iOS開発（Swift）
  - AI連携（GPT API / Azure OpenAI / Document Intelligence）  
  - クラウド（Azure / Netlify）  
---
## 研究実績

### 1. Tenderにおける資源「入出力」のスループット向上手法
**I/O Resource Throughput Improvement Method for Tender**

- **公開日**: 2020年03月03日
- **著者**: 利穂虹希, 山内利宏, 谷口秀夫 (岡山大学大学院自然科学研究科)
- **掲載先**: 電子情報通信学会大会講演論文集(CD-ROM) 2020年総合大会
- **URL**: [https://jglobal.jst.go.jp/detail?JGLOBAL_ID=202002246297867548](https://jglobal.jst.go.jp/detail?JGLOBAL_ID=202002246297867548)

#### 概要
Tenderオペレーティングシステム（The ENduring operating system for Distributed EnviRonment）における入出力性能の調整制御法に関する研究です。入出力性能調整機能において、性能調整入出力と優先度入出力を同時に実行した際のスループット向上手法を提案しています。Tenderは岡山大学の谷口秀夫教授が研究開発した分散環境向けOSで、OSが制御する対象を「資源」として管理する特徴があります。

### 2. ファイルシステムによる通信手法の簡略化
**Simplified Communication Method Using File Systems**

- **公開日**: 2019年02月28日
- **著者**: 利穂虹希, 佐野雅彦 (徳島大学)
- **掲載先**: 情報処理学会
- **URL**: [https://ipsj.ixsq.nii.ac.jp/records/196312](https://ipsj.ixsq.nii.ac.jp/records/196312)
- **主題**: ソフトウェア科学・工学

#### 概要
スマートフォンやIoT等のインターネット利用機会の増大により、通信プログラミング経験の必要性が高まっていますが、従来のソケットなどの概念は初学者には理解が難しい課題があります。本研究では、クライアント・サーバ間通信をファイルシステムとして実装することで、ファイル操作による直感的な理解とファイルシステム以外には特別なライブラリを不要とした環境の実現を目指しました。

### 3. Androidを対象とした利用者の意図しないWebサイトの分類
**Unwanted Web Site Classification for Android**

- **公開日**: 2019年10月14日
- **著者**: 利穂虹希, 折戸凜太郎, 佐藤将也, 山内利宏 (岡山大学大学院自然科学研究科)
- **掲載先**: 情報処理学会シンポジウム
- **URL**: [https://ipsj.ixsq.nii.ac.jp/records/201435](https://ipsj.ixsq.nii.ac.jp/records/201435)
- **主題**: Android, セキュリティアプリ, 悪性Webサイト, Webブラウザ, Web媒介型攻撃

#### 概要
Android端末利用者が意図せずアクセスしてしまう不正・悪性Webサイトに対する分類方法を提案した研究です。モバイル端末におけるWeb閲覧時の安全性向上を目的として、意図しないWebサイトへのリダイレクトや悪意のあるWebサイトの特徴を分析し、効果的な分類手法を開発しています。

---
## 経歴

- **2017年3月**: 阿南工業高等専門学校 制御情報工学科 卒業
- **2019年3月**: 徳島大学 制御情報工学化 A6 佐野研究室 卒業
- **2021年3月**: 岡山大学 大学院 自然科学研究科 山内研究室 修了
- **2021年4月**: NEC入社
- **2024年11月〜**: アメリカ駐在

---
## Contact
- お問い合わせは riho.dare at gmail.com までお願いいたします  
- [X (旧Twitter)](https://x.com/rihobeer2)  
- [Instagram](https://instagram.com/lobeerve)
