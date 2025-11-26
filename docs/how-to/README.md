# How-To Guides

**Task-oriented guides for common operations**

Choose the task you want to accomplish:

---

## Validation & Quality

- **[Implement Validation Gates](implement-validation-gates.md)** - Set up make quick/test/all pipeline (Factor IV)
- **[Add Pre-Commit Hooks](add-precommit-hooks.md)** - Automatic validation before commits
- **[Run Security Scans](run-security-scans.md)** - Integrate security checks into workflow

---

## Context Management

- **[Prevent Context Collapse](prevent-context-collapse.md)** - Keep under 40% budget (Factor II)
- **[Create Project Context File](create-context-file.md)** - CLAUDE.md, .cursorrules, etc.
- **[Manage Multi-Phase Workflows](manage-multiphase-workflows.md)** - Research → Plan → Implement

---

## Pattern Libraries

- **[Build Pattern Library](build-pattern-library.md)** - Reusable code patterns (Factor XII)
- **[Extract Patterns from History](extract-patterns-from-history.md)** - Mine git for patterns (Factor IX)
- **[Share Patterns Across Team](share-patterns-across-team.md)** - Team pattern libraries

---

## Measurement & Observability

- **[Track Success Rates](track-success-rates.md)** - Measure AI effectiveness (Factor V)
- **[Measure Speedup](measure-speedup.md)** - Calculate ROI on AI workflows
- **[Monitor FAAFO Metrics](monitor-faafo-metrics.md)** - Track all 5 FAAFO dimensions

---

## Session Management

- **[Resume Work Across Sessions](resume-work-across-sessions.md)** - Multi-day project continuity (Factor VI)
- **[Create Session Notes](create-session-notes.md)** - Capture context for later
- **[Bundle Compression](bundle-compression.md)** - Compress 60k → 5k tokens

---

## Team Workflows

- **[Set Up Shared Knowledge OS](setup-shared-knowledge-os.md)** - Team-wide git memory
- **[Implement Human Validation Gates](implement-human-validation.md)** - Review checkpoints (Factor VIII)
- **[Onboard Team Members](onboard-team-members.md)** - Get team to 95% success rate

---

## Debugging & Troubleshooting

- **[Debug Context Collapse](debug-context-collapse.md)** - When AI stops working well
- **[Fix Low Success Rates](fix-low-success-rates.md)** - Below 70% success? Start here
- **[Optimize Slow Workflows](optimize-slow-workflows.md)** - Make it faster

---

## Advanced

- **[Smart Routing](implement-smart-routing.md)** - Route tasks to specialized agents (Factor VII)
- **[Fail-Safe Checks](implement-failsafe-checks.md)** - Prevent repeating mistakes (Factor XI)
- **[Small Iterations](implement-small-iterations.md)** - Incremental improvements (Factor X)

---

## By Factor

Find how-to guides organized by which factor they implement:

| Factor | How-To Guides |
|--------|---------------|
| **I: Automated Tracking** | [Git Workflow](setup-git-workflow.md) |
| **II: Context Loading** | [Context File](create-context-file.md), [Prevent Collapse](prevent-context-collapse.md) |
| **III: Focused Agents** | [Multi-Phase Workflows](manage-multiphase-workflows.md) |
| **IV: Continuous Validation** | [Validation Gates](implement-validation-gates.md), [Pre-Commit Hooks](add-precommit-hooks.md) |
| **V: Measure Everything** | [Track Success](track-success-rates.md), [Measure Speedup](measure-speedup.md) |
| **VI: Resume Work** | [Session Notes](create-session-notes.md), [Resume Work](resume-work-across-sessions.md) |
| **VII: Smart Routing** | [Smart Routing](implement-smart-routing.md) |
| **VIII: Human Validation** | [Human Validation Gates](implement-human-validation.md) |
| **IX: Mine Patterns** | [Extract Patterns](extract-patterns-from-history.md) |
| **X: Small Iterations** | [Small Iterations](implement-small-iterations.md) |
| **XI: Fail-Safe Checks** | [Fail-Safe Checks](implement-failsafe-checks.md) |
| **XII: Package Patterns** | [Build Pattern Library](build-pattern-library.md), [Share Patterns](share-patterns-across-team.md) |

---

## By FAAFO Dimension

Find how-to guides organized by FAAFO goal:

| FAAFO Dimension | How-To Guides |
|-----------------|---------------|
| **Fast** | Validation Gates, Measure Speedup, Optimize Workflows |
| **Ambitious** | Pattern Libraries, Team Workflows |
| **Autonomous** | Validation Gates, Fail-Safe Checks, Success Tracking |
| **Fun** | Pre-Commit Hooks, Debug Context Collapse |
| **Optionality** | Context Management, Session Management |

---

## Quick Reference

**Most popular guides:**
1. [Implement Validation Gates](implement-validation-gates.md) - Start here
2. [Create Context File](create-context-file.md) - Prevent context collapse
3. [Build Pattern Library](build-pattern-library.md) - Reuse what works
4. [Track Success Rates](track-success-rates.md) - Measure improvement
5. [Resume Work](resume-work-across-sessions.md) - Multi-day projects

---

**Need help choosing?**
- **New to 12-Factor AgentOps?** → Start with [Implement Validation Gates](implement-validation-gates.md)
- **Context collapse issues?** → [Prevent Context Collapse](prevent-context-collapse.md)
- **Low success rate?** → [Fix Low Success Rates](fix-low-success-rates.md)
- **Want to reuse code?** → [Build Pattern Library](build-pattern-library.md)
- **Team adoption?** → [Set Up Shared Knowledge OS](setup-shared-knowledge-os.md)
