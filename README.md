# 🏠 Pipeline de Dados Imobiliários: Consolidação e ETL

## 📝 Sobre o Projeto
Este projeto simula um desafio real de uma imobiliária que precisava unificar duas bases de dados distintas:
1. **Sistema Antigo:** Dados em Dólar (USD) com descrições não estruturadas.
2. **Sistema Novo:** Dados em Real (BRL) já estruturados.

O objetivo foi criar um processo automatizado (ETL) que limpa, converte moedas e classifica os imóveis para análise de investimento.

## 🛠️ Tecnologias Utilizadas
* **Python 3.x**
* **Pandas:** Manipulação e tratamento de dados.
* **Numpy:** Suporte matemático para conversões.
* **Openpyxl:** Engine para exportação de arquivos Excel.

## 🚀 Funcionalidades do Código
- **Data Cleaning:** Separação de strings complexas (`split`) e remoção de caracteres especiais.
- **Conversão Cambial:** Automatização da conversão de USD para BRL.
- **Engenharia de Atributos:** Criação de métricas como Preço por m² e Categoria de Investimento.
- **Agregação:** Cálculo de médias regionais para auditoria de preços.
- **Exportação Multiaha:** Geração de arquivo `.xlsx` com abas separadas para análise gerencial.

## 📊 Exemplo de Resultado
O script transforma descrições como `Apartamento | Centro | $ 100,000` em dados estruturados prontos para Dashboards de BI.
