# BettasHack App: canal de atualizações

Este repositório público guarda **somente** os instaladores do BettasHack App e o manifesto `app-versao.json`
que o app consulta para saber se há versão nova. Não há código-fonte aqui.

- Cada versão é uma Release com o arquivo `Setup-BettasHackApp-<versão>.exe`.
- `app-versao.json` traz a versão atual, a URL do Setup e o SHA-256. O app confere o hash antes de abrir o instalador
  e nunca instala sem o usuário clicar.
- Nada de dados pessoais, vídeos ou segredos neste repositório.
