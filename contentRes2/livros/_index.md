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
  title: Os Livros
  limit: '30'
  tipo: '0'
  sideimage: ''
  files: |-
    content:livros:1712157031610.md
    content:livros:1712157101766.md
    content:livros:1712157400913.md

---

::showcontentindex
::