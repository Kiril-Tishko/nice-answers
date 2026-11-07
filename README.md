# Nice Answers

A diplomat's phrasebook for awkward moments. The site shows one situation at a time as a slide: you read it, try your own words, then press **Open the answer** to see a kind, diplomatic reply you can learn and use later.

## What's inside

56 situations in nine topics:

| Topic | For moments like |
| --- | --- |
| Saying no | Invitations, favors, extra work, lending money |
| Not answering | Salary questions, "when are you having kids?", gossip, confidential matters |
| Kind honesty | A gift you dislike, a meal that wasn't good, feedback on someone's work |
| Disagreeing | Meetings, wrong "facts", a boss's risky plan, offensive jokes |
| Buying time | Decisions on the spot, questions you can't answer yet |
| Under pressure | Unfair criticism, angry people, your own mistakes, interruptions |
| Grace notes | Compliments, condolences, a rival's promotion, apologies |
| Exits | Ending a long conversation, phone call or meeting |
| Diplomat-speak | Real communiqué language and what it actually means |

Each answer comes with alternatives, a short note on why it works, and sometimes a phrase to avoid.

## How to use it

Open `index.html` in any browser. No build step and no server needed.

- **Open the answer** reveals the talking point.
- **Remember** saves a phrase to your personal list (the *Remembered* topic). It is stored in your browser.
- **Shuffle** mixes the order. **List** shows every situation and answer on one page.
- Keyboard: `←` `→` to move, `Space` to open the answer, `S` to remember.
- On a phone, swipe left or right on the card.

To publish it as a website, turn on GitHub Pages for this repository (Settings → Pages → deploy from the `main` branch, root folder).

## Adding your own situations

All content lives in the `CARDS` list near the bottom of `index.html`. Each entry looks like this:

```js
{ c: "no",                       // topic id (see CATS just above)
  s: "The situation…",
  a: "The answer to learn.",
  alts: ["Another way to say it."],   // optional
  why: "Why it works.",
  avoid: "What not to say." }        // optional
```
