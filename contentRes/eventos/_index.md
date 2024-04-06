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
  title: Eventos / Workshops / Retiros
  limit: 16
  tipo: '0'
  sideimage: ''
  files: |-
    content:eventos:festivaldedomingo.md
    content:eventos:1712165595162.md
    content:eventos:1704917651756.md
    content:eventos:1712166052618.md

---

::showcontentindex
::