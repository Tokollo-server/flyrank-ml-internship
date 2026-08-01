# FL-01: Workflow Audit & AI Setup

## 1. 12-Task Workflow Audit

| Task Name | Category | Rationale |
| :--- | :--- | :--- |
| **1. Analyzing market liquidity & key levels for US30 / NAS100** | Just me | Requires real-time instinct, dynamic execution, and risk management that AI cannot reliably replicate or execute live. |
| **2. Final execution of trades on prop evaluation accounts** | Just me | Execution discipline and trade management are strictly human responsibilities to prevent account drawdowns and rule breaches. |
| **3. Writing custom React/JSX components for web apps** | Collaborate with AI | AI generates standard boilerplate and UI structures fast, while I customize logic and styling for our exact design. |
| **4. Debugging ML pipeline Python scripts (scripts 01-05)** | Delegate to AI with review | LLMs excel at spotting syntax errors, missing imports, or Pandas index bugs, which I then test and verify locally. |
| **5. Drafting weekly status updates & documentation** | Delegate to AI with review | Summarizing raw progress into structured updates saves time, though human editing ensures context remains accurate. |
| **6. Studying Anthropic Academy & Claude Code 101 materials** | Just me | True conceptual comprehension requires deep personal reading and hands-on synthesis without relying on AI summaries. |
| **7. Automating data extraction from Hugging Face DuckDB tables** | Fully automate | Standardized SQL/Python extraction queries run on schedule via scripts without requiring manual intervention. |
| **8. Running baseline vs ML model comparisons (`model_results.json`)** | Fully automate | Automated evaluation scripts compute ROC AUC and Precision@K metrics and dump structured JSON logs upon execution. |
| **9. Drafting direct messages & professional emails** | Delegate to AI with review | AI helps structure tone and clarity quickly, but I review the final text before pressing send. |
| **10. Analyzing performance decay reason codes on content pages** | Collaborate with AI | AI suggests multi-variable signal patterns, while I audit the results against actual search volume trends. |
| **11. Configuring environment variables & repo folder setups** | Fully automate | Shell scripts and automated setup scripts handle directory creation (`work/notebooks/`) and dependencies instantly. |
| **12. Reviewing prop firm evaluation rules (drawdown, consistency)** | Just me | Understanding target boundaries and strict risk rules requires full human accountability to avoid losing evaluation accounts. |

---

## 2. Target Tasks & Success Definitions

### Target Task 1: Python ML Script Debugging & Feature Engineering
* **Category:** Delegate to AI with review
* **Definition of "Done Well":** The AI identifies logical bugs or Pandas transformation errors in script pipelines within 2 minutes; the output passes local execution tests without data leakage or runtime exceptions.

### Target Task 2: Page-Level Performance Decay Reason Code Generation
* **Category:** Collaborate with AI
* **Definition of "Done Well":** Generates human-readable, actionable reason codes (e.g., `model_decline_risk`, `ctr_review_candidate`) for top-ranked pages that accurately map to underlying data thresholds with 0 false reasons upon manual audit.

### Target Task 3: Deliverable & Markdown Report Structuring
* **Category:** Delegate to AI with review
* **Definition of "Done Well":** Transforms raw experimental outputs (`model_results.json`, execution metrics) into well-structured, public-safe markdown reports following strict submission guidelines without introducing hallucinated claims or private identifiers.

---

## 3. Tool Verification & Setup Evidence

* **Claude Project:** Configured and active under *FLYRANK ML Internship Assistant*.
* **Anthropic Academy:** Enrolled in *AI Fluency: Framework & Foundations*.
