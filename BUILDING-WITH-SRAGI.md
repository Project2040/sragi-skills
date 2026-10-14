# Building with SRAGI®

**The AI model you already run + your expertise and technology + SRAGI = an AI service people can trust.**

You do not need a new model. SRAGI is an orientation layer written as text. It goes where your system prompt or instructions go, and it changes how your assistant reasons with people. Your model stays. Your knowledge, data and tools stay. SRAGI provides filter and focus. You provide the context.

## What each part brings

| Part | Who provides it | What it brings |
| --- | --- | --- |
| The AI model | You or your AI vendor | Language, general knowledge and reasoning |
| Expertise and technology | You | Your domain knowledge, data, tools, product rules and safety rules |
| SRAGI | A SRAGI profile (YAML) | How the assistant treats people: it answers the actual question, keeps facts, assumptions and uncertainty apart, never invents sources, makes hidden costs visible, leaves the final judgment with the human and avoids making people dependent on it |

## How to build it in

1. **Choose a profile.**
    - [Ultra Lite](releases/standalones/2026-10-01/SRAGI-Ultra-Lite-1.0.0-EN.yaml), about 10 KB: assistants in everyday use. Start here.
    - [Lite](releases/standalones/2026-10-01/SRAGI-Lite-1.0.0-EN.yaml), about 22 KB: a little more structure, for explanation, prioritisation and light strategy.
    - [Beliefs](releases/standalones/2026-10-01/SRAGI-Beliefs-4.0.0-EN.yaml), about 29 KB: services for reflection, meaning and identity.
    - [Core Fullstack](releases/core-fullstack/4.2.0/), five files and about 150 KB: regenerative systems design and complex decisions.
2. **Put the whole YAML file in your instruction layer.** Use it unchanged, and load all of it. Your own safety rules and product instructions stay above it. The profiles are written to follow host rules.
3. **Activate it as the host.** The profiles accept activation when the user *or the host* intends it. In a product, your system prompt states that the profile is active, so users do not need the activation phrase.
4. **Add your context next to it.** Describe what the assistant knows, which tools it has and what it must never do. SRAGI does not replace this. It decides how the assistant uses it.
5. **Test before you launch.** Ask the same questions with and without SRAGI, and compare. Use the [five test questions](online/README.md#then-test-it-with-five-questions) on flattery, grand plans, hidden costs, invented sources and dependence. A blind comparison, where the reviewer does not know which answer is which, gives the most honest result.
6. **Tell your users.** Say that the service uses AI and SRAGI, and show the [disclaimer](DISCLAIMER) where users start. Check your own legal duties, for example under the EU AI Act.

## Licence: what you may do

- **Free, under CC BY-SA 4.0.** You may use, share and adapt the YAML files, also commercially. Give attribution, mark your changes, and share adaptations under CC BY-SA 4.0.
- **Commercial licence.** If you want to build SRAGI into an existing product or service without the ShareAlike requirement, for example to keep your adapted profiles proprietary or ship them inside your product, a commercial licence is available.
- **The SRAGI® name.** Using the name in your product, for example "Powered by SRAGI®", or calling something certified or official SRAGI requires written permission.

Commercial licensing, permission to use the name and implementation support: [commercial@sragi.org](mailto:commercial@sragi.org). See also [LICENSE](LICENSE).

## Good to know

SRAGI is experimental and is not professional advice. An AI may misread or only partly follow the instructions, and you remain responsible for your service. See [DISCLAIMER](DISCLAIMER).

SRAGI® is a registered trademark of Neptunia Media AS in Norway (reg. no. 342880).
