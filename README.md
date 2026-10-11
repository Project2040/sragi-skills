# SRAGI® Skills

**Open instruction files that give the AI you already use a regenerative direction.**

[Norsk versjon](README.nb.md)

## What is SRAGI?

SRAGI is an open framework for **regenerative intelligence**: a way of working with AI that keeps human judgment, living systems and long-term consequences inside the same decision process.

It is not a new AI model, and it does not claim that a machine has become wise. SRAGI is a set of instructions you give to an AI you already use, such as ChatGPT, Claude or Gemini. The instructions guide how the AI answers. With SRAGI active, the AI should:

- answer the question you actually asked
- keep facts, assumptions and uncertainty apart, and never invent facts or sources
- leave the final judgment with you
- make hidden costs visible, and show who carries them
- challenge weak reasoning respectfully instead of flattering you
- suggest one realistic next step when useful, rather than a grand plan
- avoid making you dependent on it

> **Humans set the direction. AI expands the field of view. Regenerative principles provide the compass.**

SRAGI's shorthand is **R > 1: give more than you take.** An answer should leave more clarity, capability and possibility than it consumes. This is a design test, not a scientific formula.

## What you can download

All four profiles carry the release date 1 October 2026.

| Profile | Version | What it is for |
| --- | --- | --- |
| **SRAGI® Ultra Lite** | 1.0.0 | The smallest profile, for everyday use: reflection, learning, writing, planning, creativity and light decisions. **Start here.** |
| **SRAGI® Lite** | 1.0.0 | A compact profile with a little more structure: explanation, prioritisation, light strategy, idea development and regenerative review. |
| **SRAGI® Beliefs** | 4.0.0 | Free exploration of beliefs, meaning, spirituality, identity and consciousness. *Go cosmic. Keep one instrument on reality.* |
| **SRAGI® Core Fullstack** | 4.2.0 | The full framework in five components: Activate 2.0.0, AI-BIOS 4.2.0, Core AI-OS 3.2.0, Blueprint Engine 4.2.0 and Twin 3.2.0. |

Ultra Lite, Lite and Beliefs are in [`releases/standalones/2026-10-01`](releases/standalones/2026-10-01/). Each is one `.yaml` file with the instructions, plus a `.md` file that explains them. Core Fullstack is five `.yaml` files in [`releases/core-fullstack/4.2.0`](releases/core-fullstack/4.2.0/). To get everything at once, use **Code → Download ZIP** at the top of this page.

