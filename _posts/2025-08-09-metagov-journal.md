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
The Metagov Journal is a peer-reviewed journal that publishes “living institutions”--active communities, organizations, platforms, contracts, and other governance forms--alongside traditional scholarly work and op-eds about those institutions. It is a journal and itself a living institution. As a journal, it operates through a diamond open-access open peer review process and publishes as an overlay journal on top of arXiv, SSRN, and GitHub. As a living institution, it is a continually evolving organization composed of readers, reviewers, authors, publishers, engineers, editors, and a broad range of (socio-)technical infrastructure. We describe the genesis and context of the journal, along with some design considerations.

# Introduction
<!--Please clearly communicate why someone else should care about this institution, e.g. because it is novel or important.-->
The Metagov Journal publishes living institutions, including  online communities, companies, movements, contracts, and other institutional forms. We also publish a range of traditional papers and op-eds related to these institutions. We are a diamond open-access (free to submit, free to read) overlay journal (we host archival copies on arXiv, SSRN, and GitHub) with an open peer review system (reviews for accepted publications are public).

The Journal matters because it directly addresses a gap in how governance innovations are documented and disseminated. Practitioners rarely receive the same recognition as academic writers, and many impactful governance experiments remain undocumented. The Journal provides a venue that validates practice as a legitimate research output, invites academic scrutiny, and preserves institutional knowledge in a durable, evolving form.

# Related work
<!--Please describe other similar institutions, especially those that inspired by design or evolution of this one.-->

We have recently seen a number of interesting innovations in scholarly publishing. Just within the computer science community, *Distill* was known for its richly interactive publications [CITE] while *OpenReview* pioneered transparent review processes for large conferences [CITE]. Decades later arxiv.org still counts as an innovation and merit mentioning here as well.

Might work in ARK, the open decentralized DOI alternative, more platforms like OJS, pubpub, even notion and wikis.  torrents and OSF.io in addition to Zenodo for datasets. All ust for a proper fuller map of the space (though I'm really no expert)

Recent developments, particularly in machine learning and the sciences, have sought to improve dataset sharing, ensuring transparency and reuse. Large-scale dataset repositories such as Zenodo and peer-reviewed venues for dataset papers demonstrate both the promise and challenges of data sharing.

Also relevant are advances in semantic publishing. Semantic publishing techniques such as RDF annotation, semantic markup, and JSON-LD push scholarly outputs beyond static PDFs toward machine-readable, interoperable forms. Much more recently, decentralized publishing platforms using nanopublications propose a vision for bottom-up, web-native dissemination of scientific data and claims.

Infrastructure re: overlay journals [CITE].

Finally, there is a broader movement toward open access (OA)—-via community-driven publishing models that are free for both authors and readers.

# Genesis
Why treat living institutions as first-class scholarly objects, embedded in open data, open processes, and distributed infrastructure?

- Give more credit to practitioners rather than people who write-up their results. Elevate the work of these founders and builders to the status of a legitimate scholarly and civic contribution.
- Link practitioners with academic researchers.
- Embeds laborious institutional work within a network of peer-reviewed, openly accessible institutional profiles.
- Metagov's own research culture is stagnating and needs a new institutional context.
- Accelerate speed of innovation in institutional design.
- Disseminate useful and innovative practices.
- Plans to inherit Cryptoeconomic Systems and the earlier Metagov Journal experiments.
- Organize data.
- This institution has four roles: editors, authors, reviewers, and readers. They are listed at [...]
- Peer review adds a layer of critical reflection, ensuring that the documentation is not only accurate but also evaluated for significance, novelty, and relevance to the broader institutional landscape. Open peer review allows the community to participate.

# What does it mean to publish a living institution?
Publishing a living institution means documenting an active, evolving entity in a way that captures both its current state and its capacity for change over time. The publication must be useful for researchers--it should provide enough narrative and context to motivate further study. Importantly, however, it may not have the same kind of thesis common in research articles.

To the degree possible, we want to encourage submission of living documents and data feeds. One thought is that instead of submitting, we just have the organization submit their entire website; every website, of course, is a living institution.

While metadata is important, it's often not practical or useful to construct a large ontology that people will rarely conform to.

Who are the members or people of the institution? This is incredibly important. To the degree we can facilitate publicatino of this data through infrastructure, that would give us an extremely valuable lens on the institution.

Editability of the submission is another important question. After all, the institutions are "living" (and presumably, some will die after being submitted). No reason to impose a versioning system (yet), though interesting to think about how through a "git for orgs". On some level, we just want to provide a simple platform / coordination mechanism to help organize data collection and aggregation around institutions, especially digital ones.

Publishing a living institution is therefore both an archival act and a participatory one. It preserves knowledge for future study, while inviting ongoing interaction from the community—-whether through commentary, supplemental data, or linked projects.

We need an accounting of the people.

## How do we handle concept pieces?

# Aliveness
<!--A simple test of aliveness.-->
The institution is considered alive if it publishes at least 1 accepted submission per year. See the active website and submissions visible at [https://journal.metagov.org](https://journal.metagov.org) and on [OpenReview](https://journal.metagov.org). 

# Specification
<!--Details to reproduce this institution.-->
To reproduce this institution, i.e. to found a new Metagov Journal:
1. recruit an editorial board
2. fork the repo at [https://](https://github.com/metagov/journal) and set up a frontend for posting
3. create an OpenReview page by making an OpenReview Support Request Form, and select the options for double-blind and manual review.
4. invite submissions, mostly through direct outreach but also some marketing and community development
5. find a fiscal sponsor or create a nonprofit legal entity

# Conclusion

# Data
<!--Where to find data that allows researchers to analyze and study the institution.-->
Data about Metagov is updated at [metagov.org](https://metagov.org) and in JSON format on [GitHub](https://raw.githubusercontent.com/metagov/entity/refs/heads/main/entity.json).

# Acknowledgements
<!--In addition to typical acknowledgements, please also declare your relationship to the institution.-->
Author Joshua Tan is the founding editor of the Metagov Journal and a co-founder of Metagov.

# References
<!--Please use Science style.-->
