---
layout: post
title: "JManc Unconference 2026 — AI, Engineering Culture, and Community"
date: 2026-07-10
categories: 
  - tech
---

On **July 10, 2026**, I attended **JManc Unconference 2026**, held at AutoTrader's new office at **No. 3 Circle Square, Oxford Road, Manchester**. Doors opened at 8:30am and the event was up on the **14th floor** — the views over Manchester were already a great start to the day. The space itself was something — a beautiful modern office, and the big massive screen in the main area made the keynote presentation feel like a proper event. It was a great day, full of honest conversations and sessions that actually made you think.

![JManc Unconference 2026](/assets/jmanc_unconference_2026_4.png)

---

## A Day Shaped by AI

Compared to last year, one thing was immediately obvious: **AI was part of almost every conversation**. Java frameworks, engineering culture, the future of our jobs — it didn't matter what the session was about, AI found its way in.

That felt different. It wasn't just a hot topic anymore. In 2026, AI is something people are genuinely grappling with — how to use it well, what it means for the way we work, and honestly, what it means for us as engineers.

---

## Keynote: Staying in the Driver's Seat

The day opened with a keynote by **Clare Sudbery** — [*"The Power of Craft: Staying in the Driver's Seat of AI-Assisted Development"*](https://publish.obsidian.md/clare-sudbery-questions/Event+Resources/Talks/2026/26-07-10+JManc+unconference%2C+The+Power+of+Craft+-+Staying+in+the+Driver%E2%80%99s+Seat+of+AI-Assisted+Development) — delivered in front of that big screen, which added a nice weight to the whole thing. Her [slide deck](https://speakerdeck.com/claresudbery/the-power-of-craft-staying-in-the-drivers-seat-of-ai-assisted-development) is worth a look if you missed it.

Clare opened by acknowledging something many of us quietly carry: AI is bringing up a dizzying mix of emotions. Are we being left behind if we don't "vibe code"? Is it even possible to keep up with the disorienting pace of change? It's easy to feel alienated by the sheer scale of what's happening in our industry. But her message was clear and grounded — approached with the **spirit of exploration**, AI can actually enhance the best parts of our work: helping us experiment, learn, and solve problems in new ways.

One of the references that resonated deeply was **Kent Beck** — the person who gave us TDD and the red-green-refactor discipline that so many of us build on every day. Kent has spoken about how AI agents have brought back the joy of building software for him after decades of coding. Clare's point was elegant: bring that same **craftsman mindset** to AI. Be curious, stay disciplined, be like Kent. The engineering values we've relied on for decades — care, judgement, and craft — are not liabilities in an AI world. They are precisely our **greatest advantage**.

What stuck with me: **the engineers who will thrive are not those who hand their thinking to AI, but those who direct it**.

One line she said that I keep thinking about:

> *AI has a planetary brain, but it lacks real-world wisdom.*

AI has read practically everything. It can write code fast and often surprisingly well. But it doesn't have the lived experience of sitting in a production incident at 2am, or understanding why a particular business decision was made three years ago. That context, that wisdom — it still lives with us. The question is: **how do we make sure we don't lose it?**

---

![The Marketplace — session topics on the wall](/assets/jmanc_unconference_2026_3.jpg)
*The Marketplace — everyone pitched their topics for the day. As you can see, AI featured... a lot 😄*

## AI and the Engineering Culture Question

Almost every session touched on this in some way: **AI is changing how we work — but how do we make sure it doesn't change what we value?**

### Software Engineering Is More Than Writing Code

One session dug into how AI actually affects software engineers day to day. Nobody disagreed that AI can write code well when you give it clear requirements and a decent prompt. That part's real.

But the thing is, writing code was never really the hard bit. The hard bits are understanding what actually needs to be built, designing systems that hold up over time, dealing with production when things go wrong, and working with people who have very different ideas of what "done" means. AI doesn't really help with any of that yet.

If anything, maybe AI picking up more of the implementation work is a chance for engineers to spend more time on the things that matter more:

- Designing better, more resilient architectures
- Really understanding the business and its context
- Working more closely with stakeholders
- Getting ahead of production problems before they become crises

My worry — and it came up in the room too — is that as AI makes delivery faster, there's pressure to undervalue the engineers who do the deeper thinking. We need to push back on that and keep recognising **engineering craft and depth** for what they're worth.

### Running Local LLMs — Practical AI in Action

One session had a really practical take: running a local **Qwen model** as a coding assistant. The approach was smart — use a proprietary model to come up with a development plan, then hand the actual implementation to a locally hosted model that can churn away overnight. You cut down on token costs and your source code never leaves your machine. It was a good example of using AI thoughtfully rather than just reaching for the most expensive option.

### Java and AI Frameworks

There was a lively discussion on building AI-powered applications in Java, with frameworks like **Spring AI**, **Embabel**, and **LangChain4j** all getting mentions. But alongside the enthusiasm, people were pretty candid about the challenges — hallucinations, models behaving differently over time, prompts that stop working, gradual degradation. These are real problems that don't have neat solutions yet, and they require proper engineering discipline to manage.

---

## Is Spring Still Relevant?

One session asked the question directly: with **Quarkus** and **Micronaut** gaining traction, is Spring Boot still worth it?

The honest answer the group landed on: yes, for most teams. Quarkus and Micronaut are genuinely faster to start and lighter on memory, but Spring Boot has years of production trust behind it, a massive community, and an ecosystem that's hard to walk away from. Once **Spring Data** is woven through your domain logic — across relational databases, NoSQL, search — switching feels less like a migration and more like a rewrite.

The one exception people agreed on was ultra-low-latency systems — front-office trading and similar environments where microseconds actually matter. For everything else, Spring Boot isn't going anywhere.

---

## Protecting Engineering Culture

The thing I kept coming back to throughout the day was this: **the AI conversation is really a conversation about who we are as engineers, and what we want to hold onto**.

As AI gets more capable, there's a genuine risk that we slowly stop valuing the things that make engineering meaningful — the curiosity, the care, the hard-won experience, the mentorship, the willingness to say "I'm not sure, let me think about this properly." Events like JManc matter because they're a place where those things are still front and centre.

It was also really good to see more volunteers helping out with the **Manchester Java Community**. A community only stays alive if people put time into it, and it's encouraging to see that happening.

---

## A Big Thank You

A heartfelt thank you to:

- 🙏 **AutoTrader** — for hosting us at No. 3 Circle Square. The 14th floor office is stunning, that big screen made the keynote, and starting the morning with breakfast and those views over Manchester was a proper treat.
-  **Morson Edge** — for their support in making this event happen.
-  **Manchester Java Community** — for organising another excellent unconference and continuing to build something genuinely valuable for the regional tech community.

---

Already looking forward to **JManc 2027**. See you there! ☕🚀
