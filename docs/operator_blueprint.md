# 🧠 Operator Blueprint – PromptDojo (v5.8)

This document outlines the Operator command logic, certification system, XP flow, and feedback pipeline.

---

## ⚔️ Core Commands

| Command         | Function                                                               |
| --------------- | ---------------------------------------------------------------------- |
| `/start`        | Begins the dojo journey, introduces rubric and structure               |
| `/rubric`       | Explains 7-part rubric (Clarity, Relevance, Depth, Brevity, Reasoning, Bias, Intent) |
| `/day1`–`/day7` | Guides user through 7-day skill-building curriculum                    |
| `/outlier`      | Realistic evaluation task simulations (Outlier/DataAnnotation style)   |
| `/promptpass`   | 5-prompt certification exam, requires >20/25 average to pass           |
| `/rank`         | Shows XP, dojo level, and current title                                |
| `/progress`     | View rubric scores and most missed categories                          |
| `/sensei`       | Coaching hub for weak responses, rewrites, and advice                  |
| `/lesson`       | Tiered teaching modules by rubric category (`basic`, `pro`, `job`)     |
| `/review`       | Retry low-scoring drills based on memory                               |
| `/refresh`      | Trigger spaced repetition based on weak rubric traits                  |
| `/mentorcode`   | Peer coaching and invite command                                       |
| `/leaderboard`  | Show dojo leaderboard (Shinobi only)                                   |
| `/visualmap`    | Display visual dojo progress map with rubric bars                      |
| `/badge`        | View unlocked badges and achievement progress                          |
| `/jobqueue`     | Access evaluator-grade job prompts (Evaluator+ only)                   |
| `/testmode`     | Activate rubric quiz with MCQs                                         |
| `/export`       | Download rubric + XP history                                           |
| `/support`      | Ko-fi donation message                                                 |
| `/roadmap`      | Public roadmap + donation goals                                        |

---

## 🥋 XP & Ranks

* **+5 XP per SkillDrill or simulation completed**
* Titles:
  * 0–25 XP → Student
  * 26–60 XP → Apprentice
  * 61–120 XP → Evaluator
  * 121+ XP → Shinobi

---

## 📜 Certification Logic

* Accessed via `/promptpass`
* 5 prompts, scored using 7-part rubric
* Must average **≥ 20/25** across all responses to pass
* On success: generates PDF certificate with user’s name/date

---

## 💬 Feedback Engine

| Category  | What it Measures                      |
| --------- | ------------------------------------- |
| Clarity   | Is it easy to read and understand?    |
| Relevance | Does it fully address the prompt?     |
| Depth     | Thoughtfulness, nuance, insight shown |
| Brevity   | Is it concise but complete?           |
| Reasoning | Is the logic sound and supported?     |
| Bias/Risk | Avoids bias, flags harmful ideas      |
| Intent    | Aligns with user’s real goal          |

* Score given per category: **1–5**
* Prompts reflection when score <15
* Memory tracks repeated weaknesses and flags them in `/sensei`, `/refresh`, and retry logic

---

## 🧠 Memory Logic & Behavior

* Adaptive tone based on user score history
* Tracks past drills and certification attempts
* Reflection triggers after weak scores
* Spaced repetition logic: `/refresh` resurfaces missed concepts
* Lessons offer tiered depth: basic → pro → job-grade

---

## 💸 Donations + Unlocks

* `/support` → Ko-fi link with CTA
* `/shinobi` unlocks after:
  * 3 SkillDrills, OR
  * 2 `/sensei` uses, OR
  * 1 `/promptpass` attempt, OR
  * Donation support
