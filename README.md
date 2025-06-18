# 🧠 PromptDojo (Operator Edition)

**PromptDojo** is an Operator-native AI training tool that transforms beginners into prompt evaluation pros — in just 7 days.

Built entirely inside ChatGPT using a persistent `.json` + `.md` architecture, PromptDojo functions like a self-running dojo experience. Users complete daily drills, earn XP, and unlock certification — all guided by a dynamic AI instructor.

---

## 🎯 Mission

To make AI evaluation jobs like Outlier.ai and DataAnnotation accessible to anyone — with no prior experience — by turning training into a motivating, gamified journey.

---

## 🔍 Key Features

| Feature | Description |
|--------|-------------|
| ✅ **7-Day Curriculum** | Daily SkillDrills that build real evaluator skill |
| ✅ **Live Rubric Scoring** | Graded feedback using 5-point rubric (Clarity, Relevance, Depth, Brevity, Reasoning) |
| ✅ **PromptPass Certification** | Final exam earns downloadable PDF certificate |
| ✅ **XP + Rank System** | Level up from Student → Apprentice → Evaluator → Shinobi |
| ✅ **Donation Funnel** | `/support` and `/shinobi` routes encourage direct community funding |
| ✅ **Fully Modular** | All logic lives in GitHub `.md` + `.json` files for easy updates |

---

## 🧩 File Structure

📁 promptdojo-operator
├── README.md ← You are here
├── /config
│ └── promptdojo_v5.3.json
├── /docs
│ ├── operator_blueprint.md
│ ├── prompts_and_rubric.md
│ ├── gpt_setup_guide.md
│ └── changelog.md
└── /assets
├── logo.png
├── badge_promptpass.png
└── banner_twitter.png

yaml
Copy code

---

## 🧠 AI Operator Architecture

PromptDojo uses `.md` files as live memory for AI roles:

- `Signal`, `Forge`, `Marketing`, and others can self-deploy by reading raw GitHub docs
- Instructions, behaviors, and tasks are version-controlled and auto-loaded
- Slash commands like `/start`, `/day1`, `/rubric`, `/rank`, etc. route users through an entire training arc

---

## 🚀 How to Use

1. Visit the live GPT 👉 [PromptDojo](https://chatgpt.com/g/g-6852252d83e08191ba87d776ca14eba3-promptdojo)
2. Start with `/start` or `/day1`
3. Earn XP by completing drills
4. Pass `/promptpass` to unlock your certification
5. Donate via `/support` to help build the dojo 💙

---

## 💬 Questions?

DM the creator [@JavlinDev](https://twitter.com/JavlinDev) on X or visit [ko-fi.com/promptdojo](https://ko-fi.com/promptdojo) to support the project and see what's next.

---

## 🔒 License

MIT — use this blueprint, remix it, or fork it into your own Operator-powered product.