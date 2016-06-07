## Share, publish, & archive research products

authors: <a href="https://github.com/Reproducible-Science-Curriculum/rr-publication" target="_blank">Reproducible Science Curriculum contributors</a>, modified by NEON staff.


## Reproducibility Is Beneficial

* To us as scientists.
* To the scientific community.


##

> [Five selfish reasons to work reproducibly](http://www.genomebiology.com/2015/16/1/274) - Florian Markowetz

1. Reproducibility helps to avoid disaster.
2. Reproducibility makes it easier to write papers.
3. Reproducibility helps reviewers see it your way.
4. Reproducibility enables continuity of your work.
5. Reproducibility helps to build your reputation.

## Share vs. Publish vs. Archive.

** Share, Publish & Archive are not the same things. **

## Share

> _SHARE_: any way of sharing information -- could mean I emailed it to you


## Publish

> _PUBLISH_: The data / code are citable & discoverable

## Archive

> _ARCHIVE_: Long-term preservation -- there is a long term plan to store
(and provide access to) the data / code.

## Publish & Archive

In this presentation, we'll focus on publishing & archiving.

## Common Questions

* Why publish?
* Who are we sharing with?
* What materials do we need to publish?
* When do we make them available?
* Where do we publish various outputs?
* How do we prepare materials for publication?

##

Let's assume that we are at the point of submitting our manuscript.

## Why Publish?

* Increased visibility / citation.
* Funding agency / journal requirement.
* Community expects results from funded projects.


## Increased visibility / citation


<div class="column column1">
<figure>
  <img src="images/share-publish-archive/PiwowarVision_2013_PeerJ_Fig1.png" width="90%" alt="Baby Orang Utan hanging from a rope">
</figure>
</div>
<div class="column column2">
<small> Figure 1: Citation density for papers with and without publicly available
microarray data, by year of study publication. </small>
Source: [Piwowar & Vision. 2013. Data reuse and the open data citation advantage](https://dx.doi.org/10.7717/peerj.175)
</div>

## Requirements Can Vary

* **FUNDING AGENCIES:**  
    - [NSF Dissemination and Sharing of Research Results policy](http://www.nsf.gov/bfa/dias/policy/dmp.jsp)
    - [NIH Data Sharing policy](http://grants.nih.gov/grants/policy/data_sharing/)
* **JOURNALS:**
    - [PLOS Publishing policies](http://journals.plos.org/plosone/s/editorial-and-publishing-policies)
    - [Nature Publishing policies](http://www.nature.com/authors/policies/availability.html)

## Why Publish / Share?

* Increased visibility / citation
* Funding agency / journal requirement
* Community expects it
* _Better research_
* _More efficient, less redundant science_
    - Others can more effectively build upon your work

## Why Share? Better Research.

<div class="column column1">
![](http://journals.plos.org/plosone/article/figure/image?size=large&id=info:doi/10.1371/journal.pone.0026828.g001)
</div>

<div class="column column2">
Figure 2: Distribution of reporting errors per paper, for papers from which data
were shared and from which no data were shared.

<small>Source: [Wicherts et al. 2011. Willingness to Share Research Data Is Related to the Strength of the Evidence and the Quality of Reporting of Statistical Results.](http://dx.doi.org/10.1371/journal.pone.0026828)</small>
</div>

## Who do we need to share with?

* Collaborators.
* Peer reviewers & journal editors.
* Broad scientific community.
* General public.

>For research to be reproducible, the research products (data, code) need to be
publicly available in a form that people can find and understand them.

## What Should We Share?

**Consider a recent project or paper of yours:**

- Which parts are important to publish?
- Which parts are less important to publish?
- Which parts are too sensitive / cannot be published?


## Things We Should Publish

* Starting data set (if it's not already available)
* Metadata
* Data cleaning steps
* Analysis scripts
* Source code
* Readme


## Things We Should May or May Not Publish

* Raw data: especially if it's already available
* Processed / cleaned data
* Intermediate results

## Things We Shouldn't Publish

* Confidential (e.g., patient) data
* Material already published
* Pre-existing restrictive license
* Passwords, private keys


## How To Decide What to Publish

> Pro-Tip: Re-run your analyses: Make all of the data, code & notes needed  to
run your analysis, available.

[Computing Workflows for Biologists: A Roadmap](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002303)

## When Should I Publish?

> You can make your code and data public at any point of the research process.
When you submit a paper, results should be
reproducible and data & code should be published.

- Journals often require code publication.
- It lets the editor and the reviewers accurately review the papers research methods.
- You can often publish code and data for reviewers only to be publically released when the paper is published.

## Where Should I Publish?

* Domain-specific data repository (GenBank, PDB)
* Source code hosting service ([GitHub](http://github.com), [Bitbucket](http://bitbucket.com))
* Generic repository ([Dryad](http://datadryad.com), [figshare](http://figshare.com), [Zenodo](http://zenodo.org))
* Institutional repository
* Sharing services ([RPubs](http://rpubs.com), [iPython Notebook Viewer](http://nbviewer.ipython.org/), Dropbox, Google Drive)

## Data Sharing Repositories

[Growth of re3data.org](http://www.re3data.org/2014/11/over-1000-research-data-repositories-indexed-in-re3data-org/)
![](http://www.re3data.org/wp-content/uploads/2014/11/growth-re3data.png)

## Many repositories

[Registry of Research data Repositories](http://re3data.org)

> Pro_tip: Archival Repository is one that retains your
data for a set period of time. Funding agencies often have requirements associated
with duration of the archive.

## How to Chose a Repository

* Is there a domain specific repository?
* What are the backup & replication policies?
* Is there a plan for long-term preservation?
* Can people find your materials?
* Is it citable? (does it provide DOIs)
* Is your purpose archival, sharing or publication?

## Where to Publish Various Parts of a Project

**You will likely have different project components:**

* R Markdown (Jupyter notebook, etc)
* Source code
* Other documentation
* Raw data
* Derived data

## Where to Publish Various Parts of a Project

**Example (R focused) workflow:**

* Develop code: GitHub
* Upon Publication:
    - Share R markdown on RPubs
    - Archive a snapshot of data in Dryad
    - Code snapshot to Zenodo


## Resources: Libraries Can Help

> Pro-Tip: University and institution libraries often have resources for data
management plans, repository access and data archiving.

Ask a Librarian!

## Resources: Libraries Can Help

Example: The data management page from Duke University:
<iframe width="100%" height="700px" src="http://library.duke.edu/data/guides/data-management"></iframe>

## Document Format Considerations

**Do Use:**

* Non-proprietary file formats
* Text file formats (.csv, .tsv, .txt)

**Don't Use**

* Proprietary file formats (.xls).
* Data as PDFs or images.
* Data in Word documents.

## How to share & publish: standard data formats

> Pro-Tip: Using standard data formats increases opportunities for re-use and
expansion of your research.

## A Reproducible Project Should Include

* Top-level `README` that describes data / software package
* List files & naming conventions
* Describe abbreviations, column names, etc
* Software installation & usage instructions
    - Create separate `INSTALL` if long
* Citation instructions
    - Consider creating a [`CITATION` file](http://blog.rtwilson.com/encouraging-citation-of-software-introducing-citation-files/)
* Contribution instructions
    - Github will automatically link to `CONTRIBUTING` file for new issues and
    pull requests

## Does copyright apply?

**Copyright applies to creative works**

* source code
* text (manuscripts etc)
* images

## Does copyright apply?

**Typically not copyrightable:**

* data, results
* individual records in a database of facts

**Depends on jurisdiction and case:**

* curated collections of data
* databases
* medical images

## Choose A License


<iframe width="70%" height="700px" src="http://choosealicense.com/"></iframe>

## Software licensing guide
<small>Figure 3: Schematic representation of license directionality.</small>
<small>Source: Morin, Andrew, Jennifer Urban, and Piotr Sliz. 2012. [A Quick Guide to Software Licensing for the Scientist-Programmer.](http://dx.doi.org/10.1371/journal.pcbi.1002598) PLoS Computational Biology 8 (7): e1002598 </small>

![](images/share-publish-archive/journal.pcbi.1002598.g002.png)

## Creative Commons

<iframe width="100%" height="700px" src="http://creativecommons.org/choose/"></iframe>

## Open is not open to interpretation

[The Open Definition](http://opendefinition.org/) sets out principles that
define “openness” in relation to data and content. It makes precise the meaning
of “open” in the terms _open data_, _open content_, and _open source_:

> <small>“Open means anyone can freely access, use, modify, and share for any purpose
(subject, at most, to requirements that preserve provenance and openness).” </small>

or more succinctly:

> <small>“Open data and content can be freely used, modified, and shared by anyone for
any purpose”</small>

## Waiving copyright


<center>[![CC Zero](http://mirrors.creativecommons.org/presskit/buttons/88x31/png/cc-zero.png)](http://creativecommons.org/about/cc0)</center>

CC0 enables scientists, educators, artists and other creators and owners of
copyright- or database-protected content to waive those interests in their works
and thereby place them as completely as possible in the public domain, so that
others may freely build upon, enhance and reuse the works for any purposes
without restriction under copyright or database law.

## Dryad requires CC0

[Dryad’s use of CC0](http://datadryad.org/pages/faq#info-cc0) to make the terms
of reuse explicit has some important advantages:

* **Interoperability**: Since CC0 is both human and machine-readable, other people
nd indexing services will automatically be able to determine the terms of use.
* **Universality**: CC0 is a single mechanism that is both global and universal,
covering all data and all countries. It is also widely recognized.
* **Simplicity**: There is no need for humans to make, or respond to, individual
data requests, and no need for click-through agreements. This allows more
scientists to spend their time doing science.

## Licenses versus community norms

From the [Panton Principles](http://pantonprinciples.org/faq/#Q11_What_are_community_norms_and_why_are_they_important):

> <small>[...] in the scholarly research community the act of citation is a commonly
held community norm when reusing another community member’s work.
>
> Community norms can be a much more effective way of encouraging positive
behaviour, such as citation, than applying licenses. A well functioning
community supports its members in their application of norms, whereas licences
can only be enforced through court action and thus invite people to ignore them
when they are confident that this is unlikely.</small>

## Licenses are legal instruments


* Licenses, copyright, terms of use are complicated issues.
* There are legal implications to your choices.
* Citation is a professional norm in science.
    - We have good systems for ensuring proper citation.
    - Would you try to sue someone in court who fails to cite you properly?
* Keep it simple by putting the least-restrictive license possible

<br/>
_Let scientists do science without having to talk to lawyers._

## Challenges and concerns about publishing data and code

Thought Question: What are some of the challenges of publishing research
products? What are some of the concerns that people have?
