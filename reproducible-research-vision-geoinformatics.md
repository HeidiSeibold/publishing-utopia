# A Vision for Reproducible Research in Geoinformatics, Geography, and Geosciences

By [Daniel Nüst](https://orcid.org/0000-0002-0024-5046) and [Markus Konkol](https://orcid.org/0000-0001-6651-0976)

## What is the problem with scholarly communication today?

Research today is complex and often requires diverse skills. 
Many researchers around the globe collaborate on small or large scale projects to solve global challenges.
Often, these challenges can only be solved in a [{intra, cross, multi, inter, trans}-disciplinary](https://www.arj.no/2012/03/12/disciplinarities-2/) groups and with the help of computing.
If you need computers and algorithms to analyse data, no matter how small or big, you are in the realm of _computational research_.
This in in stark contract to how a large part of scholarly communication, i.e., [_"creation, publication, dissemination and discovery of academic research"_](https://en.wikipedia.org/wiki/Scholarly_communication), works today.
Results are mostly communicated with static documents, and to a large degree even in a format best suited for printing documents on paper &#8212; the good ol' PDF.
However, scientific output is much more than just PDFs!
The scientific article of the past does not suffice anymore to communicate knowledge.
That is why it almost feels like the widespread use of [computers broke science](https://theconversation.com/how-computers-broke-science-and-what-we-can-do-to-fix-it-49938), and we now must adjust the way we share and communicate research.
A research project today does not only create static texts as outputs, but the related data and software used to create, process, and visualise that data.
_And publishing all these building blocks of research in a reusable and sustainable way is very very hard!_
The technical solutions and environments exist, but establishing them as common scientific practice takes time and a lot of persuading because researchers will have to adjust their habits and even give up a few beloved ones.

This blog post will try introduce some arguments and present some tools to start persuading _you_ to adopt computational research practices.
We will try not to fall into [technology solutionism](https://en.wikipedia.org/wiki/Evgeny_Morozov#To_Save_Everything%2C_Click_Here%3A_The_Folly_of_Technological_Solutionism), which is very hard not to do as software engineers, but being open for new technologies and a little bit of code will get you very far.
Is there a reproducibility crisis?
[Points of](https://www.nature.com/news/1-500-scientists-lift-the-lid-on-reproducibility-1.19970) [view differ](https://doi.org/10.1073/pnas.1708272114).
Your discipline might be better or worse off, better or worse prepared, but we're not going to answer that question here.
Instead, we focus on the following one.

## What can we do to fix the computational research gap?

Well, the short version of it is: we need _carrots_ & _sticks_, _money_ & _time_.
_So no big deal?!_
In our view, there will be no crazy blockchain-based platform for science that completely replaces the funding and review mechanisms we know today, though you should be aware of [transformative topics in scholarly publishing that are widely discussed](https://doi.org/10.3390/publications7020034).
Editors and reviewers at journals serve an important purpose as gatekeepers and curators.
Instead, we should introduce concepts and processes into science that embrace digitisation, especially in a way that allows small and independent journals to embrace them, too, and that keep scientists in control.
Such change will need time.
Until there are stronger incentives, better knowledge, and an [open infrastructure](https://investinopen.org/), we must applaud researchers who _do_ increasingly publish all of the building blocks of science, namely data, software, and the used computing environment.
We should not call these researchers out, but be aware of the challenges, e.g., around [scientific software](https://www.researchprofessionalnews.com/rr-news-uk-views-of-the-uk-2020-5-critique-software-but-understand-the-constraints-it-s-written-under/), and be constructive in our criticism.
The [Open Science](https://en.wikipedia.org/wiki/Open_science) movement has achieved tremendous success, particularly in the areas of [Open Access](https://en.wikipedia.org/wiki/Open_access) and [Open Data](https://en.wikipedia.org/wiki/Open_data).
We expect Open Methods and Open Code to follow suit within the next years  &#8212; again, change will take time.

_Are Open practices prevalent?_

No, not yet, despite the [large](https://doi.org/10.7554/eLife.16800) [number](https://doi.org/10.1186/s13059-015-0850-7) [of](https://doi.org/10.1371/journal.pone.0230416) [benefits](https://doi.org/10.1109/MSP.2009.932122) (watch out, that's one paper link per word and many _carrots_ for you!).
However, software publications (e.g., [JOSS](joss.theoj.org/) and [JORS](https://openresearchsoftware.metajnl.com/)), data publications, [software](https://ropensci.org/) [review](https://www.pyopensci.org/), [open peer review](https://en.wikipedia.org/wiki/Open_peer_review), and not the least [preprints](https://en.wikipedia.org/wiki/Preprint) and [prereviews](https://www.prereview.org/) have jump started academia's catch up with digitisation in the last years. 
Scientists themselves have the power to push these changes further as [individuals, community members, and holders of offices](https://peerj.com/articles/5072/#discussion).
Across these stellar initiatives to enhance science cut many challenges on [software sustainability](https://doi.org/10.12688/f1000research.23224.1), [data and software citation](https://doi.org/10.1007/978-3-319-96418-8_34), et cetera.
This is where we turn to _money_, _carrots_, and _sticks_: only if funders and evaluators (job boards, reviewers of grants/research groups/publications) recognise benefits of transparency and reproducibility will the requirements and rewards be put into place which lead to education, promotion, and eventually funding to achieve higher standards on openness.

_So what's the golden technology that saves us?_

## Research Compendium to the rescue!

There is one key concept that we think every researcher should be aware of: the [_research compendium_](https://doi.org/10.1198/106186007X178663).
Publishing a research compendium means that all building blocks of a research paper are shared in a coherent package.
Just as with a research manuscript, you take a snapshot of your current work and publish it in reusable form under open licenses in a suitable repository, i.e., a repository assigning [a permanent identifier](https://en.wikipedia.org/wiki/Digital_object_identifier).
A research compendium can take many forms, and every scientific discipline should have a public discourse about their minimal standards and means to handle specific requirements.
Two core technologies underpin many advanced research compendia: [notebooks](https://doi.org/10.1038/d41586-018-07196-1) based on the [literate programming](https://doi.org/10.1093/comjnl/27.2.97) paradigm and [containerisation](http://doi.acm.org/10.1145/2723872.2723882).
Containers allow to capture the virtual computing environment in a portable and well-defined way.
So if you want to up your game in Reproducible Research and Open Science, these are two practical tools you need to get a handle on.
Luckily, there are [plenty](https://doi.org/10.1371/journal.pcbi.1007007) [of](https://doi.org/10.1371/journal.pcbi.1005510) [resources](https://doi.org/10.31219/osf.io/fsd7t) to [educate](https://doi.org/10.1371/journal.pbio.2006022) yourself, and likely also one related to your discipline.
Watch out for courses and workshops related to openness and reproducibility at the next event you participate in!

If you embed a container into your research compendium, we call it an executable research compendium ([ERC](https://doi.org/10.1045/january2017-nuest)).
The research compendium can then undergo a peer review, ideally including a reproduction of the entailed computational workflow.
Research compendia have the potential to [enhance peer review](https://codecheck.org.uk/slides/2020-05_ReproHack.html) and greatly improve scholarly communication.
That is precisely what some authors, communities, publishers and journals are starting to do today.
If you are an author, reviewer, or editor getting in contact with a manuscript that includes data and computations, _you should consider leveraging research compendia for better reproducibility_.
If you want to learn more about research compendia and potential implementations, take a look at the website [**research-compendium.science**](https://research-compendium.science/).
If you are interested in reproductions as part of peer review, take a look at [CODECHECK](https://codecheck.org.uk/). If you want to learn more about the platforms that are build around containers, notebooks, and research compendia, take a look at a [recent preprint on infrastructures for publishing computations research](https://arxiv.org/abs/2001.00484).
  
## What about&hellip;

We are enthusiastic about openness and reproducibility!
We acknowledge there is a [spectrum](https://doi.org/10.1126/science.1213847) and perfection should not stop you from getting started, e.g., by [publishing your code](https://www.nature.com/articles/467753a).
[Every small step counts](https://twitter.com/Protohedgehog/status/1179005154940592133)!
However, some degree of [whataboutism](https://en.wikipedia.org/wiki/Whataboutism) exists and we try to debunk some perceived concerns:

**&hellip; sensitive data?**

[The](https://doi.org/10.1016/j.polgeo.2014.11.001) [solutions](https://science.sciencemag.org/content/365/6449/127.full) [exist](https://doi.org/10.1177/0002716217742610) and range from anonymisation, synthetic data, to public infrastructures and access control.
This is a question of establishing sustainable processes and long-term infrastructure, so mostly a challenge of funding and pervasion.

**&hellip; big data?**

If your workflows use a bespoke high-performance computing with huge datasets of several Petabytes, we admit a complete reproduction during peer review is unlikely to happen.
But you never know!
The practices of making sure someone else _could_ reproduce everything will improve your work's quality.
In this case, you should include a synthetic dataset or data subset in your research compendium, so that others can explore and understand your work within more widely available computing resources.

**&hellip; sustainability and reusability?**

A research compendium as presented above is a snapshot for your work at a specific point in time, but does not touch on reusability and sustainability.
However, in most guidelines about using research compendia you will actually also learn about a good working process, not just about sharing the final product.
For example, you can use version control ([git](https://en.wikipedia.org/wiki/Git)) and online collaboration platforms (e.g., [GitLab](https://gitlab.com/) or [GitHub](https://github.com/)) to take advantage of the structure and tooling around packaging your research every day, not just when you finish a specific project.

You should realise that _future you is your best collaborator!_
Therefore, all effort you spend on documentation is very well spent.
If nothing else, then _have a `README`_ that would be sufficient for getting yourself started after one year away from a project.
Documentation for others can be added on demand.
Furthermore, using open file formats (e.g., `CSV` instead of `xlsx`) and [reasonable](https://speakerdeck.com/jennybc/how-to-name-files) [file names](https://twitter.com/redpenblackpen/status/962892473709166592) will make your work more accessible to others and future you.
If fellow scientists can build upon your data or reuse your code on their own dataset, new collaborations can happen quickly.


**&hellip; licensing?**

[Copyright](https://en.wikipedia.org/wiki/Copyright) is important &#8212; without it, you would not be able to assign a license to enable others to reuse your work. 
Copyright is also [complicated](https://doi.org/10.2218/ijdc.v1i1.3), because it varies greatly across countries.
It must be acknowledged that for some researchers, e.g., in industry collaborations or when using non-open software, publishing all data and software openly is a problem.
For the majority of publicly funded research, however, closed science practices remain because knowledge, education, habits, and best practices are missing, and concerns around licenses are not yet debunked.
There is no way around [educating](https://doi.org/10.1371/journal.pcbi.1002598) [yourself](https://doi.org/10.1109/MCSE.2009.19) on copyright questions, not the least because of the many [colours of Open Access](https://en.wikipedia.org/wiki/Open_access#Colour_naming_system).

On a technical note, more work needs to be done to assign suitable licenses to data, software, and text within a compendium. [Different license types](https://doi.org/10.1109/MCSE.2009.19) are needed for these artefacts, but it's not simple yet to achieve transparent licensing.

**&hellip; some researchers not buying in?**

Change takes time, but the disruptions in scholarly communication and the problems, such as [publication bias](https://en.wikipedia.org/wiki/Publication_bias) or [p-hacking](https://en.wikipedia.org/wiki/Data_dredging), are too pressing so that the scientific community cannot take too long to address them.
When we [improve](https://www.nature.com/news/bibliometrics-the-leiden-manifesto-for-research-metrics-1.17351) [metrics](http://juser.fz-juelich.de/record/865096/files/Peer%20Review%20and%20Bibliometrics.pdf), use [alternative ones](https://doi.org/10.1038/493159a), or adjust [researcher assessment](https://sfdora.org/), then "open science" will become "science" and "reproducible research" will become "research" again.
Until then, the spirit of [preproducibility](https://doi.org/10.1038/d41586-018-05256-0) can unite the researchers interested in better research today.
_The key challenges are social, not technological!_

## What will research communication be like in 10 years?

_Thanks for asking!_

We hope that research compendia power the scholarly communication process.
Of course we would be proud if our own concept of the _executable_ research compendium is still used.
The ERC features the idea of [bindings](https://doi.org/https://doi.org/10.1145/3331158) to let readers more easily interact with workflows and link visual presentation better to the actual used code and data &#8212; and all of that without authors becoming web developers.

With a large body of research compendia published, we expect completely new and exciting ways of discovering, integrating, and interpreting research, even using algorithms for reasoning on research compendia.
A "default to open" will save a lot of time and money: easy collaboration and reusability is the norm, because applying the new algorithm of paper A to the dataset of previously published paper B will be possible with a few clicks in an online platform.
Federated access to data and computing infrastructure is transparently negotiated in the background.
Contributions to the newly created work and citations of leveraged inputs will be stored in the metadata without manual intervention.
Adaptive presentations on research results will exist for different user types, such as decision makers, citizens, or journalists, so that current research is much better connected to the general public.
It will be like... the future! We call it an [_Open Research Infrastructure for Geoinformatics_](https://doi.org/10.4230/LIPIcs.COSIT.2019.8), but all disciplines can build upon and extend these ideas to their needs.

We are currently running small [pilot studies](https://o2r.info/pilots/) to demonstrate the concept and prototype in the "real world", but could use more interested authors and editors.
One of the pilots plans to [enhance the Open Journal System (OJS)](https://o2r.info/2020/02/26/OJS-workshop-HD/) with research compendia, as we expect universities, independent publishers, and non-profit organisations to increasingly create alternatives to large commercial publishing companies.
In light of [COVID-19](https://en.wikipedia.org/wiki/Coronavirus_disease_2019) taking a hold of humanity, the limits and [challenges around science communication](https://wonkhe.com/blogs/the-purpose-of-publications-in-a-pandemic-and-beyond/), both within academia and, more importantly, with the public, are broadly revealed.
We should take the opportunity to focus not only on reducing (oftentimes perceived) current barriers, but to foster cultural change and new innovations for a sustainable transformation towards openness and reproducibility.
Let's do it &#8212; individually and as communities.

## Who are we?

We are a part of the team behind the project [Opening Reproducible Research (o2r)](https://o2r.info/) and hope we could give you some food for thought and provide some links you had not seen before.
o2r is supported by the [DFG](https://o2r.info/about/#funding).
You can follow/contact us on Twitter [@o2r_project](https://twitter.com/o2r_project) and check out our software on [GitHub.com/o2r-project/](https://github.com/o2r-project/).
You can also fully dig into all our plans and ideas, because [we published our full research proposal](https://doi.org/10.17879/42149626934).
