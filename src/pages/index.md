---
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/header.jpg
    background_image_opacity: 65
    content: >-
      # Real, beautiful plants right to your door

      Don't forget to add your Snipcart API key to the site's configuration to
      enable Cart actions.
    actions:
      - type: action
        title: See all items
        url: /store
        style: primary
        arrow: true
  - type: featured_products_section
    title: Best sellers
    section_id: best_sellers_section
    light_title: true
    icon: true
    featured_products:
      - src/pages/products/plant1.md
      - src/pages/products/plant3.md
      - src/pages/products/plant5.md
      - src/pages/products/plant7.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - src/pages/category/bigplants.md
      - src/pages/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    title: Testimonials
    testimonials:
      - text: >-
          I didn't know the Snipcart guys were into herbs as well! How beautiful
          is that Planty theme. I'm going to launch a killer JAMstack e-commerce
          store using this for sure.
        author:
          name: John Dope
          location: 'Colorado, USA'
      - text: >-
          Well I'll be d*mned. These plants really ARE greener than any of my
          recruits.
        author:
          name: Major Payne
          location: 'VA, USA'
  - type: promotion_section
    section_id: promotion_section
    title: A new home interior for summer
    subtitle: from $149.99
    image: images/promo.jpg
    background_image: images/leaf.svg
    cta:
      type: action
      title: Discover
      url: /store
      style: secondary
      arrow: true
seo:
  type: stackbit_page_meta
  title: 'The #1 Streams Provider HD,HQ,4K VODS & Live Channels'
  description: Watch Legal Live Streams From Any Device
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: 'The #1 Streams Provider HD,HQ,4K VODS & Live Channels'
      keyName: property
    - name: 'og:description'
      value: >-
        best IPTV Services Provider,iptv cheap,iptv price,iptv instant,Offer
        iptv premium Subscriptions and IPTV Reseller Panel at best prices.
      keyName: property
    - name: 'og:image'
      value: /_static/app-assets/concept-watching-tv.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: 'The #1 Streams Provider HD,HQ,4K VODS & Live Channels'
    - name: 'twitter:description'
      value: >-
        best IPTV Services Provider,iptv cheap,iptv price,iptv instant,Offer
        iptv premium Subscriptions and IPTV Reseller Panel at best prices.
    - name: 'twitter:image'
      value: /_static/app-assets/thoughtful-sun.jpg
      relativeUrl: true
template: home
---
