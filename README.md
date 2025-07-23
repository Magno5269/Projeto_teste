# 🚀 Projeto de testes com Databricks

Este projeto é um exemplo simples de leitura de dados de eventos usando **PySpark Streaming** no **Databricks Community Edition**.
** Batch Pois o Community Edition está totalmente travado para stream **

Este repositório contém dois projetos de exemplo com **PySpark**, ideais para quem está começando com Big Data:

---

## 👶 Para iniciantes: Como criar uma conta no Databricks Community Edition

Siga o passo a passo:

1. Acesse o site: [https://community.cloud.databricks.com/](https://community.cloud.databricks.com/)
2. Clique em **"Sign Up"** (Cadastrar-se)
3. Preencha com seus dados:
   - Nome
   - E-mail
   - Senha
   - País (ex: Brazil)
4. Verifique seu e-mail (procure na caixa de entrada ou spam)
5. Após confirmar, faça login em:  
   👉 [https://community.cloud.databricks.com/login.html](https://community.cloud.databricks.com/login.html)
6. Pronto! Você já está no seu workspace do Databricks gratuito ✅

---

## 💡 Como usar estes projetos

Você precisa ter o arquivo `IMPORTS.ipynb` no mesmo diretorio que os demais arquivos.

### 1. Acesse o notebook do projeto

Você pode exportar o notebook `.ipynb` deste repositório (clique em "Download" ou "Raw" > salvar como `.ipynb`).

### 2. Faça upload no Databricks

1. No menu esquerdo do Databricks, clique em **Workspace**
2. Crie uma pasta se quiser (ex: `Projetos`)
3. Clique em **Import** > selecione o arquivo `.ipynb`
4. Abra o notebook após importado

Projeto 1 - Stream microbatch

### 3. Execute o notebook

- Clique nas células (caixas de código) e pressione **Shift + Enter** para executar.
- O código vai mostrar dados de exemplo usando PySpark.

---

## 🧪 Sobre o que esse projeto faz

Este notebook realiza:

- Leitura de arquivos JSON de eventos usando **Structured Streaming**
- Definição de `schema` manual para os dados
- Impressão dos dados no console do notebook

---

## 🔹 Projeto 2 – Criação e Tratamento de Dados em Batch

Este segundo projeto é executado em modo **batch** (não-streaming) e mostra como:
- Criar um DataFrame manualmente
- Tratar colunas
- Ingerir na tabela

📄 O notebook está neste repositório com o nome: `INFO_CORRIDAS_DO_DIA - Window.ipynb` ou `INFO_CORRIDAS_DO_DIA - GROUP.ipynb` mas lembre-se antes de baixar e usar o arquivo `INFO_TRANSPORTES.ipynb`

## 💬 Dúvidas?

Se tiver dúvidas, sugestões ou quiser melhorar o projeto, fique à vontade para abrir uma **issue** ou enviar um **pull request**!

---

📌 **Autor**: [Magno Vieira de Andrade](https://github.com/Magno5269)

