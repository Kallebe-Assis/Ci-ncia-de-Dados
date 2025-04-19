# 🧹 Limpeza de Dados - MegaSuper Vendas

Este repositório contém um notebook em Python desenvolvido como parte da atividade de **Limpeza de Dados** do curso de Ciência de Dados. A atividade foi realizada no Google Colab e tem como objetivo organizar e tratar um conjunto de dados com diversas inconsistências, oriundo da empresa fictícia **MegaSuper Vendas**.

---

## 📊 Descrição do Projeto

O notebook realiza a limpeza de um arquivo CSV com registros de vendas, que contém diversos problemas de formatação, valores inconsistentes e dados ausentes. Ao final, o DataFrame é deixado pronto para análises futuras.

---

## ✔️ Etapas Realizadas

1. **Importação do dataset**
   - Arquivo CSV carregado localmente via upload no Colab.

2. **Padronização de dados**
   - Conversão de colunas monetárias para o formato numérico adequado.
   - Remoção de símbolos como `R$` e substituição de vírgulas por pontos.
   - Padronização de colunas de datas e horários (se necessário).

3. **Tratamento de inconsistências**
   - Verificação e remoção de valores ausentes.
   - Eliminação de registros duplicados.
   - Verificação da fórmula de cálculo do `total`:  
     `total = valor * quantidade + frete`

4. **Documentação**
   - Comentários explicativos em cada etapa do código.
   - Resumo final das alterações realizadas no dataset.

---

## 🚀 Como Usar

1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Faça upload do arquivo `vendas_modificado.csv`.
3. Execute todas as células do notebook `CienciaDeDados.ipynb`.

---

## 📌 Observações

Este trabalho simula um cenário real de um analista lidando com dados desorganizados, reforçando a importância de uma base limpa para qualquer tipo de análise posterior.

---

## 👨‍💻 Autor

- Kallebe Assis Nogueira
