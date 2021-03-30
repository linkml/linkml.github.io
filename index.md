---
layout: blocks
title: LinkML - Linked data Modeling Language
date: 
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2021/03/30/screen-shot-2021-03-29-at-7-33-23-pm.png"
  navigation:
  - link: "/"
    link_text: LinkML
  - link: "#model"
    link_text: Model
  - link: "#generate"
    link_text: Build
  - link: "#codegen"
    link_text: Codegen
  - link: "#publish"
    link_text: Publish
  cta:
    url: https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll
    button_text: Import
- template: hero-banner-w-image
  block: hero-2
  slug: features
  headline: LinkML <br><strong>model your data</strong>
  content: LinkML is a general purpose modeling language that can be used with linked
    data, JSON, and other formalisms
  cta:
    enabled: true
    url: https://github.com/linkml/linkml
    button_text: 'See on GitHub '
  image:
    image: "/uploads/2021/03/30/screen-shot-2021-03-29-at-7-09-55-pm.png"
    alt_text: Product Shot
  background_image: "/uploads/2018/06/21/hero-2-bg.png"
- template: content-feature
  block: feature-1
  media_alignment: Left
  slug: model
  headline: "<strong>Model your data </strong>easily by authoring YAML files"
  content: Use the LinkML modeling language to author models for your schemas and
    data dictionaries.<br><br>The modeling language is rich employing features such
    as polymorphism, mixins/traits, mapping to ontologies, and control of JSON inlining.
    At the same time it can be used for simple tasks such as defining data dictionaries.
  media:
    image: "/uploads/2021/03/30/screen-shot-2021-03-29-at-7-05-14-pm.png"
    alt_text: uBuild Blocks Mock-Up
- template: 1-column-text
  block: one-column-1
  slug: generate
  headline: Generate schema artifacts
  content: "<strong>Generate downstream artifacts </strong>including JSON-Schema,
    ShEx, RDF/OWL, GraphQL, and SQL DDL"
- template: content-feature
  block: feature-1
  media_alignment: Right
  slug: python
  headline: "<strong>Generate Python dataclasses</strong>"
  content: LinkML can be used to generate Python data classes!
  media:
    image: "/uploads/2021/03/30/screen-shot-2021-03-29-at-7-02-30-pm.png"
    alt_text: Customize Blocks
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: "<strong>Publish</strong> your schema on the web"
  slug: The LinkML framework automates publish schema documentation using mkdocs,
    and assists in publishing schema artefacts using w3id.org
  media:
    image: "/uploads/2021/03/30/screen-shot-2021-03-29-at-7-21-58-pm.png"
    alt_text: ''
  content: ''
- template: full-width-media-element
  block: media-1
  image: "/uploads/2018/06/21/theme.png"
  caption: blah
  slug: publish
- template: detail-content
  block: text-1
  headline: Steps to Build a Model
  content: <p>You can get started right away!</p><ol><li><p>Use <a href="https://github.com/linkml/linkml-template"
    title="LinkML template">linkml-template</a> in GitHub.</p></li><li><p>Hack your
    YAML file</p></li><li><p>Add example data</p></li><li><p>Use the Makefile to generate
    all downstream artefacts</p></li></ol>
- template: simple-footer
  block: footer-1
  content: LinkML ❤︎s your data

---
