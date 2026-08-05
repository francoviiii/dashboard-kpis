# Dashboard KPIs — Fishermans & Aristocrata

Dashboard de acompanhamento semanal e mensal dos KPIs de marketing, separado por marca e por área/pessoa.

## Como publicar (GitHub Pages)

1. Crie um repositório novo no GitHub, por exemplo `dashboard-kpis`.
2. Faça upload dos arquivos desta pasta (`index.html` e este `README.md`) na raiz do repositório.
   - No GitHub: **Add file → Upload files → arraste os arquivos → Commit changes**.
3. Vá em **Settings → Pages**.
4. Em *Source*, escolha **Deploy from a branch**; em *Branch*, escolha `main` e a pasta `/ (root)`. Salve.
5. Em 1–2 minutos o dashboard fica no ar em:
   `https://<seu-usuario>.github.io/<nome-do-repo>/`

Se o repositório for privado, o GitHub Pages exige plano pago. Para acesso aberto, use repositório público.

## Como atualizar os dados toda semana

O dashboard lê a planilha diretamente no navegador — **não precisa mexer no código**.

1. Baixe a planilha do SharePoint depois que o time preencher (`.xlsx`).
2. Abra o dashboard e vá até o painel **Atualização semanal**, no fim da página.
3. Arraste o arquivo para o painel ou clique em **Selecionar planilha**.

Os números e as observações (comentários das células) são lidos das abas `Fishermans` e `Aristocrata` e ficam salvos no navegador de quem subiu. Cada pessoa que abrir o link precisa subir a planilha uma vez — ou você pode subir e compartilhar o print/tela.

### Estrutura esperada da planilha

- Duas abas: `Fishermans` e `Aristocrata`
- Coluna **B**: nome do KPI (o dashboard reconhece pelo nome, então mantenha os títulos)
- Coluna **C**: meta
- Colunas **D até S**: semanas S01 a S16
- Observações: comentários nas células das semanas

Se novas linhas de KPI forem adicionadas à planilha, elas não aparecem automaticamente — me avise que eu incluo.

## Arquivo

`index.html` é autocontido (fontes, estilos e lógica embutidos) e funciona offline.
