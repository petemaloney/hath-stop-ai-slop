---
name: ai-slop-stopper
description: Draft anything a person will send as themselves (texts, emails, posts, Slack, stories) in their real voice, and scrub AI slop before handoff. Also builds or updates their voice profile from samples they point to.
---

# AI-slop-stopper: a vaccine for the slopidemic

AI writing has a smell. People can tell within two sentences, and once they can tell, they stop trusting the person who sent it. This skill makes drafts sound like the person who will send them, and checks every draft for slop before anyone sees it.

There are three jobs: build a voice profile, draft from it, and learn from the person's edits.

## 1. Find or build the voice profile

Look for an existing profile first: a skill or file named `<name>-voice` or similar. If one exists, read it and go to step 2.

If none exists, build one. Only read sources the person points you to. Never sweep their email, drive, or chat history on your own initiative. They decide what's in the sample.

### Sources, ranked by how much to trust them

1. **Writing they did on their own, for other humans.** Texts, social posts, personal emails, Slack messages, stories, anything written before AI touched it. This is the voice.
2. **Edit pairs.** Any place you (or another AI) drafted something and they rewrote it before sending. The difference between your version and theirs is the most valuable data in the whole sample, because it shows exactly what they strip out.
3. **How they talk to an AI.** Lowest weight. People write to machines differently than to people: shorter, blunter, typo-ridden, commanding. Use it for vocabulary and attitude, never for sentence shape.

### Clean the sample before you learn from it

Many people already run their important messages through an AI. If you learn from those, you learn the AI's voice, not theirs. Before extracting anything:

1. **Remove pasted AI answers.** "Here's what ChatGPT says," bullet lists, bold headers, and long explainers.
2. **Flag likely AI-drafted messages sent as the person.** Signals: em dashes, straight apostrophes in text typed on a phone (phones produce curly ones), paragraph breaks in a text, and phrases like "No pressure," "To be clear," "That's on me," "I just wanted to." A message many times longer than the person's usual length is another sign.
3. **Show the person a sample of 10–12 flags to confirm** before trusting the detector, then remove everything it flags.
4. **Look for edit pairs inside the sample.** A raw message followed within minutes by a polished rewrite of the same thing is the best evidence of what the person keeps and what they cut.

AI help tends to show up exactly where the stakes are highest: apologies, conflict, rules, boundaries. Note which situations those were. Drafts for those situations are the ones most likely to read as AI.

Aim for at least 10 pieces across 3 or more contexts (texts, email, work chat, posts, stories). Below that, mark the profile **low confidence** and say so whenever you draft from it.

### Organize the profile by register

The same person writes a text, a work email, and a story very differently, so the profile gets one section per register. Typical registers:

- **Storytelling:** anything told as a story, whatever the destination
- **Texts to friends:** texts, WhatsApp, DMs
- **Transactional email:** customer support, logistics, quick replies
- **Work messages:** work email, Slack, Teams
- **Public posts:** LinkedIn, Facebook, anything broadcast

Give each register its own samples, traits, and confidence level. Mark a register "no samples yet" rather than guessing at it. When drafting, pick the register by format and destination, not topic. A story told inside a LinkedIn post uses the storytelling register for the story and the public-posts register for everything around it.

If a sample is a rough or unfinished draft, learn the voice from it but don't copy its rawness (typos, missing endings) unless the person says that's the target.

### What to extract, per register

Record what you observe, with a short real example for each item. No adjectives without evidence.

- **Sentence shape.** Long and chained, short and flat, run-ons, fragments. Whether they drop subjects ("saw your post") or never do.
- **How they open and how they stop.** Most real people just stop. They rarely land a closing line, and when they do, note how it's built.
- **Humor mechanics.** Deadpan, understatement, self-deprecation, running gags, absurd specifics, where the punchline sits.
- **Words they use, and words they'd never use.**
- **Punctuation and casing habits.** Em dashes or not, exclamation points, lowercase, caps for emphasis.
- **What they cut** from AI drafts (from edit pairs).

Never put personal content from a sample into the profile when it's sensitive (health, trauma, sex, legal trouble, anything about other people they wouldn't want copied). Record the style; leave the story with them.

### Keep the voice, trim the runs

Copy the quirks, not the length. If the person rambles in their samples, keep their specifics, their word choices, and the shape of their sentences, and drop the repeats and detours. The goal is them on a good day.

## 2. Draft

- **Never invent.** No made-up details, scenes, quotes, feelings, or takeaways. If a concrete detail would make the draft better, ask for it in one line instead of supplying one. Putting words in someone's mouth is the fastest way to get caught.
- Match the register for the format and destination (a text is not a LinkedIn post).
- Use full sentences with subjects unless the profile shows the person routinely drops them.
- Stay at or under the length the content needs.
- **Texts follow the person's real numbers.** Match their usual text length. If a text needs more room, split it into two or three texts the way they do, rather than sending one long one. Use curly apostrophes (’) and no em dashes, because those are the two clearest signs a text was pasted.

### The slop check (run on every draft before handoff)

Scan the draft for each tell below. Rewrite every hit. Don't just delete it; replace it with how this person would actually say it.

1. **Signposts.** "Here's the thing." "So I tried something simple." "Here's how it works." "Let me explain." Real people just say the next thing.
2. **The unearned closer.** A tidy final line that sums up the lesson, especially "I didn't X. I Y." or "It's not X, it's Y." Delete it and end where the content ends, **unless it's earned**. A closer is earned only when all three hold: it pays off a setup the piece built (a running gag, a repeated image), it uses that piece's own specifics so it couldn't be pasted onto anything else, and the person's own samples show they write closers like this. Never add one to a short post or message. Never invent the lesson; it has to be one the person stated.
3. **Tidy pairs and triplets.** "Some are idiotic. Others are brilliant. Both made it better." Three adjectives in a row. Parallel structure everywhere.
4. **Colon reveals.** "My first reaction was: ugh." Setups that pause for effect.
5. **Guru bullets.** Bullet lists for things a person would say in a sentence, especially stats on LinkedIn.
6. **Staged jokes and added kickers.** "Okay, they didn't." A joke tacked onto the end that the person didn't make.
7. **Invented specifics or feelings.** Any detail, emotion, or conclusion the person didn't give you.
8. **Even rhythm.** Paragraphs all the same size, a smooth transition into every one ("Then one day," "Eventually," "Fast forward").
9. **Clipped fragments.** "Divorce is official." "Proud of you." Unless the profile shows the person writes that way.
10. **AI vocabulary.** Delve, landscape, game-changer, journey, unlock, elevate, leverage (as a verb, outside finance), testament, navigate, "in today's world," em-dash pileups.

Some tells overlap with a person's real style: short stacked lines for a comic beat, a closer that pays off a gag. The profile decides. If the person's own samples do it, it's voice, not slop.

After rewriting, read the draft once more as the person's friend would. If any sentence makes you think "a bot wrote that," fix it.

### Handoff

Give the draft. If you need a detail from them, ask for it in one line after the draft. Don't explain your voice choices unless asked.

## 3. Learn from edits

When the person edits a draft or says it doesn't sound like them:

1. Compare your version with theirs, sentence by sentence.
2. Name what they changed in a line or two ("cut the closing line," "put 'I' back in," "swapped 'utilize' for 'use'").
3. Offer to add it to the right register in their voice profile. Save only when they say yes.

When they say a draft doesn't sound like them, the profile missed. Update the profile rather than starting over.
