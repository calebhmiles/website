+++
title = "Causal Inference for a Single Group of Causally-Connected Units Under Stratified Interference"
date = "2017-10-26"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["CH Miles", "M Petersen", "MJ van der Laan"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In revision for *Biometrics*"
#publication_short = "In *ICMEW*"

# Abstract and optional shortened version.
abstract = "The assumption that no subject's exposure affects another subject's outcome, known as the assumption of no interference, has long held a foundational position in the study of causal inference. However, this assumption may be violated in many settings, and in recent years has been relaxed considerably. Often this has been achieved with either the aid of knowledge of an underlying network, or the assumption that the population can be partitioned into separate groups, between which there is no interference, and within which each subject's outcome may be affected by all the other subjects in the group, but only as a function of the total number of subjects exposed (the stratified interference assumption). In this paper, we consider a setting in which we can rely on neither of these aids, as each subject affects every other subject's outcome. In particular, we consider settings in which the stratified interference assumption is reasonable for a single group consisting of the entire sample, i.e., a subject's outcome is affected by all other subjects' exposures, but only via the total number of subjects exposed. This can occur when the exposure is a shared resource whose efficacy is modified by the number of subjects among whom it is shared. We present a doubly-robust estimator that allows for incorporation of machine learning, and tools for inference for a class of causal parameters that includes direct effects and overall effects under certain interventions. We conduct a simulation study, and present results from a data application where we study the effect of a nurse-based triage system on the outcomes of patients receiving HIV care in Kenyan health clinics."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1710.09588.pdf"
#url_preprint = "https://arxiv.org/pdf/1710.09588.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "header.jpg"
#caption = "My caption :smile:"

+++