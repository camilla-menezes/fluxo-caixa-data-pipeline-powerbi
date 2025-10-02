# Demonstração de Fluxo de Caixa (DFC) 

Este projeto tem como objetivo analisar o fluxo de caixa de instituições financeiras atuantes no setor bancário brasileiro, utilizando uma base de dados simulada que reflete operações de entrada e saída de recursos, bem como variações no cenário macroeconômico.

<br><br>

##  Coleta, Tratamento, Limpeza e Transformação de Dados

O projeto começou com a coleta de dados financeiros em **Excel**, importados para o **Power BI** e tratados no **Power Query** para garantir consistência e confiabilidade:  
<br>
<img align="left" width="500"  src="https://github.com/camilla-menezes/DFCPortifolio/blob/main/imagens/Captura%20de%20tela%202025-09-16%20213255.png">


- Criação de parâmetro para diretório de arquivos, facilitando atualizações futuras;  <br>
- Padronização de colunas, tipos de dados e valores monetários;  <br>
- Remoção de registros duplicados ou inconsistentes;  <br>
- Categorização simplificada de entradas e saídas.  <br>
<br>

O resultado é uma base **limpa e pronta para análise dinâmica**.

<br><br>

##  Criação de Tabelas e Dicionário de Dados

Foi estruturado um **modelo estrela**, com tabelas fato e dimensão:  

- **fMovimentos**: consolida todas as transações financeiras por banco, conta e data;  
- **fSaldoAnterior**: registra os saldos iniciais de cada banco;  
- **dBancos**: descreve os bancos;  
- **dContas**: classifica contas e subgrupos contábeis;  
- **dCalendário**: fornece dimensão temporal completa (ano, mês, dia, trimestre).  

Um **dicionário de dados** documenta cada coluna, seu tipo e propósito, garantindo clareza e consistência no uso das informações.  


<br><br>

##  Dashboard Power BI
<br>
<img align="right" width="500"  src="https://github.com/camilla-menezes/DFCPortifolio/blob/main/imagens/Captura%20de%20tela%202025-09-16%20212116.png">
<br>
O dashboard desenvolvido permite análises dinâmicas e interativas:  

- Evolução mensal de entradas e saídas;  
- Comparativo de saldo por banco;  
- Saldo Acumulado e Operacional;  
- Análise detalhada por subgrupos de contas.  


O dashboard facilita a **tomada de decisão**, oferecendo insights claros sobre o fluxo de caixa.

<br><br>

<a href="https://app.powerbi.com/groups/me/reports/0058e39d-3f17-45c6-bf92-a7a2d5d64568/6513b71b44b8d6896289?experience=power-bi">Clique aqui</a> e acesse a DFC desenvolvida.

<a href="https://www.linkedin.com/pulse/demonstra%C3%A7%C3%A3o-de-fluxo-caixa-projeto-visualiza%C3%A7%C3%A3o-dados-menezes-jsoue/?trackingId=%2BHdHXZqFQ0aFG9FhJjkgFw%3D%3D">Clique aqui</a> e acesse o artigo no Linkedin.

<a href="https://www.linkedin.com/pulse/projeto-demonstra%C3%A7%C3%A3o-de-fluxo-caixa-do-excel-ao-sql-server-menezes-wljse/?trackingId=K13V8VExTvaiKSxZpR%2F79w%3D%3D">Clique aqui</a> e acesse a 2ª fase do projeto, no Linkedin.

<br><br>


 

<br><br>

##  Ferramentas Utilizadas


![Power BI Badge](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=white)
![Excel Badge](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![GitHub Badge](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)


