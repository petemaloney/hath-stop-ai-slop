# AI-slop-stopper

A vaccine for the slopidemic.

I asked Claude to draft a LinkedIn post about /mcq and it came back as AI slop: signposts, a tidy moral at the end, a bulleted list of stats, and a joke I didn't make. So instead of fixing the post, I had Claude build a skill to fix the problem.

AI-slop-stopper does three things:

1. **Learns your voice from things you actually wrote.** You point it at samples: a Google Drive folder of texts, posts, emails, and Slack messages, plus any drafts where you rewrote what the AI gave you. Those rewrites turn out to be the best data, because they show exactly what you strip out. It only reads what you point it to.
2. **Drafts in that voice and runs a slop check before you see anything.** It scans for ten tells, including the "I didn't X, I Y" closer, staged jokes, guru bullets, and invented details, and rewrites every hit.
3. **Learns from your edits.** When you change a draft, it names what you changed and offers to add it to your voice profile.

It copies your quirks, not your rambling. If you run long, it keeps your specifics and drops the repeats.

## Setup

1. Download `ai-slop-stopper/SKILL.md` and add it in Claude under Customize > Skills.
2. Make a Google Drive folder called **Voice Samples** and drop in at least 10 things you wrote yourself, from at least 3 places (texts, email, work chat, social posts). Screenshots work.
3. Connect Google Drive in Claude, then say: "Build my voice profile from my Voice Samples folder."
4. Save the profile it gives you as your own private skill. Keep it private, since it's built from your personal messages.

After that, ask for any draft you'll send as yourself and it runs automatically.

## Works well with

[hath-mcq](https://github.com/petemaloney/hath-mcq), the /mcq skill that makes the AI interview you before it builds anything.

## License

MIT. Free to use, copy, and change. See LICENSE.
