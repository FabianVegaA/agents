# Software Designer Agents

This agent framework implements a **software design framework based on three complementary perspectives**, inspired by the WRSPM (World, Requirements, Specification, Program, Machine) model. The theoretical foundation combines **philosophy** (domain ontology and semantics), **mathematics** (types, invariants, and formal correctness), and **engineering** (practical feasibility and maintainability).

Each agent applies specific, empirically proven reasoning methodologies: the **Philosopher** uses VT (Visi&on), Abduction, KADS, and Means-Ends to establish conceptual clarity; the **Mathematician** employs CSP, Natural Deduction, Tableaux, and Hoare Logic to validate formal properties; the **Engineer** applies CBR, AHP, TRIZ, and Six Thinking Hats to assess practical feasibility. The **Software-Designer** orchestrates the sequence, acts as referee in conflicts, and synthesizes recommendations.

The framework incorporates **strict validation** through mandatory checklists, **traceability** via reasoning flow reports stored as markdown files, and **conflict resolution** using TRIZ principles and PMI analysis. All of this with a **language-agnostic** design that produces lightweight design documents (ADR + Design Doc) applicable to any tech stack with an expressive type system.

## Config

### Opencode

```
mkdir ~/.config/opencode/agents/
cd ~/.config/opencode/agents/
git clone git@github.com:FabianVegaA/agents.git
```
