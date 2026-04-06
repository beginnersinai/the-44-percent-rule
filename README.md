# The 44% Rule — Find 44% More AI Use Cases In Your Business

> **The 44% Rule:** A research finding (Kim, Kim & Koning, 2026) — businesses shown how other companies reorganize around AI find **44% more AI use cases**, complete **12% more tasks**, are **18% more likely to acquire paying customers**, and generate **1.9x higher revenue**. This plugin automates that "showing" so any business can apply the rule in under 10 minutes.

## What It Is

**The 44% Rule** is a free Claude Code plugin that automates a research-backed audit of any business to find where AI should be deployed but isn't.

It's based on *"Mapping AI into Production: A Field Experiment on Firm Performance"* (Kim, Kim & Koning, March 2026) — a study of 515 startups that found the #1 bottleneck to getting value from AI isn't capability. **It's discovery.** Most people use AI for writing and chatbots and stop there. The firms that were shown how others reorganized around AI found 44% more use cases and generated 1.9x higher revenue.

This plugin automates that "showing" — it scans your workspace, maps where AI is and isn't being used across **10 core business functions**, and generates a prioritized action plan.

---

## What's In the Plugin

### 3 Slash Commands

| Command | What It Does |
|---------|-------------|
| `/map` | Full workspace scan. Discovers all your projects, maps AI usage across 10 functions for each, identifies gaps, scores opportunities, generates a complete AI Map report. |
| `/map-venture [name]` | Focused audit of a single project or business. Same 10-function analysis but deep on one venture. |
| `/map-score` | Scores and ranks all opportunities found by `/map`. Prioritizes by revenue impact, capital reduction, and ease of implementation. |

### 3 Specialized AI Agents

| Agent | Role | Color |
|-------|------|-------|
| **Venture Scanner** | Explores your workspace to discover and inventory all projects, businesses, and ventures | Cyan |
| **Gap Finder** | Maps AI usage across 10 functions and identifies where AI is absent | Green |
| **Priority Scorer** | Scores opportunities and creates a ranked action plan | Yellow |

### 1 Auto-Activating Skill

The audit skill activates automatically whenever you discuss AI adoption strategy, ask where to use AI, or mention the mapping problem. It loads the 10-function framework and examples without you needing to run a command.

### Reference Materials

- **Ten Functions Framework** — The complete 10 production functions where AI can create value, with specific indicators for each
- **Examples From Other Firms** — Real examples of how firms have deployed AI across all 10 functions (this is the "treatment" from the research paper — the "showing" that produces the 44% lift)
- **Case Studies From the Paper** — Gamma, RyzLabs, FazeShift, Ranger and the specific AI deployments that generated revenue

---

## The 10 Production Functions

Every business has 10 functions where AI can create value. Most only use AI in 1-2 of them:

1. **Product Development** — Building and improving your core offering
2. **Strategy & Planning** — Business decisions and competitive positioning
3. **Marketing & Growth** — Customer acquisition and audience building
4. **Sales & Revenue** — Converting prospects and optimizing pricing
5. **Customer Success** — Retention, satisfaction, and churn prevention
6. **Finance & Pricing** — Revenue tracking, forecasting, and pricing intelligence
7. **Operations & Logistics** — Workflows, processes, and resource allocation
8. **Content Production** — Creating content (where most people already use AI)
9. **Data & Analytics** — Measurement, reporting, and insights
10. **System Administration** — Maintaining and optimizing your tools and AI systems

If your AI usage is concentrated only in #8 (Content) and maybe #3 (Marketing), you have the mapping problem. The 44% Rule fixes it.

---

## How to Install

1. Download the ZIP file from [Releases](https://github.com/beginnersinai/the-44-percent-rule/releases) or click **Code → Download ZIP** above
2. In **Claude Cowork**: Go to Customize → click the **+** next to "Personal plugins" → drag in the ZIP file
3. In **Claude Code** (terminal): The plugin syncs automatically from Cowork, or run `/plugins add-local` with the extracted folder path
4. Type `/map` to run your first audit — no configuration needed

---

## How to Use It

### Quick Start
1. Open Claude Code in any project directory
2. Type `/map`
3. Wait for the scan to complete (takes 2-5 minutes depending on workspace size)
4. Review the generated `AI-MAP-[date].md` report
5. Type `/map-score` to get a prioritized action plan

### For a Single Project
1. Type `/map-venture MyProject`
2. Get a focused 10-function analysis with specific recommendations

### The Scoring System
Each opportunity is scored on:
- **Revenue Impact** (1-5, weighted 2x) — How much money does this make or save?
- **Capital Reduction** (1-5) — Does this eliminate a hire or expense?
- **Ease of Implementation** (1-5) — Can you do this today?

**Composite Score** = (Revenue × 2) + Capital + Ease. Maximum: 20 points.

Opportunities scoring 15+ with Ease = 5 are flagged as **"Press Send"** — infrastructure exists, nobody activated it.

---

## The Research Behind The 44% Rule

**Paper**: *"Mapping AI into Production: A Field Experiment on Firm Performance"*
**Authors**: Hyunjin Kim (INSEAD), Dahyeon Kim (INSEAD), Rembrand Koning (Harvard Business School)
**Date**: March 30, 2026
**Sample**: 515 startups

**Key findings**:
- **44% more AI use cases** discovered when shown how others use AI ← **the 44% Rule**
- 12% more tasks completed
- 18% more likely to acquire paying customers
- 1.9x higher revenue
- 39.5% less demand for external capital
- No increase in labor demand
- Gains largest at the 90th percentile — AI amplifies winners

**The core insight**: The bottleneck is discovering **where** to deploy AI, not AI capability. This plugin automates that discovery so you don't have to read the paper or hire a consultant to apply the finding.

---

## Read More

- **Plugin landing page**: https://beginnersinai.org/get-the-44-percent-rule/
- **Full article walkthrough**: https://beginnersinai.org/the-44-percent-rule/
- **The research paper, explained for beginners**: https://beginnersinai.org/mapping-ai-research-study/

---

## Naming Note

This plugin was originally released on April 5, 2026 as **"The AI Mapping Plugin"**. On April 6 we renamed it to **"The 44% Rule"** to make the value proposition clearer at a glance. The plugin's functionality, code, and structure are unchanged — only the name and branding. Existing installs continue to work; new installs use the new name. The old GitHub URL (`beginnersinai/ai-mapping-plugin`) auto-redirects to the new one (`beginnersinai/44-percent-rule`).
