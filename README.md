**Projeto Power BI - Análise de Folha de Pagamento e Salários**
---
Este projeto consiste em um dashboard interativo desenvolvido no Power BI para análise de dados salariais, benefícios e impostos de funcionários, categorizados por cargo e faixa salarial.

## 📸 Visualização do Dashboard

### Visão Geral
![Dashboard Geral](./img/DASH.jpg)

### Visão Filtrada (Exemplo: Administradores)
![Dashboard Filtrado](./img/DASH.1.jpg)

**🚀 Descrição do Projeto**

O objetivo principal deste dashboard é fornecer uma visão clara da distribuição financeira da empresa, permitindo identificar o impacto de impostos e benefícios no salário líquido, além de comparar as médias salariais entre diferentes cargos.

**🛠️ Etapas de Desenvolvimento**

1. Tratamento de Dados (Power Query)

A base de dados original em Excel passou por um processo rigoroso de ETL (Extração, Transformação e Carga) no Power Query:

Limpeza de Dados: Remoção de duplicatas e tratamento de valores nulos.

Criação de Colunas Personalizadas: Implementação de lógicas para cálculo de Salário Líquido, Salário com Ticket e descontos.

Fórmulas e Condicionais: Criação da coluna "Categoria de Salário" (Alto, Médio, Baixo) para segmentação analítica.

Tipagem: Garantia de que todas as colunas financeiras estivessem no formato de moeda correto.

2. Modelagem e DAX

Utilização de funções DAX para métricas dinâmicas, incluindo:

SalárioDosFuncionarios: Soma total do salário líquido.

MediaSalarial: Média aritmética dos salários por categoria.

MenorSalario: Identificação do piso salarial na base filtrada.

**📊 Funcionalidades do Dashboard**

O dashboard apresenta três visualizações principais:

Cards de Resumo: Exibição rápida do total de salários, média e o menor salário registrado.

Gráfico de Barras Empilhadas: Comparação entre o Salário dos Funcionários e a Soma do Salário Base por categoria e cargo.

Gráfico de Barras Horizontais: Decomposição detalhada de:

Soma de Salário Líquido

Soma de Salário com Ticket

Soma de Impostos

Soma de Benefícios

Tabela Detalhada: Visão granular com todos os valores financeiros por cargo e categoria.

**📈 Insights Obtidos**

Visualização clara de que o cargo de Programador representa a maior fatia da folha salarial na categoria "Salário Alto".

Análise do peso dos impostos em relação ao salário base, facilitando o planejamento tributário/contábil.

Filtros interativos que permitem isolar dados por cargos específicos (ex: Administrador, Gerente, Secretária).

**💻 Tecnologias Utilizadas**

Microsoft Excel: Fonte de dados.

Power Query: Tratamento e transformação de dados.

Power BI: Visualização e criação de dashboards.

Linguagem DAX: Cálculos avançados.
