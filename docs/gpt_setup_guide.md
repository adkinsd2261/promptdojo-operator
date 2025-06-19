PromptDojo Operator Setup

This document serves as the central blueprint for building, maintaining, and scaling PromptDojo as an Operator-native GPT product.

🧠 PRODUCT OVERVIEW

PromptDojo is a GPT-powered, dojo-style training experience for AI evaluation jobs. It is structured as an evergreen interactive curriculum with slash commands, XP/rank system, memory tracking, and a PromptPass certification system.

Mission: Train beginners into prompt evaluation pros through guided drills, live simulations, feedback, and repetition — no prior experience needed.

Current Version: v5.5 (Learning Overhaul)

🔗 FILE STRUCTURE (TO BE MAINTAINED IN GITHUB)

📁 promptdojo-operator
├── README.md
├── /config
│   └── promptdojo_v5.5.json
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

✅ WHAT THIS SYSTEM FIXES

Solves GPT memory reset issues by using persistent .md files as live role definitions

Enables AI assistants (Signal, Forge, Marketing) to pull structured knowledge via raw GitHub

Prevents chat collapse by enabling contextual onboarding and role-based intelligence

Adds long-term knowledge retention via spaced repetition, review drills, and adaptive feedback

🔧 OPERATOR BLUEPRINT

Core Commands:

/start – Launches user into Day 1 with onboarding + tutorial

/rubric – Explains 5-part grading system

/day1–/day7 – Themed progress arc, with adaptive pacing

/review – Repeats weak drills based on score memory

/sensei – Offers rewrites, reflections, feedback upgrades

/outlier – Real evaluator-style challenges

/promptpass – Certification trial with stricter logic and retry gate

/rank – Tracks XP, dojo rank, title

/progress – Tracks rubric averages, most missed skill

/support – Donation call-to-action

/roadmap – Public feature updates + donation transparency

/example – Provides model answers per prompt

/rephrase – Offers clarity rewrites

/language – Translates commands/feedback

/mentorcode – Future peer coaching + invite system

Certification Logic:

PromptPass unlocks after completing:

15+ SkillDrills

Rubric average > 20/25

Users must pass 5 straight evaluations

Certified users unlock resume output + PromptPass PDF + /finaltrial

XP / Ranks:

5 XP per SkillDrill, bonus for retries

Ranks:

Novice → Student → Apprentice → Evaluator → Shinobi

Shinobi = full unlock

🧠 LEARNING SYSTEM OVERHAUL (v5.5)

Key Fixes:

Structured daily curriculum (instead of single-prompt completion)

Review system: auto-prompts retry for low-scoring drills

Model answers: users can type /example after scoring <18 to see exemplar

Rewrite coaching: /sensei helps improve weak responses

Rubric quiz mode: reinforces 5-score logic via interactive quiz

Reflection prompts: forced after repeated low scores

XP locks: prevents skipping PromptPass before true prep

Emotional pacing: daily intros, tone variation, thematic motivation

🔌 WIRED FEATURES

GitHub .md structure → Operator memory & learning logic

JSON config contains all logic/state/flow

Ko-fi integration for /support

Adaptive coaching and slash command intelligence

Multilingual mode (WIP)

Public roadmap via /roadmap

Resume + certification output pipeline

