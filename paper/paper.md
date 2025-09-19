---
title: 'DBCLS BioHackathon 2025 report: Template for the very long title'
title_short: 'BioHackJP25: How we found breakfast'
tags:
  - Semantic web
  - Ontologies
  - Workflows
authors:
  - name: First Author
    affiliation: 1
  - name: Last Author
    orcid: 0000-0000-0000-0000
    affiliation: 2
affiliations:
  - name: First Affiliation
    index: 1
  - name: ELIXIR Europe
    ror: 044rwnt51
    index: 2
date: 15 September 2025
cito-bibliography: paper.bib
event: BH25JP
biohackathon_name: "DBCLS BioHackathon 2025"
biohackathon_url:   "https://2025.biohackathon.org/"
biohackathon_location: "Mie, Japan, 2025"
group: AI-survey 
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackathon-japan/bh25-bhxiv-template
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: First Author \emph{et al.}
---

# Introduction

The rapid adoption of AI in life sciences and bioinformatics has created both opportunities and challenges for researchers, making it important to understand how AI is currently used in these communities. While our study centers on Biohackathon participants, the survey also reaches members of the broader bioinformatics community through participants’ networks, capturing practices beyond the event itself. The survey gathers insights into the AI tools being used, the successes achieved, and the challenges faced, while also inviting participants to briefly review their current work to enable proper documentation and citation. We aim to gauge the current state of AI usage, highlight successes and challenges, and build a community-driven knowledge base to inform future AI development. By surveying attendees and their networks across diverse backgrounds (including Thai, Japanese, and English-speaking participants), we document AI usage, workflows, and challenges, providing a snapshot of current practices in the global bioinformatics community. Ultimately, this effort seeks to create a shared resource that both records ongoing AI research and fosters collaboration across the international life sciences community.

## Author information

Information about the authors is given in the [YAML](https://en.wikipedia.org/wiki/YAML) format at the top of this template.
For authors you provide their names, their affiliations, and ideally their [ORCID](https://orcid.org/)
identifier. For affiliations, the [Research Organization Registry](https://ror.org/) (ROR) identifier can be given.
For example, this is the author information for this template:

```yaml
authors:
  - name: David Steinberg
    affiliation: 1
    orchid: 0000-0001-6683-2270
  - name: Chatarin Wangsanuwat
    affiliation: 2
    orchid: 0000-0001-8228-2387
  - name: Lucas Feriau
    affiliation: 3
    orchid:
  - name: Pumipat Tongyoo
    affiliation: 4
    orchid: 0000-0002-3274-5475
  - name: Nattawet Sriwichai
    affiliation: 5
    orchid: 
  - name: Susumu Goto
    affiliation: 6
    orcid: 
  - name: Yukiko Noda
    orcid: 
    affiliation: 3
  - name: Hikaru Gyoji
    orcid: 
    affiliation: 3
affiliations:
  - name: Camber
    index: 1
  - name: Faculty of Medicine Siriraj Hospital, Mahidol University, Thailand
    index: 2
  - name: PENQE inc., Japan
    index: 3
  - name: Kasetsart University, Thailand
    index: 4
  - name: Chiang Mai University, Thailand
    index: 5
  - name: Database Center for Life Science (DBCLS), Japan
    index: 6
```

# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables

Tables can be added in the following way, though alternatives are possible:

```markdown
Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |
```

This gives:

Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

## Figures

A figure is added with:

```markdown
![Caption for BioHackrXiv logo figure](./biohackrxiv.png)
```

This gives:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

Figures can be scaled by adding the width or height to the Markdown like this:

```markdown
![Caption for BioHackrXiv logo figure](./biohackrxiv.png){ width=50px }
```

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References
