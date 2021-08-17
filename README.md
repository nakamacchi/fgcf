# FgCF (Financial-grade Cloud Fundamentals) コンテンツインデックス

- zip ファイルのパスワードはすべて "mskk" です。
- 各資料は、作成時点の Azure の仕様に基づいて作成されています。最新版では異なる場合がありますのでご注意ください。
- リンクが張られていないものは、開発予定 or 開発中のものです。
- マイクロソフト Web サイト上の公式ページは[こちら](https://www.microsoft.com/ja-jp/events/azurebase/fgcf/)です。（内容は同じですが、こちらのページではご利用方法や FgCF の目的、学習順序などを解説しております。）

<hr />

## FgCF について
そもそも FgCF とは何か？ に関するご紹介は、本ページの後ろのほうにあります。下記リンクでジャンプしてご確認ください。
- [Web 記事](#FgCFのご紹介)

<hr />

## Azure 学習に FgCF を利用する場合の使い方

コンテンツが多くなってきたため、オススメ学習順序を作成しました。本来であればゼロトラスト型マルチクラウド IT 環境の設計技法から学習していくべきところですが、FgCF のコンテンツを使って手っ取り早く Azure を習得したい、という方は以下の学習フローがオススメです。

![fgcf-roadmap](images/fgcf-roadmap.png)

<hr />

## FgCF 全体概要
- FgCF 全体概要解説 ([ppt](https://download.microsoft.com/download/c/d/b/cdbe46e1-6168-40af-bd86-fbcdd163cfc9/FgCF_%E2%93%AA_Overview_Explanation_Proposal_Material_v0.01.pptx), [YouTube](https://youtu.be/mTVgSGGt8NE))

## ① IT 環境
- ゼロトラスト型マルチクラウド IT 環境
  - ゼロトラスト入門編 ([Web記事](https://nakama.azurewebsites.net/?p=65), [ppt](https://download.microsoft.com/download/d/f/e/dfed7e7b-75e8-4939-823d-25a06b0abd68/FgCF_%E2%91%A0_0_Zero_trust_type_multi_cloud_IT_environment_Introduction_Further_shortened_version_v0.40.pptx), [video](https://download.microsoft.com/download/b/5/0/b507ac40-280b-413a-be8a-56b29a6a765d/2020_03_10_FgCF_ZeroTrustMultiCloudITEnvironment_movie_v0.40a.zip), [YouTube](https://www.youtube.com/watch?v=V9t3t36b4Mc)) <span style="color: red;">**★★★ 超重要！**</a>
  - OA 環境設計 ([video](https://download.microsoft.com/download/3/7/0/370c26c3-a785-462b-a484-b69500d28680/FgCF_Zero_Trust_IT_Infrastructure_Design_way_of_thinking_video_v0.17.mp4), [YouTube](https://youtu.be/_IegEjBL_ts))
  - Azure Well-Architected Framework : Security セクション概要解説 ([ppt](https://download.microsoft.com/download/1/3/8/13855030-7731-47a8-9759-ff28d9c32e3e/AzureW-AF_Security_section_Overview_documentation_v0.13.pptx), [video](https://download.microsoft.com/download/1/4/9/149d6525-9a7a-42a4-9302-87efce5f4d82/2020_06_12_AzureW_AF_Security_v0.13.zip), [YouTube](https://youtu.be/Z0gqDWX6VnE)) <span style="color: red;">**★★★ 超重要！**</a>
- Azure による仮想データセンタ構築手法
  - 共通技術
    - VDC 構築の進め方の全体像 ([ppt](https://download.microsoft.com/download/c/7/3/c73c0312-1905-4826-bf9a-d92c1a40e503/FgCF_%E2%91%A0_0b_Accredited_Azure_Base_Construction_Overview_v0.04.pptx))
    - ネットワーク基盤の構成方法
      - Azure 仮想ネットワーク基礎 ([ppt](https://nakama.blob.core.windows.net/mskk/2020_10_29_FgCF_AzureNetworkBasis_v0.35_ppt.zip?sv=2020-04-08&si=mskk-readonly&sr=b&sig=MCPZxot7ZW8MRh0zcyAXCPNKJePASpPXz77kxPFjdqk%3D), [video](https://nakama.blob.core.windows.net/mskk/2020_10_29_FgCF_AzureNetworkBasis_v0.35.zip?sv=2020-04-08&si=mskk-readonly&sr=b&sig=OB8XSjJjMTmcBSo1NElvujGA646ACeuYJ5JRptOZ41c%3D), [YouTube](https://youtu.be/SpO_cOaZxdw)) <span style="color: red;">**★★ 重要**</a>
      - ARM テンプレートの利用方法 ([ppt](https://download.microsoft.com/download/e/e/9/ee906254-0816-41f4-98eb-612bcbf1455a/ARM_template_development_v0.33.pptx), [video](https://download.microsoft.com/download/1/f/0/1f063580-4ba6-41f1-913f-2ba81425185c/2019_01_03_PracticalARMTemplate.zip), YouTube [前半](https://youtu.be/Hi4Xh8O10W8), [後半](https://youtu.be/aLLFJVcHY70)) <span style="color: red;">**★★ 重要**</a>
    - 認証基盤の構成方法
      - Azure AD 基礎 ([ppt](https://download.microsoft.com/download/1/3/8/138c3005-82f4-41db-bf78-9ce6d46af2ab/FgCF_%E2%91%A0_2_AzureAD_Overview_v0.70.pptx), [video](https://download.microsoft.com/download/f/6/0/f6093441-8ca4-4901-b74e-f87894fc9ad8/2020_01_08_FgCF_AzureADForAzureBasics_v0.22.zip), [YouTube](https://www.youtube.com/watch?v=H7TKjAGT7pA))<span style="color: red;">**★★ 重要**</a>
      - Azure AD 詳細 ([ppt](https://download.microsoft.com/download/4/4/2/442b4fb3-f47a-4d13-b67a-ab5c721dc4ac/AzureAuthorizationDesignAndManagement_v0.67.pptx))
      - Azure 管理用 Azure AD テナントの作成方法 ([ppt, video](https://nakama.blob.core.windows.net/mskk/2020_10_10_AzureAADforAzure_v0.01.zip?sv=2020-04-08&si=mskk-readonly&sr=b&sig=L5MTAK9A2Bqd19wuxja9agWfrWAEmzOfzAGJASbv8mU%3D), [YouTube](https://youtu.be/wCqnGJHQueM))
  - IaaS の構成方法
    - VNET, IaaS VM セキュリティベースライン ([ppt](https://download.microsoft.com/download/9/a/2/9a258748-936b-4b43-b127-2adc616e70d7/FgCF_%E2%91%A0_3_SecurityBaseline(IaaS)_v1.00.pptx), [video](https://download.microsoft.com/download/d/6/0/d60816c1-47d8-4e7f-9a3a-ef404b441104/2020_01_17_FgCF_SecurityBaseline(IaaS)_v1.00_SplitVersion.zip), [YouTube](https://youtu.be/uB4j8k9N4ag)) <span style="color: red;">**★ オススメ**</a>
    - リファレンスアーキテクチャ（延伸 VNET 版）と構築の要点 ([ppt](https://download.microsoft.com/download/d/f/f/dff93ba3-ab62-4a66-afc7-5d10da094c18/Web_DB_type_system_reference_architecture_and_main_points_of_construction(IaaS_VM_edition).pptx), [video](https://download.microsoft.com/download/d/a/8/da86811f-2aba-46da-ab2a-c42ed4e5a5c8/2019_11_07_FgCF_WebDB_ReferenceArchitecture(IaaSVM).zip), [YouTube](https://youtu.be/KxcieZvAJKo)) <span style="color: red;">**★★ 重要**</a>
    - リファレンスアーキテクチャ（隔離 VNET 版）と構築の要点 ([ppt](https://nakama.blob.core.windows.net/mskk/2020_12_22_FgCF_IaaS_IsolatedVNET_ReferenceArchitecture_v0.01_ppt.zip?sv=2020-04-08&si=mskk-readonly&sr=b&sig=G%2FHRQ7CUgRJxaQFM%2BMyF3%2FSBeGSjHYnojNByvJSlZOQ%3D), [video](https://nakama.blob.core.windows.net/mskk/2020_12_22_FgCF_IaaS_IsolatedVNET_ReferenceArchitecture_v0.01_movie.zip?sv=2020-04-08&si=mskk-readonly&sr=b&sig=gfcD8pnRaI%2F4czv%2B2Dq3Q9d4%2FFPsm2cOtqjcZaSRXOw%3D), [YouTube](https://youtu.be/nX4JZNXTjz4), [Azure Firewall Premium IDPS 対応版 構築スクリプト](https://nakama.blob.core.windows.net/mskk/2021_05_31_FgCF_IaaS_IsolatedVNET_ReferenceArchitecture_v0.11_docs.zip)) <span style="color: red;">**★★ 重要**</a>    
  - PaaS の構成方法
    - 入門 コンテナ技術 ([ppt](https://nakama.blob.core.windows.net/mskk/2020_07_30_DockerKubernetesBasics_v0.03_ppt.zip?sv=2020-04-08&si=mskk-readonly&sr=b&sig=SRl4SSGlKi0Ojn6VPri%2BewXyBtIPwuLgY%2BRWAQDaAg4%3D), [video](https://nakama.blob.core.windows.net/mskk/2020_07_30_DockerKubernetesBasics_v0.03_video.zip?sv=2020-04-08&si=mskk-readonly&sr=b&sig=i9UBneMqeH9Snofwhd78ScBOXh%2FKudah2BoX62EktF4%3D), [YouTube](https://youtu.be/9qFnTc382Ew)) ※ こちらはコンテナ技術 (Docker, Kubernetes など) を知らない方向けの入門コンテンツです。下記の PaaS コンテンツを見る前の基礎知識習得用にご利用ください。
    - App Service (Web App), SQL Database
      - 技術概要 ([ppt](https://download.microsoft.com/download/6/9/3/6934d11e-78dc-4c00-ae61-316067193dc1/AppService_TechnicalReference_v0.06.pptx), [video #1](https://download.microsoft.com/download/6/e/a/6ea96ebd-d9ff-4291-8976-a23698bf1282/2020_06_16_AppService_TechnicalReference_Part1.zip), [YouTube #1](https://youtu.be/DBlPPic3pJ0))
      - 構築の要点 ([video #2](https://download.microsoft.com/download/e/1/3/e130959e-7e85-48a0-a583-6ac49eed7303/2020_06_16_AppService_TechnicalReference_Part2.zip), [YouTube #2](https://youtu.be/JGNMw91ApX0))
      - リファレンスアーキテクチャ ([video #3](https://download.microsoft.com/download/1/2/4/124c009d-2783-447f-8dad-124499c1523b/2020_06_16_AppService_TechnicalReference_Part3.zip), [YouTube #3](https://youtu.be/hZz93refe1k))
    - AKS (Azure Kubernetes Services)
      - 技術概要 ([ppt](https://download.microsoft.com/download/6/4/c/64c7f727-7712-49e7-a95e-7aa19e412e68/2020_04_25_AKS_TechnicalReference_v0.14(ppt).zip), [video #1](https://download.microsoft.com/download/6/6/c/66c3ab0e-3d15-4e79-8377-a2880f1569b2/2020_04_25_AKS_TechnicalReference_v0.14(video1).zip), [YouTube #1](https://youtu.be/PrE3c1ZvL4s))
      - 構築の要点 ([video #2](https://download.microsoft.com/download/9/7/8/97858185-ba75-48a3-a931-72092b5c1279/2020_04_25_AKS_TechnicalReference_v0.14(video2).zip), [YouTube #2](https://youtu.be/PL5MtSVzdI4))
      - リファレンスアーキテクチャ ([video #3](https://download.microsoft.com/download/b/a/8/ba8a9c96-4fc8-43ed-8309-9624d1a45779/2020_04_25_AKS_TechnicalReference_v0.14(video3).zip), [YouTube #3](https://youtu.be/-Mawv15LhQc))

    - ARO (Azure Red Hat OpenShift)
      - 技術概要、構築の要点 ([ppt](https://nakama.blob.core.windows.net/mskk/2020_10_20_AROTechReference_v0.14.zip?sv=2020-04-08&si=mskk-readonly&sr=b&sig=3cCoj%2BKbuI%2BkF0x0G%2FXSzDBGuOvLhdrm9%2Bw1820%2F3nI%3D))
      - リファレンスアーキテクチャ、構築スクリプト ([ppt](https://nakama.blob.core.windows.net/mskk/2020_10_20_AROTechReference_v0.14.zip?sv=2020-04-08&si=mskk-readonly&sr=b&sig=3cCoj%2BKbuI%2BkF0x0G%2FXSzDBGuOvLhdrm9%2Bw1820%2F3nI%3D))
      - ※ ARO リファレンスアーキテクチャは Red Hat 様ご協力の元、HPE 惣道様・米倉様に開発いただきました。この場を借りてお礼申し上げます。m(_ _)m

    - Azure Batch
      - 技術概要 ([ppt](https://download.microsoft.com/download/1/a/7/1a7fb7e9-1602-46de-9ff0-e8548d146a5b/2019_05_21_AzureBatchSample_Materials.zip), [video](https://download.microsoft.com/download/4/8/b/48baeee0-921c-4ecd-afa1-c57b2dcdc935/2019_05_21_AzureBatchSample_Video.zip), [YouTube #1](https://www.youtube.com/watch?v=-cJ50AfA8B4&t=2675s))
      - 設計・実装技法 ([ppt](https://download.microsoft.com/download/4/5/4/454c783b-372f-48c1-aed8-e7b7b112599a/AzureBatch_Technical_reference_v0.20.pptx), [video](https://download.microsoft.com/download/2/1/6/2160a96c-deca-43fd-a557-72a9d29b58e1/2020_08_14_AzureBatch_TechnicalReference_v0.20.zip), [YouTube #2](https://youtu.be/o7AX2sP5TyE))
      - リファレンスアーキテクチャ
  - DevOps の構成方法
    - Azure DevOps 概要デモ ([ppt](https://download.microsoft.com/download/a/f/f/affd5a6d-342f-4c19-a250-040d1ab3ce86/AzureDevOps_OverviewAndDemo_v0.02.pptx), [video](https://download.microsoft.com/download/2/0/b/20b0d275-0256-43b2-ac39-d22c9d5a47a6/2020_02_26_AzureDevOps_OverviewAndDemo_v0.02.zip), [YouTube](https://www.youtube.com/watch?v=aMLGuAdVsQ0&t=6045s)) <span style="color: red;">**★ オススメ**</a>
  - DaaS の構成方法
    - WVD 技術リファレンス ([ppt](https://download.microsoft.com/download/7/0/4/7044dce5-224d-48ae-ab78-e25935e59b6f/WVD_Commentary_material_v0.19.pptx), [YouTube](https://www.youtube.com/watch?v=Ac6ZfZFwwIo))

<hr />

## ② ルール・ガバナンス

- ルール・ガバナンス再設計ガイド
- セキュリティ維持・監査ガイド
- SaaS セキュリティ審査ガイド

<hr />

## ③ 人材育成
- 人材育成計画策定ガイド

<hr />

# FgCFのご紹介

## はじめに ～ FgCF を開発した背景 ～
 
現在、全世界の様々な企業がデジタル変革（DX, Digital Transformation）を目指して様々な取り組みを始めており、様々な成功事例も聞かれるようになってきました。こうした中、海外や国内で成功しているデジタルカンパニーに目を向けてみると、

-	適切な技術回帰により自社の Tech Intensity （技術を自ら実践的に使いこなす力）を高める
-	競争領域に関しては、内製型アジャイル開発にシフトして、継続的に企業競争力を強化する
-	非競争領域に関しては、アウトソースを活用しながらも、開発の主導権は自社できちんと握って適切な開発を進める
 
といった取り組みが多く見受けられるようになってきました。
 
この流れを強く加速することになった大きな原因のひとつが、ここ 10 年で大きく進んだ、様々なクラウドサービス（SaaS, PaaS, IaaS）の登場です。エンドユーザ企業がハードウェアや基盤を容易に調達できるようになった結果、従来、ハードウェアメーカー主導で進めざるを得なかった IT サービスの企画・検討・開発を、ユーザ企業主導で進めていくことができる環境が整いました。日本でも、多くの企業が、多種多様なクラウドサービス（Microsoft 365, SFDC, Slack, Zoom, AWS, GCP, Azure など）をいかに上手くマルチに活用し、自社 IT をどのように改善・強化するかを考えるようになってきています。

![fgcf-pic1](images/fgcf-pic1.png)

しかしこの恩恵に預かるためには、『自社の中に Tech Intensity （技術を自ら実践的に使いこなす能力と人材）を持つこと』が必須要件になります。日本の大企業に目を向けてみると、2000 年頃より始まったアウトソースを過度に進めすぎたが故に、デジタル変革を推進していくための「底力」を失ってしまっているケースが少なくありません。その中でも特に大きな課題として考えられるのが以下の 3 つです。
 
1. 閉鎖的な IT 環境 : 境界セキュリティを前提とした IT 環境
1. 新技術導入がしにくい社内ルール : 最新技術の積極活用を拒む過度なルール
1. IT 人材の技術力不足 : 最新技術を利活用できない・手を動かせないレガシー人材の増加

![fgcf-pic2](images/fgcf-pic2.png)

## FgCF の目指すもの
 
こうした流れを踏まえると、日本企業がデジタル変革へ取り組んでいくためには、その基盤として改めて①～③の改善に取り組み、自社の Tech Intensity（テクノロジー強度）を強く改善・強化していく必要があります。FgCF （Financial-grade Cloud Fundamentals）は、この取り組みを推進することを目的として生まれました。

![fgcf-pic3](images/fgcf-pic3.png)
![fgcf-pic4](images/fgcf-pic4.png)

この FgCF は、様々な各種のハイレベルなリファレンスアーキテクチャやテクノロジガイドライン類を、日本のお客様に使いやすい・わかりやすい形で提供することを目的として開発されています。これは以下の理由によります。
 
- 米国マイクロソフト本社からは以下のような各種のガイドライン類やドキュメント類が提供されている。
  - CAF （Cloud Adoption Framework）
  - Azure VDC （Azure Virtual Data Center）
  - Azure WAF （Azure Well-Architected Framework）
  - 製品ドキュメント（docs.microsoft.com）
  - Microsoft Learn
- しかしこれらはドキュメント量が膨大、かつ英語圏特有の「読みづらさ」があり、初学者がとっつきづらい
 
FgCF では最初に覚えるべき設計セオリーを、日本語で端的に学べるように整備することで、①～③を素早く理解・整備していけるようにすることを目指しています。

![fgcf-pic4](images/fgcf-pic5.png)

※ （参考） FgCF は "Financial" と銘打ってはいるものの、考え方やリファレンスそのものは金融業界に留まらず利用できるものです。公共系、製造系など、セキュリティに対して特に高い要件を有する業界・業種であっても問題なく利用できる、という意味合いで "Financial-grade" という名称をつけています。
 
## FgCF の資料の歩き方
 
FgCF では、（今後の IT 環境のあるべき姿としての）ゼロトラスト型 IT 環境をベースに置いた考え方を採用しており、様々なリファレンスアーキテクチャもこれを念頭に置いた設計を行っています。しかし、「ゼロトラスト」に関しては用語の定義が人によって異なることから、以下の順序で FgCF 関連資料をご確認いただければと思います。

- すべての利用者
  - まず「ゼロトラスト型マルチクラウド IT 環境入門」を確認する
  - さらに、共通技術として以下を学習する
    - VDC 構築の進め方の全体像
    - ネットワーク基盤の構築方法（VNET, ARM テンプレート）
    - 認証基盤の構築方法（Azure AD）
- IT インフラエンジニアの方々
  - IaaS の構成方法
  - DaaS の構成方法
- 開発エンジニアの方々
  - PaaS の構成方法
  - DevOps の構成方法

また関連して、xDM（意思決定者）の方々向けにはルール・ガバナンスに関する資料や人材育成に関する資料をご確認ください（これらの資料は今後、随時公開予定です）。
 
## Special Thanks
 
FgCF の開発にあたっては、マイクロソフト社内外のエンジニア・アーキテクトの皆様から多大なご協力を頂きました。改めて御礼申し上げます。今後とも引き続き、日本の Tech Intensity 強化のため、ご一緒できれば幸いです。

<div style="text-align: right;"> 
2020/06/08<br />
FgCF 開発リード テクニカルアーキテクト<br />
日本マイクロソフト株式会社 金融統括営業本部<br />
インダストリーテクノロジーストラテジスト<br />
赤間 信幸
</div>