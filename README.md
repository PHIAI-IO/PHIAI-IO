# Φ  Phi AI

**Agentic systems that run real commercial operations — and the discipline to verify their numbers.**

Most AI work stops at *it responds*. The harder question is whether what it says is **true**.
Everything here is built for that second half.

---

### What lives here

**[mcp-comex-brasil](https://github.com/PHIAI-IO/mcp-comex-brasil)** — MCP server for Brazilian
foreign-trade data. The official dataset has a defect no documentation warns about: filter by
air transport and only 24% of what comes back actually passed through an airport. Most of the
rest cleared at *seaports* and is fertiliser. Uncorrected, air weight inflates 4.1× and freight
per kilo drops 70% — silently. This server applies the
correction and returns the evidence for why it was needed.

*Four tools that don't lie, instead of forty that don't know.*

---

### The method

Three rules that show up in every repository here:

**Primary sources over summaries.** Customs microdata, not trade-press figures. If a number
can be recomputed from the original records, it is.

**Verify the dataset before trusting it.** Fields lie. A tool that confidently serves a wrong
number is worse than no tool at all — it launders the error through an agent that has no way
to know.

**Declare the limits.** What a dataset *cannot* answer is part of the answer. Every output says
what it does not cover.

---

### Who

Built by **Luis Delfin** — Market Intelligence Lead at JOTA Switzerland Brasil, where these
ideas run in production: an ERP-integrated commercial OS with agents used daily by a B2B sales
force, and the reporting pipeline behind it.

Twenty months before that, warehouse floor. The method is not academic.

[phiai.io](https://phiai.io) · [LinkedIn](https://www.linkedin.com/in/luis-delfin/)

---
---

<h3>Português</h3>

**Sistemas agênticos que operam negócios de verdade — e o rigor de verificar os números que eles produzem.**

A maior parte do trabalho com IA para em *"respondeu"*. A pergunta difícil é se o que ele diz é
**verdade**. O que está aqui foi construído para essa segunda metade.

**[mcp-comex-brasil](https://github.com/PHIAI-IO/mcp-comex-brasil)** — servidor MCP de comércio
exterior do Brasil. A base oficial tem um defeito que nenhuma documentação avisa: filtrar pelo
modal aéreo devolve carga em que apenas 24% passou de fato por um aeroporto — a maior parte do
resto despachou em **portos** e é fertilizante. Sem corrigir, o peso aéreo infla 4,1× e o frete
por quilo cai 70% — em silêncio. Este servidor aplica a correção
e devolve a evidência de por que ela era necessária.

**As três regras:** fonte primária em vez de resumo publicado · verificar se o campo diz o que
parece dizer, antes de confiar · declarar o que o dado **não** responde, porque isso também é
resposta.
