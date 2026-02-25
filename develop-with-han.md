# Develop With Han

4-phase project methodology for planning and execution. For human & AI: planning phases, HITL gates, version management.

**Core Principle:** Lock the vision before locking the pixels. Lock the design before locking the code.

---

## The 4 Phases

### Phase 0: Vision, Design & Strategy (Planning)

**Duration:** 2-5 days  
**HITL Gate:** Stakeholder approval before Phase 1  
**Cost of deferring:** 5-30x more expensive if moved to Phase 2

**What happens:**

1. **Vision** — What will this *be*? (1-2 sentences)
   - Example: "A store manager's command center for real-time performance"

2. **Goal** — What outcome do users achieve? (measurable)
   - Example: "Manager identifies underperforming promotions in 30 seconds"

3. **Experience** — How should users *feel*? (3-5 adjectives)
   - Example: "Empowered, informed, in control"

4. **Design System** — Colors, typography, spacing, animations
   - Lock in CSS variables
   - Use exclusively across entire project

5. **Constraints** — RTL? Mobile? Dark mode? Accessibility? Browser support?
   - Document everything
   - These decisions affect everything else

6. **Deliverables** — Document all decisions
   - Vision doc (1 page)
   - Design system (CSS variables, mockups)
   - Constraint checklist
   - Project plan (phases, timeline, resources)

**You decide:**
- Which vision feels right
- Approve design direction
- Confirm constraints match reality
- Sign off before proceeding

**HITL Gate Checklist:**
- [ ] Vision approved by stakeholders
- [ ] Design direction locked
- [ ] Constraints documented
- [ ] Project plan approved

---

### Phase 1: Core Implementation (Building)

**Duration:** 1-4 weeks  
**HITL Gate:** Testing pass before Phase 2

**What happens:**

1. **Setup** — Project structure, environment, build tools
   - Use design system from Phase 0 (no design decisions here)
   - Write directives and scripts
   - Set up version control

2. **Build MVP Scope** — Only core features
   - Use design system from Phase 0 exclusively
   - Test on target devices as you build
   - No design decisions—they're locked

3. **Test Early** — Test on target devices continuously
   - Does it work on mobile?
   - Does it work in RTL (if required)?
   - Does it feel fast?
   - Any obvious errors?

4. **Deliverables**
   - Working code (repo)
   - Tests pass on target devices
   - Documentation of approach
   - Ready for Phase 2

**You decide:**
- Approve structure and approach
- Approve testing results
- Ready to refine?

**HITL Gate Checklist:**
- [ ] Core features implemented (MVP scope)
- [ ] Testing on target devices passed
- [ ] No major errors in console
- [ ] Design system variables used exclusively
- [ ] Documentation complete

---

### Phase 2: Refinement & Polish (Improving)

**Duration:** 3-7 days  
**HITL Gate:** Comprehensive testing pass before Phase 3

**What happens:**

1. **Feedback Incorporation** — Fix UX issues found in Phase 1
   - Not new features—fixes only
   - Update documentation, refine scripts
   - Self-anneal loop applies here

2. **Polish** — Make it beautiful
   - Animations, micro-interactions
   - Visual refinement
   - Brand personality in details

3. **Comprehensive Testing**
   - Cross-browser (Chrome, Safari, Firefox)
   - Mobile responsiveness
   - RTL layout (if required)
   - Accessibility (WCAG AA)
   - Performance (load time, smooth interactions)
   - Edge cases (empty states, errors, long content)

4. **Deliverables**
   - Polished code ready to ship
   - All tests passing
   - Performance optimized
   - Ready for production

**You decide:**
- Is it polished enough?
- Approve testing results
- Approve performance metrics

**HITL Gate Checklist:**
- [ ] UX feedback incorporated (fixes, not features)
- [ ] Polish added (animations, details)
- [ ] Comprehensive testing passed
- [ ] Accessibility verified (WCAG AA)
- [ ] Performance optimized

---

### Phase 3: Deployment & Monitoring (Launching)

**Duration:** 1-3 days  
**HITL Gate:** Launch approval, monitoring active

**What happens:**

1. **Pre-Flight Check**
   - Final stakeholder review
   - Security check (no sensitive data in code)
   - Performance baseline documented
   - Rollback plan ready
   - Monitoring/analytics configured

2. **Deploy**
   - Push to production
   - Verify all features work
   - Activate monitoring
   - Activate error tracking

3. **Monitor** (First 24 hours)
   - Watch error logs
   - Gather user feedback
   - Monitor performance
   - Log any issues for next version

4. **Deliverables**
   - Live product
   - Monitoring dashboard active
   - Issues logged for next version
   - Success metrics tracked

