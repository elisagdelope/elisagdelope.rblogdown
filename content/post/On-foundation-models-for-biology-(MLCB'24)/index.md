---
title: "On foundation models for biology (MLCB'24)"

subtitle: "Notes from the Machine Learning for Computational Biology 2024 conference discussion panel"

summary: "Notes from the Machine Learning for Computational Biology 2024 conference discussion panel"

authors: 
- admin

tags: 
- Academic

categories: []

date: 2024-09-09T19:35:55+01:00
lastmod: 2024-09-09T10:41:55+01:00

featured: false

draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Image credit: [**Corcel AI**](https://app.corcel.io/image-studio/app/generate-ultra)'
  focal_point: ""
  placement: 2
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

The field of biology is cooking a revolution, with the emergence of foundation models that leverage artificial intelligence (AI) to efficiently process and model the complex nature of molecular systems. However, the current conceptualization of these models is still evolving, and there are many unanswered questions about how to best apply them to biological systems. 

A foundation model in biology leverages AI methods to efficiently process and model the complex nature of molecular systems. These models need to integrate massive amounts of data — spanning DNA sequences, RNA levels, protein expression, and environmental factors — to understand the characteristics and underlying mechanisms of complex systems such as humans or animals. However, it is yet to be known how much data, and what kind of data, is needed to build a foundation model in biology that we can trust and use for real world applications. Are the current datasets like the UK biobank, with 500,000 genomes linked with health information and biomarkers enough? do we need to include more modalities? how many? And what's the best way to combine these modalities?

### MLCB 2024 panel discussion on foundation models for biology

Last week I attended the panel discussion on foundation models in biology of the Machine Learning conference in Computational Biology (where by the way I had a contribution!) featuring five academic experts in the field: Maria Chikina, Anshul Kundaje, Su-In Lee, Jian Zhou, and Sergey Ovchinnikov, moderated by James Zou. They shared their thoughts on the potential and challenges of applying these models to biological systems, and I found some quite interesting views on the topic which I wanted to share and expand with my notes on this. Here, I'll summarize the key points from the discussion and add my own notes and views. The recordings of all of the talks from the conference (including the discussion panel) are available online [here](https://sites.google.com/cs.washington.edu/mlcb2024/). 


{{< figure src="images/mlcb2024_panel.png" width="650">}}

The discussion gravitated around the current state of the art of the so-called *foundation models*, how useful they are and if they really have the ability solve any task currently. The panel also challenged the definition of foundation models, with some arguing that it should be based on the model's ability to capture underlying biology, rather than just taking its size or number of parameters as the prominent characteristics. Maria Chikina emphasized the importance of considering the problem statement and the task at hand when designing and evaluating foundation models. 

There are currently three basic types of models: for proteins, for single cell, and for DNA, and the utility of them seems to be widely different. For example, the panel agreed that protein language models have been quite successful in several benchmarks and useful for multiple applications despite some limitations and possibly the need for structure information. In contrast, the single cell models have not shown as much promise yet. I personally agree on this take, as research in single cell data, compared to that of proteins, is still in its infancy and there are many challenges to overcome, such as the high dimensionality of the data, the sparsity, and the noise. 

{{< figure src="images/genomics.webp" width="400" caption="Image generated with AI">}}

The panel also highlighted the challenges of applying foundation models to genomics, including the need for high-quality data and the difficulty of predicting useful tasks. Other concerns are inherent to the field of biological data, such as biases, artifacts, and confounders. Indeed, in my experience genomics data is often noisy and incomplete, which can make it difficult to train effective foundation models. It was also noted in the discussion that scaling up data and compute in biology can be limited by the number of base pairs and genes, and whether using genomes from different organisms would have implications in the patterns learned by the model. 

An interesting idea that sparked from the conversation was the potential for using single cell data to align DNA and protein language models, which sounds quite smart, as eventually these three modalities of foundation models should be coherent with each other. However, working with single cell data includes challenges such as the need for high-quality data and the difficulty of predicting useful tasks. 

### Concerns around interpretability

Jian Zhou also raised a common concern when it comes to foundation models in biology, this is, the importance of understanding the success and failure modes of foundation models and developing techniques to make them more transparent and interpretable, especially when understanding the underlying biological mechanisms is crucial. It was suggested that incorporating biological priors into the foundation models might improve both their performance and interpretability, and techniques such as attention mechanisms and feature importance could be used in this regard. I think this is a relevant point, as the interpretability of these models is crucial for their adoption. 

{{< figure src="images/biology_interpretability.webp" caption="Image generated with AI">}}

### Self-supervised learning and algorithmic improvements

There was an interesting debate on the trade-offs between using self-supervised pre-training and training task-specific models, arguing that a combination of both approaches may be the most effective. Sergey Ovchinnikov mentioned that self-supervised learning can be challenging because it's difficult to design effective self-supervised learning objectives. There were also a few ideas on the potential for algorithmic improvements based on large self-supervised models in biology, such as using protein embeddings for similarity instead of doing homology detection and alignment, together with the potential for using synthetic data to improve the performance of DNA language models.


### The future of computational biology

The audience raised the potential for computational biology to become "another AI field", and the implications of this development. I think this is a very interesting view, and one that seems to be shared by the tech community. As per Jensen Huang, CEO of Nvidia, *"For the first time in our history, in human history, biology has the opportunity to be engineering, not science"*. 

There is a lot of excitement - but also overhype I think -, around the potential of AI in biology. My feeling is that overall this has a net positive effect, as it brings collective interest, investments, resources and research focus to this area. I also agree that to some extent, at some point all fields will become an AI field, just like currently all or most fields have a computational sub-field such as computational biology, computational chemistry, computational linguistics, computational physics, computational mechanics, etc. 

That said, the current hype around AI in biology is possibly overlooking the many challenges that are yet to overcome, such as the ones discussed in the panel, and even beyond task- or data-specific foundation models, before we achieve some sort of "artificial general intelligence" (the so-called *"AGI"*) of how a functional organism and all its underlying mechanisms and processes work. More importantly, I think that the field of biology is so complex and diverse that even though we are starting to engineer it, it will still take a long time before we can fully understand and model it with AI. To that date, all the collective scientific developments in biology, be it computational, AI-based or not, are still science that maybe one day, can be used to train a graciously engineered foundation model. The good news is, we are on the right path, and the excitement and interest in the field will propel it forward at much faster speed.

In conclusion, the currently available foundation models in biology are not yet at the point where they can be used for real-world applications, but they are getting there. I think this is a very exciting time to be in the field of computational biology and I'm bullish about the potential. I look forward to seeing how these foundation models will evolve in the future!


