- **Opening date:** 1 December 2020 (next 1 February 2021)
- **Closing date:** 1 February 2021 (next 1 April 2021)
- **Short description:** NGI Zero Discovery will support new ideas and core technologies improving search and discovery. We are seeking project proposals between € 5.000 and € 50.000 – with the potential to scale them up if there is proven potential. Search and discovery are basic human needs for humans of all ages, and we would like to put powerful new technology in the hands of future generations as building blocks for a fair and democratic society and an open economy that benefits all.
- **Target participants:** Projects are judged on their technical merits, strategic relevance to the Next Generation Internet and overall value for money. The key objective is to deliver potential break-through contributions to the open internet. All scientific outcomes must be published as open access, and any software and software must be published under a recognised open source license in its entirety. More information on eligibility: https://nlnet.nl/discovery/eligibility/
- **Visit:** https://nlnet.nl/discovery

---

### Project

Unfold Research

### Website

https://unfoldresearch.com

### Abstract
> Can you explain the **whole project** and its expected outcome(s). <br/>
> (max 1200 characters)

A community-driven academic publishing platform and a knowledge repository, that also offers an alternative way to how scholars make their living and fund their research.

The core of the platform is the ability to link the content together and use the points-based voting mechanics to help filter and curate content, thus making the discovery of relevant, high quality, trusted content easy. With these reputation points that users earn by posting their content, we aim to provide a new metric for academic contributions that replaces h-index, and we plan to integrate payments that distribute available funding to researchers based on those metrics, thus completely disrupting the academic business model.

Additionally, we’ll be building a suite of digital services and tools, under the same umbrella, including e-lab notebooks, peer review system, reference management, data collection and verification, project funding and supervision, conference organizer,… that are all integrated together, and create a seamless and pleasant experience for scholars, that have been, historically, accustomed to very pricey and cumbersome experiences and workflows.

### Experience
> Have you been involved with projects or organisations relevant to this project before? And if so, can you tell us a bit about your contributions?

