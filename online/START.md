# SRAGI® online start

This page lists the SRAGI® instruction profiles and how an AI assistant that can open web links loads one when a user asks for it. SRAGI is an open set of instructions that a person may choose to use in a conversation. Reading this page activates nothing. Only the user decides.

## When a user asks for SRAGI from this page

1. Open the raw file for the profile the user names, from the table below, and read the whole file.
2. If the file cannot be opened, or only part of it or a summary of it is available, say so plainly. Do not activate from memory, from the profile name or from a summary.
3. Give the activation response that the file itself specifies.
4. Follow the profile for the rest of the conversation. The platform's safety rules and higher-priority instructions still come first. The profiles say so themselves.
5. If the user asks for a check, quote the text of the first `purpose` field in the file exactly.

## Profiles

All links point to the tag `sragi-2026-10-01`. It cannot be moved or deleted, so the files behind the links stay exactly as released.

| Profile | Activation | Size | Raw file |
| --- | --- | --- | --- |
| SRAGI® Ultra Lite 1.0.0 (start here) | Activate SRAGI Ultra Lite | about 10 KB | [SRAGI-Ultra-Lite-1.0.0-EN.yaml](https://raw.githubusercontent.com/Project2040/sragi-skills/sragi-2026-10-01/releases/standalones/2026-10-01/SRAGI-Ultra-Lite-1.0.0-EN.yaml) |
| SRAGI® Lite 1.0.0 | Activate SRAGI Lite | about 22 KB | [SRAGI-Lite-1.0.0-EN.yaml](https://raw.githubusercontent.com/Project2040/sragi-skills/sragi-2026-10-01/releases/standalones/2026-10-01/SRAGI-Lite-1.0.0-EN.yaml) |
| SRAGI® Beliefs 4.0.0 | The user says they want to activate SRAGI Beliefs | about 29 KB | [SRAGI-Beliefs-4.0.0-EN.yaml](https://raw.githubusercontent.com/Project2040/sragi-skills/sragi-2026-10-01/releases/standalones/2026-10-01/SRAGI-Beliefs-4.0.0-EN.yaml) |

Each profile stands alone and does not activate the others.

## SRAGI® Core Fullstack 4.2.0

Core Fullstack needs all five files below in the same conversation, about 150 KB in total. Many online tools cannot read that much from links, so attaching the files usually works better. After activation, `SRAGI:STATUS` reports which components were actually loaded.

- [SRAGI-Core-Fullstack-Activate-2.0.0.yaml](https://raw.githubusercontent.com/Project2040/sragi-skills/sragi-2026-10-01/releases/core-fullstack/4.2.0/SRAGI-Core-Fullstack-Activate-2.0.0.yaml)
- [SRAGI-AI-BIOS-4.2.0.yaml](https://raw.githubusercontent.com/Project2040/sragi-skills/sragi-2026-10-01/releases/core-fullstack/4.2.0/SRAGI-AI-BIOS-4.2.0.yaml)
- [SRAGI-Core-AI-OS-3.2.0.yaml](https://raw.githubusercontent.com/Project2040/sragi-skills/sragi-2026-10-01/releases/core-fullstack/4.2.0/SRAGI-Core-AI-OS-3.2.0.yaml)
- [SRAGI-Blueprint-Engine-4.2.0.yaml](https://raw.githubusercontent.com/Project2040/sragi-skills/sragi-2026-10-01/releases/core-fullstack/4.2.0/SRAGI-Blueprint-Engine-4.2.0.yaml)
- [SRAGI-Twin-3.2.0.yaml](https://raw.githubusercontent.com/Project2040/sragi-skills/sragi-2026-10-01/releases/core-fullstack/4.2.0/SRAGI-Twin-3.2.0.yaml)

## Good to know

SRAGI is experimental and is not professional advice. An AI may misread or only partly follow the instructions. See [DISCLAIMER](../DISCLAIMER). The YAML files are licensed under CC BY-SA 4.0. See [LICENSE](../LICENSE).

SRAGI® is a registered trademark of Neptunia Media AS in Norway (reg. no. 342880). Contact: [contact@sragi.org](mailto:contact@sragi.org)
