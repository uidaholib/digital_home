---
title: About
layout: about
permalink: /home/about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://objects.lib.uidaho.edu/campus/campus00811.jpg" heading="Digital Collections" text="University of Idaho Library" padding="6em" %}

{% include feature/nav-menu.html sections="About Digital Collections;CollectionBuilder;History;Contact" %}

# About Digital Collections

University of Idaho Library Digital Collections make tens of thousands of rare and unique items openly available online for research and learning.
The unique content includes digitized and born-digital materials curated by [Special Collections and Archives](https://www.lib.uidaho.edu/special-collections/), community partners, and scholarship projects.

Digital Collections contains over [120 custom collection websites and exhibits]({{ '/home/collections.html' | relative_url }}), each providing features to browse, explore, and understand the items with meaningful context. 
All individual items can also be discovered in our complete [search index](https://digital.lib.uidaho.edu/search) featuring tools to filter, sort, and search through thousands of records and full text data.

Collection strengths include [jazz]({{ '/home/collections.html#Jazz' | relative_url }}), Idaho [mining]({{ '/home/collections.html#Mining' | relative_url }}) and [wilderness]({{ '/home/collections.html#Wilderness' | relative_url }}), and [U of I history]({{ '/home/collections.html#campus' | relative_url }}).

These resources are created and maintained by the Library's Digital Collections Team, a collaborative effort between [Special Collections and Archives](https://www.lib.uidaho.edu/special-collections/) and the [Center for Digital Inquiry and Learning (CDIL)](https://cdil.lib.uidaho.edu/).
New items, collections, and exhibits are continually added, along with ongoing work to enrich metadata and enhance useability.
Contributors include employees across the library, student workers, fellows, researchers, and community partners.
Our most up to date procedures and standards are shared at our [Digital Collections Documentation site](https://uidaholib.github.io/digital-collections-docs/).

We invite you to explore, discover, and enjoy our unique collections!

<a href="https://digital.lib.uidaho.edu/search" class="btn btn-outline-primary m-3"><svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" width="16" height="16" fill="currentColor" class="bi icon-sprite" viewBox="0 0 16 16"><path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001q.044.06.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1 1 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0"/></svg> Digital Collections Search</a>
<a href="https://uidaho.co1.qualtrics.com/jfe/form/SV_eqZdsQyel8sKBAG?source_link=https://www.lib.uidaho.edu/digital/home/about.html" class="btn btn-outline-primary m-3"><svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" width="16" height="16" fill="currentColor" class="bi icon-sprite" viewBox="0 0 16 16"><path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414zM0 4.697v7.104l5.803-3.558zM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586zm3.436-.586L16 11.801V4.697z"/></svg> Contact Form</a>
<a href="https://lib.uidaho.edu/help/" class="btn btn-outline-primary m-3"><svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" width="16" height="16" fill="currentColor" class="bi icon-sprite" viewBox="0 0 16 16"><path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14m0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16"/><path d="M5.255 5.786a.237.237 0 0 0 .241.247h.825c.138 0 .248-.113.266-.25.09-.656.54-1.134 1.342-1.134.686 0 1.314.343 1.314 1.168 0 .635-.374.927-.965 1.371-.673.489-1.206 1.06-1.168 1.987l.003.217a.25.25 0 0 0 .25.246h.811a.25.25 0 0 0 .25-.25v-.105c0-.718.273-.927 1.01-1.486.609-.463 1.244-.977 1.244-2.056 0-1.511-1.276-2.241-2.673-2.241-1.267 0-2.655.59-2.75 2.286m1.557 5.763c0 .533.425.927 1.01.927.609 0 1.028-.394 1.028-.927 0-.552-.42-.94-1.029-.94-.584 0-1.009.388-1.009.94"/></svg> Library Help</a>
{:.text-center}

{% capture cdm %}
Please note that University of Idaho Library migrated our digital collections platform in January 2024. Older links that include the domain `digital.lib.uidaho.edu` will no longer function. *Those items still exist!* 
Please use our [CONTENTdm Migration Reference page](https://www.lib.uidaho.edu/digital/cdm-reference/){:.alert-link} to find current locations for broken links or use our updated [Digital Collections Search](https://digital.lib.uidaho.edu/search){:.alert-link}.
{% endcapture %}
{% include feature/alert.html text=cdm color="warning" %}{:.narrow-content}

## CollectionBuilder 

Most of our digital collections are generated using [CollectionBuilder](https://collectionbuilder.github.io), an open source minimal infrastructure platform developed by a team of librarians at the University of Idaho.

CollectionBuilder is driven by metadata and powered by static-web technology, so it's intuitive for librarians to use, lightweight, customizable, and secure. CollectionBuilder requires only a spreadsheet of metadata and a directory of digital objects to facilitate multiple modes of entry into a digital collection by generating timelines, maps, and browsing features that contextualize the collection's historic items. Following a Collections as Data model, CollectionBuilder also generates data files in multiple formats for researchers and patrons to download and explore.

Simple yet powerful, CollectionBuilder ensures that digital curation and preservation is in the hands of librarians. Read more about CollectionBuilder's minimal-computing approach at <https://collectionbuilder.github.io/>.

The University of Idaho's [Center for Digital Inquiry and Learning](https://cdil.lib.uidaho.edu/) has received grant funding to support further development of CollectionBuilder, including:

- *National Leadership Grant for Libraries* from the [Institute for Museum and Library Services (IMLS)](https://www.imls.gov/), titled ["Growing CollectionBuilder, A Sustainable Digital Exhibit Framework and Static Web Development Model"](https://www.imls.gov/grants/awarded/lg-252326-ols-22){:target="_blank" rel="noopener"}, 2022 to 2025.
- [Digital Humanities Advancement grant from the National Endowment for the Humanities (NEH)](https://securegrants.neh.gov/publicquery/main.aspx?f=1&gn=HAA-281018-21), 2021 to 2023.
- *National Leadership Grant for Libraries* from the [Institute for Museum and Library Services (IMLS)](https://www.imls.gov/grants/awarded/lg-34-19-0064-19){:target="_blank" rel="noopener"}, 2019 to 2021.

## History

Digital collections at U of I Library started in 2008 with an initial charge to digitize and make accessible the library's renowned [International Jazz Collections](https://www.ijc.uidaho.edu/). 
The Digital Initiatives department was established advance work on digitization, metadata, digital preservation, digital collections, and web sites, with a physical location in Library room 211.
Originally constructed as a space to support the research interests of the university -- David and Ann Lau donated funds in the 1990s to what was then the Lau Periodicals Service Center in honor of David's parents, Heber and Rhea -- the center was re-dedicated in April 2011 to acknowledge its function as the digital heart of the library.
As the services of the unit and needs of the campus continued to expand, Digital Initiatives grew into a campus digital scholarship center, the [Center for Digital Inquiry and Learning (CDIL)](https://cdil.lib.uidaho.edu) in 2016.

As past digital initiatives librarians mused:

> The Digital Initiatives department digitizes. That may not come as a surprise, but despite the fact that it is not all we do, digitization -- including the scanning of photographs, feed scanning of books, conversion of legacy files, batch processing of born-digital files, and other tasks -- is the foundation by which we build our collections and web sites and through which we digitally preserve institutional, local and scholarly material and resources.
> 
> But, again, digitizing is not all we do. We also work with departments, schools, librarians, citizens, machines, code, and each other to provide guidance on digital tools, projects and preservation, and to identify, acquire, and promote new collections.
{:.blockquote .p-3}

Digital collections are a collaborative and ever evolving effort to open access and understanding to fascinating resources.

## Contact

<a href="https://uidaho.co1.qualtrics.com/jfe/form/SV_eqZdsQyel8sKBAG?source_link=https://www.lib.uidaho.edu/digital/home/about.html" class="btn btn-outline-primary m-3"><svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" width="16" height="16" fill="currentColor" class="bi icon-sprite" viewBox="0 0 16 16"><path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414zM0 4.697v7.104l5.803-3.558zM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586zm3.436-.586L16 11.801V4.697z"/></svg> Contact Form</a>

- [Evan Peter Williamson](https://www.lib.uidaho.edu/about/people/ewilliamson.html), Unit Head for Digital Scholarship and Open Strategies
Digital; Digital Infrastructure Librarian; Co-Director of CDIL
- [Andrew Weymouth](https://www.lib.uidaho.edu/about/people/aweymouth.html), Digital Initiatives Librarian
- [Kevin Dobbins](https://www.lib.uidaho.edu/about/people/kdobbins.html), Digital Labs Manager
- [Maryelizabeth Koepele](https://www.lib.uidaho.edu/about/people/mkoepele.html), Digital Projects Manager
- [Devin Becker](https://www.lib.uidaho.edu/about/people/dbecker.html), Associate Dean Research and Instruction; Co-Director of CDIL
