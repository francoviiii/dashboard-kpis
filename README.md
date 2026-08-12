# Dashboard KPIs — Fishermans, Aristocrata & Operacional

Duas páginas de acompanhamento semanal e mensal, separadas por área e por pessoa.

- `index.html` — **Marketing** (abas Fishermans / Aristocrata)
- `operacional.html` — **Operacional** (Suporte / Samuel e Produção / Juliana)

As duas páginas se linkam pelo menu no topo.

## Como publicar (GitHub Pages)

1. Suba `index.html`, `operacional.html` e este `README.md` na raiz do repositório.
   No GitHub: **Add file → Upload files → arraste os arquivos → Commit changes**.
2. **Settings → Pages** → *Source*: **Deploy from a branch** → *Branch*: `main`, pasta `/ (root)` → **Save**.
3. Em 1–3 minutos o site fica em `https://<seu-usuario>.github.io/<nome-do-repo>/`

## Como atualizar toda semana

São **duas planilhas diferentes**, cada uma na sua página. Não precisa mexer no código.

| Planilha | Abas | Onde subir |
| --- | --- | --- |
| Marketing | `Fishermans`, `Aristocrata` | página **Marketing** (`index.html`) |
| Operacional | `Operacional` | página **Operacional** (`operacional.html`) |

Em cada página, desça até o painel **Atualização semanal**, arraste o `.xlsx` ou clique em **Selecionar planilha**. Se subir a planilha errada na página errada, o dashboard avisa e não carrega.

Os números ficam salvos no navegador de quem subiu — cada pessoa que abrir o link precisa subir a planilha uma vez.

### Estrutura esperada das planilhas

- Coluna **B**: nome do KPI (o dashboard reconhece pelo nome — mantenha os títulos)
- Coluna **C**: meta
- Colunas **D até S**: semanas S01 a S16
- Observações: comentários nas células das semanas

Se linhas de KPI novas forem adicionadas, elas não aparecem sozinhas — me avise que eu incluo.

## Arquivos

`index.html` e `operacional.html` são autocontidos (fontes, estilos e lógica embutidos) e funcionam offline.
