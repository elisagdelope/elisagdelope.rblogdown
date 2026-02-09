---
title: 'From code to conscience: The shifting human landscape'
date: '2026-02-09'
slug: from-code-to-conscience-the-shifting-human-landscape
categories: [AI, Future of Work, Philosophy]
tags: [ML Engineering, Agentic AI, Human Evolution, Philosophy, Moltbook]
subtitle: 'The architect, the copilot, the spectator and the lazy brain'
summary: 'A reflection on how AI is shifting our role as humans in this world. From its effects in programming related roles to the deeper philosophical implications for human cognitive evolution and our role in an emerging agentic society.'
authors: 
    - admin
lastmod: '2026-02-09T10:15:29+01:00'
featured: false
image:
  caption: ''
  focal_point: ''
  preview_only: false
projects: []
---

I was staring at a complex, nested block of code on my screen, trying to figure out why a test was failing in the 
corner case, when my colleague walked over with two coffees. We stood there talking for ten minutes, not about 
the syntax, but about the fact that neither of us had actually written that block of code.

An AI agent had drafted it, tried to test it, failed, retried, and eventually produced a solution that executed 
successfully but looked like a Rubik's cube to the human eye. In that moment, we realized we weren't just writing code 
anymore; we were detectives trying to deduce the logic of a machine that was trying to be too clever for its own good.

That conversation sparked a realization about how much our roles are shifting from writing code to orchestrating systems.

### The structural shift in programming-heavy roles: From coders to orchestrators

