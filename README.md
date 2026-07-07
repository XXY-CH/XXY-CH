<div align="center">

# CachoidXie

I build agent systems, memory scaffolds, and developer tools that leave evidence behind.

[Agnet](https://github.com/XXY-CH/Agnet) /
[Research DOI](https://doi.org/10.5281/zenodo.20041183) /
[Email](mailto:cachoidxx@gmail.com)

</div>

---

## Agnet

[Agnet](https://github.com/XXY-CH/Agnet) is the project I would point to first.

It is an accountability layer for agent work. The basic idea is simple: when an agent claims it opened a task, produced an artifact, or completed a step, that claim should leave a receipt another process can check.

The work is less about making agents look impressive in a transcript, and more about making their output auditable after the fact.

```text
claim -> receipt -> artifact manifest -> verifier -> boundary document
```

Current shape:

- signed task receipts and artifact manifests
- verifier paths for proof bundles instead of self-reported summaries
- local public-node proof flows with explicit reachability labels
- boundary documents that say what is proved, what is not, and what is still speculative
- a path from local proof to real cross-host verification

The parts I care about most are the boring ones: fail-closed checks, narrow claims, reproducible commands, and docs that keep the system honest.

---

## Other Work

| Project | What it is |
| --- | --- |
| [Aetherion](https://github.com/XXY-CH/Aetherion) | A local-first agent harness for permissions, memory, event logs, and governed tool use. |
| [CodeNexus](https://github.com/XXY-CH/CodeNexus) | An online judge for education: sandboxed execution, class data, teacher workflows, and code feedback. |
| [Anamnesis](https://github.com/XXY-CH/Anamnesis) | A long-context memory research scaffold around recurrence, residual attention, retrieval, and cheaper remembered evidence. |

---

## How I Work

- Build the smallest thing that can be run and argued about.
- Keep claims narrower than the evidence.
- Treat docs as part of the system, especially when they describe boundaries.
- Prefer a verifier over a pitch.
- Make failure modes visible early.

---

## Tools I Reach For

Rust, Go, TypeScript, Python, React, PostgreSQL, Redis, Docker, Linux.

The stack changes. The habit does not: make the system inspectable, then make it better.

---

## Contact

`cachoidxx@gmail.com`
