---
title: "Matching with Text Data: An Experimental
Evaluation of Methods for Matching
Documents and of Measuring Match Quality"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Luke Miratrix
- Aaron Russell Kaufman
- L. Jason Anastasopoulos

# Author notes (optional)
#author_notes:

date: "2021-02-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-03-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Political Analysis*
publication_short: In *PA*

abstract: Matching for causal inference is a well-studied problem, but standard methods fail when the units to match are text documents: the high-dimensional and rich nature of the data renders exact matching infeasible, causes propensity scores to produce incomparable matches, and makes assessing match quality difficult. In this paper, we characterize a framework for matching text documents that decomposes existing methods into: (1) the choice of text representation, and (2) the choice of distance metric. We investigate how different choices within this framework affect both the quantity and quality of matches identified through a systematic multifactor evaluation experiment using human subjects. Altogether we evaluate over 100 unique text matching methods along with 5 comparison methods taken from the literature. Our experimental results identify methods that generate matches with higher subjective match quality than current state-of-the-art techniques. We enhance the precision of these results by developing a predictive model to estimate the match quality of pairs of text documents as a function of our various distance scores. This model, which we find successfully mimics human judgment, also allows for approximate and unsupervised evaluation of new procedures in our context. We then employ the identified best method to illustrate the utility of text matching in two applications. First, we engage with a substantive debate in the study of media bias by using text matching to control for topic selection when comparing news articles from thirteen news sources. We then show how conditioning on text data leads to more precise causal inferences in an observational study examining the effects of a medical intervention.

# Summary. An optional shortened abstract.
summary: Just testing to see if this works.

tags: ['Published']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'matching_text.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
