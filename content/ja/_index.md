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
        - [**2024/12**] 母校の福井高専にて高専からの編入や研究についての先輩講座を実施 ([スライド](./pdfs/20241219_3EI_石本.pdf))．
        - [**2024/12**] 国際会議APSEC 2024にて，(1) 併設ワークショップのEEE-OSSにパネリストとして参加，(2) 本会議Technical Trackで論文発表．
        - [**2024/11**] 第31回ソフトウェア工学の基礎ワークショップ (FOSE2024) に参加し，ポスター発表．
        - [**2024/10**] ソフトウェア工学のトップ国際論文誌TOSEM (ACM Transactions on Software Engineering and Methodology) に論文採択（Repairs and Breaks Prediction for Deep Neural Networks）
        - [**2024/09-10**] 国立情報学研究所 石川 冬樹准教授の研究室を訪問し共同研究を実施
        - [**2024/09**] 国際会議APSEC 2024 Technical Track に論文採択 ([An Empirical Study on Self-Admitted Technical Debt in Quantum Software](/ja/publication/ishimoto-2024-qsatd/))．
        - [**2024/07**] [MSR Summit Japan 2024](https://posl.ait.kyushu-u.ac.jp/~msrsummitjapan2024/#) 参加．
        - [**2024/03**] [8大学共同開催「情報学 for all by all」](https://www.i.u-tokyo.ac.jp/events/joho-for-all2024/) 登壇．
        - [**2023/10-11**] 東京大学 Lei Ma准教授の研究室にて特別研究学生として在籍．
        - [**2023/10**] 国際会議QRSに参加し，論文発表（オンラインで発表）．

        [すべてのニュース >>](/ja/news)
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: list

  - block: collection
    id: publications
    content:
      title: 論文誌・国際会議論文
      subtitle: Refereed and first-authored
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](/ja/publication/).
        {{% /callout %}}

        [研究成果の一覧 >>](/ja/achievements)
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
