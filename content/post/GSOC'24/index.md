---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "My journey to Google Summer of Code (GSoC) 2024"

subtitle: "One of the best programs to get into Open Source"

summary: ""

authors: 
- admin

tags: []

categories: []

date: 2024-05-21T18:22:01+01:00
lastmod: 2024-05-22T18:23:01+01:00

featured: false

draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---


As I was finalizing my PhD thesis in late 2023, I had the fortune of connecting with [Paulina Paiz](https://pau-paiz.notion.site/Lina-Paiz-6516127ba94e4d8fa58d26e97d207357), a Stanford master's student with a shared background and passion for tech and bio. Upon learning about my research, she introduced me to Google Summer of Code (GSoC). Her insights and experience with the program piqued my interest, leading me to explore the world of open-source contributions.

Long story short and fast-forward 6 months, my GSoC proposal to integrate the ESM-2 model (Meta's open source protein language model) from Hugging Face into DeepChem for predicting protein binding sites was accepted. I am excited to share with you my motivations and how I crafted a successful proposal, hoping it will inspire you to apply to GSoC'25 and future editions.

## Why open source?

Open-source software is the backbone of many technological advancements, freely available for anyone to use, modify, and distribute. Developed by a community of contributors, it plays a vital role in both industry and academia, fostering collaboration and innovation. Contributing to open-source projects helps you learn new skills, build your portfolio, and connect with other developers. It also gives back to the community and improves software that is used by many people. Examples like the Linux operating system, Apache web server, and Python programming language highlight the power of open-source collaboration. 

As a researcher used to solitary coding, I found that OS communities, like those in GSoC, offer valuable feedback and discussion opportunities. These interactions allow to learn from experienced developer, improve your code, and makes your work more visible and impactful. Above all, it shifted my approach towards building code that stands the test of time and usage. Additionally, contributing is also a way for me to give back, as I have benefited from open-source software in many ways. 


## What is Google Summer of Code and what makes it interesting?

Google Summer of Code (GSoC) is an international program by Google athat introduces students and young developers to open source (OS) software development. In this 12 to 22-week summer program, participants collaborate with OS organizations on meaningful projects, guided by experienced mentors. GSoC offers a unique blend of learning, professional growth, and networking, along with a stipend, creating a mutually beneficial environment for both contributors and organizations. Students get to 1) learn and contribute to real projects with production-quality code; 2) expand their network and career advice from supportive mentors; and 3) be paid for their contributions; while organizations benefit from the work of talented students, and cultivate a post-GSoC contributors pool, some of whom may return as mentors in future GSoC editions (my mentor in GSoC '24 had been a GSoC student in the past).

I was honestly impressed by the program's support for students and the quality of the community. It is a great opportunity to learn, grow, and connect with professionals in a field of your interest. Check the timeline and eligibility criteria in the [Google Summer of Code website](https://summerofcode.withgoogle.com/).

{{< figure src="images/logo.png">}}


## Crafting a successful proposal

Accepted organizations in GSoC are listed in the website. You can browse the list, and submit 1 to 3 proposals for contribution. The proposal is your chance to stand out, reflecting your skills, motivation, and fit with the project. 

The proposal should be clear, concise, and well-structured in terms of what you want to contribute and how you plan to do that. Most orgs provide a template, use it if available! As an inspiration, my GSoC'24 proposal for DeepChem included the following sections: 

- Introduction: Present your project explaining its significance and how it addresses a current need within the organization and its users. For instance, if you're proposing a new functionality that would solve an open issue in the Github repository, mention it and add the link to your text. Make the relevance clear.

- Relevant Experience and Interest: Share your background and why you're interested and suited for this project. Link GitHub repositories, previous pull requests, LinkedIn, or other relevant material that supports your claims. Your excitement for the project should be evident!.

- Work Plan: This is the core of the proposal. Outline your plan by breaking it down to smaller tasks and explaining your implementation strategy. My proposal to integrate the ESM-2 protein language model into DeepChem included two main tasks: 1) Data Acquisition and Preprocessing, and 2) Model Design and Implementation. The work plan should be detailed and realistic, showing that you have a clear idea of what you want to do and how you plan to do it. 

Following DeepChem's template, I divided my work plan into sections: Design and pseudocode, testing plan, sources of risk, milestones, timeline and pull requests. In my proposal, all sections were linked to each other and coherent, e.g., the first milestone was to implement the data preparation and feature extraction using ESM-2, with deliverables including a unit test report demonstrating successful implementation,  and a PR expected within 3 weeks including pre-processing code, feature extraction functions, and tests. In addition, one source of risk was compatibility issues between the data formats expected by the pre-trained ESM-2 model and DeepChem.

- Community: You are adviced to discuss your ideas and get feedback from the community before submitting to GSoC. This is essential IMO to improve your proposal as you will be talking to potential mentors and the people who will rank your proposal: You want to make them very excited about it! Describe how you've used the community feedback to refine your proposal and include your plans for continued engagement, such as attending office hours.

- Resources Required: Quite self-explanatory. Include hardware, software, data, and any other resources that are necessary for the project. You should also mention if you need help to get them.

- Bibliography


## Embrace the outcome

Once proposals are submitted, they undergo a review and scoring process by the organizations and GSoC organizers. After about a month, applicants receive the results. Successful candidates are paired with mentors and should begin their projects. As a successful GSoC contributor, you will be expected to write weekly reports, attend meetings with your mentor and office hours, and participate in the community (at least, these are some of the expectations at DeepChem). A final report and code submission conclude the program, leading to a stipend and a completion certificate if all goes well.

My proposal was succesful, and while I'm grateful and thrilled, just completing the proposal and joining the DeepChem community [already felt like a win to me](https://x.com/elisagdelope/status/1775826138419376522). In the process I connected with individuals I admire, like Stanley Bishop (*Science Stanley*) and Bharath Ramsundar. The program is competitive though and not everyone gets accepted - this year saw 9,107 submitted proposals and 1,220 GSoC contributors accepted. If you don't get in, it's not the end; you can still engage with the community, learn, contribute and build your portfolio. Seek feedback so you are better prepared next year!

{{< figure src="images/medal-tag.png">}}

I hope this post was helpful and that it motivates you to apply to GSoC or other open-source programs. If you have any questions, feel free to reach out to me on [Twitter](https://twitter.com/elisagdelope) or [LinkedIn](https://www.linkedin.com/in/elisagdelope/). Good luck! 🍀
