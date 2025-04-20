---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: about.biography
    id: about
    content:
      title: プロフィール
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  - block: markdown
    id: news
    content:
      title: ニュース
      text: |-
        - [**2025/04**] 国際会議EASE 2025 Short Papers, Emerging Results Trackにて論文採択 (Evaluating Mutation-based Fault Localization for Quantum Programs)
        - [**2025/03**] ソフトウェアサイエンス研究会 (SIGSS) @奄美大島で発表 ([量子プログラムに対するミューテーションに基づく欠陥局所化](https://ken.ieice.org/ken/paper/20250312QcJC/))．
        - [**2024/12**] 母校の福井高専にて高専からの編入や研究についての先輩講座を実施 ([スライド](./pdfs/20241219_3EI_石本.pdf))．
        - [**2024/12**] 国際会議APSEC 2024にて，(1) 併設ワークショップのEEE-OSSにパネリストとして参加，(2) 本会議Technical Trackで論文発表．
        - [**2024/11**] 第31回ソフトウェア工学の基礎ワークショップ (FOSE2024) に参加し，ポスター発表．
        - [**2024/10**] ソフトウェア工学のトップ国際論文誌TOSEM (ACM Transactions on Software Engineering and Methodology) に論文採択（Repairs and Breaks Prediction for Deep Neural Networks）
        - [**2024/09-10**] 国立情報学研究所 石川 冬樹准教授の研究室を訪問し共同研究を実施

        [すべてのニュース >>](/ja/news)
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: list

  - block: collection
    id: publications
    content:
      title: 主要な論文
      subtitle: Refereed and first-authored
      text: |-
        [研究成果の一覧 >>](/ja/achievements)
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](/ja/publication/).
        {{% /callout %}}

      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation

  # - block: markdown
  #   id: awards
  #   content:
  #     title: 受賞
  #     text: |-
  #       1. [令和4年度電子情報通信学会ソフトウェアサイエンス研究会研究奨励賞](https://www.ieice.org/iss/ss/award.html), 2023年3月．
  #       2. [情報処理学会2021年度コンピュータサイエンス領域奨励賞](https://www.ipsj.or.jp/award/cs-award-2021.html), 2021年6月．
  #       3. [第207回ソフトウェア工学研究会 学生研究賞](https://www.sigse.jp/award.html), 2021年3月．
  #       4. 情報処理学会北陸支部 平成30年度 優秀学生賞, 2019年3月．

  #       [研究成果の一覧 >>](/ja/achievements)
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '2'
  #     view: list

  # - block: markdown
  #   id: achievements
  #   content:
  #     title: 研究成果
  #     text: |-

  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: list

  - block: contact
    id: contact
    content:
      title: 連絡先
      email: ishimoto🌟posl.ait.kyushu-u.ac.jp（replace 🌟 for at）
      phone: (+81) 092 802 3606
      address:
        street: 
        city: 
        region: 〒819-0395 福岡県福岡市西区 元岡744 ウエスト2号館 - 810
        postcode: 
        country: Japan
        country_code: JP
      # Automatically link email and phone or display as text?
      autolink: false
      coordinates:
        latitude: '33.59884074165763'
        longitude: '130.2237709386205'
    design:
      columns: '2'
---
