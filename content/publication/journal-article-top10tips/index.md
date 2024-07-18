---
title: "Ten quick tips for biomarker discovery and validation analyses using machine learning"
authors:
- Ramon Diaz-Uriarte
- admin
- Rosalba Giugno
- Holger Fröhlich
- Petr V. Nazarov
- Isabel A. Nepomuceno-Chamorro
- Armin Rauschenberger
- Enrico Glaab

date: "2022-08-11T00:00:00Z"
doi: "https://doi.org/10.1371/journal.pcbi.1010357"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "PLOS Computational Biology"
publication_short: ""

abstract: High-throughput experimental methods for biosample profiling and growing collections of clinical and health record data provide ample opportunities for biomarker discovery and medical decision support. However, many of the new data types, including single-cell omics and high-resolution cellular imaging data, also pose particular challenges for data analysis. A high dimensionality of the data in relation to small numbers of available samples (often referred to as the p >> n problem), influences of additive and multiplicative noise, large numbers of uninformative or redundant data features, outliers, confounding factors and imbalanced sample group numbers are all common characteristics of current biomedical data collections. While first successes have been achieved in developing clinical decision support tools using multifactorial omics data, e.g., resulting in FDA-approved omics-based biomarker signatures for common cancer indications [1], there is still an unmet need and great potential for earlier, more accurate and robust diagnostic and prognostic tools for many complex diseases. Here, we provide a set of broadly applicable tips to address some of the most common pitfalls and limitations for biomarker signature development, including supervised and unsupervised machine learning, feature selection and hypothesis testing approaches. In contrast to previous guidelines discussing detailed aspects of quality control, statistics or study reporting, we give a broader overview of the typical challenges and sort the quick tips to address them chronologically by the study phase (starting with study design, then covering consecutive phases of biomarker signature discovery and validation, see also the overview in Fig 1). While these tips are not comprehensive, they are chosen to cover what we consider as the most frequent, significant, and practically relevant issues and risks in biomarker development. By pointing the reader to further relevant literature on the covered aspects of biomarker discovery and validation, we hope to provide an initial guideline and entry point into the more detailed technical and application-specific aspects of this field.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Research
featured: true 

# links:
# - name: ""
#url: 'https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010357'
url_source: 'https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010357'
url_pdf: 'https://journals.plos.org/ploscompbiol/article/file?id=10.1371/journal.pcbi.1010357&type=printable'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_video: ''
 
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
