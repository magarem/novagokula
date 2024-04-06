---
components:
  showContent:
    mode: simple
params_schema:
  title:
    label: Título
    type: string
  limit:
    label: Limite
    type: string
  tipo:
    label: Tipo
    type: string
  sideimage:
    label: Imagem superior
    type: text+button
    buttonLink:
      label: Selecionar
      link: openImageManagerModal
  files:
    label: Arquivos
    type: textarea
params_data:
  title: Alimentação
  limit: 51
  tipo: '0'
  sideimage: ''
  files: |-
    content:alimentacao:confrariavegana.md
    content:alimentacao:bistro.md
    content:alimentacao:eka.md
    content:alimentacao:1712245107898.md
    content:alimentacao:lanchonetejaganata.md

---

::showcontentindex
::