📊 Dashboard Financeiro - Power BI
✅ Descrição do Projeto
Este projeto consiste no desenvolvimento de um Dashboard Financeiro no Power BI, com foco na análise e visualização da movimentação financeira da empresa.
O trabalho foi realizado como parte de um projeto didático, utilizando dados fictícios fornecidos exclusivamente para fins educacionais.

O desenvolvimento seguiu um fluxo orientado a requisitos de negócio, organizando as informações em três telas principais para oferecer uma visão clara, detalhada e gerencial dos dados.

🙏 Agradecimento
Gostaria de agradecer ao professor Nogueira J. pela elaboração deste conteúdo educativo, pela disponibilização das bases de dados fictícias e dos layouts de fundo que foram utilizados na construção deste dashboard.

📺 Aula completa:
https://www.youtube.com/watch?v=mrmrqgvtKFI&list=PL81QNM0GmZdpdhUyIVkqGob51KZxx8ulv

📺 Canal do professor:
https://www.youtube.com/@nogueira_junior

🔗 LinkedIn do professor:
https://www.linkedin.com/in/nogueira-junior/

⚠️ Observação Importante
➡️ Este projeto é totalmente didático.
➡️ Os dados utilizados são fictícios e não refletem nenhuma situação real.
➡️ O objetivo é exclusivamente o desenvolvimento e demonstração de competências técnicas em análise de dados e visualização com Power BI.

🗂️ Estrutura do Dashboard
1️⃣ Tela: Home
Introdução ao painel.

Visão geral rápida da movimentação financeira da empresa.

Indicadores de receita, despesa, lucro e fluxo de caixa apresentados de forma resumida e visualmente intuitiva.

2️⃣ Tela: Painel Geral
Análise consolidada de:
✔️ Receita por mês vs. mês do ano anterior.
✔️ Receita por tipo de conta.
✔️ Pagamentos por tipo de conta e por mês.
✔️ Receita por cliente.

Visualizações: Gráficos de colunas, barras e linhas para comparações temporais e categóricas.

3️⃣ Tela: Detalhamento
Foco no Fluxo de Caixa, apresentado de forma aprofundada:
✔️ Gráfico de Cascata — evidencia entradas e saídas ao longo dos meses.
✔️ Tabela Detalhada — permite a análise minuciosa de cada movimentação.

🎯 Requisitos de Negócio
Conforme o documento fornecido, o dashboard atende aos seguintes pontos:

✔️ Analisar a movimentação financeira da empresa (receitas, custos, despesas e lucros).
✔️ Comparar receita mês a mês, incluindo comparação com o ano anterior.
✔️ Visualizar receita e pagamento por tipo de conta.
✔️ Avaliar o fluxo de caixa em gráfico e tabela.

📊 Fontes de dados: TXT, Excel e OneDrive.

🛠️ Metodologia Aplicada
O desenvolvimento seguiu os 7 Pilares essenciais de projetos de Business Intelligence:

1️⃣ Extração: Dados coletados de arquivos TXT, Excel e OneDrive.

2️⃣ Estruturação: Organização das informações financeiras, preparando-as para a modelagem e análise.

3️⃣ Modelagem:

Construção de um modelo relacional robusto, utilizando modelo estrela com tabela fato (movimentações financeiras) e tabelas dimensão (contas, clientes, tempo).

Criação da dCalendar, uma tabela de datas personalizada e enriquecida com colunas como:
✔️ Nome do dia
✔️ Nome e abreviação do mês
✔️ Semana do mês e do ano
✔️ Trimestre e Ano
✔️ Mês/Ano combinado

🔗 Importância: A dCalendar foi fundamental para análises temporais, segmentações e comparações entre períodos.

4️⃣ Cálculos:

Desenvolvimento de medidas DAX para calcular:
✔️ Receita total e por tipo de conta
✔️ Pagamentos
✔️ Comparativos anuais
✔️ Lucro
✔️ Fluxo de caixa acumulado

5️⃣ Visuais:

Escolha criteriosa de gráficos (cascata, colunas, linhas) para criar uma narrativa visual clara.

Estruturação das três telas: Home → Geral → Detalhamento.

6️⃣ Distribuição:

Preparação do arquivo .pbix para compartilhamento interno e integração via Power BI Service.

7️⃣ Automatização:

Configuração de atualizações automáticas de dados, garantindo que as informações estejam sempre atualizadas e precisas.

🗺️ Modelagem de Dados
O modelo seguiu as boas práticas:

✅ Modelo Estrela:

Tabela Fato: Movimentações financeiras.

Tabelas Dimensão: Contas, Clientes, Tempo (dCalendar).

✅ Relacionamentos:

Estabelecidos entre as tabelas com chaves apropriadas, garantindo a integridade e consistência dos dados.

✅ Medidas:

Fórmulas DAX criadas para facilitar análises rápidas e precisas.

📥 Como Reproduzir
Abrir o arquivo dashboard_financeiro.pbix no Power BI Desktop.

Revisar as três telas:

Home

Painel Geral

Detalhamento

Navegar pelas segmentações e filtros:

Períodos de tempo

Tipos de conta

Clientes

🚀 Resultados Obtidos
✔️ Dashboard claro, intuitivo e de fácil navegação.
✔️ Atende aos requisitos de negócio com análises detalhadas e comparativas.
✔️ Proporciona visão estratégica sobre a movimentação financeira.
✔️ Permite tomada de decisão rápida e baseada em dados.

🔮 Próximos Passos
Incluir análises preditivas:
✔️ Projeção de fluxo de caixa.
✔️ Previsão de receita e despesas.

Melhorar a automação com parâmetros dinâmicos e integração com Power BI Service para relatórios online.

📫 Contato
João Uriel Silva Arraes
LinkedIn
Email: joao_uri@hotmail.com

✅ Estrutura do Repositório
markdown
Copiar
Editar
dashboard-financeiro-powerbi
│
├── README.md
├── dashboard_financeiro.pbix
├── Requisitos_de_Negocio.txt
├── Modelagem_de_Dados.txt
├── dCalendar.m
└── images
    ├── tela_home.png
    ├── painel_geral.png
    └── detalhamento_fluxo_caixa.png
✅ Conclusão
Este projeto demonstra como, a partir de um projeto didático bem estruturado, é possível desenvolver uma solução clara e eficiente utilizando Power BI.
Aplicamos boas práticas de modelagem, visualização e automação, resultando em um produto final que agrega valor educacional e técnico ao aprendizado em Business Intelligence.
