# PromptDojo Operator Setup – v5.8

This document serves as the blueprint for PromptDojo’s Operator-native GPT product.

🧠 PRODUCT OVERVIEW

PromptDojo is a GPT-powered dojo-style training engine for AI evaluation jobs. Built with a full slash-command curriculum, rubric scoring, XP tracking, spaced repetition, and a peer-coaching ecosystem.

Mission: Train beginners into certified prompt evaluators — no prior experience required.

Current Version: v5.8 (Evaluator Arc Expansion)

---

🔗 FILE STRUCTURE

📁 promptdojo-operator  
├── README.md  
├── /config → promptdojo_v5.8.json  
├── /docs  
│   ├── operator_blueprint.md  
│   ├── prompts_and_rubric.md  
│   ├── gpt_setup_guide.md  
│   ├── changelog.md  
│   └── marketing_strategy.md  
└── /assets  
    ├── logo.png  
    ├── badge_promptpass.png  
    └── banner_twitter.png

---

✅ FIXES IN v5.8

- Tiered lessons: `/lesson [topic] basic|pro|job`
- Automatic reflection prompts on rubric fail
- New drills for Bias + Intent dimensions
- Visual UI via `/visualmap`
- Peer coaching via `/mentorcode`
- Leaderboard with `/leaderboard`
- Job-style queue via `/jobqueue`
- Rubric quiz mode: `/testmode`
- Export XP and rubric with `/export`

---

🧠 TEACHING SYSTEM – v5.8

| Feature              | Description                                                    |
|----------------------|----------------------------------------------------------------|
| Slash curriculum     | Day-by-day drills, feedback loops, adaptive retries            |
| XP + ranks           | 5 XP per drill, with ranks: Student → Shinobi                  |
| Rubric-based grading | 7 traits scored from 1–5                                       |
| Memory-based review  | Tracks weak skills and triggers spaced repetition              |
| Reflection coaching  | Triggered at score <15                                         |
| Tiered lessons       | `/lesson` now has depth levels and checkpoints                 |
| Job-style prompts    | Real-world test queue gated by rank                            |
| Peer layer           | Mentor invites and leaderboard progression                     |
| Certification        | `/promptpass` requires >20 avg and grants resume + PDF badge   |

---

🧩 CORE COMMANDS (v5.8)

`/start` → onboarding  
`/day1`–`/day7` → skill drills  
`/lesson` → teaching by rubric trait  
`/review` → retry weak drills  
`/refresh` → spaced repetition  
`/sensei` → feedback hub  
`/promptpass` → certification  
`/rank` → XP and dojo level  
`/progress` → rubric score chart  
`/mentorcode` → invite peer  
`/leaderboard` → Shinobi rankings  
`/jobqueue` → task stream (Evaluator+)  
`/badge`, `/visualmap`, `/export`, `/testmode`

---

🎯 CERTIFICATION REQUIREMENTS

To unlock `/promptpass`:

- 15+ SkillDrills  
- Rubric average ≥ 20  
- Must pass 5 consecutive prompt scores  
- Unlocks PDF + resume output

---

💙 SUPPORT

PromptDojo is community-supported. `/support` links to Ko-fi and unlocks bonus modes.