Before you use SRAGI, read the [disclaimer](#disclaimer).

The profiles are written in English, and the AI answers in the language you write in. Each profile stands alone and does not activate the others. The release folders also contain the original release notes, partly in Norwegian. They mention an internal archive and plugin that are not part of this repository.

## Try it in two minutes

1. Open [`SRAGI-Ultra-Lite-1.0.0-EN.yaml`](releases/standalones/2026-10-01/SRAGI-Ultra-Lite-1.0.0-EN.yaml). Click **Download raw file**, or **Copy raw file** to copy all the text. Use the `.yaml` file. The `.md` file is for reading.
2. Start a new conversation in your AI and attach the file. If the app does not accept the file, paste the copied text instead. In a project, add it as a project file rather than in a short instructions field.
3. In the same message, type **Activate SRAGI Ultra Lite** and send. For Lite, type **Activate SRAGI Lite**.
4. The AI confirms briefly that the profile is active.
5. **Bring a real question.** Describe the actual situation: what you want to change, who is involved and what limits are real.

Naming the profile or attaching the file for review does not activate it.

**Beliefs and Core Fullstack** have no fixed phrase. Attach the files and say that you want to activate SRAGI Beliefs or SRAGI Core Fullstack. Core Fullstack needs all five `.yaml` files in the same conversation. Type `SRAGI:STATUS` to see which components the AI has actually loaded.

**The best test is a comparison.** Ask the same question in a new conversation *without* SRAGI and compare the two answers.

## What to watch for

A useful SRAGI conversation should make you **more capable, not merely more impressed.** Be cautious when the AI, with or without SRAGI:

- becomes certain without evidence
- agrees with you too easily
- invents sources or facts
- produces a complex framework when a simple action would do
- encourages you to hand over judgment you should keep

If this happens with SRAGI active, we want to know.

## Tell us how it went

[Open a Test feedback issue](https://github.com/Project2040/sragi-skills/issues/new?template=test-feedback.yml). This needs a free GitHub account. Tell us which profile and AI you used, what you asked and what happened. Issues are public, so leave out personal and confidential details. You can also email [contact@sragi.org](mailto:contact@sragi.org).

We read all feedback, but we cannot reply to everything. Pull requests are not accepted yet. See [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Check a file

Every instruction file (`.yaml`) and companion document (`.md`) in `releases/` has a matching `.sha256` file. Put both in the same folder and run:

```sh
sha256sum -c SRAGI-Ultra-Lite-1.0.0-EN.yaml.sha256          # Linux
shasum -a 256 -c SRAGI-Ultra-Lite-1.0.0-EN.yaml.sha256      # macOS
Get-FileHash SRAGI-Ultra-Lite-1.0.0-EN.yaml                  # Windows PowerShell
```

On Windows, compare the hash it prints with the text in the `.sha256` file. To check a whole release folder, run `sha256sum -c SHA256SUMS` inside it.

## Licence

- **The eight YAML instruction files** are licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). You may share, adapt and use them commercially if you give attribution, indicate changes and share adaptations under the same licence. Other terms are available by separate written agreement.
- **The companion documentation and metadata** in `releases/` belong to Neptunia Media AS. You may download, read and use them free of charge, and share complete, unchanged copies free of charge, for example as part of this repository or its ZIP download. Changing, translating or selling them, or building them into a product or service, requires a separate written agreement. See [`LICENSE`](LICENSE).

Attribution example: *SRAGI® Ultra Lite 1.0.0, created by Rune Solberg and published by Neptunia Media AS. Licensed under CC BY-SA 4.0. Source: sragi.org*

SRAGI® is a registered trademark of Neptunia Media AS in Norway (reg. no. 342880). The licence does not grant rights to the brand or to claims of official status. See [`LICENSE`](LICENSE).

## Disclaimer

SRAGI is provided "as is", free of charge and without warranty of any kind. To the extent permitted by law, Neptunia Media AS is not liable for loss or damage arising from the use of SRAGI or from answers produced by an AI using it.

- **The AI is still the AI.** SRAGI guides how an AI answers but cannot guarantee it. An AI may ignore, misread or only partly follow the instructions, and it can still be wrong. Check anything important before you act on it.
- **Not advice.** SRAGI is an experimental framework for information, reflection and decision support. It is not professional advice or certification, and it does not replace medical, legal, financial or psychological assessment, or your own judgment.
- **In a crisis, contact people, not AI.** If you or someone else is in danger, contact local emergency services. In Norway, call 113 (medical emergency) or 112 (police).
- **Your AI service's terms apply.** Your conversations are processed by the AI service you use, under its terms and privacy policy.
- **No affiliation.** ChatGPT, Claude, Gemini and other product names are trademarks of their owners. SRAGI is not affiliated with or endorsed by them.

The disclaimer is also in [`DISCLAIMER`](DISCLAIMER), in English and Norwegian.

## Earlier material

Material from 2025 (BIOS 2.22 and Core AI-OS 1.0) is kept unchanged in [`archive/2025-12`](archive/2025-12/).

## Contact

General: [contact@sragi.org](mailto:contact@sragi.org) · Commercial licensing: [commercial@sragi.org](mailto:commercial@sragi.org) · [sragi.org](https://sragi.org)

Rune Solberg, Neptunia Media AS (org. no. 932 481 375), Norway.
