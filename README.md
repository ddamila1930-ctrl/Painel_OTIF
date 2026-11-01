# 📊 Painel OTIF · Logística

Painel web interativo desenvolvido em arquivo único para monitoramento, análise de indicadores e gestão de entregas (**OTIF - On-Time In-Full**).

## 🚀 Funcionalidades

* **Importação Flexível**: Suporte a arquivos Excel (`.xlsx`) via *drag-and-drop* ou seleção direta.
* **Filtros Dinâmicos**: Filtragem por ano, mês, semana, escritório de vendas, transportadora e status OTIF.
* **KPIs em Tempo Real**: Acompanhamento percentual do OTIF geral e comparação direta com a meta configurável.
* **Visualização Gráfica (SVG)**:
  * Evolução do OTIF % por semana e por mês.
  * Desempenho comparativo por transportadora.
  * Ranking de escritórios de vendas.
* **Gestão de Ocorrências**: Tabela detalhada de pedidos com suporte a anotações de motivos de atraso e números de protocolo (com salvamento local via `localStorage`).
* **Exportação e Backup**: Baixe os dados filtrados em formato CSV ou faça o backup/restauração das anotações em JSON.

## 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3**: Layout responsivo e estilização moderna.
* **JavaScript (Vanilla)**: Lógica de negócio, manipulação de DOM e processamento de dados.
* **JSZip**: Biblioteca embutida para leitura e descompactação de arquivos `.xlsx` diretamente no navegador.

## ⚙️ Como Usar

1. Baixe o arquivo `Painel_OTIF.html`.
2. Abra-o em qualquer navegador web moderno (Chrome, Edge, Firefox).
3. Arraste ou selecione a sua base de dados em Excel (`BASE.xlsx`) para carregar o painel instantaneamente.
