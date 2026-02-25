# Develop With Han

A 4-phase project methodology for planning and execution. Lock vision before pixels. Lock design before code.

**For:** Solo developers, freelancers, product builders
**Solves:** Scope creep, unclear phases, expensive rework, unclear success criteria
**Result:** Predictable timelines, quality gates, continuous learning

---

## How to Use

**1. Download**
Get `develop-with-han.md` from this repo.

**2. Add to your AI assistant**
Paste it into your Claude.ai project instructions, ChatGPT custom instructions, or any AI tool that accepts context. It becomes your AI's working methodology.

**3. Drop it in your project root**
```
your-project/
├── develop-with-han.md   ← here
├── src/
└── ...
```

**4. Start working**
Begin at Phase 0. Don't skip it.

**5. Call it in Claude Code**

Point Claude Code at the methodology and tell it where you are:

```bash
# Start a new project from Phase 0
claude "Read develop-with-han.md. Help me complete Phase 0 for [project name]. Ask me the vision questions."

# Audit where you actually are
claude "Read develop-with-han.md. Audit this project and tell me which phase we're in and what's missing."

# Gate check before moving phases
claude "Read develop-with-han.md. We think we're ready to move from Phase 1 to Phase 2. Run the gate check."

# Resume after time away
claude "Read develop-with-han.md. Summarize current phase status and give me the next 3 actions."

# End-of-phase handoff
claude "Read develop-with-han.md. We just finished Phase 1. Write the phase summary and what Phase 2 needs to know."
```

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
