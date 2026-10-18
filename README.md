# segundo-cerebro-databricks
Segundo Cérebro construído no NotebookLM focado no aprendizado prático de Databricks.

# 🧠 Segundo Cérebro: Domínio Prático de Databricks (NotebookLM)

> **Objetivo:** Criar um segundo cérebro baseado nos ensinamentos de Databricks como um especialista ensinando sua experiência para um iniciante passo a passo em cada detalhe.

Este repositório documenta a criação, curadoria e validação de um assistente de conhecimento personalizado construído com o **Google NotebookLM**, alimentado exclusivamente por fontes oficiais e especializadas em Databricks, Apache Spark e Arquitetura Lakehouse.

---

## 🔗 Link de Acesso ao NotebookLM
* 📌 **Acesse o caderno compartilhado:** [Clique aqui para abrir o Domínio Prático de Databricks](https://notebook.google.com/notebook/2f56f0d6-3ecb-4e27-b219-07443f5e6a53?authuser=1)
*(Caderno público para visualização, sem dados pessoais ou materiais protegidos).*

---

## 📚 Curadoria de Fontes e Confiabilidade

Para garantir que o assistente responda com precisão técnica e sem alucinações, foram selecionadas fontes com alto rigor técnico:

### 1. Documentação Oficial e Treinamentos (Autoridade Máxima)
* **[Databricks Documentation](https://docs.databricks.com/):** Fonte primária de arquitetura, tipos de compute (Serverless/Classic) e melhores práticas.
* **[Databricks Training & Fundamentals](https://www.databricks.com/br/learn/training/home):** Cursos fundamentais e conceitos oficiais da criadora do Spark.
* **[Databricks Demo Center](https://www.databricks.com/br/resources/demos/videos/data-science-and-ai/data-science-and-machine-learning-on-databricks):** Demonstrações reais de Ciência de Dados e Machine Learning.

### 2. Tutoriais Especializados e Comunidade Técnica
* **[DataCamp - How to Learn Databricks](https://www.datacamp.com/pt/blog/how-to-learn-databricks):** Roteiro estruturado de aprendizado para quem vem do zero.
* **[Comunidade r/brdev](https://www.reddit.com/r/brdev/comments/1l6q14g/como_aprender_databricks/):** Experiências e dores reais de desenvolvedores brasileiros no mercado de dados.
* **[Data Science Academy (DSA)](https://blog.dsacademy.com.br/):** Trilha de formação e melhores práticas em Apache Spark.
* **Curadoria de Aulas em Vídeo (YouTube):** Seleção de tutoriais práticos cobrindo desde a criação de workspace e clusters até a Arquitetura Medallion.

### 3. Síntese via Deep Research
* **Relatório estruturado:** *"Aprendizado de Databricks do iniciante ao avançado passo a passo para se tornar um especialista"*, integrando conceitos teóricos com aplicação de mercado.

---

## ⚙️ Diretriz de Comportamento (Prompt de Sistema)

Para garantir que o NotebookLM se comporte como um mentor paciente e prático, foi aplicada a seguinte diretriz de comportamento:

> *"Você é um Engenheiro e Cientista de Dados Especialista em Databricks. Sua missão é ensinar um iniciante que quer ingressar no mercado de trabalho. Sempre explique os conceitos com clareza, utilizando analogias práticas antes do código. Nunca use jargões sem explicá-los. Ao responder, baseie-se estritamente nas fontes fornecidas e cite de qual documento, vídeo ou manual oficial a resposta foi extraída."*

---

## 💬 Validação: Perguntas, Respostas e Citações

Abaixo estão as perguntas de validação feitas ao assistente para testar a fidelidade às fontes:

### Pergunta 1: *"O que é a Arquitetura Medallion e por que ela é usada no Databricks?"*
* **Resposta do NotebookLM:** A Arquitetura Medallion é um padrão de design de dados que organiza o fluxo em três camadas lógicas de qualidade crescente: **Bronze** (dados brutos/raw), **Silver** (dados limpos, filtrados e tipados) e **Gold** (dados agregados prontos para análise de negócios e modelos preditivos). Ela garante governança, rastreabilidade e performance nas consultas.
* **Fontes citadas:** *Databricks Fundamentals* e *Vídeos práticos de Lakehouse*.

### Pergunta 2: *"Como um iniciante pode praticar Databricks sem pagar nada?"*
* **Resposta do NotebookLM:** A forma recomendada é utilizando o **Databricks Free Edition**, que oferece um ambiente de nuvem gratuito com capacidade de computação para estudos de Apache Spark e notebooks interativos, sem necessidade de cadastrar cartão de crédito.
* **Fontes citadas:** *Documentação de Introdução ao Databricks (Getting Started)* e *Deep Research - Roteiro de Estudos*.

### Pergunta 3: *"Qual a diferença entre usar Python puro e PySpark dentro do Databricks?"*
* **Resposta do NotebookLM:** O Python convencional roda em um único nó/núcleo (como em scripts locais). O PySpark é a API em Python que distribui o processamento em múltiplos nós (clusters Spark), permitindo processar volumes massivos de dados (terabytes/petabytes) com alta velocidade.
* **Fontes citadas:** *DataCamp - Guia de Aprendizado* e *DSA Trilha Spark*.

---

## 📁 Evidências e Materiais Gerados

Na pasta `/evidencias` deste repositório você encontra:
1. `chat-citacoes-01.png` e `chat-citacoes-02.png`: Prints demonstrando que as respostas possuem os marcadores numéricos de citação das fontes.
2. `mapa-mental-databricks.png`: Visualização conceitual dos módulos de aprendizado gerada a partir do caderno.
3. `resumo-executivo.pdf`: Guia rápido consolidado para consulta offline.

---

## ✅ Checklist de Conformidade com o Desafio

- [x] O tema e objetivo estão claramente definidos na introdução.
- [x] Fontes listadas com justificativa de confiabilidade e autoridade técnica.
- [x] Diretriz de comportamento (persona do mentor) documentada.
- [x] Perguntas e respostas acompanhadas das devidas citações de fontes.
- [x] Link público de compartilhamento do NotebookLM configurado.
- [x] Repositório público, na conta do autor e com nome padronizado (`segundo-cerebro-databricks`).