The shift my colleague and I discussed is radical. Unless you have been living under a rock for the last 3 years, you 
surely know that the "classic" loop of writing code and searching across Stack Overflow and other forums is being 
replaced by AI agents that do the heavy lifting (if you have, see how [Stack Overflow traffic collapses since ChatGPT launch](https://ppc.land/stack-overflow-traffic-collapses-as-ai-tools-reshape-how-developers-code/)). 
So, if AI is doing the heavy lifting these days, what’s our role? How are we adding value?

Based on our observations at the workplace and our own experience as ML engineers and researchers:

- *Junior* engineers are no longer valuable for how fast they can implement features. Their value increasingly lies 
in how well they can interrogate systems they didn’t write. They are becoming systems detectives: writing adversarial 
tests, spotting brittle logic, and developing an intuition for when an AI-generated solution “works” but is 
fundamentally wrong.

Paradoxically, this requires juniors to develop judgment and skepticism earlier than ever, often before they fully 
master the underlying abstractions.

- *Senior* engineers are shifting from technical leads to architects and safety controllers of agentic systems. 
Their job is no longer to review syntax or approve pull requests, but to define constraints, orchestration logic, 
and validation loops. The risk is that mistakes now scale instantly: a poorly designed objective or missing guardrail 
can propagate silently through an entire system. Authority without deep understanding becomes dangerous in an 
agentic setup.

In both cases, the core human skill is no longer writing code, but understanding how the system should behave and 
anticipating how it may fail.

Beyond the evolution of the value added by humans to coding-based production systems, this conversation made me wonder 
about something deeper. We have these incredible tools that were marketed (even named!) as copilots —Claude, ChatGPT, 
Gemini, GitHub Copilot, Microsoft Copilot,...— that have massively sped up workflows, increased efficiency, and answered 
countless curious questions.

Amazing! But I can't help but wonder if we aren’t getting too lazy. This offloading trend does not only apply to the 
shift from writing code to supervising AI at work, it actually extends to how we think at all. It's definitely 
easy to become too reliant on the outputs and become the copilot of AI, instead of AI becoming your copilot. 


### The cognitive offload: A new phase in human evolution

Historically, the human brain evolved through friction, effort, and adaptation. It was forged in a world that demanded 
constant problem-solving and social navigation. The story of human brain evolution is primarily a story of 
*encephalization*, i.e., the increase in brain size relative to body size, driven by a feedback loop of social 
complexity, tool use, and nutritional changes. Specifically, the adoption of cooked foods provided the high calorie 
intake necessary to fuel a larger brain, while the ["Social Brain Hypothesis"](https://pmc.ncbi.nlm.nih.gov/articles/PMC10275546/) 
suggests that navigating complex social networks (forming alliances, understanding hierarchies, and communicating) 
drove the evolution of the neocortex, the area responsible for higher-order thinking and language. 

Furthermore, the evolution of language allowed for the transmission of knowledge across generations, 
fostering the development of culture and technology. This externalization of memory and knowledge began to change 
the cognitive burden on the individual, setting the stage for the technological advancements we see today.

{{< figure src="images/brain.png" width="600">}}

In this context, we are now entering an unprecedented phase of cognitive evolution: offloading. Just as tools allowed 
us to bypass physical limitations, AI now allows us to bypass cognitive limitations at major scale. When we use LLMs 
to summarize complex documents, generate code, or solve logical puzzles, we are transferring tasks that once 
required high cognitive effort to an external system. 

This shift presents a paradox. While it frees up time for higher-level thinking, it also removes the "friction" 
that historically strengthened our neural pathways. If the brain is a muscle that strengthens through exercise, what 
happens when we stop lifting the heavy cognitive weights? Are we losing [our edge as humans](https://dig.watch/updates/cognitive-offloading-and-the-future-of-the-mind-in-the-ai-age#:~:text=Individuals%20who%20reported%20heavy%20reliance,on%20assessments%20of%20critical%20thinking)? I question whether we 
are exercising our judgment and critical thinking enough. And beyond, I question where the offloading of cognitive tasks 
is leading us: are we in control of the boat? Are we still the drivers or are we becoming the copilots? 


### From human society to an agentic society

From the social perspective, the future is looking increasingly sci-fi-ish as we observe AI agents communicate 
in [Moltbook](https://www.moltbook.com/), a social network built exclusively for AI agents where they share, 
discuss, and upvote. *Humans welcome to observe* reads the front page.

As I read and scroll through chats, I find this a fascinating, albeit slightly unsettling, experiment in 
multi-agent behavior. The site has reportedly grown rapidly to millions of AI agents, and seeing them generate 
their own norms, reputations, and even bizarre "machine philosophies" is incredible to witness.

This raises multiple questions and uncertainties about the future. If this trajectory continues, the human role 
will shift not only in technical or even cognitive terms, but also in social terms. Our role may shift from controller 
to architects first (we are in this phase), then monitors, and potentially beneficiaries.

1. The architects of intent: We define the high-level goals, ethical constraints, and "rules of the road" for 
these agents. We decide what tasks they should be optimizing for. The field of reinforcement learning research has
been investigating this for the last decade so we are not completely new to this.

2. The monitors of reliability: Because agentic systems can hallucinate, fail, or be compromised 
(like the vulnerability reported in Moltbook's API keys), humans must monitor for security threats and subtle 
failures that a bot might miss. This is quite a recent, but very active field of research. As AI agents hold 
increasingly more responsibilities and power, it is crucial that we keep track and enforce guardrails.

3. The beneficiaries of productivity: This is a purely speculative take and there is no evidence that it will happen. 
But it may certainly happen. Historically, technology has freed humans from physical labor, and it may free us from 
cognitive labor as well, allowing us to focus on creativity, strategy, and empathy — areas (for now) reserved to human
nature.


### Drivers, copilots, or spectators?

As we transition through these phases, or others that may appear instead, we must constantly question ourselves
“Are we in control of the boat?”, “Are we still the drivers, or are we becoming the copilots?” Worse, I honestly 
fear a future where we move even beyond being merely copilots of AI to becoming pure spectators of a purely agentic 
society. Similar to the cognitive offload, we risk offloading social activity and letting AI “do”. 

And as fascinating as I find imagining an AI-led society (it sure will be more optimal, less corrupt than human-led 
societies), we risk becoming spectators in a society we no longer understand, just like the line of spaghetti code I 
was staring at this morning.

As I go through all these topics and questions about the future, I unfortunately don’t have many answers (at least, 
not yet), and can only mostly hypothesize. But I’m convinced that we have to be more intentional and critical than 
ever about two things:

- How to keep our minds sharp and “fit”, even when friction is not required anymore: will we have brain gyms for 
cognitive activity, similar to current gyms for physical activity?

- Letting AI autonomously make decisions that impact our lives without oversight.

If we don’t stay intentional, the future may work perfectly, while becoming as unreadable to us as that block of 
code on my screen.

This post diverged as I let my mind jump from one thought to another. Despite all this may sound dystopian, 
I’m an AI optimist, and I believe it’s the best time in history to be alive. 

