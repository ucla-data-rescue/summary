Introduction
------------

The [End of Term Web Archive](http://digital2.library.unt.edu/nomination/eth2016/about/) is a project to preserve public government websites and data that are at risk of being removed during the transition from one US administration to another.  The Federal government has produced a great many websites and resources, and the process of archiving them takes weeks and months.  The goal of current _data rescue_ efforts is to identify the most urgent cases so that they get archived sooner.  "Urgent cases" are those that the incoming administration may be particularly antagonistic towards.

While we want as much as possible to go into the Internet Archive, some of the open data resources made available by different government agencies are in formats that the Internet Archive is not designed to handle technologically.  These data need to be downloaded separately, packaged up in a container along with a description of what the data is, and uploaded in other open repositories designed specifically for data archiving.

Summary of the webcrawler
-------------------------

A webcrawler is a program that visits a web page, stores a copy, then examines the page looking for links to _other_ web pages, follows those links, and repeats the process for every new page found.  It is useful to understand a little bit about how crawlers work and what their limitations are.

* [Understanding what the Internet Archive webcrawler does](https://docs.google.com/document/d/1PeWefW2toThs-Pbw0CMv2us7wxQI0gRrP1LGuwMp_UQ/edit)

* [Seeding the End of Term crawler's list of URLs to crawl](https://docs.google.com/document/d/1qpuNCmBmu4KcsS_hE2srewcCiP4f9P5cCyDfHmsSAVU/edit)

More information for seeders and sorters
----------------------------------------

The _Seeders and Sorters_ team canvases the resources of a given government agency, identifying important URLs.  URLs are nominated (equivalently, "seeded") using the [Chrome extension](https://chrome.google.com/webstore/detail/nominationtool/abjpihafglmijnkkoppbookfkkanklok) or bookmarklet developed for this purpose.  Each URL is added to a spreadsheet.

The reason for a human in the loop is this: the technological limitations of today's webcrawlers means that not everything can be automatically downloaded, so humans are needed to sort pages by whether they _can_ be completely captured automatically.  This sorting is really only provisional: when in doubt, seeders mark a URL as not crawlable, and humans in the next step of the workflow (the _researchers_) take a closer look at the "uncrawlables".

* [The nomination tool Google Chrome extension](https://chrome.google.com/webstore/detail/nominationtool/abjpihafglmijnkkoppbookfkkanklok)

* [The agency forecasts developed by EDGI](https://envirodatagov.org/agency-forecasts/) &ndash; we are focusing on DOE for seeding, and a set of uncrawlable resources identified by past events. In this UCLA event, our seeding and sorting goal will be Department of Energy (DOE) sites. We will prioritize (1) Office of Energy Efficiency and Renewable Energy, (2) Office of Science, (3) Energy Information Administration, (4) Federal Energy Regulatory Commission, and (5) National Renewable Energy Laboratory, in that order.

* **[Assignment tracking spreadsheet](https://docs.google.com/spreadsheets/d/10M1_AyyJFpBIDZ7s6VzVa98Tx8zJBIoJESLlHZkJ018/edit#gid=707149033)**

More detail for researchers
---------------------------

_Researchers_ take a closer look at URLs that seeers and sorters flagged as possibly not crawlable.  This activity requires more familiarity with HTML, JavaScript, the types of resources that might be encountered on the web, and how the web works in general.

* [Summary of procedure for researchers](https://github.com/datarefugephilly/workflow/blob/master/research.md)

* [Tips from Sam about what's uncrawlable](https://docs.google.com/document/d/1ZSx7zO6hRB_jjzwPO-zu-ps2eueZh3wRk4MrCxkMX_w/edit)

For many people and events, the researchers and harvesters overlap considerably.  For this reason, they work off the same list of URLs.  In our event, we are using a subset of uncrawlable URLs that was determined to be higher priority and already confirmed to be uncrawlable. This list of URLs is in a spreadsheet listed in the next step below.

More details for harvesters
---------------------------

Harvesters take the "uncrawlable" content and try to figure out how to capture it. This is often a complex task that can require substantial technical expertise, and often requires different techniques for different types of content.  A good description of the process has been put together by the DataRefuge group at UPenn in their toolkit:

* [Harvesting toolkit](https://github.com/datarefugephilly/workflow/tree/master/harvesting-toolkit)

The list of uncrawlables for our event is the following:

* The [uncrawlables work list](https://docs.google.com/spreadsheets/d/12BCFVgOleNWOqClKFUTz8SBCP7xClTGgs4nldh8XRj4/edit?usp=sharing)

More details about bagging, uploading and metadata creation
-----------------------------------------------------------

The steps above are part of a larger workflow still under active development by several groups.  The workflow tries to address the different kinds of content and websites that can be encountered.  Currently, the clearest articulation of that workflow is the following documentation developed by the UPenn group:

* [Philly workflow](https://github.com/datarefugephilly/workflow)


Additional details
------------------

[EDGI  (Environmental Data & Governance Initiative)](https://envirodatagov.org) is an international effort to develop tools, research networks, and initiatives to archive public environmental data proactively.  Together with [DataRefuge](http://www.ppehlab.org/datarefuge/), an effort from the University of Pennsylvania Program in the Environmental Humanities, they have been organizing data rescue events since December 2016.  We are using the workflows and tools they have been evolving.

* [EDGI Home page](https://envirodatagov.org)

* [EDGI EOT toolkit description](https://github.com/edgi-govdata-archiving/eot-sprint-toolkit)

License
-------

The diagram above is licensed according to the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/) by Michelle Murphy, University of Toronto, 2016.
