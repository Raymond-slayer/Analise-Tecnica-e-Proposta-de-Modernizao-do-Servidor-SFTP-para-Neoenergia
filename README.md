# Análise Técnica e Proposta de Modernização do Servidor SFTP para Neoenergia

Este repositório documenta um projeto de consultoria realizado para a **Neoenergia**, uma empresa privada do setor elétrico brasileiro.

---

## 🎯 Objetivo do Projeto

Proporcionar uma experiência prática de consultoria em tecnologia, abordando a análise, avaliação e proposta de modernização de um servidor utilizado para transferência segura de arquivos (SFTP). O foco está na aplicação de conhecimentos da disciplina de **Arquitetura de Computadores**.

---

## 👥 Membros da Equipe

- Integrante 1  
- Integrante 2  
- Integrante 3  
- Integrante 4
  
---

## 🧩 Descritivo da Consultoria

A consultoria teve como escopo a análise técnica do servidor `bmep967.neoenergia.net`, utilizado pela Neoenergia para operações críticas via **SFTP (Secure File Transfer Protocol)**.

### 🔧 Especificações Técnicas:

- **Sistema Operacional:** UNIX  
- **Processador:** Intel Xeon (x64)  
- **Memória RAM:** 32GB DDR4  
- **Armazenamento:** HD de 500GB (~468GB utilizáveis)

### 📊 Resultados da Análise:

#### • CPU:
- Utilização média baixa (~30% em pico)
- Atividade mais intensa em horário comercial
- **Status:** Normal

#### • Memória:
- Uso de ~90% das páginas de memória
- ~10% de memória real disponível para aplicações
- **Status:** Normal (com necessidade de monitoramento)

#### • Disco (HD):
- Uso de 95.5% (~447GB usados)
- Apenas ~20,5GB (~4,5%) disponíveis
- **Status:** Em risco crítico

---

## ⚠️ Problema Identificado

O **HD do servidor encontra-se em estado crítico de ocupação**, o que pode levar a falhas de upload, indisponibilidade do serviço SFTP, perda de logs e possíveis travamentos.

---

## ✅ Soluções Propostas

### 🔹 1. **Implementação de SSD NVME M.2 (1TB)**
- Armazenamento rápido e confiável
- SSD para aplicação SFTP; HD mantido para o sistema
- Custo estimado: R$ 600 a R$ 900 (único)

### 🔹 2. **Migração para Armazenamento em Nuvem**
- Uso de Azure, Google Cloud ou AWS S3
- Alta escalabilidade, disponibilidade e automação
- Custo estimado mensal: R$ 1300 a R$ 1400

### 🔹 3. **Modelo Híbrido (Local + Nuvem)**
- Dados recentes no HD/SSD local; backups na nuvem
- Ferramentas como Rclone ou S3FS para integração
- Custo estimado mensal: R$ 700 a R$ 1200

**📌 Recomendação Final:** Adoção do **Modelo Híbrido**, combinando desempenho local com escalabilidade e segurança da nuvem.

---

## 📁 Entregáveis do Projeto

- **Mapa Mental:** *[Disponível em breve]*  
- **Podcast:** *[Disponível em breve]*  
- **Quiz Interativo:** *[Disponível em breve]*

---

## 📝 Feedback do Cliente

> *Feedback pendente.*

---

Este `README.md` atende aos critérios da disciplina para a **Tarefa 1 – Repositório GitHub**, incluindo: objetivo, descrição técnica, entregáveis, equipe e proposta de solução com análise crítica.
