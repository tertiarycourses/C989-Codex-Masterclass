# Codex Masterclass

Take one startup — Cook & Bake Academy Singapore — from a written brief to a live, assisted and governed website in one day, using Codex, the agentic coding surface in the ChatGPT desktop app.

| Course detail | Information |
|---|---|
| Course code | `C989` |
| Programme | Non-WSQ |
| Duration | 1 day / 7.5 instructional hours (9:30am – 5:30pm) |
| Registration | [View course details and register](https://www.tertiarycourses.com.sg/codex-masterclass.html) |

## About the course

Learners play the AI-assisted developer behind Cook & Bake Academy, a fictitious cooking and baking school with two campuses and 20 hands-on courses (based on the [Codex demo site](https://alfredang.github.io/codex-demo/)). Each lab starts from what the previous one produced:

- **Build** — Codex plans the site with `/plan`, builds it from the course catalogue, adds durable rules in `AGENTS.md` and a sign-up form for every course, and publishes it to GitHub Pages and Sites.
- **Assist** — Codex turns the course brochures into a SQLite FTS5 knowledge base and builds a fully static RAG course assistant (HTML/CSS/JavaScript, no backend) driven to 30/30 golden questions with `/goal`.
- **Check** — the assistant gets a bring-your-own-key ChatGPT mode and is red-teamed; the whole site is QA-tested with `@Computer Use`.
- **Govern** — community skills from skills.sh, custom skills made with `$skill-creator`, a timed workshop popup, and a hook that re-checks the site after every edit.

Along the way learners use the Codex features that make an agent dependable: `AGENTS.md`, `/plan`, `/goal`, plugins, `@Computer Use`, skills from skills.sh, custom skills and hooks — and evaluate every result against evidence before it goes out.

## Learning outcomes

By the end of the course, learners will be able to:

1. Analyse agentic AI applications — ChatGPT, ChatGPT Work and Codex — and their strengths, limitations and suitability for a business problem.
2. Correlate the design of an agent's instructions, tools and retrieval with the efficiency and quality of the result.
3. Assess the effectiveness, safety and reliability of agent-built work using golden-question evaluation, hooks, Computer Use testing and human review.
4. Evaluate comparative effectiveness and recommend a governed way to run agentic AI applications in a real business, using observable evidence.

## Topics covered

| Topic | What it covers | Labs |
|---|---|---|
| **1. Fundamentals: Chat, Work and Codex** | evolution of AI engineering, harness engineering and the agent loop, OpenAI products and GPT-6 models, the desktop app and plugins, projects and permissions, the 7-step workflow, `/plan`, `AGENTS.md`, publishing | 2–4 |
| **2. Tools and the SQLite RAG Assistant** | Codex slash commands and `/goal`, RAG, a SQLite FTS5 knowledge base in the browser, golden-question evaluation, bring-your-own-key ChatGPT mode, red-teaming, `@Computer Use` QA | 5–8 |
| **3. Skills and Hooks** | `SKILL.md` vs `AGENTS.md`, installing skills from skills.sh, `$skill-creator`, a timed workshop popup, and a hook that re-checks every edit | 9–11 |

## Labs

Each lab has its own folder with the scenario and context, a step-by-step README (Markdown and PDF), copy-paste prompts (Markdown and PDF), starter assets, a solution state where the lab produces code, and an evidence checklist. Start with the [scenario](labs/SCENARIO.md) and the [labs index](labs/README.md).

The labs are numbered 2–11 to match the shared Cook & Bake lab series; the series' Lab 1 (market research) is not part of this course, so start at Lab 2.

2. [Plan and Build the Site with /plan](labs/lab-02-plan-and-build-the-site/README.md)
3. [Project Rules and a Sign-up Form for Every Course](labs/lab-03-rules-and-signup-forms/README.md)
4. [Publish the Site: GitHub Pages and Sites](labs/lab-04-publish-the-site/README.md)
5. [Turn the Brochures into a SQLite Knowledge Base](labs/lab-05-sqlite-knowledge-base/README.md)
6. [Build the Course Assistant and Drive It with /goal](labs/lab-06-course-assistant-and-goal/README.md)
7. [Add ChatGPT Mode, Then Try to Break It](labs/lab-07-chatgpt-mode-and-red-team/README.md)
8. [QA the Whole Site with @Computer Use](labs/lab-08-qa-with-computer-use/README.md)
9. [Install Community Skills from skills.sh](labs/lab-09-skills-from-skills-sh/README.md)
10. [Create Custom Codex Skills](labs/lab-10-custom-codex-skills/README.md)
11. [A Workshop Popup and a Hook That Checks Every Edit](labs/lab-11-workshop-popup-and-a-hook/README.md)

## Public package

- **Courseware v1.0** in [courseware/](courseware/):
  - [Slide deck (PDF)](courseware/Codex%20Masterclass%20%28C989%29-v1.0.pdf) · [PPTX](courseware/Codex%20Masterclass%20%28C989%29-v1.0.pptx)
  - [Learner Guide (PDF)](courseware/LG-Codex%20Masterclass%20%28C989%29.pdf) · [DOCX](courseware/LG-Codex%20Masterclass%20%28C989%29.docx)
  - [Lesson Plan (PDF)](courseware/LP-Codex%20Masterclass%20%28C989%29.pdf) · [DOCX](courseware/LP-Codex%20Masterclass%20%28C989%29.docx)
- [Learner Guide (Markdown, v1.0)](LG-Codex%20Masterclass%20%28C989%29.md) — concepts and the full step-by-step procedure for every lab
- [Scenario](labs/SCENARIO.md) and [labs index](labs/README.md)
- 10 self-contained lab folders; Lab 11's solution holds the complete verified Cook & Bake site

You need the ChatGPT desktop app ([download](https://chatgpt.com/download/)) with Codex, and a GitHub account. All business data is synthetic; every learner email address in the fixtures resolves to your own inbox through plus-addressing.

## Distribution boundary

This public repository contains the courseware, learner-safe guidance, synthetic data and lab assets. Only the current courseware version is published. Source references, build tooling, archived versions, credentials, `.env` files and QA artifacts are intentionally excluded. The API keys in Lab 11 (`sk-proj-TEST…`) are deliberate fakes used to prove the secrets hook works.

## Provider

Tertiary Infotech Academy Pte. Ltd.
UEN: `201200696W`
