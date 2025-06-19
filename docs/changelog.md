# PromptDojo Changelog

---


## v5.6.1 – Notion Backend Integration (2025‑06‑18)

**Summary:**

Enabled persistent memory for PromptDojo using Notion as a backend database. Tracks XP, rubric scores, drill history, and PromptPass unlocking in real-time.

### 🧠 Backend Integration:

- Added Notion API sync via `promptdojo_v5.6.json`
- Tracks `user_id`, `xp`, `rank`, `rubric_scores`, `completed_drills`, `promptpass_unlocked`
- Config includes `database_id` and `api_token`
- Ready for full Operator persistence and live training logs


## v5.6 – Daily Progression Overhaul (2025‑06‑XX)

**Summary:**

Transforms PromptDojo into a true long-form learning engine with enforced progression, deepened teaching logic, and mastery-based certification.

### 🔧 Fixes & Features:

- Added **minimum daily curriculum**: 5+ unique prompts per day
- Implemented **strict daily gating**: users cannot skip ahead
- Launched **XP & retry system**: all <18/25 scores must be redone
- New **model answer logic** via `/example`
- Added **rewrite coaching** via `/sensei` command
- Introduced **reflection prompts** after weak scores
- `/promptpass` now locked until:
    - 15+ SkillDrills completed
    - Rubric average > 20/25
- Daily intros + tone enhancements for emotional continuity
- Added `/roadmap` and `/commands` for better transparency

### 📊 Education Improvements:

- No more 3-hour completions — full dojo arc now takes ~7+ sessions
- Curriculum is structured to mirror real evaluator expectations
- Focused on long-term retention, review, and iteration

---

## v5.5 – Evergreen Learning System (2025‑06‑XX)

- Removed 7-day limit: PromptDojo now supports ongoing mastery
- `/review`, `/example`, and adaptive retry flow added
- Rebalanced XP progression + rank system
- `/rubricquiz` and `/progress` enhanced to track weakest category

---

## v5.4 – Tier 3 Curriculum Finalization (2025‑06‑XX)

- Locked XP gate for `/promptpass`
- Introduced `/finaltrial` (post-cert boss challenge)
- Resume/LinkedIn badge output added post-certification
- Coaching upgrades for struggling learners

---

## v5.3 – Structured Curriculum Patch (2025‑06‑XX)

- Each day now includes 3–5 prompts minimum
- Reflection questions added for knowledge retention
- Daily gating logic initiated (partial)

---

## v5.2 – Onboarding, Role Expansion (2025‑06‑XX)

- `/sensei` and `/rank` added
- Added feedback loop for underperforming users
- Certification tracking logic improved

---

## v5.0 – Operator Launch Version (2025‑06‑XX)

- All GPT logic and product files wired into GitHub via `.md` docs
- Introduced slash-command powered curriculum
- Initial PromptPass system launched

### ✅ v4.0–v4.9 (June 12–14, 2025)

* Rebranded from PromptTrainer → PromptDojo
* Introduced `/shinobi` paywall mode + `/roadmap`
* Integrated memory, donation flow, retry coaching

### ✅ v3.x and earlier (June 10–12, 2025)

* MVP product proof-of-concept
* Initial rubric feedback loop + `/support`
* Used as resume project for evaluator jobs
