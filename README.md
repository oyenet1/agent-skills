<!--
  ──────────────────────────────────────────────────────────────────
  🏢 Company Name: Bonifade Technologies
  👨‍💻 Developer: Bowofade Oyerinde
  🐙 GitHub: oyenet1
  📅 Created Date: 2026-04-05
  🔄 Updated Date: 2026-04-05
  ──────────────────────────────────────────────────────────────────
-->

# Agent Skills

A collection of reusable AI agent skills by [Bowofade Oyerinde](https://github.com/oyenet1) / **Bonifade Technologies**.

## Available Skills

### [course-creator](./course-creator/)

Builds structured, dependency-aware programming and tech courses from user goals.

Generates:
- Course metadata and timeline (weeks + study hours)
- Chapter and lesson breakdown in dependency order
- Page-by-page teaching content with beginner-friendly examples
- Exercises (minimum 3 per chapter) and assignments (minimum 5 per chapter)
- Project portfolio by track (frontend/backend/fullstack) with realtime/WebSocket coverage

Grounds outputs using roadmap.sh, official framework docs, and optional supplementary references.

Intake it handles:
- Topic confirmation (programming/technology)
- Course type (`frontend`, `backend`, `fullstack`)
- Framework stack (max 2) with language auto-resolution
- AI-driven development preference
- Duration (`weeks x hours/week`) and workload warning when too short

Built-in guarantees:
- Foundations-first learning path before project work
- Strict prerequisite ordering (e.g. HTML -> CSS -> JS/TS)
- Backend/fullstack early architecture modules (UML, DB design, system design)
- DevOps module before final projects
- Distinct end-of-course projects with societal/business usefulness

Final output order:
1. Course Metadata
2. Course Content Summary (Chapter Outline)
3. Detailed Pages by Chapter
4. Exercises and Assignments
5. Project Portfolio
6. Tools and Deployment Plan
7. Learning Milestones by Week

Reference files:
- [course-creator/SKILL.md](./course-creator/SKILL.md)
- [course-creator/references/course-blueprint.md](./course-creator/references/course-blueprint.md)
- [course-creator/references/tech-mapping.md](./course-creator/references/tech-mapping.md)
- [course-creator/references/pdf-derived-roadmap-notes.md](./course-creator/references/pdf-derived-roadmap-notes.md)

Example prompt:
```text
Create a 12-week fullstack course for a beginner using Nuxt.js + Hono.js, 8 hours/week, AI-driven development enabled. Make it project-based, include at least 7 projects, and ensure one project uses WebSockets.
```

**Install:**
```bash
npx skills add oyenet1/agent-skills@course-creator
```

---

### 🔬 [spec-driven-development](./spec-driven-development/)

**Specification-Driven Development (SDD)** — transforms vague ideas into structured, implementation-ready specifications.

Takes any rough requirement and produces:
- `requirements.md` — User stories + testable acceptance criteria (WHEN/SHALL/IF)
- `design.md` — Architecture, components, data model, API contracts
- `tasks.md` — Ordered, dependency-aware implementation checklist

**Install:**
```bash
npx skills add oyenet1/agent-skills@spec-driven-development
```

**Triggers on:** "spec this", "SDD", "plan this feature", "break this down", "generate requirements", "write a spec", and more.

---

## Installing Skills

```bash
# Install a specific skill globally
npx skills add oyenet1/agent-skills@course-creator -g

# Install another specific skill globally
npx skills add oyenet1/agent-skills@spec-driven-development -g

# Install all skills from this repo
npx skills add oyenet1/agent-skills --all
```

## License

MIT — see [LICENSE](./LICENSE).
