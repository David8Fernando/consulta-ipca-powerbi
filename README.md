# Consulta IPCA no Power BI

Este repositório demonstra como obter dados do IPCA diretamente no Power BI usando uma consulta nula.

## Como usar

1. **Criação da consulta M no Power BI**:
    - No Power BI, crie uma nova consulta em branco.
    - Copie o código M presente no arquivo `consulta-m/Consulta_IPCA.txt` e cole-o na consulta M do Power BI.

2. **Código M para obter os dados do IPCA**:
    - O código M obtém os dados da API do Banco Central e os transforma em uma tabela com o IPCA acumulado por ano.

3. **Exemplo de arquivo Power BI**:
    - Baixe o arquivo `exemplos/Exemplo_PowerBI.pbix` para ver um exemplo de relatório configurado com os dados do IPCA.

## Passos detalhados para configuração

### Passo 1: Criar uma consulta em branco
1. No Power BI Desktop, clique em **Transformar Dados**.
2. Clique em **Nova Fonte** e selecione **Consulta Nula**.

### Passo 2: Inserir o código M
Copie o código M do arquivo `consulta-m/Consulta_IPCA.txt` e cole-o na consulta em branco. O código M se conecta à API do Banco Central e retorna os dados do IPCA acumulado.

### Passo 3: Criar visualizações
Após a consulta ser executada, você pode usar os dados na construção de visualizações no Power BI.
