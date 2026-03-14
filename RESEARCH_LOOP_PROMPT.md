Read book outline from docs/book-outline.md
Read TOC docs/table-of-contents.md
Read ./agents.md for available agents
Read book chapter tracker from docs/chapter_tracker.md
Read scratchpad.md

The goal of this project is to write the book "Acceleralpho: Evolution of coding agents and agentic harnesses". It must be beginner-friendly, but also the absolutely cutting edge of the modern production-grade quality research into plate and mante models and other earth systems. Intuition and philosophy must come always first, the explanations must be intuitive and introduce concepts gradually without overload.

Pick ONE item to improve in book and work on it.

IMPORTANT:
- work only on ONE improvement
- if code needs to be run - it must be done in ./src directory; it should never be added to commits
- follow book style guidance docs/book_style.md
- each chapter must be building each piece in logical progression (no "we'll come back to it later"), must have deliverable and verification. This is hands-on engineering first book. 
- Explain intuition behind every formula when it is introduced the first time.
- Prefer mermaid diagrams for flowcharts and block diagrams
- verify code examples are functional and produce documented output that is aligned with intention
- focus only on production-grade 2026 edition only
- perform necessary research, web search as needed - use available agents to do it
- Use LaTEX format for formulas when needed
- Add a short How to read this chapter box at the top of each math-heavy chapter, tell the reader what to understand now, what to memorize, and what is reference material
- Break dense theory into repeated loops: concept -> worked numeric example -> code -> check-yourself prompt; 3-6 concept loops with a mini worked example in a chapter
- Use O’Reilly-style Tip / Warning / Sidebar blocks for traps instead of burying them in prose
- Title key equations and key code blocks. You already title figures and tables; do the same for the math and main code examples. “Equation 5-1. Some Math Problem” and “Example 4-1. How s works” are much easier to revisit than anonymous blocks.
- Promote retrieval practice at chapter ends. The repeated Updated File Layout + Verification Checklist + What We Built.  Include Wrapping Up / Further Reading / Exercises, optional build-verification appendix.
- chapters ouput must be written in the format: `docs/part1/1.1 Your First Rust Program.md`
- Update scratchpad.md to add/remove/modify action items and information relevant for next iteration of this work, organize work items by part/chapter
- Update docs/chapter_tracker.md to track current implementation status; if file exists, make it a link in the tracking table
- Update docs/references.md with the list of resources used to build materials
- after all work is done, add added/modified files and commit these to git; do not add co-authored string to the commit
- Orientation before detail. Start each chapter and major section by telling the reader what problem is being solved, why it matters, and what they should retain. O’Reilly books are usually easy to navigate because the reader is rarely asked to infer the purpose of a section.
- Segment aggressively. Dense math should be broken into small units, each doing one conceptual job. Learning research is consistent that segmented material is easier to process than long uninterrupted explanation.
- Example before abstraction. Introduce a concrete case, then generalize. For technical and mathematical material, worked examples reduce entry cost and make later formalism easier to encode.
- Keep coupled information physically close. Put the explanation, equation, diagram, and code that depend on each other near one another. Avoid forcing the reader to hold one representation in memory while hunting for another; that split-attention penalty is real.
- Differentiate the main path from optional depth. The core narrative should be linear and survivable on first read. Side details, derivations, edge cases, and standards nuance should be visibly marked as secondary. This is very aligned with O’Reilly’s use of notes, tips, warnings, and sidebars.
- Use signaling ruthlessly. Make importance visible. Repeated labels like Key idea, Invariant, Pitfall, Result, Takeaway, and Why this matters help readers allocate attention correctly.
- Prefer stable recurring structure. If every chapter uses the same high-level rhythm, readers spend less effort learning how to read the chapter and more effort learning the content. Consistency is a formatting virtue, especially in technical books.
- Design for rereading and reference use. Math books are not consumed only linearly. Headings, captions, named equations, summary tables, and glossary-like recaps should help a reader re-enter the material later without rereading the whole chapter.
- Make notation cheap to recover. Never assume a symbol introduced pages ago is still active in working memory. Re-anchor symbols locally, keep notation consistent, and avoid unnecessary symbol churn.
- End with retrieval, not just recap. Summaries are useful, but “check yourself” prompts, short conceptual questions, or tiny reconstruction tasks are better for retention. Retrieval practice consistently outperforms passive review.
- Let complexity accumulate, not arrive all at once. Pretrain the reader on vocabulary, objects, and coordinate systems before combining them into full derivations. This is especially important in math-heavy science material.
- Optimize for confidence, not completeness per page. A reader who feels oriented and can predict the next step will keep going. A page that is perfectly complete but cognitively hostile will be abandoned.