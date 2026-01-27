---
layout: page
date: 2025-08-03
tags:
  - deveploment
  - software
  - documentation
---
Ao iniciar o [[Ultimate Meme Payloader]] ele faz alguns cheques, começando com [[Arquivos importantes#^db88a7|general.ini]], ele é o arquivo principal para a configurações do aplicativo inteiro.
# Database de pops
Ao iniciar o Ultimate Meme Payloader inicia um processo de registrar cada 'pop'.
## Cada evento em ordem
- Primeiro registra cada pasta existente em `[pasta do aplicativo]\ultimate_meme_payloader\memes\`
- Limpa o nome de cada pasta removendo o `\` de `examplefolder\`
- Define a localização exata do [[Arquivos importantes#^daf75d|config.ini]] de cada *pop*
- Depois outro loop ocorre onde coloca cada configuração na coordenada X dentro do arquivo array [[Arquivos importantes#^cf7084|meme.arr]]
# Easter-Eggs
Caso você tenha Winamp instalado o app reproduzirá o icônico áudio ao iniciar UMP.
Clicando no nome do autor redirecionará para `https://modulandostars.fyi/` ou clicando o nome do software abrirá a página oficial.