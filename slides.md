---
title: 'Ciklum presentation'
layout: intro
# Presentation Setup (for all option see: https://sli.dev/custom/#frontmatter-configures)
theme: ./theme
class: 'text-center'
highlighter: shiki # https://sli.dev/custom/highlighters.html
lineNumbers: true # show line numbers in code blocks
drawings:
  persist: false # persist drawings in exports and build
transition: none # no transition for better online screen sharing - or use "slide-left"
css: unocss
mdc: true # enable "Markdown Components" syntax: https://sli.dev/guide/syntax#mdc-syntax
routerMode: hash # more compatible with static site hosting
---

::date::
29.05.2024

::title::
# Accessible web without hassle

::description::
<div class="pb-6">Libraries and tooling for developers</div>
<div>Tomas Rezac</div>
<div>FE Lead Developer at Ciklum</div>

---
layout: centered

background: '#f3f3f3'
---

# Do you need to know everything?

<v-clicks depth="1">

- Differences between A, AA, AAA WCAG (Web Content Accessibility Guidelines by W3C) levels of conformance
- All WAI-ARIA roles, states, properties, attributes (Web Accessibility Initiative - Accessible Rich Internet Applications)

</v-clicks>

---
layout: centered

---

# We need to be aware of a lot of accessibility aspects

## Dos and don'ts by [GOV.UK](theme/Dos_Donts.pdf)


---
layout: centered
background: '#f3f3f3'
---

# Before you start coding make sure

<v-clicks depth="1">

- There is only content needed on every single page
  - Avoid a huge number of interactive elements
  - Each page can be accessed in a few steps
  - Content is ordered in a logical way
- Texts are short in plain language and easy to understand
  - Texts are supported by diagrams, images and pictograms
- There is enough space between texts and interactive elements
  - Interactive elements are big enough
- Colors are accessible with good contrasts
  
</v-clicks>

---
layout: centered
---

# Choosing the right colors 

## [https://palette.rocks](https://palette.rocks/)


---
layout: centered
background: '#f3f3f3'
---

# When you start coding make sure

<v-clicks depth="2">

  - Semantics are for accessibility, not for developers
    - Use as little wrappers as possible
    - Use semantic HTML over aria roles (understanding of landmarks)
  - Get rid of bad habits and practices
    - don't be afraid of 
      - `.h1` instead of `h1`  (understanding of Outlines)
      - using semantics and accessibility attributes for styling: `aria-busy=true`, `role=tablist`, `role=tab`, `aria-invalid=true`
      - classes are for style variants, not necessarily for defaults
    - keep html font-size: 100% 
    - use new features like `inert`, `dialog`, `logical properties`
  
</v-clicks>


---
layout: centered
background: ./theme/bgs/wawy2.png
---

# Tools for coding accessible webs

- Use accessibility readers
- [https://polypane.app](https://polypane.app/)



---
layout: centered
background: '#f3f3f3'
---

# Libraries and Frameworks

<v-clicks depth="2">

- Javascript
  - Headless
    - React Aria, Radix UI, HeadlessUI + tailwind, Ant Design
    - Shadcn/ui (react, svelte, vue)
  - Styled (optionally)
    - Material UI, Bootstrap, Chakra-UI
- CSS 
  - Pico.css
  - [Sugar.css](https://sugar-css.com/)

</v-clicks>

---
layout: centered
---

# The future

- More native accessible CSS API
- [Popover and Anchor API](https://codesandbox.io/p/sandbox/popover-menu-f6p52q?file=/styles.css)



---
layout: centered
---

# Questions?

---
layout: thank-you
---
