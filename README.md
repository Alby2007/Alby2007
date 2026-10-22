# Hi, I'm Alby

I'm a 19 year old self-taught developer from London, UK. Right now I'm building [Characterly](https://characterly.app/) — before that: algorithmic trading, cryptographic compliance, and AI safety research. I don't have a CS degree. Everything here I figured out by building it.

---

## What I'm working on

**[Characterly](https://characterly.app/)** is where most of my time goes now: a Discord companion and social-memory platform. Everyone awakens one permanent AI companion in 1:1 DMs; a marketplace layered on top lets people publish and adopt characters — standard character-card imports carry the history over, so a character you already have shows up remembering you. In servers, summoned companions reply under their own name and avatar via webhooks while the bot itself stays invisible plumbing. Memory and the relationship graph are inspectable and consent-gated. (Repo is private for now.)

**Trading Galaxy** is an algorithmic trading intelligence platform I co-founded and built the technical side of. It runs a bot fleet across 535 tickers on 24 global markets, deployed on OCI. The knowledge base is the interesting part: it's an RDF triple store with confidence decay, source authority weighting, contradiction detection, and epistemic stress signals across six signal families. There's a full MCP interface so you can query the whole system in natural language. The KB architecture was deliberately modelled on how Palantir's Ontology layer works: typed entities, predicate vocabulary, causal edges, and adaptive retrieval under uncertainty. The public KB code lives in [Mem-Backend](https://github.com/Alby2007/Mem-Backend).

---

## Other things worth looking at

[PLTM-Claude](https://github.com/Alby2007/PLTM-Claude-repost-) gives Claude Desktop persistent memory across sessions: typed memory system, embedding-based semantic search, a 3-judge memory jury, and a real-time React dashboard. It got picked up independently by LobeHub and Glama without me submitting it anywhere.

[BetaScan](https://github.com/Alby2007/BetaScan) (ImpactNet) is test-impact prediction research for TypeScript/Vitest repos: given a code change, which tests does it actually affect? The interesting result was nearly a negative one — a free, deterministic import-distance heuristic tied or beat a diff-reading LLM on the held-out trpc repo, even though the LLM had helped on the dev repo. Call edges add a modest increment over import edges; the LLM adds nothing cross-repo.

[NLSV1](https://github.com/Alby2007/NLSV1) is Neuralese — a constructed language designed for token-efficient LLM reasoning. The pipeline mines primitives from gemma-2-2b activations, structures them into a typed ontology, generates a grammar + type checker, translates CoT datasets, then LoRA fine-tunes and evaluates reasoning chain length against an English CoT baseline.

---

## Stack

Python, TypeScript, C#, React, FastAPI, Flask, PostgreSQL, SQLite, RDF/SPARQL, ZK circuits (Circom/PLONK/Groth16), OCI, Cloudflare, Railway, MCP, Discord API

---

## Contact

Site: [characterly.app](https://characterly.app/)
Twitter/X: [@Alb20j](https://x.com/Alb20j)
Email: [cybercatcatcher@proton.me](mailto:cybercatcatcher@proton.me)
