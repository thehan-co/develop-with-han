# Develop With Han

A 4-phase project methodology for planning and execution. Lock vision before pixels. Lock design before code.

**For:** Solo developers, freelancers, product builders
**Solves:** Scope creep, unclear phases, expensive rework, unclear success criteria
**Result:** Predictable timelines, quality gates, continuous learning

---

## The Problem

Most projects suffer from the same pattern:
- Vision gets locked too late (after design starts)
- Design keeps changing during build
- Testing happens at the end (expensive)
- Each project repeats the same mistakes

This methodology prevents that.

---

## The 4 Phases

### Phase 0: Vision, Design & Strategy (Planning)
Lock vision, design system, and constraints *before* building anything.

**Duration:** 2-5 days
**Outcome:** Locked decisions, approved plan
**Cost of deferring:** 5-30x more expensive if moved to later phases

### Phase 1: Core Implementation (Building)
Build the MVP using the design system from Phase 0. No design decisions here.

**Duration:** 1-4 weeks
**Outcome:** Working MVP with core features
**Testing:** On target devices as you build

### Phase 2: Refinement & Polish (Improving)
Fix UX issues, add polish, run comprehensive testing.

**Duration:** 3-7 days
**Outcome:** Polished, tested product ready to launch
**Testing:** Cross-browser, mobile, accessibility, performance

### Phase 3: Deployment & Monitoring (Launching)
Deploy to production, verify, monitor for issues.

**Duration:** 1-3 days
**Outcome:** Live product, monitoring active, issues logged
**Testing:** Real-world usage, user feedback

---

## Why This Works

**Phase 0 prevents 80% of rework.**
5 hours of planning saves 40 hours of rebuilding. Vision decisions are cheap in Phase 0, expensive in Phase 2.

**Phases are sequential, not flexible.**
You can't add features in Phase 2. You can't redesign in Phase 1. Clear boundaries = predictable scope.

**HITL (Human-In-The-Loop) at every gate.**
You approve before moving forward. No surprises.

**Version tracking (x.y) shows progress.**
Phase 1.0, 1.1, 1.2 → Phase 2.0 → Launch. You always know where you are.

---

## How to Use

1. Download `develop-with-han.md` from this repo
2. Drop it in your project root folder
3. Open it in your browser or text editor — read it once
4. Start at Phase 0. Don't skip it.

```
your-project/
├── develop-with-han.md   ← here
├── src/
└── ...
```

---

## In Your AI Coder

Drop the file in your project root. Then point your AI coding tool at it.

**Claude Code — copy and run:**

```bash
# Start Phase 0 on a new project
claude "Read develop-with-han.md. Start Phase 0 for [project name]. Ask me the vision questions."

# Find out which phase you're actually in
claude "Read develop-with-han.md. Audit this project. Which phase are we in and what's incomplete?"

# Gate check before moving to the next phase
claude "Read develop-with-han.md. Are we ready to move from Phase 1 to Phase 2? Run the gate check."

# Resume after time away
claude "Read develop-with-han.md. What phase are we in? Give me the next 3 actions."

# Close out a phase
claude "Read develop-with-han.md. Phase 1 is done. Write the summary and brief for Phase 2."
```

Works the same way with Cursor, Windsurf, or any AI coding tool that reads files from your project.

---

## Real Example Timeline

**Project:** E-commerce dashboard for store managers

**Phase 0:** 3 days
- Vision: "Store manager command center for real-time decisions"
- Design system: Colors, typography, spacing locked
- Constraints: Mobile-first, RTL support
- Approval: ✅ Signed off

**Phase 1:** 2 weeks
- 1.0: Core features (dashboard, analytics, promotions)
- 1.1: Bug fixes from testing
- 1.2: Polish & refinement

**Phase 2:** 4 days
- Comprehensive testing (cross-browser, mobile, accessibility)
- Performance optimization
- Final polish

**Phase 3:** 1 day
- Deploy to production
- Monitor for issues
- Celebrate

**Total:** ~23 days from vision to live
**No surprises:** Every phase delivered what Phase 0 promised

---

## The Philosophy

This isn't about following rules. It's about:

✅ **Clarity** — You know what you're building and when
✅ **Quality** — Testing happens throughout, not at the end
✅ **Speed** — Clear scope prevents delays
✅ **Learning** — Each phase documents what you learned

❌ **Not:**
- Waterfall (rigid, inflexible)
- Agile (vague phases, unclear scope)
- Ad-hoc (chaos disguised as flexibility)

---

## For Solo Developers & Freelancers

You're both the builder and the approver. Still do all 4 phases — it forces clarity on yourself.

- **Phase 0:** Why am I building this? What does success look like?
- **Phase 1:** Build the core, test on devices as you go
- **Phase 2:** Polish, test thoroughly
- **Phase 3:** Launch, monitor, iterate in next version

---

## License

MIT License — Use freely, credit the author.

**Author:** Han Rabinovitz | [Clarity Beyond AI](https://www.linkedin.com/in/hanrabinovitz/)

---

## Full Methodology

See `develop-with-han.md` for detailed phase breakdown, checklists, version management, and common questions.

---

**Questions?** Open an issue or reach out on [LinkedIn](https://www.linkedin.com/in/hanrabinovitz/).
