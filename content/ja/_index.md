---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

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
        - [**2023/07**] MSR Asia Summit 2023 (札幌&定山渓, 北海道で開催) にLocal Arrangement Chair, ポスター発表者として参加．3日間という短期間で研究に取り組むResearchathonにも参加．
        - [**2023/06**] 国際会議EASE (オウル, フィンランドで開催) に参加し，論文発表．
        - [**2023/05**] 国際会議ICSEおよび併設会議のCAIN (メルボルン, オーストラリアで開催) に参加．CAINにて論文発表.
        - [**2023/04**] 国際会議EASE (International Conference on Evaluation and Assessment in Software Engineering) の Journal First track に採択 (論文誌ISTに採択された論文の発表)．
        - [**2023/03**] SE4AIに関する国際会議CAIN (International Conference on AI Engineering – Software Engineering for AI) に論文採択 ([An Initial Analysis of Repair and Side-effect Prediction for Neural Networks](/ja/publication/ishimoto-2023-initial/))．
        - [**2023/03**] 修士（工学）取得．

        [以前のニュース >>](/ja/news)
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: list

  - block: collection
    id: publications
    content:
      title: 論文誌・国際会議論文
      subtitle: 査読付き
      # text: |-
      #   # {{% callout note %}}
      #   # Quickly discover relevant content by [filtering publications](./publication/).
      #   # {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  - block: markdown
    id: awards
    content:
      title: 受賞
      text: |-
        1. [令和4年度電子情報通信学会ソフトウェアサイエンス研究会研究奨励賞](https://www.ieice.org/iss/ss/award.html), 2023年3月．
        2. [情報処理学会2021年度コンピュータサイエンス領域奨励賞](https://www.ipsj.or.jp/award/cs-award-2021.html), 2021年6月．
        3. [第207回ソフトウェア工学研究会 学生研究賞](https://www.sigse.jp/award.html), 2021年3月．
        4. 情報処理学会北陸支部 平成30年度 優秀学生賞, 2019年3月．

        [研究成果の一覧 >>](/ja/achievements)
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: list

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
        region: 〒819-0395 福岡県福岡市西区 元岡744
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
