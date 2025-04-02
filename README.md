# FLUID Dev Rule
Cursor, Cline and Windsurf rules files to help you follow the FLUID principles.

FLUID is a new way to think about AI-assited dev as per my blog post https://aibuddy.software/mutable-by-design-the-fluid-software-philosophy/

FLUID's goal is to fork from the days of SOLID and embrace mutability in code rather than artifact preservation. 

*These rules where by:* https://gist.githubusercontent.com/ruvnet/7d4e1d5c9233ab0a1d2a66bf5ec3e58f/raw/923916fa92cd225c3d5eeec12a184a4a2a2462ff/.cursorules.txt

# FLUID Principles

F – Flexible Composition
Design in loosely coupled, swappable parts. Think composability over inheritance, simple functions over deep hierarchies. Anything that helps AI (or you) reshape it later.

L – Live Prototypes
Work live. Build in hot environments — REPLs, notebooks, dev servers — to explore ideas and tighten your feedback loop. But don’t stop there: snapshot working prototypes and harden them through tests, CI, and version control. FLUID doesn’t mean skipping rigor — it means deferring it until you’ve found something worth solidifying.

U – Unified Context
Code with context. Focus on reducing ambiguity — your future self, teammates, and AI assistants will all benefit. Think less about documentation and more about supplying the system with meaningful, actionable information.

I – Intent-Driven Structure
Don’t just write for form, write for collaboration. Give functions, files, and variables meaningful names, but remember — the AI is reading too. Use comments to convey intent clearly, not just style. Prioritize clarity of why so the system — human and machine — stays in sync.

D – Dynamic Refactorability
Expect change. Encourage it. Make code easy to mutate, regenerate, and improve. Let the AI reshape your logic, reroll your structures, and keep the system flowing.
