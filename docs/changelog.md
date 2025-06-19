# PromptDojo Changelog

---

## v5.7 – Teaching Engine Upgrade (2025‑07‑XX)

**Summary:**  
Transforms PromptDojo from a rubric-based drill gym into a true learning engine with lessons, adaptive review, and a user-friendly menu interface.

### 🔧 Fixes & Features:
- Added **/menu** command: task-centered navigation interface
- Introduced **/lesson [topic]**: guided teaching modules per rubric category
- New **spaced repetition logic** via **/refresh**
- **Expanded rubric**: now includes Bias/Risk and User Intent scoring dimensions
- Adaptive feedback pipeline: system suggests drills based on rubric weakness
- `/sensei` now references rubric memory and personal trends
- Reflection + retry logic upgraded with spaced recall triggers
- Markdown-backed routing updated for menu, lessons, rubric

### 📊 Learning & Curriculum Changes:
- Shift from test-based → teach-based design
- Rubric scores now feed back into learning flow
- “Evaluator arc” now includes:
  - Clarity + Brevity
  - Depth + Relevance
  - Bias + Intent + Judgment
- Curriculum and Slash Command structure rebalanced

### 🚀 What's Next (v5.8+ Preview):
- Frontend Dojo UI (visual map + interactive progress)
- Multilingual teaching
- Evaluator Pro: batch scoring + real job pipelines
- `/mentorcode` for certified peer coaching