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
        - [**2026/01**] 博士論文「Debugging AI-enabled and Quantum Software Systems」の公聴会を実施．
        - [**2025/12**] 国際会議SANER 2026 ERA Track に論文採択 (Leveraging Mutation Analysis for LLM-based Repair of Quantum Programs)．
        - [**2025/10**] スイス・Università della Svizzera italiana (USI)のGabriele Bavota教授のもとを訪れ共同研究プロジェクトを推進．
        - [**2025/09**] カナダ・Queen's UniversityのAhmed E. Hassan教授, Hao Li博士のもとを訪れ共同研究プロジェクトを推進．
        - [**2025/09**] 日本ソフトウェア科学会第40回大会@東海大学品川キャンパスにてトップカンファレンス・トップ論文誌特別講演のセッションで発表．
        - [**2025/07**] MLSE夏合宿 2025@箱根にて既発表論文発表．
        - [**2025/06**] 国際会議FSE 2025@トロンヘイム, ノルウェーにて論文発表 (Journal First Track)．
        - [**2025/06**] 国際会議EASE 2025@イスタンブール, トルコにて論文発表 (Short Papers, Emerging Results Track)．
        - [**2025/04**] 国際会議EASE 2025 Short Papers, Emerging Results Trackにて論文採択 (Evaluating Mutation-based Fault Localization for Quantum Programs)
        - [**2025/03**] ソフトウェアサイエンス研究会 (SIGSS) @奄美大島で発表 ([量子プログラムに対するミューテーションに基づく欠陥局所化](https://ken.ieice.org/ken/paper/20250312QcJC/))．

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
