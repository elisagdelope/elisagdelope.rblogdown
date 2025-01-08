---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "On the weight of AI: Felix Hill’s 200Bn Weights of Responsibility"

subtitle: ""

summary: "A reflection on the transformative potential of simply asking for what you want or need, and how taking the initiative can lead to surprising opportunities and benefits. While asking doesn't guarantee success, it opens doors and creates opportunities for growth."

authors: 
- admin

tags: []

categories: []

date: 2025-01-02T18:22:01+01:00
lastmod: 2025-01-08T18:23:01+01:00

featured: false

draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false
  placement: 2

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
I recently stumbled upon Felix Hill’s post [200Bn Weights of Responsibility](https://docs.google.com/document/d/1aEdTE-B6CSPPeUWYD-IgNVQVZM25f7MF-u9qn5KJJvo/mobilebasic), expecting a technical deep dive into AI research at big tech labs. 
Instead, I found one of the most profoundly human, moving blogs I’ve ever read—one that shook me to my core. 

It’s raw, it’s real, and it strikes a chord for anyone who’s worked in AI, or any field that demands everything you have and then asks for more.

Felix exposes the reality of working at the forefront of AI these days (having worked at Google DeepMind), revealing a stark contrast to the glossy image of stock options and groundbreaking innovations. 
Beneath the surface lies relentless pressure and an insatiable demand for results, which shattered my naïve belief
that industry labs were immune to the stress I had always associated with academia's [publish or perish](https://pmc.ncbi.nlm.nih.gov/articles/PMC2439458/) culture.

---
### When success is stress

Felix Hill is no longer with us, and his words carry an aching honesty that makes his reflections both inspiring and devastating.
His passing adds poignant urgency to the conversation about how we design, support, and sustain work in modern AI, and beyond, for any transformative technology we create. 
Should we confront and rethink the systems we build around it?

I never met Felix in real life, but read some of his papers during my PhD and found his research inspiring. Now his words made me bittersweetly question the human cost behind the fast and furious race for [AGI](https://cis.temple.edu/~pwang/Publication/AGI_Aspects.pdf).
Rest in peace, Felix.

Felix paints a vivid picture of what it’s like to work as a researcher in AI today at a tech giant lab that might surprise many: behind the glamorous image of stock options and breakthrough innovations lies a world of relentless pressure and unyielding demands.

Yes, the field is booming, and the world is fascinated —whether it’s by AI-powered toothbrushes or language models so massive they could probably bench-press a small planet; 
But for those working behind the scenes, the pressure is immense.

{{< figure src="images/stress.jpg" width="650" title="Can we make this field emotionally sustainable?">}}

Reflecting on my own experience as a job market candidate last year, there seems to be an unspoken rule: success often hinges on an impressive, long list of publications.

Initially, I thought this intensity was confined to the academic culture, where, especially in the AI and LLM fields, publications have become currency for promotions, GPU access, internships, grant funding, high-paying industry jobs, startup opportunities, etc.

And while you'll hear faculty hiring committees and industry HR teams claim “We don’t count papers or citations”, the profiles of successful candidates tell a different story. 
Rarely do they have just a few papers. It feels as if the side effects of research have started to overshadow its original purpose of advancing knowledge for its own sake, and now everything is about chasing the rewards tied to the act of research.

And this pressure extends far beyond the job market.

In transitioning from academia to an industry lab, I was struck by the intense drive to be *first and best*. 
Felix’s reflections on this relentless competition echoed my own growing realization of just how demanding this environment can be.

The pressure isn’t just about delivering cutting-edge technology ahead of the competition—it’s also a wake-up call for practitioners struggling to keep pace with AI’s rapid advancements. 
As [Yann LeCun](https://yann.lecun.com/) once remarked, *“You cannot keep updated. Just pick your area and stick to those updates.”*



### The inescapable spotlight (not in Europe tho)
Felix recounts a moment at a party, hoping to unwind with a drink in hand and an 80s synth-pop playlist in the background. 
Suddenly, he’s cornered by a crowd—lawyers, doctors, and bankers—all eager for his take on ChatGPT. 
At first, it sounds flattering. But for someone living and breathing AI around the clock, the last thing you want is to discuss work at a social event. 
Sometimes, you just want to talk about football or debate about pineapple on pizza. (*Spoiler: it belongs.*)

This anecdote highlights a unique stressor for AI researchers: the inability to escape their work. 
In the main US cities, where even the walls advertise GPUs, the relentless immersion in AI culture turns researchers into mini-celebrities. 
It might sound cool, but the constant spotlight comes with no "off" switch. And researchers are typically neither trained for nor interested in celebrity-level attention.

Whether for better or worse, the dynamic in Europe is different. 
While Silicon Valley is playing the game of AI dominance, Europe plays the game of [AI regulation](https://www.whitecase.com/insight-our-thinking/ai-watch-global-regulatory-tracker-spain). 
This means no social spotlight on researchers here, but hey we have our own trouble: a stifling lack of innovation. The loss of Europe's significance in the
global AI landscape is however a topic for another post.



### The war of the weights

Felix draws a striking analogy between working in modern AI and being at war—not a literal one, but a relentless battle of scale, speed, and stakes. 
It feels less like tinkering in a lab and more like an arms race. The goal? Build the biggest, baddest model to crush the competition. 
Driven by tech giants’ push for dominance, this war has reshaped not only industry, but also academia. 
Since the start of my PhD in 2020, I've seen the focus slowly but surely shift towards larger models and field-specific applications, leaving many areas of ML in the shadows.

The stakes are absurdly high, and the costs aren’t just financial or reputation-wise. Felix hits on something crucial here: the toll on creativity. 
When a researcher's job becomes about grinding out incremental improvements to massive systems, the joy of discovery—the reason most got into research—starts to fade. 
And the pressure of knowing that tiny tweaks in your research could swing billion-dollar stock valuations? That’s not what grad school prepares you for.

He makes a point on how the scale of modern AI has sidelined traditional scientific inquiry. 
In LLM research, almost no innovation is required beyond scale. And if it is, experiments would be so expensive it's not affordable. 
So, what's the role of scientists in this context?
He compares this to losing control over your own ideas, a crushing reality for researchers, typically driven by intellectual curiosity.

Even in fields of application of ML, where I have been working for the last years, one can easily observe how leveraging neural nets scale and most recently LLMs scale sidesteps most other methodologies.

The once-rewarding cycle of asking questions, testing hypotheses, and discovery now feels almost irrelevant when brute force and scale seem to win the day (remember the publications rush to win the GPU access race!).

{{< figure src="images/bruteforce.jpg" width="650" title="Can we make this field emotionally sustainable?">}}


---

### The rich man’s problem

Felix also reflects on the paradox of wealth in AI. You’d think sky-high salaries at tech giants [insert Meta/OpenAI salary reference here] would be a balm for the stress (I thought that too!) —spoiler: they don’t.

Making those huge amounts of money doing what you love can make you love it a little less, especially when external pressures (read: corporate greed) start driving your work. Remember that you typically don't get into research for the money.
Sudden wealth brings its own, unexpected issues. The allure of money can dilute the passion that initially drove your work, especially when corporate greed begins to dictate your direction. 
Let’s be real: not sure about nowadays, but nobody used to get into research for the money.

Felix describes the darker side of sudden wealth of AI researchers citing examples from celebrity culture: addictions, broken relationships, and a sense of purposelessness. 
That comparison hit me hard. In Europe, it feels worlds apart, as we don't have almost any big AI company nor those jaw-dropping half-million-dollar salaries (mind-blowing, right??).

{{< figure src="images/richman.jpg" width="650" title="AI researchers in Silicon Valley are mini-celebrities">}}

---


### The takeaway: Making AI human again

Felix’s post isn’t just about the stress; it’s a call to action for a kinder, more compassionate and supportive AI community. 
The world of AI might be built on weights and biases, but Felix reminds us that it’s still a human endeavor.
He believed in AI research and its potential to solve humanity’s greatest challenges. 

But he also challenged us to make the field emotionally sustainable, ensuring that we care for ourselves as much as we care for the systems we build.
But his post is also a challenge to the rest of us: Can we make this field emotionally sustainable? We should ensure that we care for ourselves as much as we care for the systems we build.
So, here’s to Felix—and to making AI research not just a force for good, but a place where the people creating the future can thrive too.



