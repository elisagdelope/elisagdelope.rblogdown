---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Getting started with Protein Language Models"

subtitle: "A brief motivation for PLMs and curated collection of materials"

summary: "Dive into the world of protein language models (PLMs) with this curated collection of resources."

authors: 
- admin

tags: []

categories: []

date: 2024-05-15T18:22:01+01:00
lastmod: 2024-05-16T18:22:01+01:00

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


Proteins are the tiny workhorses that power life, playing vital roles in every biological process. Like sentences crafted from words, proteins are intricate sequences of 20 different amino acids. The order of these amino acids determines the protein's 3D structure, which in turn dictates its function and interactions within biological systems.

Protein language models (PLMs) such as Meta's ESM-2 or Google DeepMind's AlphaFold, harness the power of natural language processing and transformer architectures — now AlphaFold3 with diffusion techniques on top — to decode the language of proteins in a similar way than their cousins, the Large language models (LLMs) like the infamous chat-GPT. And then again, just like LLMs are changing the way we work, the rise of PLMs is putting the field of biology is on the cusp of a new era. 

PLMs are trained on extensive datasets of protein sequences spanning the evolutionary tree of life, "learning" the essence of protein structure and function without direct knowledge of their physical/chemical properties or 3D structure (although they can be  incorporate this information in a conditional manner for specific applications). This training enables them to perform a variety of tasks, from modeling to design, with remarkable accuracy. 

I think these models will change the way many research problems are tackled in biology. But this is not yet another opinionated post about whether AI will lead to our doom or usher in a utopian future. Instead, I've tried to make a treasure trove of resources to jumpstart your journey into the fascinating world of protein language models, with a spotlight on ESM-2 as it's the model I know best. 

Embarking on this adventure requires a solid understanding of both biology and machine learning. Pace yourself, master the basics, and then delve into the complexities.  Let the learning begin! 🚀

<br>

## **Grasping PLMs**

