+++
title = "PuFFIN - a parameter-free method to build nucleosome maps from paired-end reads"
date = 2014-09-01
draft = false

authors = ["**Anton Polishko**","Evelien M. Bunnik" ,"Karine Le Roch", "Stefano Lonardi"]

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
publication = "*BMC Bioinformatics*"
publication_short = ""

# Abstract and optional shortened version.
abstract = "We introduce a novel method, called PuFFIN, that takes advantage of paired-end short reads to build genome-wide nucleosome maps with larger numbers of detected nucleosomes and higher accuracy than existing tools. In contrast to other approaches that require users to optimize several parameters according to their data (e.g., the maximum allowed nucleosome overlap or legal ranges for the fragment sizes) our algorithm can accurately determine a genome-wide set of non-overlapping nucleosomes without any user-defined parameter. This feature makes PuFFIN significantly easier to use and prevents users from choosing the \"wrong\" parameters and obtain sub-optimal nucleosome maps. PuFFIN builds genome-wide nucleosome maps using a multi-scale (or multi-resolution) approach. Our algorithm relies on a set of nucleosome \"landscape\" functions at different resolution levels: each function represents the likelihood of each genomic location to be occupied by a nucleosome for a particular value of the smoothing parameter. After a set of candidate nucleosomes is computed for each function, PuFFIN produces a consensus set that satisfies non-overlapping constraints and maximizes the number of nucleosomes. We report comprehensive experimental results that compares PuFFIN with recently published tools (NOrMAL, TEMPLATE FILTERING, and NucPosSimulator) on several synthetic datasets as well as real data for S. cerevisiae and P. falciparum. Experimental results show that our approach produces more accurate nucleosome maps with a higher number of non-overlapping nucleosomes than other tools."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["nucleosomes", "nucleosome positioning", "Algorithms", "Bioinformatics", "Combinatorial Libraries", "Computational Biology/Bioinformatics", "Computer Appl. in Life Sciences", "Microarrays"]

# Links (optional).
url_pdf = "http://www.cs.ucr.edu/~stelo/papers/BMCbio14.pdf"
url_preprint = ""
url_code = "https://github.com/antonpolishko/Puffin"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [
    {name = "PubMed", url = "https://www.ncbi.nlm.nih.gov/pubmed/25252810"},
    {name = "BMC Informatics", url = "https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-15-S9-S11"}

]

# Digital Object Identifier (DOI)
doi = "10.1186/1471-2105-15-S9-S11"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
