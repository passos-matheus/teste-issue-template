<!--
🇧🇷 Português | 🇺🇸 English

Use este PR para adicionar seu arquivo em `./participants/<seu-usuario-github>.json` e registrar sua submissão.
Para PRs de documentação, engine ou infra, o checklist abaixo não se aplica — pode apagar a seção.

Use this PR to add your file to `./participants/<your-github-username>.json` and register your submission.
For docs, engine or infra PRs, the checklist below does not apply — feel free to delete the section.
-->

## 🇧🇷 Descrição / 🇺🇸 Description

<!-- 🇧🇷 O que esse PR faz? / 🇺🇸 What does this PR do? -->

---

## ✅ Checagem obrigatória da submissão / Submission checklist

### 🇧🇷 Português

**Recursos e rede**
- [ ] Minha submissão respeita o limite de **1 unidade de CPU** e **350MB de memória**, somando todos os serviços declarados no `docker-compose.yml`.
- [ ] Meu backend escuta na **porta 9999**.
- [ ] As imagens utilizadas são compatíveis com **linux/amd64**.
- [ ] O modo de rede está como **bridge** (o modo `host` não é permitido).
- [ ] Nenhum serviço está em modo **privileged**.

**Topologia**
- [ ] Tenho **pelo menos um load balancer** e **duas instâncias de API**.
- [ ] Meu load-balancer passou na lei Gabriel-2025: não tem lógica de aplicação nem responde pelas APIs (sem `~smart~ load balancing`).

**Repositório**
- [ ] Meu repositório é **público**.
- [ ] Tenho a branch `main` com o código-fonte e a branch `submission` com os arquivos de execução.
- [ ] A branch `submission` tem o `docker-compose.yml` na **raiz**.
- [ ] A branch `submission` tem um `info.json` preenchido.

### 🇺🇸 English

**Resources and network**
- [ ] My submission respects the limit of **1 CPU unit** and **350MB of memory**, across all services declared in `docker-compose.yml`.
- [ ] My backend listens on **port 9999**.
- [ ] The images used are compatible with **linux/amd64**.
- [ ] Network mode is set to **bridge** (`host` mode is not allowed).
- [ ] No service runs in **privileged** mode.

**Topology**
- [ ] I have **at least one load balancer** and **two API instances**.
- [ ] My load balancer complies with the Gabriel-2025 law: no application logic and it does not respond on behalf of the APIs (no `~smart~ load balancing`).

**Repository**
- [ ] My repository is **public**.
- [ ] I have a `main` branch with the source code and a `submission` branch with the execution files.
- [ ] The `submission` branch has `docker-compose.yml` at the **root**.
- [ ] The `submission` branch has a filled-in `info.json`.

---

🚀 🇧🇷 Seja feliz! / 🇺🇸 Have fun!
