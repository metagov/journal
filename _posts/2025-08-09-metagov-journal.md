---
layout: post
title: The Metagov Journal
date: 2025-08-09
authors: Joshua Tan
reviews: https://openreview.net/forum?id=uQW9yeormT
archival: https://github.com/posts/2025-08-09-metagov-journal.md
---

The Metagov Journal is a peer-reviewed journal that publishes living institutions.

# Abstract
The Metagov Journal is a peer-reviewed, diamond open-access overlay journal that publishes “living institutions”--active communities, organizations, contracts, and other governance forms--alongside traditional scholarly work and op-eds about them. It serves as both a publication venue and a governance experiment itself, using an open peer review process to bridge the gap between practitioners and academic researchers, accelerate institutional innovation, and build a public knowledge base of governance practice. The journal itself is a living institution, continually evolving in editorial process, technical infrastructure, and community engagement. This submission also describes the genesis and context of the journal, along with some design considerations.

# Introduction
<!--Please clearly communicate why someone else should care about this institution, e.g. because it is novel or important.-->
The Metagov Journal publishes living institutions, including  online communities, companies, movements, contracts, and other institutional forms. We also publish a range of traditional papers and op-eds related to these institutions. We are a diamond open-access (free to submit, free to read) overlay journal (we host archival copies on arXiv, SSRN, and GitHub) with an open peer review system (reviews for accepted publications are public).

The Journal matters because it directly addresses a gap in how governance innovations are documented and disseminated. Practitioners rarely receive the same recognition as academic writers, and many impactful governance experiments remain undocumented. The Journal provides a venue that validates practice as a legitimate research output, invites academic scrutiny, and preserves institutional knowledge in a durable, evolving form.

# Related work
<!--Please describe other similar institutions, especially those that inspired by design or evolution of this one.-->

We have recently seen a number of interesting innovations in scholarly publishing. Just within the computer science community, *Distill* was known for its richly interactive publications [CITE] while *OpenReview* pioneered transparent review processes for large conferences [CITE]. 

Recent developments, particularly in machine learning and the sciences, have sought to improve dataset sharing, ensuring transparency and reuse. Large-scale dataset repositories such as Zenodo and peer-reviewed venues for dataset papers demonstrate both the promise and challenges of data sharing.

Also relevant are advances in semantic publishing. Semantic publishing techniques such as RDF annotation, semantic markup, and JSON-LD push scholarly outputs beyond static PDFs toward machine-readable, interoperable forms. Much more recently, decentralized publishing platforms using nanopublications propose a vision for bottom-up, web-native dissemination of scientific data and claims.

Infrastructure re: overlay journals [CITE].

Finally, there is a broader movement toward open access (OA)—-via community-driven publishing models that are free for both authors and readers.

# Rationale
Why treat living institutions as first-class scholarly objects, embedded in open data, open processes, and distributed infrastructure?

- Metagov itself is stagnating, and needs a new institutional context.
- Give more credit to practitioners rather than people who write-up their results.
- Link practitioners with academic researchers.
- Accelerate speed of innovation.
- Disseminate useful and innovative practices.
- Organize data.
- This institution has four roles: editors, authors, reviewers, and readers. They are listed at [...]

# Aliveness
<!--A simple test of aliveness.-->
The institution is considered alive if it publishes at least 1 accepted submission per year.
See the active website and submissions visible at [https://journal.metagov.org](https://journal.metagov.org) and on [OpenReview](https://journal.metagov.org). 

# Specification
<!--Details to reproduce this institution.-->
To reproduce this institution, i.e. to found a new Metagov Journal:
1. recruit an editorial board
2. fork the repo at [https://](https://github.com/metagov/journal) and set up a frontend for posting
3. create an OpenReview page by making an OpenReview Support Request Form, and select the options for double-blind and manual review.
4. invite submissions, mostly through direct outreach but also some marketing and community development
5. find a fiscal sponsor or create a nonprofit legal entity

# Data
<!--Where to find data that allows researchers to analyze and study the institution.-->
Data about Metagov is updated at [https://metagov.org] and in JSON format on [GitHub](https://raw.githubusercontent.com/metagov/entity/refs/heads/main/entity.json).

# Acknowledgements
<!--In addition to typical acknowledgements, please also declare your relationship to the institution.-->
Author Joshua Tan is the founding editor of the Metagov Journal and a co-founder of Metagov.

# References
<!--Please use Science style.-->
