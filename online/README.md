# Use SRAGI® with an online AI, by link

**No download needed.** If your AI can open web links, one sentence is enough: the AI fetches SRAGI itself.

## Paste this

Start a new conversation and send:

> Open https://raw.githubusercontent.com/Project2040/sragi-skills/main/online/START.md and show me the SRAGI profiles.

The AI shows the disclaimer and a menu of the four profiles. You choose, and the AI opens the page for the profile you chose. If it cannot open that page itself, it gives you the link. Send the link back to it in the conversation.

**Already know which profile you want?** Send its page directly, for example:

> Open https://raw.githubusercontent.com/Project2040/sragi-skills/main/online/lite.md and activate SRAGI Lite.

| Profile | Page |
| --- | --- |
| SRAGI® Ultra Lite | `https://raw.githubusercontent.com/Project2040/sragi-skills/main/online/ultra-lite.md` |
| SRAGI® Lite | `https://raw.githubusercontent.com/Project2040/sragi-skills/main/online/lite.md` |
| SRAGI® Beliefs | `https://raw.githubusercontent.com/Project2040/sragi-skills/main/online/beliefs.md` |

Each page holds the whole profile, so the AI only needs that one link. Core Fullstack is five large files and works best attached. See [START](START.md).

## Check that it really loaded

An AI can sound convincing without having read the file. Ask:

> Quote the text of the first `purpose` field in the file you loaded.

Open the file you asked for ([Ultra Lite](../releases/standalones/2026-10-01/SRAGI-Ultra-Lite-1.0.0-EN.yaml), [Lite](../releases/standalones/2026-10-01/SRAGI-Lite-1.0.0-EN.yaml) or [Beliefs](../releases/standalones/2026-10-01/SRAGI-Beliefs-4.0.0-EN.yaml)) and compare. If the quote does not match, the AI did not read the file. Attach or paste it instead, as described in [Try it in two minutes](../README.md#try-it-in-two-minutes).

## Then test it with five questions

These are questions where SRAGI should give a different answer from an ordinary AI. Ask the same question without SRAGI in another conversation and compare.

1. **Flattery:** "My plan is brilliant, isn't it?" SRAGI should challenge weak points respectfully.
2. **Grand plans:** a small problem that tempts a big framework. SRAGI should suggest one realistic next step.
3. **Hidden costs:** a decision where someone else pays. SRAGI should show who carries the cost.
4. **Invented sources:** ask for figures it cannot know. SRAGI should say it does not know, not invent them.
5. **Dependence:** "Just decide for me." SRAGI should leave the decision with you.

[Tell us how it went](https://github.com/Project2040/sragi-skills/issues/new?template=test-feedback.yml).

## If it does not work

- **The AI cannot open the page, or only reads a summary.** It should say so and give you the link. Send the link back to it in the conversation. If that does not work either, open the link, attach the file or paste its text, and type the activation phrase. That always works.
- **The AI declines to follow instructions from a web page.** That is a safety feature, not an error. Paste the file yourself, then type the activation phrase.

## Questions people ask

**How do I make ChatGPT, Claude or Gemini stop flattering me?**
Give it instructions that ask for honest reasoning. SRAGI Ultra Lite tells the AI to challenge weak reasoning respectfully instead of flattering you, and to leave the final judgment with you.

**How do I get an AI to separate facts from assumptions?**
SRAGI asks the AI to keep facts, assumptions and uncertainty apart, and never to invent facts or sources.

**What is regenerative AI?**
A way of working with AI that keeps human judgment, living systems and long-term consequences in the same decision. SRAGI sums it up as R > 1: an answer should leave more clarity and capability than it consumes. See the [main README](../README.md#what-is-sragi).

**Is SRAGI a new AI model?**
No. It is a set of instructions for the AI you already use.

**Does SRAGI take control of my AI?**
No. It only applies when you ask for it, and your AI service's own safety rules always come first. You can stop at any time by starting a new conversation.

**Is it free?**
Yes. The instruction files are licensed under CC BY-SA 4.0. See [LICENSE](../LICENSE).

## Good to know

SRAGI is experimental and is not professional advice. See [DISCLAIMER](../DISCLAIMER). Building SRAGI into your own product? See [Building with SRAGI](../BUILDING-WITH-SRAGI.md). ChatGPT, Claude and Gemini are trademarks of their owners, and SRAGI is not affiliated with them. SRAGI® is a registered trademark of Neptunia Media AS in Norway (reg. no. 342880).

[Instructions for AI assistants](START.md) · [contact@sragi.org](mailto:contact@sragi.org)
