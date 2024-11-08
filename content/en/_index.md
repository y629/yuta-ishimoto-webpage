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
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: Refereed and first-authored
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](/en/publication/).
        {{% /callout %}}

        [All research achievements >>](/en/achievements)
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation

  - block: contact
    id: contact
    content:
      title: Contact
      email: ishimoto🌟posl.ait.kyushu-u.ac.jp（replace 🌟 for at）
      phone: (+81) 092 802 3606
      address:
        street: 744 Motooka
        city: Nishi-ku
        region: Fukuoka
        postcode: 819-0395
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
