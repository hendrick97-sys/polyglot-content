# POLYGLOT â€” RepositÃ³rio PÃºblico de ConteÃºdo Educacional

Este repositÃ³rio contÃ©m exclusivamente os arquivos JSON estruturados de currÃ­culo, histÃ³rias e nivelamento para os 7 idiomas suportados pelo aplicativo **POLYGLOT**, distribuÃ­dos gratuitamente via **GitHub Pages**.

## Estrutura do ConteÃºdo
- manifest.json: Manifesto de integridade com hashes SHA-256, versÃµes e lista de arquivos.
- languages.json: Metadados e configuraÃ§Ãµes dos 7 idiomas.
- en/, es/, it/, r/, de/, u/, ja/:
  - curriculum.json: Unidades e liÃ§Ãµes graduadas A1â€“C2.
  - stories.json: Biblioteca de histÃ³rias com vocabulÃ¡rio e exercÃ­cios de interpretaÃ§Ã£o.
  - placement.json: Teste diagnÃ³stico de nivelamento CEFR.

## AtualizaÃ§Ã£o de ConteÃºdo
Os arquivos sÃ£o validados por integridade SHA-256 e consumidos de forma segura e incremental pelo aplicativo POLYGLOT.