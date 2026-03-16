# Plan Education DIO — Projeto de Copiloto Técnico

Este repositório faz parte dos estudos da **Digital Innovation One (DIO)** e apresenta um experimento de **copiloto técnico orientado a planejamento (PLAN Mode)** para desenvolvimento de software.

A proposta do projeto é utilizar um assistente de IA atuando como um **copiloto de programação**, responsável por **planejar a implementação antes da escrita de código**, estruturando etapas, riscos, validações e organização do projeto.

## 🚀 Objetivo

Criar um fluxo de desenvolvimento mais seguro e previsível, onde cada funcionalidade passa primeiro por um **plano técnico revisável**, reduzindo retrabalho, erros de arquitetura e decisões improvisadas.

## 🧠 Conceito: Copiloto em modo PLAN

No modo PLAN, o assistente atua como um **arquiteto técnico**, focado em:

* definição de escopo
* planejamento incremental
* identificação de riscos
* organização de arquivos e estrutura do projeto
* estratégia de testes e validação

Antes de qualquer implementação, o sistema produz um **plano estruturado contendo:**

* objetivo da funcionalidade
* contexto e assunções
* escopo e limitações
* estratégia de implementação
* arquivos afetados
* plano passo a passo
* testes e validação
* riscos e mitigação

## 🛠️ Stack utilizada

O projeto assume como base principal:

* **Node.js**
* **TypeScript**
* **Express** (quando necessário para APIs)
* **Jest / Vitest** para testes
* **ESLint** para padronização de código
* **Prettier** para formatação

Gerenciadores de pacotes suportados:

* npm
* yarn
* pnpm

A stack pode ser adaptada dependendo do contexto do projeto.

## 🎯 Benefícios da abordagem

* desenvolvimento mais organizado
* melhor previsibilidade técnica
* redução de bugs estruturais
* documentação automática do raciocínio de implementação
* maior clareza para colaboração em equipe

## 📚 Contexto educacional

Este projeto foi criado como parte do aprendizado em engenharia de software e uso de **IA como ferramenta de apoio ao desenvolvimento**, explorando práticas de:

* planejamento técnico
* arquitetura incremental
* engenharia de prompts
* integração entre IA e fluxo de desenvolvimento

## 📌 Status do projeto

Projeto em evolução, sendo utilizado para testes de fluxo de planejamento e melhoria contínua da metodologia **PLAN-first development**.

---

💡 *Ideia central:*
Antes de escrever código, **planeje como um arquiteto. Depois implemente como um engenheiro.**
