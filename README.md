<p align="center">
  <img src="docs/banner.svg" alt="SLA / SLO Templates banner" width="100%" />
</p>

<h1 align="center">sla-slo-templates</h1>

<p align="center">
  <strong>EN</strong> Templates for Service Level Agreements and Objectives<br/>
  <strong>PT</strong> Templates para Acordos e Objetivos de Nível de Serviço
</p>

<p align="center">
  <a href="https://github.com/manansbdb/sla-slo-templates/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/SRE-8b5cf6?style=for-the-badge" alt="SRE" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Templates for Service Level Agreements and Objectives. | Templates para Acordos e Objetivos de Nível de Serviço. |
| Free templates/checklists you copy into your own docs — no paid services. | Templates/checklists gratuitos para copiares — sem serviços pagos. |

```mermaid
flowchart LR
  A["🎯 SLO"] --> B["📜 SLA"]
  A --> C["📉 Error budget"]
  B --> D["🤝 Customer promise"]
  C --> E["🧭 Release / pause"]
  style A fill:#8b5cf6,stroke:#6d28d9,color:#fff
  style B fill:#3b82f6,stroke:#1d4ed8,color:#fff
  style C fill:#f59e0b,stroke:#b45309,color:#fff
  style D fill:#0ea5e9,stroke:#0369a1,color:#fff
  style E fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/sla-slo-templates.git
cd sla-slo-templates
```

### 2) Copy templates / Copia os templates

```bash
cp templates/SLO.md /path/to/your-docs/SLO.md
cp templates/SLA.md /path/to/your-docs/SLA.md
cp templates/error-budget.md /path/to/your-docs/error-budget.md
```

### Requirements / Requisitos

- `git`
- No runtime dependencies

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/sla-slo-templates.git
cd sla-slo-templates
cp templates/SLO.md ./SLO.md
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `templates/SLO.md` | SLO definition / Definição de SLO |
| `templates/SLA.md` | Customer-facing SLA / SLA para clientes |
| `templates/error-budget.md` | Error budget policy / Política de error budget |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
sla-slo-templates/
├── docs/banner.svg
├── templates/SLO.md
├── templates/SLA.md
├── templates/error-budget.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
