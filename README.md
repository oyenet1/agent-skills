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
- Exercises (minimum 3 per chapter) and assignments (minimum 5 per course)
- Project portfolio by track (frontend/backend/fullstack) with realtime/WebSocket coverage

Grounds outputs using roadmap.sh, official framework docs, and optional supplementary references.

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
