# 🧠 Resumo de Estudos: Inteligência Artificial e IA Generativa

## 📌 Tópicos Estudados

- Fundamentos da IA Generativa  
- Conceitos Fundamentais de IA  
- Fundamentos do Aprendizado de Máquina  
- Conceitos de Processamento de Linguagem Natural (PLN)  
- Análise de Sentimentos com Language Studio no Azure AI

---

## 🔷 1. Fundamentos da IA Generativa

A **IA Generativa** é um campo da Inteligência Artificial que permite criar novos conteúdos, como texto, imagens, áudios, códigos e muito mais.

### Conceitos-chave:
- **Modelos Generativos**: como os LLMs (Modelos de Linguagem de Grande Escala), por exemplo, o GPT (Generative Pretrained Transformer).
- **Treinamento prévio (pretraining)** + **ajuste fino (fine-tuning)**: o modelo é treinado com grandes volumes de dados e depois refinado para tarefas específicas.
- **Prompt Engineering**: técnica de criação de comandos/textos para guiar o comportamento dos modelos generativos.

### Exemplos de aplicações:
- Chatbots, assistentes virtuais, geração de código, design de conteúdo, criação de imagens, etc.

---

## 🔷 2. Conceitos Fundamentais de Inteligência Artificial

A **IA** busca desenvolver sistemas capazes de executar tarefas que exigiriam inteligência humana.

### Tipos de IA:
- **ANI (IA Estreita)**: especializada em tarefas específicas (ex: reconhecimento facial).
- **AGI (IA Geral)**: ainda teórica, seria capaz de realizar qualquer tarefa cognitiva.
- **ASI (IA Superinteligente)**: uma IA mais inteligente que o ser humano (hipotética).

### Abordagens:
- **Baseada em regras (Rule-Based)**
- **Aprendizado baseado em dados (Data-Driven)**

### Áreas comuns:
- Visão Computacional  
- Reconhecimento de Fala  
- Robótica  
- Processamento de Linguagem Natural

---

## 🔷 3. Fundamentos do Aprendizado de Máquina (Machine Learning)

### Definição:
Machine Learning é o processo pelo qual computadores aprendem a partir de dados sem serem explicitamente programados para cada tarefa.

### Tipos de Aprendizado:

| Tipo                   | Descrição                                      | Exemplo                      |
|------------------------|-----------------------------------------------|------------------------------|
| Supervisionado         | Modelo aprende com pares entrada-saída (label) | Classificação, Regressão     |
| Não Supervisionado     | Modelo detecta padrões em dados não rotulados  | Clustering, Redução Dimensional |
| Aprendizado por Reforço| O agente aprende por tentativa e erro          | Jogos, Robótica, Otimização  |

### Termos importantes:
- **Overfitting**: quando o modelo se ajusta demais ao conjunto de treino.
- **Underfitting**: quando o modelo não consegue capturar os padrões dos dados.
- **Features e Labels**: atributos de entrada e saídas esperadas.
- **Pipeline de ML**: coleta de dados → pré-processamento → treinamento → avaliação → implantação.

---

## 🔷 4. Processamento de Linguagem Natural (PLN ou NLP)

### Objetivo:
Permitir que máquinas entendam, interpretem e gerem linguagem humana.

### Principais tarefas:
- **Tokenização**: dividir texto em palavras ou frases.
- **Stemming/Lemmatização**: reduzir palavras à sua forma raiz.
- **NER (Reconhecimento de Entidades Nomeadas)**: identificar nomes, lugares, datas.
- **POS Tagging**: identificar a classe gramatical das palavras.
- **Classificação de texto**: como análise de sentimentos.

### Modelos populares:
- **BERT**, **GPT**, **RoBERTa**, **T5**

### Casos de uso:
- Chatbots, resumo automático de textos, tradutores automáticos, análise de sentimentos, assistentes virtuais.

---

## 🔷 5. Análise de Sentimentos com Azure AI Language Studio

### O que é?
O Azure AI Language Studio é uma plataforma no Microsoft Azure para tarefas de PLN, como classificação de texto, extração de entidades, e análise de sentimentos.

### Etapas da prática:
1. **Importação de textos** (ex: avaliações de clientes).
2. **Uso da ferramenta de Análise de Sentimentos**:
   - Atribuição de score positivo, neutro e negativo.
   - Identificação de frases-chave.
   - Detecção de linguagem.

### Insights:
- A ferramenta permite **customizar modelos** para domínios específicos.
- Resultados podem ser exportados e integrados a **Power BI**, **Power Apps**, etc.
- **Alta precisão** em textos bem formatados, mas sensível a ambiguidade.

---

## ✅ Conclusões e Insights Finais

- A IA Generativa representa uma **evolução expressiva** na capacidade de máquinas criarem conteúdo complexo.
- O conhecimento dos fundamentos de IA e ML permite **estruturar soluções mais eficientes e inteligentes**.
- O domínio de PLN é essencial para lidar com **grandes volumes de texto**, especialmente em análise de sentimentos.
- O uso do Azure AI Language Studio facilita a **aplicação prática de IA** mesmo sem conhecimento avançado de programação.
- É essencial ter uma **visão ética e responsável** no desenvolvimento e uso de IA.

---

## 📚 Recomendações para Estudos Futuros

- Praticar com **datasets reais** (IMDb, Yelp, Tweets).
- Explorar **modelos LLM open-source** como LLaMA ou Mistral.
- Aprofundar-se em **Prompt Engineering**.
- Testar a integração de IA com **aplicações low-code/no-code** (Power Platform, Zapier, etc.).
- Estudar **responsabilidade e vieses algorítmicos**.
