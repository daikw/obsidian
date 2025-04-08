[[第３回] AIロボット駆動科学研究会 - connpass](https://ai-robot-science.connpass.com/event/344570/)

#### 招待講演
##### 一杉 太郎（東京大学 教授 ／ 東京科学大学 特任教授）-san
- 誰もが使える自動・自律実験をコンセプトに？
- デジタルラボラトリーを実現しよう
	- 標準化 / Plug and Play 型
	- 研究者目線で欲しいものは？ハードウェアではない
	- デジタル化込みの機材は吹っかけられる
- 自動実験システムのアーキテクチャ
	- 実験はフレキシブルである必要がある
	- マイクロサービスの集合が妥当か？
	- LADS（Laboratory and Analytical Device Standard）
	- ベイズで次の実験提案、サンプルアプリ: [MKI-bayesopt](https://mki-bayesopt-v3.mkilabs.io/mitools)
- 参考:
	- [2-3\_LADSLaboratory-and-Analytical-Devices-Standard.pdf](https://jp.opcfoundation.org/wp-content/uploads/sites/2/2023/12/2-3_LADSLaboratory-and-Analytical-Devices-Standard.pdf)
##### 夏目 徹　（産業技術総合研究所 首席研究員） -san
- [ロボティック・バイオロジー・インスティテュート株式会社 Robotic Biology Institute Inc. | RBI](https://rbi.co.jp/) の創業者
- MAHOLOを作っている
	- [インタビュー：ロボティック・バイオロジー・インスティテュート株式会社：産総研ベンチャー創出・支援プロジェクト - TECH Meets BUSINESS](https://unit.aist.go.jp/ipaspro2023/tmb/interview16.html)
	- [安川電機のロボット技術とアステラス製薬の製薬技術を融合した細胞医療プラットフォーム構築について | Category: お知らせ | 安川電機](https://www.yaskawa.co.jp/newsrelease/news/1223302)
	- [細胞医療製品を双腕ロボットで量産、アステラス製薬が2026年に治験薬を供給へ：ロボット開発ニュース（1/2 ページ） - MONOist](https://monoist.itmedia.co.jp/mn/articles/2308/10/news086.html)
- 効率化・省人化・省力化は、大した価値を生まない。本質的な価値を追求する
	- そういうのは人件費を下げるだけ
	- ロボット経済学
	- 真のハイスループット
		- Development Lead time: 0
		- Down time: 0
- Embryoid body (EB) を介した分化の研究
	- QbD: Quality by Design
- Robotic Biology
	- Robotics and AI Accelerate Life Science

## パネルディスカッション
### 登壇者
```
AIロボット駆動科学を支える産業のあり方について学術・企業の両視点から：  
  
［モデレーター］  
　‣ 高橋 恒一（理化学研究所）  
　‣ 長藤 圭介（東京大学）  
  
［パネリスト］  
　‣ 夏目 徹　（産業技術総合研究所 首席研究員）  
　‣ 一杉 太郎（東京大学 教授 ／ 東京科学大学 特任教授）  
　‣ 小山 聡　（株式会社堀場製作所）  
　‣ 伴野 太一（株式会社島津製作所）  
　‣ 栗田 真嗣（オムロン株式会社）
```
### メモ
- 長藤さん
	- [Research – 長藤・木崎研究室　東京大学 大学院工学系研究科 機械工学専攻](https://www.hnl.t.u-tokyo.ac.jp/en/research-2/)
- 高橋さん
	- 淘汰ありきの活動
	- **自己保守性** が重要と考えている: [自動実験ラボの自律化に向けた自己保守能力の提案](https://www.jstage.jst.go.jp/article/pjsai/JSAI2023/0/JSAI2023_4Q3OS1403/_article/-char/ja/)
	- 物理的な部分も含めて「関数型」にすべき
- 一杉さん
	- 自動自律実験システムの成功は、依頼元側の理解度次第かも
	- 経営判断において、コストパフォーマンスがどの程度かを測定できる必要がある
	- 大企業はダメ、ベンチャーで赤掘って投資しよう
- 夏目さん
	- まず経済性を追求、ニーズ != 市場
	- マーケットにシビアに向き合う・いわゆる市場調査はしない
	- ワンオフを作らない、再利用できるものを作る。柔軟性と拡張性に徹底的にこだわる
	- 人間にはできない精度・汎用性が価値。多品種・少量・頻量
	- ライフサイエンスもマテリアルサイエンスも、自動化における本質的な問題は同じ
		- 違いはワークの数とインキュベーション環境
	- ヒューマノイドに足は要らない（？
- 伴野 太一（島津
	- 液クロ装置の作成
	- 計測インフォマティクス
	- [Development of the autonomous lab system to support biotechnology research | Scientific Reports](https://www.nature.com/articles/s41598-025-89069-y)
	- データの統合管理・解析ができないという顧客が多い
	- [Googleが科学者向けのAIアシスタント「AI co-scientist」を発表 - GIGAZINE](https://gigazine.net/news/20250220-google-ai-co-scientist/)がすごいぞ
- 栗田 真嗣（オムロン
	- 画像処理アルゴリズム開発
	- 「人とロボットが共存できる世界を作る」
	- 次世代ラボオートメーション
		- 人（研究者）と共存できるシステム
	- 「結果と設定ファイルをどう管理するか」は企業ごとに固まってきている
- 小山 聡（堀場
	- 自動車開発用テスト自動化装置・排ガス総量測定
	- 堀場はグローバル企業
	- データの再利用性を確保するのは難しい
	- 分析系は非常に複雑で、標準化は難しい
	- 制約と汎用性はトレードオフ？
### 個人的メモ
- 標準化の話
	- 結論を出すだけだったら、 ChatGPT に考えさせた方が速いかも: https://chatgpt.com/share/67e0f8ed-345c-8012-b6b6-a90f0d67e5e2
	- 参加者同士で「あの時こういう話をしたよね」が標準化を進めるのに重要かも、グルーブ感
	- データや仕様の標準化は乱立しがち、生き残ったものが標準だと思う
- 柔軟性の話
	- システムに何を期待するかと、そのシステムの汎用性の関係
	- UI / UX 設計と同じような話？システムデザインの話
	- 「柔軟性と拡張性に徹底的にこだわる」のは、いわゆる[第二のシステム](https://gist.github.com/kaznak/bb365649fc82d185a2dd47bc7f38e8e8)では？
- 計測機器システムの自動化の値段が非常に高い、同じ技術なのになんで？
	- 物売りのビジネスにそぐわないから。
	- ファウンドリーライクなビジネスにすれば解決するかも
- その他
	- 当たり前だが、やはり研究者視点が強いと感じる、細かい技術の解像度はそれなりな印象
	- でも自分に必要なものがわかっている感じ、強い
	- 夏目先生がすごい。研究サイドがビジネス理解を、市場を作っていく考え方をしている。本質的。
## LT
### 堀場製作所 Stars 製品
- [STARS ENTERPRISE - Laboratory Management information system - HORIBA](https://www.horiba.com/jpn/automotive/products/detail/action/show/Product/stars-enterprise-1593/#show-more)
- 燃料電池の ...？
### TechShare株式会社
- [TechShare －ロボット製品やシングルボードコンピュータの販売・開発サービスを提供するテクノロジーベンチャー](https://techshare.co.jp/)
- ロボットアーム・AGV・UGV・その他 IoT 製品などのリセラー
- ソフトウェア開発も行うらしい？
### オムロンサイニックエックス株式会社
- OSXはオムロンの中の研究所らしい
	- 線形モデルから脱却したオープン型先行研究モデル
	- 数年後に必要になりそうなテーマをやる
- SINIC: Seed Innovation to Need Impetus Cyclic
	- [SINIC理論 | OMRON Industrial Automation](https://www.ia.omron.com/jp/corporate_profile/philosophy/sinic_theory/)
	- [未来への羅針盤「SINIC（サイニック）理論」 | 企業理念経営について | オムロン](https://www.omron.com/jp/ja/about/corporate/vision/sinic/theory.html)
### 株式会社システム計画研究所 / ISP
- [人工知能 | プロダクト・サービス | システム計画研究所／ISP](https://www.isp.co.jp/products/ai/index.html)
- ロボット・エッジ端末にAIを導入する
