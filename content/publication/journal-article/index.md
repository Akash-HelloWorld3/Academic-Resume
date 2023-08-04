---
title: "Enhancing Heart Disease Prediction Through KBEST-PCA Fusion Feature Selection and Ensemble Modeling With Gaussian Naive Bayes Boosting"
authors:
- Dhivya P
- Sangavi N
- admin
- Anooskavin G
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2023-07-17T00:00:00Z"
doi: "	https://doi.org/10.36948/ijfmr.2023.v05i04.4378"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*International Journal for Multidisciplinary Research, 1*(1)"
publication_short: "IJFMR"

abstract: 	Heart disease is a prevalent health condition with significant implications for patient health and well-being. Accurate and timely diagnosis plays a crucial role in effective treatment and management. In this study, we propose a combined approach using SelectKBest, Gaussian Naive Bayes (GNB), and Gradient Boosting Machines (GBM) to develop a robust predictive model for heart disease diagnosis. The SelectKBest algorithm is employed to identify the most informative features from the Statlog Heart Disease dataset. Statistical measures such as chi-squared test are utilized to select the top K features that exhibit the strongest associations with the target variable. The selected features are then used to train a GNB classifier, capturing the probabilistic relationships between the features and the diagnosis of heart disease. Predictions generated from the GNB model are combined with the original features, creating an extended feature matrix. Subsequently, a GBM ensemble model is trained on the extended feature matrix, leveraging the sequential combination of weak learners to improve the overall predictive performance. To evaluate the effectiveness of the proposed approach, extensive experiments are conducted on the Statlog Heart Disease dataset. Performance metrics including accuracy, precision, recall, and F1 score are used to compare the combined SelectKBest-GNB-GBM approach against individual classifiers and existing methods.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.ijfmr.com/papers/2023/4/4378.pdf
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
