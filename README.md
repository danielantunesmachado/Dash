# Dashboard — Correções & Fila

Este repositório contém um dashboard HTML estático gerado com Plotly para acompanhar:
- Correções por dia e média móvel de 10 dias;
- Tamanho da fila, idade média por escola e redação mais antiga por escola.

## Como publicar com GitHub Pages (sem Actions)
1. Faça o push deste repositório com a pasta `docs/` (já incluída).
2. Em **Settings → Pages**, na seção **Build and deployment**, selecione **Source: Deploy from a branch**.
3. Escolha **Branch: main** e **Folder: /docs**. Salve.
4. A página será publicada em `https://<seu-usuario>.github.io/<seu-repo>/`.

## Como publicar com GitHub Actions (recomendado)
1. Em **Settings → Pages**, na seção **Build and deployment**, selecione **Source: GitHub Actions**.
2. Faça push do arquivo de workflow abaixo em `.github/workflows/deploy-dashboard.yml` (já incluído).
3. Ao fazer push para `main`, o workflow gerará e publicará o site.

Você pode editar `docs/index.html` a qualquer momento e fazer um novo push para atualizar o dashboard.
