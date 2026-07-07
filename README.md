<div align="center">

# CachoidXie

I build agent systems that leave receipts.

[Agnet](https://github.com/XXY-CH/Agnet) ·
[Research DOI](https://doi.org/10.5281/zenodo.20041183) ·
[Email](mailto:cachoidxx@gmail.com)

</div>

---

## The work I would show first

**Agnet** is my strongest current project: a local-first accountability layer
for agent work.

I do not want agents that merely sound certain in a transcript. I want systems
where a later verifier can answer harder questions:

- what was requested
- who accepted the work
- what policy and approval evidence applied
- which artifacts were produced
- which receipt, digest, and audit entry anchor the claim
- what the system explicitly does not prove yet

Agnet is the proof layer around those questions. It signs task openings,
receipts, artifact manifests, proof bundles, sandbox claims, queue actions, and
audit trails, then keeps the boundaries narrow enough for another process to
check.

```text
claim -> receipt -> artifact manifest -> verifier -> boundary document
```

Current status: research prototype, local-first, v12 active. It is not a
production agent network, scheduler, economic layer, or container-isolated
runtime. That boundary is deliberate: the point is to make evidence legible
before making the system bigger.

[Read Agnet](https://github.com/XXY-CH/Agnet)

---

## What I keep optimizing for

I like systems where the boring parts are first-class:

- fail closed when evidence is missing
- make claims smaller than the proof
- prefer verifiers over summaries
- keep manifests close to the bytes they describe
- write boundary docs before the demo starts lying

Most of my work sits somewhere between agent runtimes, memory, developer tools,
and verification. The stack changes; the habit does not.

---

## Other work

| Project | Shape |
| --- | --- |
| [Aetherion](https://github.com/XXY-CH/Aetherion) | Local-first agent harness for permissions, memory, event logs, and governed tool use. |
| [CodeNexus](https://github.com/XXY-CH/CodeNexus) | Online judge for education, sandboxed execution, teacher workflows, and code feedback. |
| [Anamnesis](https://github.com/XXY-CH/Anamnesis) | Long-context memory scaffold around recurrence, retrieval, and cheaper remembered evidence. |

---

## Tools

Go, Rust, TypeScript, Python, React, PostgreSQL, Redis, Docker, Linux.

I reach for whatever makes the system easier to inspect.

---

`cachoidxx@gmail.com`
