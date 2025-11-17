# Dashboard_para-Analise_de_Transportadora

# 🚚 Dashboard de Acompanhamento de Fretes e Logística

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data%20Analysis-blue?style=for-the-badge)

> **Nota:** Este projeto utiliza dados fictícios para fins de demonstração de portfólio.

![Dashboard Preview](Dashboard%202%20imagem.png)

## 📌 Sobre o Projeto

Este projeto consiste em um **Dashboard Executivo de Logística** desenvolvido no Microsoft Excel. O objetivo principal é monitorar a performance de entregas, custos de frete e identificar gargalos na operação logística entre diferentes transportadoras e unidades de distribuição (São Paulo e Natal).

A ferramenta permite que gestores analisem rapidamente o **OTIF (On Time In Full)** e entendam as causas raiz dos atrasos.

## 🎯 Problema de Negócio Resolvido

A empresa precisava de visibilidade sobre:
1.  **Eficiência das Transportadoras:** Qual parceiro entrega mais rápido e com menos avarias/problemas?
2.  **Controle de Custos:** O valor pago em fretes está proporcional ao volume transportado?
3.  **Causas de Atraso:** Os atrasos são culpa da transportadora, do estoque ou da emissão de notas?

## 📊 Principais Indicadores (KPIs)

O painel apresenta os seguintes indicadores chave:

* **Total de Entregas:** Volume total no período analisado.
* **Status de Entrega:** Comparativo entre entregas "No Prazo" vs. "Atrasadas".
* **Performance (%)**: Taxa de entregas realizadas dentro do prazo acordado.
* **Custo Logístico:** Valor total gasto com fretes (R$) vs. Valor das mercadorias transportadas.
* **Análise de Causas:** Gráfico de rosca detalhando os motivos de atraso (Ex: Problemas de transporte, Demora na emissão de NF, Estoque).
* **Visão Geográfica:** Volume de entregas por destino (Capitais) e origem (CDs).

## 🛠️ Ferramentas e Técnicas Utilizadas

Neste projeto, foram aplicadas técnicas avançadas de Excel e Análise de Dados:

* **Tratamento de Dados (ETL):** Limpeza e padronização da base de dados bruta de fretes.
* **Modelagem de Dados (Star Schema):**
    * Uso de *Tabela Fato* (Transações de frete) e *Tabelas Dimensão* (Cadastros de Transportadoras, Rotas e Unidades).
    * Relacionamento entre tabelas (uso de PROCV/VLOOKUP ou Relacionamentos do Excel).
* **Tabelas Dinâmicas:** Consolidação dos dados para alimentar os gráficos.
* **Segmentação de Dados (Slicers):** Criação de filtros interativos (Ano, Mês, Unidade) para navegação dinâmica.
* **Design de Dashboard:**
    * Layout escuro (Dark Mode) para melhor contraste.
    * Hierarquia visual e alinhamento de elementos.
    * Formatação condicional para destacar status.

## 📂 Estrutura do Arquivo

* `Base de Dados`: Contém o registro histórico das solicitações de transporte.
* `Tabelas Auxiliares`: Cadastros de Unidades, Transportadoras e Cidades.
* `Cálculos`: Aba oculta onde ocorrem as agregações das Tabelas Dinâmicas.
* `Dashboard`: A interface visual final para o usuário.

## 🚀 Como Executar o Projeto

1.  Faça o download do arquivo `Dashboard 2.xlsx` neste repositório.
2.  Abra o arquivo no Microsoft Excel (versão 2016 ou superior recomendada).
3.  Utilize os filtros laterais (Segmentação de Dados) para alternar entre os meses e unidades e ver os gráficos reagirem automaticamente.

---
*Desenvolvido por Bruno Lemos
*Conecte-se comigo no [LinkedIn](www.linkedin.com/in/bruno-lemos-dados)*
