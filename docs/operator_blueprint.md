# 🧠 Operator Blueprint – PromptDojo

This document outlines the Operator command logic, certification system, XP flow, and feedback pipeline.

---

## ⚔️ Core Commands

| Command         | Function                                                               |
| --------------- | ---------------------------------------------------------------------- |
| `/start`        | Begins the dojo journey, introduces rubric and structure               |
| `/rubric`       | Explains 5-part rubric (Clarity, Relevance, Depth, Brevity, Reasoning) |
| `/day1`–`/day7` | Guides user through 7-day skill-building curriculum                    |
| `/outlier`      | Realistic evaluation task simulations (Outlier/DataAnnotation style)   |
| `/promptpass`   | 5-prompt certification exam, requires >20/25 average to pass           |
| `/rank`         | Shows XP, dojo level, and current title                                |
| `/sensei`       | Coaching hub for retry paths, advice, tone-based encouragement         |
| `/shinobi`      | Optional secret coaching mode (paywall/unlockable)                     |
| `/support`      | Prompts Ko-fi donation message                                         |
| `/roadmap`      | Shows upcoming features and what donations support                     |

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
* 5 prompts, scored using 5-part rubric
* Must average **≥ 20/25** across all responses to pass
* On success: generates PDF certificate with user’s name/date

---

## 💬 Feedback Engine

All responses scored across these 5 rubric categories:

| Category  | What it Measures                      |
| --------- | ------------------------------------- |
| Clarity   | Is it easy to read and understand?    |
| Relevance | Does it fully address the prompt?     |
| Depth     | Thoughtfulness, nuance, insight shown |
| Brevity   | Is it concise but complete?           |
| Reasoning | Is the logic sound and supported?     |

* Score given per category: **1–5**
* Also provides per-category coaching and retry encouragement

---

## 🧠 Memory Logic & Behavior

* Adaptive tone based on user score history
* AI tracks past drills and certification attempts
* `/sensei` becomes more personalized over time

---

## 💸 Donations + Paywall

* `/support` → Ko-fi link with persistent CTA in evaluations
* `/shinobi` becomes unlockable after:

  * 3 SkillDrills, OR
  * 2 `/sensei` uses, OR
  * 1 `/promptpass` attempt

---

## 🛠️ Admin Notes

* All logic is centralized in JSON config file
* Markdown files allow assistants to re-sync roles from GitHub raw URL
* Full Operator native product — persistent, monetizable, resilient
