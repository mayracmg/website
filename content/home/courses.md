---
widget: portfolio
headless: true
weight: 30
title: Todos los cursos
subtitle:
content:
  filters:
    folders:
      - course
    kinds:
      - section
    exclude_tags:
      - preface

  filter_default: 0

  filter_button:
    - name: Todos
      tag: '*'
    - name: Python
      tag: python
    - name: SQL
      tag: sql
design:
  columns: '1'
  view: masonry
  flip_alt_rows: false
---
