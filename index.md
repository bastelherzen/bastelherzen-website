---
layout: blocks
title: Bastelherzen
date: 2021-04-28T23:00:00.000+00:00
page_sections:


  - template: navigation-header-w-button
    block: header-2
    logo: "/assets/logos/logo.svg"
    logotext: "astelherzen"
    navigation:
      - link: "#"
        icon: "/assets/images/icons/cart.svg"
        cart: true

  - template: hero-banner-w-image
    block: hero-2
    slug: hero
    headline: <strong>Wir sind Bastelherzen.</strong>
    content: Hier findest du all unsere Produkte direkt zum Kauf!
    background_color: "#005f69"
    cta:
      enabled: true
      url: "#products"
      button_text: Zu unseren Produkten

  - template: block-break-id
    block: break-id
    id: "products"

  - template: block-category-plottern
    block: category
    name: Plotterliebe.
    description: Liebevoll beplotterte Gegenstände.
    ctaContent: Hier gibts noch mehr davon!
    background-color: '#fafafa'
    number: 0
    cards:
      - number: 1
        id: aufbewahrungsglas
        name: "Aufbewahrungsglas"
        content: "Dieses Aufbewahrungsglas mit den Sprüchen 'blabla' und 'blabla2' eignet sich besonders für Mutter- oder Geburtstage zum Verschenken"
        price: "19,99€"
        image: "/assets/images/products/aufbewahrungsglas/aufbewahrungsglas_6.jpg"
        infolink: "/aufbewahrungsglaeser"
      - number: 2
        id: koordinatenrahmen
        name: "Koordinatenrahmen"
        content: "Dieses Aufbewahrungsglas mit den Sprüchen 'blabla' und 'blabla2' eignet sich besonders für Mutter- oder Geburtstage zum Verschenken"
        price: "19,99€"
        image: "/assets/images/products/bilderrahmen_coordinates/IMG_0909.JPG"
        infolink: "/koordinatenrahmen"
      - number: 3
        id: blumenrahmen
        name: "Blumenrahmen"
        content: "Dieses Aufbewahrungsglas mit den Sprüchen 'blabla' und 'blabla2' eignet sich besonders für Mutter- oder Geburtstage zum Verschenken"
        price: "19,99€"
        image: "/assets/images/products/bilderrahmen_firstsummer/IMG_0872.JPG"
        infolink: "/blumenrahmen"
      - number: 4
        id: grabkerze
        name: "Grabkerze"
        content: "Dieses Aufbewahrungsglas mit den Sprüchen 'blabla' und 'blabla2' eignet sich besonders für Mutter- oder Geburtstage zum Verschenken"
        price: "19,99€"
        image: "/assets/images/products/kerze/IMG_0888.JPG"
        infolink: "/grabkerze"

  - template: block-category-plottern
    block: category
    name: Makrameeliebe.
    description: Wir machen auch Makramee!
    ctaContent: Noch mehr gibts hier!
    background-color: '#fafafa'
    slug: references
    number: 1



  
  - template: simple-footer
    block: footer-2
    col_1: <a href="impressum">Impressum</a>
    col_2: Wir mit ❤︎ aus Olfen
    col_3: <a href="">Datenschutz</a>
---
