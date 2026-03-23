# Análise de Fluxo de Caixa e Estruturação de Dados

### Excel → SQL Server → Power BI

## Visão Geral

Este projeto tem como objetivo estruturar e analisar o fluxo de caixa de instituições financeiras, transformando dados operacionais descentralizados em uma solução analítica confiável e orientada à tomada de decisão.

A solução integra diferentes etapas do processo de dados, desde a organização em Excel até a modelagem em SQL Server e visualização em Power BI.

---

## Problema de Negócio

A gestão de fluxo de caixa baseada em planilhas pode gerar:

* Falta de visibilidade sobre entradas e saídas
* Dificuldade em acompanhar o saldo ao longo do tempo
* Risco de inconsistência nos dados
* Baixa capacidade de antecipar problemas financeiros

Este projeto resolve esses desafios ao estruturar os dados e criar uma visão analítica do fluxo financeiro.

---

## Stack e Arquitetura

* Excel (origem dos dados)
* SQL Server (tratamento e modelagem)
* Power BI (visualização e análise)

---

## Pipeline de Dados

* Coleta de dados financeiros em Excel
* Tratamento, limpeza e padronização no Power Query
* Estruturação em modelo dimensional (Star Schema)
* Integração com Power BI para análise interativa

---

## Decisões Analíticas

* Utilização de modelo estrela para otimizar performance
* Separação entre tabelas fato (movimentos) e dimensões (bancos, contas e calendário)
* Estruturação para análise temporal e financeira consistente
* Uso de DAX para cálculo de saldo, entradas, saídas e fluxo

---

## Principais Insights

* Queda nas entradas em determinados períodos, gerando desequilíbrio no fluxo de caixa
* Manutenção das saídas mesmo com redução de receita, indicando ausência de ajuste operacional
* Tendência de saldo negativo ao longo do tempo, sugerindo risco financeiro
* Concentração de impacto financeiro negativo em uma única instituição bancária, sugerindo possível desequilíbrio na alocação de recursos  

---

## Recomendações Estratégicas

* Investigar causas da redução de entradas (inadimplência, queda de receita ou fatores externos)
* Ajustar estrutura de custos e revisar despesas fixas
* Implementar monitoramento preditivo do fluxo de caixa
* Revisar estratégia de alocação de recursos entre bancos

---

## Preview do Dashboard

<p align="center">
  <img src="imagens/Captura de tela 2025-09-16 212116.png" width="900">
</p>

---

## Dashboard

O dashboard permite uma análise completa do fluxo de caixa, incluindo:

- Evolução temporal de entradas e saídas  
- Comparação de desempenho entre instituições financeiras  
- Acompanhamento do saldo acumulado ao longo do tempo  
- Identificação de principais drivers de saída por subgrupo  

Arquivo disponível em:  
dashboard/dfc-fluxo-caixa-analise-financeira.pbix

---

## Projeto Completo

* 🔹 [Parte 1 – Estruturação e SQL](https://www.linkedin.com/pulse/projeto-demonstra%C3%A7%C3%A3o-de-fluxo-caixa-do-excel-ao-sql-server-menezes-wljse/?trackingId=K13V8VExTvaiKSxZpR%2F79w%3D%3D)
* 🔹 [Parte 2 – Visualização e análise](https://www.linkedin.com/pulse/demonstra%C3%A7%C3%A3o-de-fluxo-caixa-projeto-visualiza%C3%A7%C3%A3o-dados-menezes-jsoue/?trackingId=%2BHdHXZqFQ0aFG9FhJjkgFw%3D%3D)

---

## Estrutura do Projeto

- data/ → bases de dados  
- dashboard/ → arquivo Power BI  
- imagens/ → prints do projeto  
- docs/ → documentação  

---

## Possíveis Evoluções

* Automação da ingestão de dados
* Implementação de modelos preditivos
* Monitoramento contínuo do fluxo de caixa
* Integração com sistemas financeiros

---

## Sobre

Profissional com sólida capacidade analítica, focada em transformar dados em insights estratégicos e estruturar soluções orientadas à tomada de decisão.

Experiência com Power BI, SQL e análise de dados financeiros.
