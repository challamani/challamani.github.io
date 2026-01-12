---
layout: post
title: "My 3-Year Rollercoaster at Daytona Systems India Pvt Ltd (2017–2019)"
date: 2026-01-12
categories: 
  - experiences
---

My 3-Year Rollercoaster at Daytona Systems India Pvt Ltd: From Junior Engineer to Senior Engineer (2017–2019)

# Beyond the Code: My 3-Year Rollercoaster at Daytona Systems India Pvt Ltd

Looking back at my time with Daytona Systems India Pvt Ltd (Jan 2017– Oct 2019), it feels like a lifetime of learning packed into three transformative years. It was the place where I first touched Kubernetes, traveled across continents, and learned that sometimes the best solutions come from a random GitHub repo rather than a complex enterprise plan.

## The Interview I Thought I Failed

I’ll be honest: I still don't know how I got the job. The interview was a gauntlet—a technical phone screen followed by a coding round that felt like climbing a mountain, ending with an Engineering Manager who asked questions I felt completely unprepared for. I walked out certain I’d missed the mark.

### Questions that I still remember:

- Implement a min stack, supporting push, pop, and getMin in O(1) time.
- Trapping Rain Water or Trapping Snow between buildings.
- Shortest path between two cities in a weighted graph.

But Daytona took a bet on me. I joined as a Software Engineer and, within a year, was promoted to Senior. That first appraisal was a huge moment of validation—it turned out that my "bad" interview was actually the start of a very successful partnership.

## Lessons from the "Early Days"

My first real task was a classic: configuring MySQL Datasources in Jboss for a payout backend. It sounds simple now, but back then, it was my "welcome to the big leagues" moment.

Then came the decisions we learn from. We moved to Payara Fish—looking back, probably one of our worst architectural calls!—but it taught me that tech choices have long-term consequences. I spent a lot of time in those days just trying to make the developer experience better. I remember writing a massive README and setting up the Payout Partner (PP) UI and Backend on local hosts so the rest of the team didn't have to struggle with setup every morning.

### The "Ugly" Solutions That Worked

Before I knew better, I was asked to enable auditing in the PP application. My solution? Using Java Reflection and .equals() to compare every field and store changes as key-value pairs in the DB.

Today, I’d probably use a dedicated auditing library or an event-sourcing pattern, but at the time, seeing that logic actually track changes in the database was a win. It solved the problem when we needed it most.

## In Bangalore Dev, built a payout solution for Malawi: The USSD Project

One of my favorite memories was the USSD application. We initially tried to implement in PHP with stack datastructure, but it just wasn't holding up. We eventually found a Java repository (github repo) utilizing a dequeue technique that was exactly what we needed.

It wasn’t an overnight success—we spent three months in limbo because the backend APIs weren't ready—but the payoff was worth it. Shipping that product and knowing that partners in Malawi were processing payments on simple, non-touchscreen phones was a powerful reminder of why we build software. It wasn't about the newest tech; it was about the reach.

## The Day Sania Raj Saved Us

We didn’t have unit or integration tests back then. Deployment was basically "hit go and pray." During a BAS (Banking Payments) deployment, everything crashed. No payments were processing, and—in a moment of pure panic—we realized the deployment team hadn't taken a backup of the JAR/WAR files.

I thought I was done for. But Sania Raj, a tech champion in the SA team, knew a deep Jboss trick to recover the previous version. That day, Sania didn't just save the deployment; he saved my sanity. It was a wake-up call about the importance of DevOps and safety nets.

## Exploring the Unknown: K8s and Camunda

By 2018, the "Cloud Native" buzz was starting. I was tasked with setting up a Kubernetes cluster on a laptop. There were no polished YouTube tutorials then. I ignored the official kubernetes.io docs (mistake!) and followed a "Bare Metal Kubeadm" blog. It was a mess, but it was my mess, and it led to our team’s first real knowledge-sharing session on container orchestration.

Later, we dove into the Camunda BPMN engine for HelloPaisa Bank’s customer onboarding. We were exploring the WSO2 stack and deploying everything into K8s. I even built some dynamic worker implementations for Camunda service tasks—PoCs that I was genuinely proud of.

## The South Africa Connection

Visiting South Africa twice wasn't just about work; it was about the culture. I remember a party at Sania’s house where he sat us down and explained what is Oauth2, how google's Latitude and Longitude capture works with satellite timestamp based algo. It was one of those "lightbulb" moments that you can't get from a textbook.

And of course, there was the fun—visiting Kruger National Park, seeing Cape Town, and bonding with the Mauritius team. Even the awkward moments, like my lead asking for an alcohol bottle and me—inexplicably—asking for the 2000 rupees back! I still wonder why I did that, especially since he was such a great mentor to me.

## Closing Thoughts

My final months at Daytona were spent on a PoC for dataset classification, using data to segment users into Gold and Silver tiers for automated discounts. It was a fitting end to a role that allowed me to constantly pivot between backend Java, DevOps, and data logic.

Daytona India wasn't just a workplace. It was where I learned to be a Senior Engineer, where I learned that a tech champion can save your career, and where I realized that software is ultimately about the people using it—whether they are in a high-rise in Bangalore or a village in Malawi.


What Daytona gave me:

- My first real exposure to Docker and Kubernetes.
- The chance to master Camunda and WSO2.
- Global perspective through international travel.

Lifelong friends and mentors.

In November 2019, I moved on to a new chapter with JP Morgan in Glasgow, UK, but the foundation of who I am as an engineer was built in the trenches at Daytona.