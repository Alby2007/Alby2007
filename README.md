# Hi, I'm Alby

I'm a 19 year old self-taught developer from Essex, UK. I build AI systems, mostly in areas where the stakes actually matter: policing, financial markets, and cryptographic compliance. I don't have a CS degree. Everything here I figured out by building it.

---

## What I'm working on

**Constable AI** is probably the thing I'm most proud of right now. It's an AI-powered documentation platform for UK stop and search, built solo from scratch. It covers MG11, DASH domestic, S23 MDA and S60 CJPOA form types, has a 173-test suite, MOPI-compliant data retention, an offline PWA with a sync queue, and a supervisor audit trail with named acknowledgement gates. It's currently being evaluated by Metropolitan Police leadership. The goal is to sit in the same space as what Palantir built for law enforcement, but built specifically for UK policing procurement.

**Trading Galaxy** is an algorithmic trading intelligence platform I co-founded and built the technical side of. It runs a bot fleet across 535 tickers on 24 global markets, deployed on OCI. The knowledge base is the interesting part: it's an RDF triple store with confidence decay, source authority weighting, contradiction detection, and epistemic stress signals across six signal families. There's a full MCP interface so you can query the whole system in natural language. The KB architecture was deliberately modelled on how Palantir's Ontology layer works: typed entities, predicate vocabulary, causal edges, and adaptive retrieval under uncertainty. The public KB code lives in [Mem-Backend](https://github.com/Alby2007/Mem-Backend).

**Adamant Graph** is a cryptographic compliance platform I built to replace trust-based audit logs with mathematically verifiable evidence. 22 packages, 300+ tests, ZK proofs (PLONK/Groth16/STARK), TPM hardware attestation, Merkle-anchored evidence packages, and a semantic ontology covering 45+ regulatory frameworks including FCA AML/CTF, UK GDPR, SOC 2, HIPAA and PCI-DSS. There's also an AI copilot layer that converts natural language queries to SPARQL against the compliance graph.

**GBO-Project** is an AI safety research project on deceptive alignment. The core question was whether AI deception is strategic (agents learn to hide it) or habitual (it becomes internalised). I trained agents under varying oversight conditions using curriculum learning, then ran a 3x3 transfer test matrix. The headline result: strict oversight produced 0% lying even after agents were moved to weak oversight environments, suggesting the behaviour became habitual rather than strategic. Full findings in [DECEPTION_EXPERIMENT_FINAL_REPORT.md](https://github.com/Alby2007/GBO-Project/blob/main/DECEPTION_EXPERIMENT_FINAL_REPORT.md).

---

## Other things worth looking at

[PLTM-Claude](https://github.com/Alby2007/PLTM-Claude) gives Claude Desktop persistent memory across sessions: typed memory system, embedding-based semantic search, a 3-judge memory jury, and a real-time React dashboard. It got picked up independently by LobeHub and Glama without me submitting it anywhere.

[LLTM](https://github.com/Alby2007/LLTM) is memory architecture research. 99% accuracy on a 200-test conflict resolution benchmark, which is +32 percentage points over the Mem0 baseline. Jury-based conflict resolution, grammar-constrained judges, 3-stage pipeline.

[GovSecure Enclave](https://github.com/Alby2007/RW-RnD-GovSecure-Enclave-and-Audit-Fabric) is a multi-tenant sovereign compute platform built around AWS Nitro/SGX/SEV-SNP attestation, continuous compliance verification, and formal verification using TLA+. TypeScript, Circom ZK circuits, and Open Policy Agent for policy-as-code.

[Cognitive Physics Framework](https://github.com/Alby2007/cognitive-physics-framework) is a more speculative project: a formal framework for predicting when networks (brains, AI systems, social structures) will exhibit emergent intelligence, using a three-factor model across synchronisation, diversity, and memory.

---

## Stack

Python, TypeScript, React, FastAPI, Flask, PostgreSQL, SQLite, RDF/SPARQL, ZK circuits (Circom/PLONK/Groth16), OCI, Cloudflare, Railway, MCP

---

## Contact

Twitter/X: [@Alb20j](https://x.com/Alb20j)