I’ve previously founded Nodebook (https://nodebook.io) - a graph-based reference manager whose aim was to enable information organization and discovery for academics through a highly visual and interactive graph UI, and build a collaboration hub on top of it, with the main idea of “mapping the world’s knowledge”. I’ve spent in total 3 years working on it, researching the market and competition, talking with local (Serbian) academic institutions, doing interviews with scholars and learning about their needs and habits, perfecting the UX, and building the entire website stack from the ground up.

I also spent ~6 months building nextgen e-lab notebooks for academics (twitter.com/n3pmngr). for which I decided will become a part of Unfold Research eventually.

I’ve also talked with other teams working on similar projects and exchanged experience and knowledge with them, including Knowledge Futures Group (PubPub, Underlay), Liberate Science, Octopus Science, Crowdpeer, Hypothesis, Wikimedia…

As a senior full-stack web developer, I am familiar with technical challenges and potential solutions for them, which will enable us to focus on solving the actual business problem and iterate quickly. I also spent a few years as a computer graphics researcher and published a paper; and I continued doing research in theoretical computer science, so I am also familiar first-hand with the kind of problems that academics face. On top of that, working on my own startups has provided me with a certain mentality that, I believe, is able to understand the business and market needs and combine them with technical challenges and execute on them efficiently.

### Amount

50,000 eur

### Use
> Explain what the requested budget will be used for? <br/>
> Does the project have other funding sources, both past and present? <br/>
> (If you want, you can in addition attach a budget at the bottom of the form)

The majority of the costs would be for salaries - a total of 3 web engineers (front-end, back-end, full-stack, all work-from-home), for a 10-12 months runway. There are optional one-time expenditures (laptops). Infrastructure needs will be sufficiently covered for a while (through a $5000 free Amazon Activate credit) and would not be a huge problem until a significant need for scaling arises.

We plan to focus on building the core services first - versioning of publications, file management, reporting system, basics of the voting system, linking system, search, and tagging; and setting up infrastructure and building the UI. Together, these represent a simple, yet meaningful whole, which we can extend further, start seeding with the content, and slowly opening to user niches.

We will work as a for-profit, but with a steward-ownership model. Funding’s primary goal is to enable us to become self-sustainable, and to be able to continue building our vision independently from that moment on.

So far, the project’s been self-funded. A P&L sheet is provided as an attachment.

### Comparison
> **Compare** your own project with existing or historical efforts.

We’re combining several concepts that all exist separately already and purposely aiming them at academic needs, and then enabling new opportunities to disrupt how academic research is done, measured, and funded.

Publishing platforms aren’t new (there’re thousands, Academia, ResearchGate, OSF, to name a few), but unless automated, there’s very little incentive for somebody to engage in any meaningful way with those platforms. We think that new metrics and funding opportunities that we’ll be offering are probably the strongest incentive that there can be.

Crowd-sourced knowledge exists with the projects such as Wikipedia and Hypothes.is, and community-driven websites like Reddit and Stack Exchange, but so far there hasn’t been a successful combination of both, especially not the one focused on academia. Incredibly important is the topic of content moderation and abuse prevention, and it is points-based voting mechanics that will enable curation; and the reputation points the users earned will progressively unlock them new privileges on the platform, building a community and content that can be trusted.

Services like Github and OSF, showed us that it is possible to create within such highly transparent (open source/open science, versioned content) environments, and for good science, this is also a must.

The biggest mistakes that all of the publishing platforms were making so far were lack of incentives, moderation and curation (and we address all of those as mentioned), and a totally wrong approach for seeding the content - our approach will be focused on a-niche-at-a-time, and will enable us to extract learnings from them, all the while also providing them a value.

### Challenges
> What are significant technical **challenges** you expect to solve during the project, if any?

The architecture of Unfold will have to be distributed and asynchronous, combining different services (self-hosted and managed). Besides a general compute and a database, we also have to deal with: file uploading and processing (object storage, thumbnail generation, plagiarism detection etc), voting system and data aggregation (a lot of cron jobs to extract and aggregate data), search (populating ElasticSearch index and good search parametrization), versioning (all main content types are versioned (changes recorded over time) as to enable more transparency in research, and in some cases, there are couplings of two types of versioned content (files and publications, for example), which complicate architecture and could impact performance if not very careful), caching and rate-limiting (we’ll be implementing a caching layer, with Redis as a key-value store, that will be used by all the other dedicated services).

As can be seen, there are multiple challenges, but we are aware of them and we’ve already organized the infrastructure and architecture accordingly.

### Ecosystem
> Describe the ecosystem of the project, and how you will engage with relevant actors and promote the outcomes?

Academia can swallow new, small projects quite easily, so our approach will be centered around a gradual acquisition strategy - we’ll be opening the platform to the users one niche at a time (instead of opening it publicly at once). Our goal is to completely satisfy that one group of users, and gather useful feedback and insights that will enable us to continuously improve and balance the platform, while still being able to maintain full control and focus. This will enable us to also achieve a good SEO score for particular research areas, making our platform also progressively more visible and reachable.

We also plan to introduce the aforementioned alternative funding model for particular niches as a proof-of-concept, that will enable us to test and demonstrate that the business model *can* be improved and more satisfaction and fairness can be achieved.

We plan on collaborating with actors that promote (and work on) Open Science - eLIFE, Knowledge Futures, Digital Science, OSF, Wikimedia,... also offering our platform to all journals as their main publishing channel, and to all universities, journals, research groups and individuals our tools and services, either for direct use or through integrations.

All outside actors and our communities will help us create trust with the bigger academic community and public, which will undoubtedly take some time, and help us integrate new metrics and a new funding model in more and more places.

### Attachments

- [P&L sheet](p_and_l.pdf)
- [Design mockup](design_mockup.pdf)
