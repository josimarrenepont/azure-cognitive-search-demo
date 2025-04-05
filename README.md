# 🔍 Projeto: Pesquisa Cognitiva com IA do Azure

Este projeto demonstra como configurar e aplicar **Azure Cognitive Search** integrado com **Inteligência de Documentos** e **Serviço de Linguagem de IA** para extrair, enriquecer e pesquisar informações de forma inteligente.

---

## 🎯 Objetivo

Utilizar o poder da IA para transformar documentos em fontes de dados pesquisáveis e ricas em significado, automatizando tarefas como:

- Extração de frases-chave  
- Detecção de idioma  
- Análise de sentimento  
- Pesquisa semântica

---

## ⚙️ Passo a Passo - Como configurar a Pesquisa Cognitiva no Azure

1. **Acesse o portal do Azure** e crie um recurso de:
   - Azure Cognitive Search
   - Azure AI Document Intelligence
   - Azure Language Service

2. **Crie um novo índice de pesquisa**
   - Escolha um container (pode ser um Blob Storage com documentos PDF)
   - Habilite a extração de texto com IA (OCR + Análise de Texto)

3. **Adicione uma Skillset (conjunto de habilidades cognitivas)**
   - Habilidade: OCR
   - Habilidade: Extração de frases-chave
   - Habilidade: Análise de sentimento
   - Habilidade: Reconhecimento de entidades

4. **Execute o indexador** para que ele leia os documentos e crie um índice pesquisável

5. **Teste a busca**
   - Acesse o recurso de Cognitive Search
   - Use termos e observe os resultados com frases-chave, entidades e sentimentos destacados

---

## 📥 Documentos usados

Todos os testes foram feitos com um PDF contendo opiniões de clientes sobre um produto, disponível na pasta `/inputs`.

---

## 💡 Possibilidades de Uso

- Portais de busca interna em empresas  
- Automatização de leitura de contratos  
- Ferramentas de compliance e auditoria  
- Atendimento ao cliente com busca semântica em históricos

---

## 📚 O que aprendi

- Como usar IA para interpretar documentos automaticamente  
- A diferença entre análise de texto simples e enriquecimento cognitivo  
- A integração entre diferentes serviços do Azure: Fala, Linguagem, Pesquisa e Document Intelligence  
- A importância de documentar bem projetos no GitHub

---

📌 Projeto criado como parte do curso da **DIO.me** — _Impulsione seu portfólio com Azure!_
