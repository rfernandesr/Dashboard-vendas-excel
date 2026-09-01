# Mini Dashboard Dinâmico de Vendas — Excel

Dashboard interativo desenvolvido no Excel para acompanhamento de performance de vendas por vendedor e por período, utilizando tabelas dinâmicas, segmentações de dados (slicers) e gráficos dinâmicos conectados.

## Objetivo

Consolidar dados brutos de uma base de vendas em um painel visual único, permitindo filtrar rapidamente os resultados por **Ano** e por **Vendedor**, sem precisar mexer diretamente na base de dados.


## Funcionalidades

- **Segmentações de Dados (Slicers)** para filtrar por Ano (2016, 2017, 2018) e por Vendedor, atualizando todos os gráficos simultaneamente.
- **Gráfico de Vendas Perdidas** por vendedor, em formato de barras horizontais.
- **Gráfico de Valor Médio de Venda** por vendedor.
- **Gráfico de Vendas Mensais**, comparando a evolução de cada vendedor ao longo dos 12 meses do ano selecionado.
- Layout limpo, com identidade visual própria (paleta de cores e cabeçalho customizados).

## Estrutura do arquivo

| Aba | Conteúdo |
|---|---|
| `Painel` | Dashboard principal com os slicers e gráficos |
| `BaseDeDados` | Base de dados bruta (Mês, Ano, Vendedor, Clientes Visitados, Negócios Fechados, Valor Vendido) formatada como Tabela |
| `TDVendas` | Tabela dinâmica com o total de vendas por vendedor/mês |
| `TDVendasPerdidas` | Tabela dinâmica com o total de vendas perdidas por vendedor |
| `TDValorMedio` | Tabela dinâmica com o valor médio de venda por vendedor |

## Competências demonstradas

- Tabelas dinâmicas (Tabela Dinâmica / Pivot Tables)
- Segmentação de Dados (Slicers) conectada a múltiplas tabelas dinâmicas
- Gráficos dinâmicos vinculados a tabelas dinâmicas
- Boas práticas de layout e usabilidade para painéis de gestão

## Ferramentas utilizadas

Microsoft Excel (Tabelas Dinâmicas, Segmentação de Dados, Gráficos Dinâmicos)

## 👤 Autor

**Raphael** — [LinkedIn](https://www.linkedin.com/in/raphaelfernandesbr/)

---

## OBS 
O arquivo `.xlsx` completo está disponível neste repositório para download e exploração interativa (basta abrir e clicar nos filtros de Ano e Vendedor para ver o painel se atualizar).
