# 📊 Data Governance & Cloud Foundations

![Governance](https://img.shields.io/badge/Governance-Data%20Life%20Cycle-blue) ![Compliance](https://img.shields.io/badge/Compliance-LGPD%20%7C%20GDPR-green) ![Cloud](https://img.shields.io/badge/Cloud-AWS%20Foundations-orange)

## 📌 Visão Geral / Overview

**PT-BR:** Este repositório documenta um projeto prático de **Governança de Dados** aplicada a ambientes Cloud e Infraestrutura. O projeto simula cenários reais de empresas e startups, unindo conformidade legal (LGPD/GDPR) com segurança técnica.

**EN:** *This repository documents a practical Data Governance project applied to Cloud and Infrastructure environments. It simulates real-world startup scenarios, merging legal compliance (LGPD/GDPR) with technical security.*

---

## 🎯 Objetivos do Projeto / Project Goals

* **Inventário Estruturado:** Criação de mapeamento de dados com classificação de sensibilidade.
* **Papéis e Responsabilidades:** Definição de *Data Owners, Stewards e Admins*.
* **Data Lifecycle:** Modelagem do ciclo de vida do dado (do nascimento ao descarte).
* **Compliance Framework:** Aplicação de checklists práticos de LGPD e GDPR.
* **Risk Mitigation:** Demonstração de como a governança resolve problemas reais de vazamento e acesso indevido.

---

## 🏗️ Estrutura do Repositório / Repository Structure

```text
data-governance-cloud-foundations/
├── 01-inventario-dados/          # Classificação, riscos e papéis (Owners/Stewards)
├── 02-fluxo-dados/               # Mapeamento do ciclo de vida (Data Flow)
├── 03-politicas-governanca/      # Políticas de acesso e classificação
├── 04-compliance-lgpd-gdpr/      # Checklists de conformidade legal
└── 05-caso-real-simulado/        # Resolução de problema real de empresa (Business Case)
```
---

## 🧠 Conceitos Trabalhados / Core Concepts

* **Data Classification:** Público, Interno, Confidencial e Sensível.
* **Princípio do Menor Privilégio:** Controle de acesso baseado na necessidade de conhecimento.
* **Integrity & Availability:** Garantia de que o dado esteja seguro e disponível.
* **Cloud Integration:** Governança aplicada diretamente à infraestrutura escalável.

---

## 🛠️ Ferramentas Utilizadas / Tech Stack

* **Documentation:** Markdown / Google Docs
* **Diagrams:** Draw.io (Fluxos de dados e Arquitetura)
* **Organization:** Google Sheets (Inventário e Matriz de Riscos)
* **Version Control:** GitHub

---

## 🧪 Caso Real Simulado / Real-World Case Study

O projeto foca em uma empresa fictícia que coleta dados via web e armazena em nuvem. A governança é aplicada para:

1.  **Mapear** responsáveis por cada bucket/banco de dados.
2.  **Definir** políticas de retenção para evitar custos desnecessários e riscos legais.
3.  **Garantir** que apenas perfis autorizados acessem dados sensíveis.

👉 **Veja os detalhes na pasta:** `[05-caso-real-simulado/]`

---

## 🚀 Próximos Passos / Roadmap

- [ ] Integrar logs de auditoria (AWS CloudWatch/CloudTrail).
- [ ] Implementar automação de backup com políticas de retenção via código.
