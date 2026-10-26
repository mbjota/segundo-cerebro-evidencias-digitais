# 🧠 Segundo Cérebro com IA: Cadeia de Custódia em Evidências Digitais

Projeto desenvolvido para o desafio de criação de um assistente de estudo personalizado utilizando o **Gemini Notebook** (antigo NotebookLM). O objetivo deste repositório é documentar a curadoria de fontes confiáveis, a diretriz de comportamento configurada e os testes de rastreabilidade realizados no caderno.

---

## 🎯 Tema e Objetivo

> **Objetivo Geral:** *Capacitar a consulta rápida, técnica e fundamentada sobre os procedimentos legais e práticos da cadeia de custódia e preservação de vestígios computacionais sob a legislação brasileira.*

---

## 📚 Fontes Selecionadas e Confiabilidade

As fontes inseridas no caderno foram selecionadas sob rigoroso critério de confiabilidade e cobrem múltiplos formatos:

| Formato | Fonte / Título | Justificativa de Confiabilidade |
|---|---|---|
| **Legislação (PDF)** | Lei Federal nº 13.964/2019 (Código de Processo Penal - Arts. 158-A a 158-F) | Canal legislativo oficial do Planalto, representando o marco legal obrigatório da cadeia de custódia no Brasil. |
| **Norma Técnica (PDF)** | Diretrizes da Norma ABNT NBR ISO/IEC 27037 | Padrão normativo reconhecido internacionalmente para tratamento de evidências digitais. |
| **Vídeo (YouTube)** | Aula Prática: Cálculo de Hash e Integridade Forense | Material técnico de especialista em segurança da informação demonstrando o uso prático de funções criptográficas. |

---

## ⚙️ Diretriz de Comportamento (Persona do Assistente)

Para garantir respostas precisas e estritamente atreladas às fontes, o Gemini Notebook foi configurado com a seguinte instrução:

> *"Atue como um Perito Criminal Especialista em Evidências Digitais e Procedimentos Investigativos. Suas respostas devem ser estritamente fundamentadas nas fontes fornecidas neste caderno. Sempre cite a lei, o artigo ou o minuto do vídeo de apoio. Caso o tema não conste nos documentos, responda honestamente que a informação está indisponível."*

---

## 🔍 Interação com as Fontes (Evidências de Rastreabilidade)

Aqui estão as perguntas-chave realizadas no chat do caderno e a comprovação de que as respostas foram extraídas diretamente dos materiais de apoio:

### ❓ Pergunta 1: Quais são as etapas oficiais que compõem a cadeia de custódia segundo a lei brasileira?
*   **Resposta obtida:** O assistente listou as 10 etapas legais obrigatórias: reconhecimento, isolamento, fixação, coleta, acondicionamento, transporte, recebimento, processamento, armazenamento e descarte.
*   **Fonte de origem:** Artigo 158-B do Código de Processo Penal (incluído via arquivo legislativo).
*   *Comprovação visual:* Arquivo salvo em `assets/print-chat-citacao-1.png` demonstrando a citação direta da lei.

### ❓ Pergunta 2: Como deve ser garantida a integridade de um arquivo digital coletado para fins periciais?
*   **Resposta obtida:** O assistente apontou a necessidade de gerar o valor de hash (como SHA-256) imediatamente após a coleta e realizar a cópia bit a bit.
*   **Fonte de origem:** Diretrizes do manual técnico de ISO 27037 e demonstração prática no minuto 12:45 do vídeo do YouTube.
*   *Comprovação visual:* Arquivo salvo em `assets/print-chat-citacao-2.png` exibindo os trechos de validação de integridade.

---

## 📦 Materiais de Estudo Gerados no Estúdio (Studio)

Os seguintes artefatos complementares foram exportados e estão salvos na pasta `/outputs` deste repositório para consulta:

*   **Guia de Estudos:** Roteiro prático com perguntas e respostas de fixação localizado em [`outputs/guia-de-estudos.md`](outputs/guia-de-estudos.md).
*   **Mapa Mental:** Representação gráfica das etapas da cadeia de custódia localizada em [`outputs/mapa-mental.png`](outputs/mapa-mental.png).
*   **Áudio de Síntese:** Resumo em áudio (formato podcast explicativo) em [`outputs/audio-overview-resumo.mp4`](outputs/audio-overview-resumo.mp4).
