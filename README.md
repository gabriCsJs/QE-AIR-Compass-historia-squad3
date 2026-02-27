# Fase 2 – Atividade em Squad
## Prática de Git, Branches e Merge (Simulação com Git Flow)

### 📌 Objetivo
Esta atividade foi desenvolvida com o objetivo de praticar, em equipe, os principais conceitos de versionamento utilizando **Git**, incluindo:

* **Criação de branches**
* **Commits organizados**
* **Merge entre branches**
* **Resolução de conflitos**
* **Simulação do fluxo Git Flow (manual)**

A proposta consistiu na construção colaborativa de uma história fictícia, onde cada integrante contribuiu com uma parte do texto em uma branch separada, promovendo integração progressiva via `develop` até a consolidação final.

---

### 👥 Integrantes do Squad
* Arlen
* Leticia
* João
* Gabriel

---

### 🧠 Contexto da Atividade
Foi criada uma narrativa intitulada:  
> **“Um dia na vida de um QA em produção”**

A história simula o ciclo real de um incidente em ambiente produtivo, passando por:
1. **Descoberta do bug**
2. **Investigação técnica**
3. **Comunicação e validação da correção**
4. **Prevenção e melhoria contínua**

Cada integrante ficou responsável por uma etapa da narrativa, desenvolvida em sua própria branch.

---

### 🌿 Estrutura de Branches
O fluxo utilizado seguiu a seguinte hierarquia:

```text
main
└── develop
    ├── feature/arlen-story
    ├── feature/gabriel-story
    ├── feature/joao-story
    └── feature/leticia-story
```
---

### Estratégia aplicada:

A branch develop foi utilizada como ponto de integração.

Cada integrante criou sua feature branch a partir de develop.

Após finalizar sua parte da história, realizou merge para develop.

Conflitos (quando existentes) foram resolvidos manualmente.

Ao final, foi simulado o processo de integração para main.

---

### 🔁 Fluxo de Trabalho Utilizado
Criação da branch develop.

Criação de branches individuais para cada parte da história.

Commits organizados seguindo padrão descritivo.

Merge progressivo das features em develop.

Simulação de merge final para main.

Exercício de revert e correção de merge indevido (aprendizado prático).

---

### 🧪 Conceitos Praticados
Versionamento colaborativo.

Organização de histórico de commits.

Boas práticas de nomenclatura de branches.

Resolução de conflitos de merge.

Diferença entre merge, rebase e revert.

Importância da branch develop como ambiente de integração.

Governança da branch main.

---

### 📂 Arquivo Principal
story.txt: Contém a narrativa construída colaborativamente pelo squad.

---

### 🎯 Aprendizados da Atividade
A integração frequente reduz conflitos complexos.

Feature branches não devem depender diretamente umas das outras.

A branch develop centraliza o trabalho colaborativo.

Erros de merge fazem parte do processo e reforçam o entendimento do fluxo.

O versionamento é uma ferramenta de organização e rastreabilidade, não apenas de armazenamento de código.

---

###📎 Conclusão
A atividade permitiu simular um fluxo de trabalho próximo ao ambiente profissional, reforçando práticas essenciais de colaboração em equipe e controle de versões.