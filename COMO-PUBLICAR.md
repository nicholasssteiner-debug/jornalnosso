# Como publicar uma matéria

1. Crie um arquivo novo dentro da pasta `_posts/`, com o nome no formato:
   `AAAA-MM-DD-titulo-curto.md` (exemplo: `2026-09-25-novo-laboratorio-de-informatica.md`)

2. Cole este modelo no início do arquivo e preencha:

```
---
title: "Título da matéria"
categories: [cidade]
author: "Seu nome"
summary: "Resumo de uma linha que aparece nas listagens."
---

Primeiro parágrafo da matéria.

Segundo parágrafo da matéria.
```

3. `categories` deve ser uma das opções: `cidade`, `economia`, `esportes`, `cultura`, `opiniao`.

4. Salve, faça commit e `git push`. O GitHub Pages publica a matéria automaticamente em alguns minutos — ela aparece sozinha na home e na página da seção correspondente, sem precisar editar mais nada.

## Como incluir uma imagem

1. Coloque o arquivo de imagem dentro da pasta `assets/images/` (formatos comuns: `.jpg`, `.png`, `.webp`).
2. No corpo da matéria, no ponto onde a imagem deve aparecer, adicione:

```
![Descrição da imagem](/assets/images/nome-do-arquivo.jpg)
```

A descrição entre colchetes é importante para acessibilidade (leitores de tela) — descreva o que aparece na imagem.
