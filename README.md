# SAIL Critical Thinking Module

A portable, credentialed module for teaching AI critical thinking in any business course.

**Live Site:** [https://harslan.github.io/sail-critical-thinking-module/](https://harslan.github.io/sail-critical-thinking-module/)

---

## Overview

This module addresses a critical gap in business education: students who either avoid AI entirely or outsource their thinking to it completely. Using Suffolk University's SAIL Framework, it provides a progressive scaffold that develops genuine AI critical thinking skills — not just AI awareness.

## The Three-Phase Approach

| Phase | Focus | Student Activity | SAIL Pillars |
|-------|-------|------------------|--------------|
| **1. Foundation** | Think Without the Crutch | Complete discipline-relevant task without AI | AI Literacy, Innovation/Inquiry |
| **2. Integration** | Use AI, But Question Everything | Repeat task with AI; document and critique | AI Literacy, Innovation/Inquiry, Social Intelligence |
| **3. Leadership** | Own Your Human-AI Partnership | Develop personal AI use framework | All four pillars |

## Repository Structure

```
sail-critical-thinking-module/
│
├── index.html                  # Main public-facing site
├── README.md                   # This file
├── LICENSE                     # MIT License
│
├── /docs                       # Supporting documentation
│   ├── implementation-guide.md     # For faculty adopting the module
│   ├── credentialing-spec.md       # Badge/Credly requirements
│   └── assessment-rubrics.md       # Grading criteria for reflections
│
├── /canvas                     # Canvas-specific resources
│   ├── module-outline.md           # What goes in each Canvas module
│   ├── assignment-prompts.md       # Copy-paste ready prompts
│   └── quiz-bank.md                # Optional knowledge-check questions
│
├── /examples                   # Discipline-specific adaptations
│   ├── strategy/                   # Sam Rosen's pilot implementation
│   ├── marketing/                  # Marketing adaptation (template)
│   └── finance/                    # Finance adaptation (template)
│
└── /assets                     # Images, badges, graphics
    ├── sail-badge.png              # Credential badge design
    └── framework-diagram.png       # Visual of the 3-phase model
```

## Quick Start

### For Faculty
1. Review the [Implementation Guide](docs/implementation-guide.md)
2. Copy materials from `/canvas` into your Canvas course
3. Customize the domain-specific task for your discipline
4. See `/examples` for discipline-specific adaptations

### For Developers
```bash
# Clone the repository
git clone https://github.com/harslan/sail-critical-thinking-module.git

# Local preview (Python 3)
python -m http.server 8000
# Then open http://localhost:8000
```

## Key Features

### Portable & Embeddable
Any professor can copy this module into their Canvas course. The core scaffold is discipline-agnostic; professors customize only the domain-specific task.

### Credentialed
Completion earns students a verified micro-credential (Credly-compatible) that signals AI critical thinking skills to employers.

### Assessment Integrity
Three strategies ensure authentic student work:
1. **Personal Artifact Documentation** — Students submit real AI conversation screenshots with annotations
2. **Live Metacognitive Prompts** — Timed reflection questions during (not just after) the module
3. **Peer Accountability** — Students review and critique each other's AI interaction logs

## SAIL Framework

- **S**ocial Intelligence — Communicating AI decisions to diverse stakeholders
- **A**I Literacy — Understanding capabilities, limitations, and appropriate use
- **I**nnovation/Inquiry — Questioning outputs and pushing beyond first answers
- **L**eadership — Taking responsibility for human-AI collaboration outcomes

## Credentialing Options

| Tier | Requirement | Badge |
|------|-------------|-------|
| **Bronze** | Completed all three phases | ✓ |
| **Silver** | Passed reflection quality threshold | ✓✓ |
| **Gold** | Contributed to peer review or case library | ✓✓✓ |

## Attribution

**Developed by the SAIL Collaborative**  
Suffolk University, Sawyer Business School

**Project Lead:** Hasan Arslan, Chief AI Officer & Associate Professor

**Contributors:**
- Jodi Detjen
- Ariel Tevet-Markelevich
- Sam Rosen (Strategy pilot)

## License

MIT License — See [LICENSE](LICENSE) for details.

---

*Part of Suffolk University's commitment to preparing students for AI-augmented careers.*