[**A review on protein language models**](https://www.apoorva-srinivasan.com/plms/): This accessible yet technical blog post introduces the protein lexicon before exploring the architecture of transformer-based models.

[**Evolutionary Scale Modeling using Protein Language Models**](https://amiteshbadkul.github.io/blog/2023/esm2-explained/): A blog post that (sub)titles itself as "ESM2 model explained" says pretty much everything. A deep dive into the ESM-2 and ESMFold models, explaining their significance in the realm of biological language models.

[**Decoding Protein Structures: From AlphaFold to Beyond**](https://www.recursion.com/news/demystifying-protein-structure-prediction-models-alphafold-rosettafold-esmfold-and-beyond): Blog post from Recursion. It discusses *Multiple Sequence Alignment (MSA)* in the context of several PLMs, such as AlphaFold2, RoseTTaFold, OmegaFold, HelixFold-Single, and ESMFold, and their performance in terms of accuracy, speed, and reliance on additional gene sequencing information for inference (i.e. structure prediction).  


<br>

## **Delving Deeper for the researchy minds**

[**Designing Proteins with Language Models**](https://www.nature.com/articles/s41587-024-02123-4.pdf), by Jeffrey A. Ruffolo & Ali Madani (Nature, 2024): A succinct and illustrative academic primer on PLMs and their application in protein engineering. Honestly, my favorite resource to gain a clear understanding of these methods and the article I would advice if you want to read one and only one document on this. The downside is it's not open-access, but highly recommended concise and informative read for those with institutional access.

If you are research-inclined and have time, the list or relevant and foundational articles in the field is endless, and I suggest you check [Kevin Kaichuang Yang's repository](https://github.com/yangkky/Machine-learning-for-proteins?tab=readme-ov-file#generative-models). It is a great resource of papers, tools and dataset categorized by subtopics.

If you have less time, but want to stay grounded in the field with a few prominent articles, foundational models and their applications, here my very short list I believe worth reading:

[**Learning the protein language: Evolution, structure, and function**](https://www.cell.com/cell-systems/fulltext/S2405-4712(21)00203-9?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2405471221002039%3Fshowall%3Dtrue), by Tristan Bepler and Bonnie Berger (Cell systems, 2021);

[**Learning functional properties of proteins with language models**](https://www.nature.com/articles/s42256-022-00457-9), by S. Unsal, et al. (Nature Machine Intelligence, 2022);

[**Evolutionary-scale prediction of atomic level protein structure with a language model**](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v3) by Z. Lin, et al. (bioRxiv, 2022; Science, 2023);

[**Generalized Biomolecular Modeling and Design with RoseTTAFold All-Atom.**](https://www.biorxiv.org/content/10.1101/2023.10.09.561603v1), by R. Krishna, et al. (bioRxiv, 2023);

[**De novo design of protein structure and function with RFdiffusion.**](https://www.nature.com/articles/s41586-023-06415-8), by J.L. Watson (Nature, 2023);

[**PoET: A generative model of protein families as sequences-of-sequences.**](https://arxiv.org/abs/2306.06156), by T.F. Truong Jr and Tristan Bepler (aRxiv, 2023);

The very recent [Nature paper on AlphaFold3](https://www.nature.com/articles/s41586-024-07487-w)  is also a must-read, but it's not open-access. You can also get a flavour of this new model in the [DeepMind blog](https://blog.google/technology/ai/google-deepmind-isomorphic-alphafold-3-ai-model/#life-molecules).

<br>

## **Getting started with no (or little) code**

[**OpenProtein.AI Guide**](https://docs.openprotein.ai/): OpenProtein.AI is a commercial platform to train custom and pre-trained foundation models and PLMs such as AlphaFold2, ESM, and PoET, for tasks like function prediction, structure prediction, and de novo protein design tools. This guide provides an overview of ML models to integrate in protein engineering workflow. In addition, the [OpenProtein Python client](https://docs.openprotein.ai/api-python/index.html) documentation offers a range of tutorials and case-studies, mainly using the OpenProtein library and the generative model PoET.

<br>

## **Getting your hands dirty with code**
[**Train Your Own Protein Language Model In Just a Few Lines of Code**](https://www.blopig.com/blog/2023/04/train-your-own-protein-language-model-in-just-a-few-lines-of-code/): A step-by-step guide from the Oxford Protein Informatics Group on implementing and fine-tuning a PLM using the HuggingFace Transformers library.


[**Predicting Protein-Protein Interactions Using a Protein Language Model**](https://huggingface.co/blog/AmelieSchreiber/protein-binding-partners-with-esm2): A tutorial-style blog post in Hugging Face explaining how to use ESM-2 to score pairs of proteins using masked language modeling loss, for predicting protein-protein interactions. It's a great tutorial to get started with ESM-2 and Hugging Face Transformers written by the talented Amelie Schreiber. I won't hide it, I'm quite a fan of her work, in particular her [Hugging Face articles/tutorials](https://huggingface.co/AmelieSchreiber). 

[**In Silico Directed Evolution of Protein Sequences with ESM-2**](https://huggingface.co/blog/AmelieSchreiber/directed-evolution-with-esm2): This is another gem by Amelie Schreiber, guiding on using ESM-2 for in-silico directed evolution of protein sequences, with the ultimate goal to potentially optimize protein-protein interactions. 

<br>

## **Going all-in with code**
[**GitHub - facebookresearch/esm**](https://github.com/facebookresearch/esm): Dive into the GitHub repository of the Fundamental AI Research Protein Team (FAIR) Protein team at Meta, which includes the code and pre-trained weights for transformer PLMs such as the cutting-edge ESM-2 and ESMFold, together with the MSA Transformer, ESM-1v and ESM-IF1. 

[**GitHub - google-deepmind/alphafold**](https://github.com/google-deepmind/alphafold): In 2020 AlphaFold took the world by storm and was recognized to solve the “protein folding problem”. The code of v1 and v2 is open-source and available on GitHub. The most recent version, AlphaFold3, has just been released, expanding the capabilities beyond proteins to a broad spectrum of biomolecules, and incorporating diffusion to their previous transformer-based architecture (Evoformer). The model is accessible through a free [server](https://golgi.sandbox.google.com/about), but a bit dissapointingly, the code and weights are not available.


[**ESM - Hugging Face docs**](https://huggingface.co/docs/transformers/en/model_doc/esm): Explore this page for augmented documentation on pre-trained ESM2 models as well as usage examples by the community.

<br>

## Thoughts on transformer-based vs diffusion models: what's next?
(Yes, this section is opinionated; feel free to disagree)

Transformer-based models are well-established and efficient, making them great for tasks like protein structure prediction (think AlphaFold2). They're also excellent at capturing long-range dependencies within protein sequences, hence understanding the relationships between different parts of a protein sequence.

Diffusion models are a newer class of generative models that learn the data distribution by modeling it as a diffusion process. This technique is used in models like RFDiffusion, Diffusion Protein Language Model (DPLM), Distributional Graphormer, or LigandMPNN, and also in Alphafold3, where the Evoformer (evolutional transformer) from Alphafold2 got improved by assembling its structural predictions using a diffusion network. 

Despite being less computationally efficient than transformers, diffusion-based models have shown impressive capabilities in generating structurally plausible, novel, and diverse protein sequences. For instance, the DPLM showed superior representation learning and versatility compared to ESM-2 (transformer architecture). They were originally known for their effectiveness in image generation, and have been improved by incorporating transformer architectures (e.g., the Diffusion Transformer -DiT-). The recent AlphaFold3 paper adds to what seems a powerful combination of both methods. Transformers provide strong contextual understanding, while diffusion models can introduce more diversity and novelty in protein sequence generation. New architectures and techniques are emerging all the time, but I think the future likely lies in combining the strengths of both approaches. 

<br> 

I hope this post helps you get started in the field of protein language models. If you have any questions or suggestions, please feel free to reach out to me. Always happy to help! 😊
