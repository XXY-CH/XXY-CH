<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:090d16,45:1e3a8a,100:06b6d4&text=CachoidXie&fontColor=ffffff&fontSize=48&fontAlignY=40&desc=Systems%20%E2%97%86%20AI%20Memory%20%E2%97%86%20Research%20Engineering&descAlignY=62&descSize=16&descFontColor=a5f3fc" alt="CachoidXie banner" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2500&pause=1000&color=06B6D4&center=true&vCenter=true&width=900&lines=Fortis+Fortuna+Adiuvat.;Building+AI-native+systems+from+first+principles.;Long-context+memory%2C+online+judge%2C+agent+infrastructure.;Research+ideas+should+compile%2C+run%2C+and+survive+tests.)](https://git.io/typing-svg)

[![Profile Views](https://komarev.com/ghpvc/?username=XXY-CH&style=flat-square&color=06b6d4&label=profile%20views)](https://github.com/XXY-CH)
[![GitHub Followers](https://img.shields.io/github/followers/XXY-CH?style=flat-square&logo=github&color=0ea5e9&labelColor=0f172a)](https://github.com/XXY-CH?tab=followers)
[![Research DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20041183-2563eb?style=flat-square&labelColor=0f172a)](https://doi.org/10.5281/zenodo.20041183)
[![Email](https://img.shields.io/badge/email-cachoidxx%40gmail.com-0f172a?style=flat-square&logo=gmail&logoColor=white&labelColor=0f172a)](mailto:cachoidxx@gmail.com)

</div>

---

## 🧠 About Me

> **I build research-shaped systems**: online judges that understand teaching data, AI-agent infrastructure that can inspect and improve code, and memory-centric modeling experiments that try to make long-context reasoning cheaper, sharper, and more auditable.
> 
> My favorite work lives at the boundary where a mathematical claim has to become a running system: proofs, tests, architecture diagrams, telemetry, and a repository that another engineer can actually clone, compile, and reproduce.

---

## 🎯 Core Research Lanes

| Lane | Initiative & System Scope | Active Repository |
| :--- | :--- | :--- |
| **🧠 Long-Context AI** | RetNet-style retention, Engram lookup, Block Attention Residuals, milestone snapshots | [`engram-retention`](https://github.com/XXY-CH/engram-retention) |
| **🎓 AI Education** | Online judge platform for school teaching, evaluation, and AI-assisted governance | [`CodeNexus`](https://github.com/XXY-CH/CodeNexus) |
| **🔄 Agent Memory** | Systems where agents learn, forget, route, and self-improve over time | [`dna-memory`](https://github.com/XXY-CH/dna-memory) / [`evolver`](https://github.com/XXY-CH/evolver) / [`mindx`](https://github.com/XXY-CH/mindx) |
| **👥 Multi-Agent** | Interactive classrooms and coordination surfaces for AI-assisted learning | [`OpenMAIC`](https://github.com/XXY-CH/OpenMAIC) |
| **📡 Edge & Signals** | WiFi sensing, inference pipelines, and non-visual perception systems | [`RuView`](https://github.com/XXY-CH/RuView) |

---

## 💡 Featured Repositories

<div align="center">
  <table width="100%">
    <tr>
      <td width="50%" valign="top" style="border: 1px solid #1e293b; border-radius: 8px; padding: 16px; background-color: #0b0f19;">
        <div align="left">
          <img src="https://img.shields.io/badge/Research-Scaffold-06b6d4?style=flat-square" alt="Research Scaffold" />
          <h3>💡 <a href="https://github.com/XXY-CH/engram-retention" style="text-decoration: none; color: #38bdf8;">Engram Retention</a></h3>
          <p style="color: #94a3b8; font-size: 14px; line-height: 1.5;">PyTorch research scaffold for budgeted long-context memory: RetNet recurrence, hashed Engram lookup, Block Attention Residuals, and milestone snapshots.</p>
          <p style="margin-top: 12px;">
            <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
            <img src="https://img.shields.io/badge/PyTorch-ee4c2c?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
            <img src="https://img.shields.io/badge/Deep_Learning-06b6d4?style=flat-square" alt="DL" />
          </p>
        </div>
      </td>
      <td width="50%" valign="top" style="border: 1px solid #1e293b; border-radius: 8px; padding: 16px; background-color: #0b0f19;">
        <div align="left">
          <img src="https://img.shields.io/badge/AI--Native-Platform-2563eb?style=flat-square" alt="AI-Native Platform" />
          <h3>🚀 <a href="https://github.com/XXY-CH/CodeNexus" style="text-decoration: none; color: #38bdf8;">CodeNexus</a></h3>
          <p style="color: #94a3b8; font-size: 14px; line-height: 1.5;">An AI-native online judge platform designed for school teaching, judging, integrity workflows, and educational data intelligence.</p>
          <p style="margin-top: 12px;">
            <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
            <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
            <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
          </p>
        </div>
      </td>
    </tr>
  </table>
</div>

---

## 🗺️ System Map

```mermaid
graph TB
    %% Styling Definitions
    classDef research fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#f8fafc;
    classDef systems fill:#0f172a,stroke:#2563eb,stroke-width:2px,color:#f8fafc;
    classDef core fill:#090d16,stroke:#06b6d4,stroke-width:3px,color:#06b6d4,font-weight:bold;
    
    subgraph Research_Loop ["The Research & Formalization Loop"]
        A["Research Questions"]:::research --> B["Formal Assumptions"]:::research
        B --> C["Executable Prototypes"]:::core
        C --> D["Rigorous Tests & Ablations"]:::research
        D --> E["Docs & Proof Trail"]:::research
        E --> B
    end

    subgraph Applied_Systems ["Applied Systems Engineering"]
        C --> F["CodeNexus <br> (AI Education & OJ)"]:::systems
        C --> G["DNA-Memory / Evolver <br> (Agent Memory Scaffolds)"]:::systems
        C --> H["Engram-Retention <br> (Long-Context Models)"]:::systems
        C --> I["RuView <br> (WiFi Sensing & Edge)"]:::systems
    end

    %% Adjust layouts/spacing
    style Research_Loop fill:#070a13,stroke:#1e293b,stroke-width:1px,color:#94a3b8
    style Applied_Systems fill:#070a13,stroke:#1e293b,stroke-width:1px,color:#94a3b8
```

---

## 🛠️ The System & Research Stack

<div align="center">

| Layer | Technologies & Frameworks |
| :--- | :--- |
| **🚀 Core Systems & Languages** | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| **🧠 Deep Learning & AI Research** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Neural Retention](https://img.shields.io/badge/Memory--Centric-Models-06b6d4?style=flat-square) ![Agent Scaffolds](https://img.shields.io/badge/Agent-Scaffolds-2563eb?style=flat-square) |
| **💾 Infrastructure & Pipelines** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

</div>

---

## 📐 Engineering Taste & Axioms

> *"Simplicity is a prerequisite for reliability."* — Edsger W. Dijkstra

*   **Executable First**: Start with the actual running system, not a slogan or an empty abstraction.
*   **Ablated & Proven**: Keep claims narrow and humble until comprehensive tests and rigorous ablations make them stronger.
*   **Falsifiable Architectures**: Design architectures that can be actively inspected, systematically reproduced, and disproven.
*   **Evidence-Centric AI**: Build AI features around solid empirical evidence, auditability, and governance workflows, not just chat wrappers.
*   **Documentation as Code**: Treat system documentation and formal proof trails as core components, never as packaging after the fact.

---

## 📊 System Telemetry & Signal

```yaml
host: XXY-CH@github
status: active
repositories: 19 public
focus_areas: [Engram Retention, CodeNexus, OpenMAIC, RuView]

[Languages by Repo Count]
JavaScript  ████████████████ 4
C++         ████████████ 3
Python      ████████████ 3
Rust        ████████████ 3
TypeScript  ████████████ 3
Go          ████ 1
```

| Domain | Center of Gravity | Description |
| :--- | :--- | :--- |
| **🧠 Research Code** | `engram-retention` | Keeps proofs, configs, tests, and citation metadata unified in a single reproducible PyTorch scaffold. |
| **⚙️ Systems Code** | `CodeNexus` | Pushes AI-native online judging from simple sandbox testing to real-world educational workflows. |
| **🔄 Agent Scaffolds** | `dna-memory` / `evolver` | Explore the practical bounds of adaptive memory, routing, and self-evolution. |
| **🌐 Interface Surfaces** | `OpenMAIC` | Experiments with multi-agent orchestration and coordination spaces. |

> [!NOTE]
> This telemetry panel is rendered statically to prevent dynamic API outages (e.g., 503 errors from external README card services) and maintain optimal loading performance.

---

## 📬 Contact & Connection

*   **Email**: [cachoidxx@gmail.com](mailto:cachoidxx@gmail.com)
*   **GitHub Profile**: [github.com/XXY-CH](https://github.com/XXY-CH)

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:06b6d4,50:1e3a8a,100:090d16" alt="footer" />

</div>
