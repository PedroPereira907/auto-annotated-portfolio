---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: >-
    /images/634897-download-wallpaper-colored-smoke-clean-wallpaper-1366-x-768-desktop-background.webp
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 20
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: "oLÁ, o meu nome é Pedro pereira e sou aluno da oficina no curso\_ gestão e programação de sistemas informáticos."
    subtitle: >-
      Estou no meu último ano de curso e pronto para enfrentar os desafios da
      industria de programação, já obtive experiência em diversas linguagens e
      programas como irei mostrar mais abaixo no portfolio.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions: []
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projetos
  - type: CtaSection
    title: Conhece-me melhor
    text: >
      Carrega no botão abaixo para saber mais informações minhas como estudos,
      skills e empresas que trabalhei.
    actions:
      - type: Button
        label: Informações
        altText: ''
        url: /info
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: center
      text:
        textAlign: center
      actions:
        justifyContent: center
---
