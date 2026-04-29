![[0428.mov]]

**Role:** Solo designer & developer
**Timeline:** Jan – Apr 2026
**Type:** Capstone · Chrome Extension

---  

Four years ago, I was stuck in my room during lockdown, staring at a closet full of clothes I didn't like anymore.

Most of them I'd bought on impulse — chasing some version of myself I'd assembled from TikTok and Instagram. The pandemic forced me to confront it. I upcycled what I could, donated the rest, and felt immense relief.

I broke out of the cycle. But I know so many people are still stuck in it.

92 million tonnes of textile waste are produced globally every year. 85% ends up in landfills. The scale of the problem is enormous — but the root of it is personal and psychological. So that's where I started.

---

## Why do we keep buying things we don't need?


Before building anything, I spent time trying to actually understand the cycle. Not from a sustainability angle — from a behavioral one. Why does someone who *knows* they have too many clothes still click buy?


I reviewed research, mapped causes, and started talking to people. I posted on r/anticonsumption and r/sustainableshopping — two communities full of people who are aware of the cycle and still fighting it. The posts got over 115,000 views combined. People had a lot to say.


I followed up with 9 interviews. I let conversations go wherever they went. And across all of it — the research, the Reddit posts, the interviews — one pattern kept appearing that I hadn't expected.


**People already pause at the cart.**


Not occasionally. Consistently. They leave things in their bag for days. They remove items. They close the tab and come back. They second-guess. The hesitation is already there — it's just not being used for anything.


That was the insight that changed the whole project. The pause already exists. I just needed to make it mean something.


---

## Who keeps ending up in this cycle?


Through the research, a clear picture of the target user emerged. I started calling her the aspirational scroller.


She's 18 to 29. She wants to buy better — she cares about sustainability, she's self-aware — but she doesn't always have the budget, so she defaults to fast fashion. And she's not just buying a sweater. She's buying into a version of herself she's trying to become.

  
She's extremely online. TikTok is her shop window. Adding to cart has become muscle memory. One-click checkout means spending money barely feels like spending money anymore.

  
The dopamine hits the moment she clicks buy. The guilt arrives with the package.


She already wants to make better choices. She just gets stumped.


She doesn't need fixing. She needs a moment.


---

## What was already out there

Before designing anything, I looked at what already existed.

There's an extension called The Impulse Judge that surfaces humorous "roasts" you have to type out before checking out. Creative, effective trigger point — but the design is rough and the humor wears thin. I tested it with past interviewees. They agreed.

Then there's Think Twice, Buy Once — a mobile app that encourages you to wait before buying and tracks money saved. Clean layout, but no contextual pop-up. You have to manually enter every item you're considering, outside the shopping context entirely. Too much friction.

Neither one combines the right things: the moment (at checkout, in context) with the experience (warm, non-judgmental, designed with care). That's the gap.

---
## Testing the idea before building it

I didn't start with code. I started with cards.

I kept thinking about what a well-meaning friend might say to someone about to make an impulse buy — someone who cared enough to ask, but would never make you feel guilty for it. I workshopped those nudges until I had prompts organized around three simple lenses: money, space, and need.

Then I printed them as little card packets and handed them to about 70 people to keep with them and use whenever they shopped online. I wanted the stakes to be real — used in context, not simulated.

I got 7 responses back. And that handwriting made it worth it:

*"Mmm... probably not :/"*

*"I would feel sad in the moment. I wouldn't think about it 30 minutes later. (temporary sadness)"*

*"It'll go on my shelf, near my storage boxes"*

3 out of 7 still bought. 4 didn't. But all 7 reflected. That was the whole point.

Those responses sharpened the copy, refined the tone, and gave me enough confidence to start building the real thing.


---
## So what is Sift?

Sift is a Chrome extension that intercepts the checkout button on H&M and surfaces a deck of playing-card-style prompts before you buy. It doesn't block you. It doesn't lecture you. It just asks one good question — and then gets out of the way.

The playing card metaphor was borrowed directly from the physical testing kit. That connection was intentional. The whole project is about making a pause feel tangible, not digital and clinical.

The three pillars came straight from the research — participants consistently described their regrets through these same three lenses:

- **Money** — Can I actually swing this? What am I giving up?

- **Space** — Will this have a home? What has to move to make room?

- **Need** — Do I want it or need it? Am I shopping for my actual life or my fantasy life?

Users choose which pillars they want active. They can change them on the fly. They can always skip. The whole experience is built around trust, not restriction.

---
## How it actually works

You're on H&M. You've got a few things in your bag. You click "Continue to checkout."

Sift intercepts that click. The page dims slightly. A card deck slides in from the corner. The first card says: *"Your cart's not going anywhere. Shuffle through, take your time, and jot down some thoughts."*

Each card after that is a prompt from your selected pillars. You can type a response — or just read and sit with it. There's a pencil icon if you want to change pillars mid-session; the deck reshuffles. There's a quiet exit link if today genuinely isn't the day for this.

The last card hands the decision back to you: *"That's it. The call is yours. If you go through with this purchase, cherish it."*

No guilt. No blocking. Just the pause that was already there — made a little more useful.

---
## The cards themselves

The prompts are split across three pillars, each with its own tone.

**Money cards are direct.** No softening.

*"If nothing here was on sale, would you still be checking out?"*

*"Does this cart feel like an investment in yourself, or a temporary fix?"*

**Space cards are warm.** Almost meditative — pulling you out of the screen and into your actual physical life.

*"Close your eyes. Where does all of this go when it arrives?"*

*"Is your closet a curated collection or just... crowded? Where does this addition fit in?"*

**Need cards are cheeky.** A best friend who loves you but will absolutely call you out while smiling.

*"If you couldn't post a photo in these, would they still be in your cart?"*

*"If this cart disappeared and you had to find every item again, would you bother?"*

---
## The exit

The dismiss button — "I don't need Sift today" — was just as considered as the rest. Clicking it opens a small modal:

*"Sift doesn't always need to fit. Maybe you're buying a gift for someone you love, or maybe you just really need this. Either way, it's yours."*

A small note at the bottom reminds you that you can reactivate from the toolbar any time.

No guilt. No "are you sure?" No friction. If someone needs out, they get out cleanly.

---
## The brand

Sift is grounded and reflective, so the palette is muted: Parchment, Stone, Terracotta, Espresso. Each pillar has its own accent — money in warm gold, space in sage green, need in dusty mauve.

The name came from committing to the card metaphor. You sift through decisions, through cards — so you don't have to sift through your closet later.

Typography: Happy Monkey for the wordmark, Geist for body, Geist Mono for labels and pillar tags.

---
## What I actually learned

The biggest thing this project confirmed: the problem isn't a lack of awareness. People know they overshop. They know they'll probably regret it. But willpower is a depleting resource against platforms that are very good at what they do.

Design that adds meaningful friction is more useful than design that lectures.

Sift doesn't try to stop people from wanting things. It trusts them to make good decisions when given a moment to breathe. That trust is the whole product.

If I could go back, I'd test even earlier. The physical cards were the right instinct — I'd have done three rounds of those before writing a single line of code.

---
## What's next

Expanding to more retailers. A reflection history page where you can look back at past sessions and notice your own patterns. A public launch. Maybe a mobile widget down the line.

---

*This started as a messy closet. It turned into a question about why we do this to ourselves — and whether a well-placed pause can help.*


*I think it can.*