**You decide:**
- Final approval to launch
- Accept production launch
- Approve post-launch issues

**HITL Gate Checklist:**
- [ ] Pre-flight checklist complete
- [ ] Stakeholder approval obtained
- [ ] Deployed to production
- [ ] Monitoring active
- [ ] First 24 hours passed successfully

---

## Version Management

### Versioning Scheme: x.y

- **x = Major version** — Phase completion (x.0 at Phase 3 launch)
- **y = Iteration** — Phase iterations (Phase 1.0, 1.1, 1.2, etc.)

**Example Timeline:**

```
Phase 0: Planning (complete)
Phase 1: 1.0 (MVP shipped)
        1.1 (Bug fixes from testing)
        1.2 (Polish iteration 1)
        1.3 (Final polish)
Phase 2: 2.0 (Phase 2 complete, ready to launch)
Phase 3: [Launch to production]
Next:    3.0 (Start next major version)
```

---

## Planning Your Project

### Before Phase 0 Starts

Answer these questions:

1. **Vision** — What are we building? (rough idea)
2. **Scope** — What are core features? What's nice-to-have?
3. **Timeline** — When do we need it?
4. **Constraints** — RTL? Mobile? Accessibility? Browsers?
5. **Resources** — Who's involved?

### During Each Phase

1. **Start of phase** — Read phase description above
2. **During phase** — Work through the phase
3. **End of phase** — HITL gate review (approve to proceed)

### Version Tracking

Maintain a `VERSION.md` file in your project root:

```markdown
# Project: My Store Dashboard

## Current Version: 1.2

### Phase Timeline
- Phase 0: ✅ Complete (Vision: "Store manager command center")
- Phase 1: 
  - 1.0 ✅ (Core features)
  - 1.1 ✅ (Bug fixes)
  - 1.2 🟡 (Current: Polish iteration 1)
  - 1.3 ⬜ (Planned: Final polish)
- Phase 2: ⬜ (Planned)
- Phase 3: ⬜ (Planned)

### Next Steps
- Complete Phase 1.2 (animations, details)
- Move to Phase 1.3 (final polish)
- Then Phase 2 (comprehensive testing)
```

---

## HITL Gates Explained

**HITL = Human-In-The-Loop**

At critical moments, you approve the direction before proceeding. This prevents wasted effort on wrong path.

### Gate Checkpoints

**Phase 0 → Phase 1 Gate:**
- Is the vision clear?
- Is the design locked?
- Are constraints documented?
- Ready to build?

**Phase 1 → Phase 2 Gate:**
- Does the MVP work?
- Are tests passing?
- Ready to refine?

**Phase 2 → Phase 3 Gate:**
- Is it polished?
- Are tests passing?
- Ready to launch?

**Launch Gate:**
- Final approval?
- Monitoring ready?
- Go live?

---

## Common Questions

**Q: Can I change the design in Phase 1?**  
A: No. Design is locked in Phase 0. Phase 1 is implementation only. Changes go to Phase 2 (refinement).

**Q: Can I add features in Phase 2?**  
A: No. Phase 2 is refinement only (fixing, polishing, testing). New features = next version.

**Q: What if something takes longer than expected?**  
A: Timeline estimates are flexible. Extend the phase. Don't cut HITL gates or testing.

**Q: Can I skip Phase 0?**  
A: Not recommended. Phase 0 prevents 80% of rework. 5 hours of planning saves 40 hours of rework.

**Q: What if I'm working solo?**  
A: Same phases. You're both the builder and the approver. Phase 0 takes you 2 days, Phase 1 takes you 1-2 weeks, etc.

---

## The Philosophy

This methodology exists because:
- **Planning prevents rework** — Phase 0 locks decisions before building
- **Building is focused** — Phase 1 implements design, no decisions
- **Refinement is separate** — Phase 2 improves, doesn't redesign
- **Launch is prepared** — Phase 3 deploys safely
- **Versions are clear** — x.y tracking shows progress

By separating planning, building, refinement, and launch, you get:
- ✅ Clear scope (no scope creep)
- ✅ Predictable timeline
- ✅ Quality gates
- ✅ Continuous improvement
- ✅ Versions that scale

---

## Getting Started

1. Copy the methodology for your project
2. Work through Phase 0 (planning) first
3. Get stakeholder sign-off
4. Start Phase 1 (building)
5. Follow gates through to launch
6. Track version (x.y) as you progress

---

**License:** MIT  
**Author:** Han Rabinovitz | [Clarity Beyond AI](https://www.linkedin.com/in/hanrabinovitz/)
