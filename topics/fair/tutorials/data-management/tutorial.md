---
layout: tutorial_hands_on
title: FAIR data management solutions
abbreviations:
  FAIR: Findable, Accessible, Interoperable, Reusable
  DMP: Data Management Plan
  PID: Persistent Identifier

zenodo_link: ''
questions:
- Is there a reproducibility crisis?
- What can go wrong with data analysis?
objectives:
- Learn best practices in data management
- Learn how to introduce computational reproducibility in your research
time_estimation: "10M"
key_points:
- FAIR data management allows machines to automatically find and use the data accordingly.
tags:
- fair
- dmp
- data stewardship
priority: 2
contributions:
  authorship:
    - kkamieniecka
    - poterlowicz-lab
  editing:
    - hexylena
  funding:
    - elixir-uk-dash
subtopic: fair-data

requirements:
  - type: "internal"
    topic_name: fair
    tutorials:
      - fair-intro

---


The FAIR (Findable, Accessible, Interoperable, Reusable)  data stewardship created the foundation for sharing and publishing digital assets, especially data. This apply to machine accessibility and emphasize that all digital assets should share data in a way that will enable maximum use and reuse.

This tutorial is a short introduction to the FAIR data management framework. You can find out more at the [FAIR Pointers](https://elixir-uk-dash.github.io/FAIR-Pointers/ep1/index.html) online course.

> <agenda-title></agenda-title>
>
> In this tutorial, we will cover:
>
> 1. TOC
> {:toc}
>
{: .agenda}

# Data management planning
In recent years, we have noticed a data explosion. The number of sequence records in each release of [GenBank](https://www.ncbi.nlm.nih.gov/genbank/statistics/), from 1982 to the present, doubled in size approximately every 18 months. Significant amounts of data are available to researchers, and it is easier than ever to collect data, but information then needs management. It's not just about size. Data protection law means that working with data from humans is hard.  A **data management plan (DMP)** is essential to achieve secure, excellent and FAIR data management. DMPs are often described as living documents and should be updated regularly. Plans made before the data is collected are projections, which frequently need amending as the research project progresses.

There are several ways to set up FAIR (Findable, Accessible, Interoperable, Reusable) data management plans (DMPs) :
  - Findable (F): Data description and collection or reuse of existing data
  - Accessible (A): Standardised authentication or authorisation (e.g. HTTP, HTTPS)
  - Interoperable (I): Documentation and data quality
  - Reusable (R): Storage and backup supported by legal and ethical requirements

    Or use a template from a funder. 

## Data description and collection or reuse of existing data
Reusing legacy datasets from institutional repositories or the digital libraries data collections can be FAIRified retrospectively. Support for data collection and development, throughout the life cycle can be provided and followed by change management and capacity improvement.

Multi-part FAIR research need a way of wrapping up, describing and sharing to promote the reuse of data. **Data sharing agreements** define the purpose of data sharing. Reference roles and responsibilities; specifies the purpose and legal requirements, e.g. for data security.  **Data sharing or transfer agreements** are often standardised. It's essential to use templates and only amend them with legal review. 

An institutional aim should be to create an integrated view and context over fragmented resources using their **persistent identifiers (PIDs)** and **metadata**. This is why we only use DOIs and standard metadata.

Enhancing reproducibility, quality and transparency by ensuring information flow and showcasing secondary use is also a part of data management. Promoting hands-on data experience and events activities built an collaborative environment for reproducible science.


## Documentation and data quality
Having access to local knowledge and encouraging best practises at the departmental level is a smart way to offer direction on a variety of standards and methods. In order to implement FAIR data practises within an institution, resources and infrastructure are needed. To increase the possibility of data reuse, several FAIR requirements can be satisfied using freely available guidelines e.g. [RDMkit](https://rdmkit.elixir-europe.org/), [FAIR Cookbook](https://faircookbook.elixir-europe.org/content/home.html), [ELIXIR-UK DaSH Fellowship](https://sites.google.com/view/navigation-portal-fellowship/home?authuser=0) initiative and repositories e.g. [Zenodo](https://zenodo.org/), [Harvard Dataverse](https://dataverse.harvard.edu/) and [figshare](https://figshare.com/).

## Storage and backup
SSystems for storage, backup and collaboration, such as the enterprise version of Google Drive used at Oxford Brookes, rely on robust technical infrastructure. However, it's crucial to underscore the importance of access management. This involves exploring the access controls on folders, using passwords, and not leaving defaults in place. A standard operating procedure for your research project is also essential to prevent accidental deletion or unintentional alterations to the data. 

At the heart of the FAIR research data lifecycle are repository services. These are not just a necessity, but a powerful tool for researchers. They provide easy access to the data, a persistent identifier, and descriptive metadata that support interoperability. More than just basic data storage, repositories offer a range of services. They can manage access and use of private information, facilitate peer review, and even ensure digital preservation. By utilizing these services, researchers can efficiently manage their data, freeing up their time for more important tasks.

We advise users to follow the procedure below:

1. The most effective option (if available) is to maintain the data by acknowledging discipline-specific criteria using an established, dedicated (external) data archive or repository that caters to the study domain or the funder's preferred repository.  
and then 
2. Using RADAR or Akivum to ensure the University has a copy. You can also use these as an option if a discipline-specific repository is not suitable or too expensive

The library can assist in offering advice on choosing a repository. 
## Legal and ethical requirements
It is always important to consider ethics before making any decisions. Ethics should come first in any research method, process, or approach.  You should consult your Frio and look at the ethics application form. 

# Conclusion
You will have the advantage of saving time and resources by planning how to FAIRify your data in the early phases of your research endeavour. To put this into action, a data management strategy, or DMP, must be written. A DMP is also where you outline your data collection, storage, processing, sharing, and disposal procedures. Planning the management and FAIRification of your data reduces the possibility of issues down the road, whether they be practical, legal, or technical.

Keep in mind that creating FAIR data is a complex process. Consider how you can make your data FAIR one step at a time at each stage of the creation, collection, documentation, storage, sharing, archiving, and preservation processes. The framework for the rest of your study planning is laid by incorporating your data documentation. Imagine you want to use a dataset that was generated by another researcher and how you would like it to be found. Hope this quick introduction to FAIR data management solutions will help you improve not only your experience with data but also influence others by using your guidance and FAIRified resources.
