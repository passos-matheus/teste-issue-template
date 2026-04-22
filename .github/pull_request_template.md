<!--
🇧🇷 Use este PR para adicionar `./participants/<seu-usuario>.json`. Em PRs de doc/engine/infra, apague o checklist.
🇺🇸 Use this PR to add `./participants/<your-username>.json`. For docs/engine/infra PRs, delete the checklist.
-->

## Descrição / Description

<!-- 🇧🇷 O que esse PR faz? / 🇺🇸 What does this PR do? -->

## Checklist da submissão / Submission checklist

- [ ] **1 CPU + 350MB RAM** no total entre os serviços / total across services
- [ ] Backend na **porta / port 9999**
- [ ] Imagens / images **linux/amd64**
- [ ] Rede / network **bridge** (sem `host`, sem `privileged` / no `host`, no `privileged`)
- [ ] **≥ 1 load balancer + 2 APIs**, LB sem lógica de aplicação (lei Gabriel-2025) / LB with no app logic (Gabriel-2025 law)
- [ ] Repo **público / public** com branches `main` + `submission`
- [ ] `submission` tem / has `docker-compose.yml` na raiz / at root + `info.json`

