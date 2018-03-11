# Building communities to support Research Software Engineering

## Background

So many of us have been fired up by the [UK Research Software Engineer (RSE) initiative](http://rse.ac.uk) and it's spread throughout further European Countries. The spark for this particular meeting started at the [2nd RSE conference](http://rse.ac.uk/conf2017/) held in 2017. 

For me, the initiatives described by [Toby Hodges](https://twitter.com/tbyhdgs) at [European Molecular Biology Laboratory (EMBL)](https://www.embl.de/) at Heidelberg and [Tobias Schlauch](https://twitter.com/TobiasSchlauch) at the [German Aerospace Center (DLR)](http://www.dlr.de/sc/en/desktopdefault.aspx/tabid-1177/) had been two of my favourite talks and motivated me to find out more. I kept in touch with Toby and we informally swapped notes over online meetings. In the meantime Toby and Tobias had already been synthesising some of their experiences, published in [this post](https://www.software.ac.uk/blog/2017-12-13-encouraging-good-software-development-practice-research-teams) at the [Software Sustainability Institute's website](https://www.software.ac.uk/). I was also excited to see the results of the [German RSE](http://www.de-rse.org/en/) survey presented by [Stephan Janosch at FORCE17](http://www.de-rse.org/blog/2018/03/06/verteilung-der-umfrage-in-deutschland.html) but saddened by some of them.

In particular, too big a portion of German RSEs do not look forward to another day's work or see RSE as a long-term career option in that first survey. I wanted to give each one a giant hug! 

<img src="assets/vibes.png" height="300" width="500">
<br>
source: ['Results of RSE-de 2017 survey' presented at FORCE17 by Stephan Janosch](https://presentations.copernicus.org/FORCE2017-30_presentation.pdf)

While there's surely a whole host of reasons, we all feel an important aspect of the UK RSE initiative has been to gather us up into a community. With that in mind, an interesting question arose: 

> How can we leverage community to spread better research software development practice and create a better working environment for all?

And how better to answer it than to get around a table and swap notes on our experiences of community building so far? 

Motivated by a need to learn more about building remote communities, with a view to expanding the community beyond their locale, the [EMBL Bio-IT](https://www.embl.de/research/interdisciplinary_research/bioinformatics/community/bio-it/) biocomputing community made arrangements to host us all at their site in Heidelberg and set the date for 24 Jan 2018. Myself and Stephan were also gratefully supported by the Software Sustainability Institute and EMBL Bio-IT respectively who covered our costs for the trip.

## Participants

![](assets/peeps.jpeg)
<br>
_Clockwise from bottom-left: Anna Krystalli, Stefan Helfrich, Toby Hodges, Stephan Janosch, Michael Meinel, Malvika Sharan_

Toby Hodges, Malvika Sharan, and Georg Zeller shared experiences from EMBL Bio-IT, with a brief appearance (via video call) from Aidan Budd to provide details of the early days; Michael Meinel representing the DLR took Tobias Schlauch' place who sadly could not join; Stephan Janosch brought experiences from a number of initiatives, spanning from his local institution Max Planck Institute of Molecular Cell Biology and Genetics ([MPI-CBG](https://www.mpi-cbg.de/en/home/), via the [Dresden Concept](http://www.dresden-concept.de/en/home.html), a research alliance among 24 Dresden based research institutions, to the national de-RSE network of German RSEs; Stefan Helfrich, an excellent impromptu addition resulting from Toby's involvement in [the Carpentries' mentorship groups program](https://github.com/carpentries/mentoring/tree/master/mentoring-groups), represented the Network of European Bioimage Analysts ([NEUBIAS](https://eubias.org/NEUBIAS/)) as well as German BioImaging ([GerBI](http://germanbioimaging.org)).

My own interest came from exploring the literature on [**communities of practise**](http://wenger-trayner.com/introduction-to-communities-of-practice/) for a proposal I was writing. Communities of practice provide a domain specific platform through which to bringing outsiders in through practice and participation. A productive and creative culture is established through shared, codified repertoires of best practice and supplemented by channels of tacit knowledge flow. Their magic lies in the social capital they create across the network of collaborative relationships they foster. 

Some of the most successful modern communities of practice are digital open source communities. They leverage the internet and digital tools to codify, document, develop, share and communicate community knowledge, expand networks and culture, and actively invite and encourage participation. In turn they have made the internet the rich place it is today. 

I also quickly realised I had experience of some great examples of such open source communities from which to draw inspiration. From the [Mozilla Open Leaders mentorship program](https://mozilla.github.io/leadership-training/), [rOpenSci](https://ropensci.org/) and wider [R programming community](https://www.r-project.org/), to local communities, as a co-organiser of the [R Users group](https://www.meetup.com/SheffieldR-Sheffield-R-Users-Group/) and the nascent [dataviz.shef](http://dataviz.shef.ac.uk/) initiative looking to build community around data visualisation across the University of Sheffield.

As community builders seeking to facilitate broad culture change and capacity building in computational research practice, there is much to emulate from open source approaches. But once we've shown researchers some of the tools at their disposal, how to use them and some best practice guidelines, success depends very much on their response to the challenge we are effectively posing to them as users, beautifully articulated in the intro to [**open advice**](http://open-advice.org/#rmobox):

> Yes, users. Even if you did not realize it or "never signed up for no community," you in fact are already a part of this community. The question is whether you'll choose to participate actively.


**A lot more is possible if they are willing to participate.**

## On the Day

The motivation for this meeting was to swap notes on what we've tried already to build community, what worked particularly well and identify challenges and steps for the future.  Here we try and pull together some recurring threads in our experiences. But please note that the examples mentioned in this blog are by no means exhaustive. 

### What Works

#### Knowing your community

This is fundamental to the community's ability to add value and should be one of the first community development steps. We need to know both where the community is at and where they want to go. Activities responsive to such community goals, needs and aspirations will generate a higher rate of engagement and voluntary participation.

*And it all started with a survey*: we all started with some form of surveying our communities. But on-going revisiting and reflecting on such fundamentals is important for community sustainability. 

#### Effective communication channels

**Community == communication**

Effective communication channels are vital for both the transfer and processing of information, particularly of tacit knowledge, but also for fostering social, collaborative relationships. Across the various initiatives, approaches tried include mailing lists, [Slack](https://slack.com) and [Glip](https://glip.com) channels, [Google Groups](https://groups.google.com/) and other discussion forums. 

A stand out example of community communication is the [mattermost](https://about.mattermost.com/) based Bio-IT internal chat system, set up by community members. Fine control of the features and privacy of the system has made it highly adaptable to serving the community's needs. Coupled with an internally hosted [GitLab](http://gitlab.com/) based repository system, they've managed to build a thriving complementary online community actively engaged in sharing, co-developing, reviewing and discussing their software. The only drawbacks are that it can be difficult to open up discussion to the outside world. 

But it's important to note that it's often more efficient to signpost and develop links across communities than trying to reproduce parallel versions. For example, for R questions beginners might have, I would unhesitantly guide learners to the [R for Data Science (#R4DS) slack community](https://medium.com/@kierisi/r4ds-the-next-iteration-d51e0a1b0b82). The 1000+ strong slack team of mentors and learners is a constant hive of discussion, trouble shouting and sharing wins while working through [R for Data Science](http://r4ds.had.co.nz/). For slightly more technical questions, I might guide someone to the [rOpenSci](https://ropensci.org/) [slack community](), the [rOpenSci](https://discuss.ropensci.org/) or [Rstudio](https://community.rstudio.com/) discussion boards (powered by [discourse](https://www.discourse.org/), another nice open source community building resource) or #rstats [stackovelflow](https://stackoverflow.com/questions/tagged/r).

Overall to be successful, they'll need to be diverse enough to allow for varied communication styles, including the option for private communication, but to be most effective they're better when they are integrated.

#### Codifying and documenting community practice.

A foundational resource for establishing community culture and practice is the codification and dissemination of standards and guidelines. The German Aerospace Center (DLR) approach is a particular great example. They make use of wikis and check lists in a variety of formats (e.g., Markdown and Microsoft Office Word) to help guide software development. They have established a minimum requirement for all software and further recommendations follow a tiered level framework determined by a software's application class, in particular the software scope and size as well as the foreseen period of development. Individual recommendations are linked to reasoning and further advice which help researchers to understand and get behind the recommended practices. Importantly, the group work with contacts at each institute of the DLR to regularly get feedback on evolving requirements for guidelines, new tools and training. 

<img src="assets/ts-guidelines.png" width="800" height="600">
<br>
_Slide from Tobias Schlauch's_ [_talk_](http://rse.ac.uk/conf2017/wp-content/uploads/sites/2/2017/11/Helping-a-friend-out-%E2%80%93-Guidelines-for-better-software_4_3.pptx) _at 2nd RSE conference: 'Helping a friend out: Guidelines for better software'_.

Materials are currently in German but as we eagerly await their translation into English, perhaps this is somewhere the RSE community can help, by establishing community translation initiatives (see this [excellent post by Achintya Rao](https://medium.com/@RaoOfPhysics/a-guide-to-collaborative-translation-workflows-48c259100614) on how collaborate translation could be supported). 

More broadly, excellent Guidelines of Best Practice and documentation are emerging, e.g.

- the Netherlands [eScience Centre Guide](https://guide.esciencecenter.nl/). 
- the rOpenSci [Reproducible Research Guide](https://ropensci.github.io/reproducibility-guide/)
- the British Ecological society  Guides to [Data Management](https://www.britishecologicalsociety.org/wp-content/uploads/2017/06/BES-Data-Guide-2017_web.pdf) and [Reproducible code](https://www.britishecologicalsociety.org/wp-content/uploads/2017/12/guide-to-reproducible-code.pdf)
- [The Practice of Reproducible Research](https://www.practicereproducibleresearch.org/): Case Studies and Lessons from the Data-Intensive Sciences

Efforts also take the form of laboratory level project management policies and tools e.g.

- [Kirstie Whittaker](https://github.com/WhitakerLab/WhitakerLabProjectManagement) and [Christie Bahlai](https://github.com/BahlaiLab/Policies/blob/master/Project_completion.md)'s lab policies.
- [Ben Marwick lab's `rrtools`](https://github.com/benmarwick/rrtools), open lab level tools for setting reproducible research projects

At this point, it feels like we should be building upon and refining such efforts rather than duplicating them and feel that focusing on developing reusable, customisable templates to help guide best practice would serves us well.

Having said all this, it is important to note that community documentation can take many forms, including blogs, wikis, READMEs, bug reports, discussion boards and sites like Stack Overflow. It still blows my mind that the substantial R-related content on Stack Overflow, without which I would have never completed a PhD, was seeded by a [flashbombing the site with R questions and answers](http://www.decisionsciencenews.com/2009/09/03/r-flashmob-2-tuesday-8-september-2009/) back in 2009, and arguably became a foundational online knowledge base for the R community. Such repositories of tacit knowledge provide platforms for the community to process information and incorporate into refinements of tools and best practice guidelines.

#### Actively fostering engagement and participation

Successful communities thrive on diverse contributions from a wide range of their members. Most of the attendees at this particular meeting were representing the efforts of a much broader selection of contributors to their respective communities. The role of a community coordinator is often to encourage and facilitate the voluntary efforts of the larger group, and it is this engagement across the whole community that, in turn, produces the most amazing results. To get some idea of the number of individual contributions that it can take to create a successful community, check out the Acknowledgments slide from [Toby's talk at RSE17](http://rse.ac.uk/conf2017/wp-content/uploads/sites/2/2017/11/Bioinformatics_Community_Hodges_RSE17_2.pdf)!

Welcoming, supportive active community catalysts [can have a huge impact in setting the tone](https://ropensci.org/blog/2017/07/18/value-of-welcome/), and can be the deciding factor on whether newcomers choose to stay and participate. It's no surprise we routinely ended up back at Bio-IT t~0~, and **Aidan Budd**'s initial vision, drive and ability to be the hub that drew other people together. Other great examples include **Maëlle Salmon** ([\@ma_salmon](https://twitter.com/ma_salmon)) as an **rOpensci** package review editor, **Stefanie Butland** ([\@StefanieButland](https://twitter.com/StefanieButland)) as **rOpensci** community manager and **Jesse Maegan** [\@kierisi](https://twitter.com/kierisi) for establishing [#R4DS](https://medium.com/@kierisi/r4ds-january-challenge-69324561ef2b) and Abigail Cabunoc Mayes, ([\@abbycabs](https://twitter.com/abbycabs)) Practice Lead of the Mozilla Working Open mentorship program. 

Ultimately, though, it's about member participation, so the superpower of great community catalysts is to actively acknowledge and promote member contributions and help them share their stories, ideas and questions. And while this all may come more naturally to some, we can all aspire to be better community catalysts.

I'll leave you with another quote from open advice, this time by [Jono Bacon]():

> I have talked about there being two types of community managers;
> those who go out and give presentations and wave their hands
> around talking about a product or service, and those who work with
> a community of volunteers to help them to have a fun, productive
> and enjoyable collaborative experience. I am more interested in the
> latter – I feel that is what a real community manager does. 

#### Training

We all identified providing training, developing materials and workshops still fundamental to baseline computational skill development. Initiatives like the Carpentries or Elixir are making huge strides in establishing the foundations for scaling. We also all recognised the importance of flexibility and hearing from your community and being able to adaptively develop training according to identified domain needs. 

But to for both individuals and the community to reap the benefits of technical training, it's important to equip researchers with the digital citizenship skills required to be effective nodes. The ability to access and recycle material, share through and post to the web are incredibly empowering, but only up to a point. Being able to effectively propose an idea, share it, build it in the open, get feedback, onboard collaborators and incorporate contribution underpin the emergent community social capital and knowledge flow we see in open source communities today. So skills in collaboration, leadership, mentorship and even asking for and giving help are critical. Additionally, an ability to iterate in response to user feedback requires humility, openness and transparency. As community leaders, we set the precedent and the tone for any community so effective leadership must be driven from the position of a peer. 
 
#### Events!

Communities are above all social so bringing people together through events is vital. To keep people engaged and maximise participation, good variety and rhythm are key.

Conferences are still a great place to get together and there is no doubt that the RSE conferences have been a huge spring board for the UK RSE community and beyond. The centrality of the [conference](http://eubias.org/NEUBIAS/neubias2020-conference/symposium2017-lisbon/) in the maintenance of the NEUBIAS community also speaks volumes about the importance for technical disciplines of science to have that space for knowledge exchange and network building. Since members of the NEUBIAS community are spread all over Europe with small communities (if at all) at their local institutes, an annual conference offers great possibilities to get work done. This is especially important since many members are in scientific support positions with little time to get involved in community activities during working hours. Conferences attendance, however, implies blocked time on the calendar and offers the chance to collaborate "offline".

But there's a lot more fun we can have with events! For example my favourite thing to organise is hackathons! Academic "fun" hacks can be a sociable and effective way of getting people to learn/practice new things and tackle challenges in their field without pressure and with the support of others. They are great opportunities to practice more fundamental skills like using version control systems to collaborate online while hack themes can provide opportunity to delve into more specific topics. For example, the Reproducibility hackathons ([#ReproHack](http://rse.shef.ac.uk/blog/opencon_london/)) we organised as part of the OpenCon Berlin (2016) and London (2017) satellite events, gave participants the opportunity to explore other people's code and data and get exposure to different approaches to making research reproducible.

Other more focused learning sessions like **coding clubs** and **training schools/learnathons** are great ways to bring people together to work on more advanced topics and get feedback. Coding clubs work best when sessions are focused, like working through a book, training program or even blogposts. In the case of workshops, as materials have to be moderated/prepared by someone, the events have the side-effect of bringing together not only learners but also trainers over a period of time that facilitates fruitful discussions.

Note that local events can also now easily open up proceedings to remote participants. Streaming or recording events, allowing call ins or even just opening a gitter channel or posting links to live documents could help broaden engagement.

Final top tip: Food and drink == always a winner! 

#### Buy in from upper management + funding

One of the key drivers of the longest standing and most developed communities is buy in and support from upper management or sponsorship early on. Bio-IT benefited by a need for the initiative being flagged early on and led to them now having nearly 8 years of well-resourced effort under their belt. Similarly, the DLR initiative was driven by first raising awareness at upper management level which subsequently lead to upper management support.

Related to buy in is financial support of activities. At the very least, funding for dedicated community building personnel can provide an important start. e.g. 

```
EMBL and DLR <- want to expand on the funding?> 
```

and Mike Croucher's EPSRC Fellowship supported such seed roles at the University of Sheffield. 

Since research is an inherently international and/or multi-organization endeavor, financial support from umbrella organization can also be sought. The European Union, for instance, has established a programme (COST) for setting up international research networks which supported costs associated with NEUBIAS setup, events (conferences, training schools, short scientific exchanges) and networking activities. Additional information on funding schemes is described in [Eisfeld-Reschke J., Herb U., Wenzlaff K. (2014) Research Funding in Open Science. In: Bartling S., Friesike S. (eds) Opening Science. Springer, Cham](https://doi.org/10.1007/978-3-319-00026-8_16).


### Continuing Challenges

#### Moving From a Top Down to a Decentralised Model

We were all in agreement that one of the most challenging aspects of sustaining community is enlisting contributions. Challenges to peoples time and the non trivial work providing support and encouragement required to foster welcoming inclusive environments pose challenges to motivating participation.

To a certain extent, dedicated seed staff will likely continue to be an important determinant on the probability a community building initiative succeeds. While making the most of the available tools and practices we've been discussing (automation, open, reusable materials, good communication channels) can really aid decentralisation, to sustain momentum, mechanisms to empower and recruit grassroots leadership is required.

#### Lack of Funding & Recognition

Something I found really interesting was that both (Toby) EMBL and (Tobias) DLR had not realised how far ahead the initiatives they represented were in the areas they were leading. Tobias said he just saw it as part of his job and assumed everyone did the same. To me, this reflects how many such activities are often undervalued. Where they're supported, there's not the tendency to shout about it and when they're not, no one sees a problem leading to difficulties attracting funding.

RSE UK, RSE de and what is slowly but surely developing into an international initiative (RSE Int) have definitely been a big driver of raising awareness. Our experiences here it Sheffield with having 2 of the first EPSRC fellows has made the benefits of such funding and recognition tangible and easier to promote in time. But there is a long way to go before this becomes widespread throughout research institutions so, until then this will likely be a continuing battle.

#### Measuring success

Time and again, and related to why these activities aren't appreciated, we find it difficult to measure and promote the effect of community and capacity building efforts in computational research skills as they can be hard to link to publications. A particular difficulty raised by the DLR team is how to measure improvements in the **quality** of software researchers produce. Ultimately, this is what determines whether research software is more dependable and indeed more reusable.

Equally, quoting Kevin Ottens at the Desktop Summit 2011 in Berlin: 

> "Community building is family and friendship building."

How do we actually measure this? How do we judge whether a community building project has been successful in the context of a proposal/call? Such difficulty in measuring success also feeds into to funding challenges. 

## Future

### Community Calls

This meeting should be just the start of something bigger. The group attending formed organically, starting with a few folks at RSE17, who shared an interest in community building and a desire to learn from one another, gathering a few more along the way. However, much talk at the meeting centered around other individuals and communities that have inspired us and would likely have much of their own to contribute to things we discussed. We've also seen that, while UK-RSE is having success in bringing people together, German RSEs still feel isolated. Challenges remain and there is plenty of scope to share strategies and experience between communities.

So, it's clear that we would all benefit from opening up our future discussions. In the coming weeks, Toby and Malvika hope to organise the first in a series of open calls for anyone interested in building communities. The first call planned will focus on strategies to bring geographically isolated individuals into a community, addressing the feelings of loneliness and lack of in-person contact described above. Anyone reading this is welcome to join us: watch this space for further updates!

### Reusable, customisable templates

Although we represent different communities with a range of goals, we found common ground in the methods we use, the events we attend/organise, and the challenges we face. A great way to share experience and enable people to start building a community (or contribute to an existing one!) is to provide checklists, protocols, and templates for them to adapt and re-use in their own work. This has the added benefit of reducing redundancy of effort across our institutions and communities.

The Carpentries do a great job of this with their [lesson template](https://github.com/swcarpentry/styles) (CC-BY license), which can be used to more easily create and contribute new lessons and has also been forked and adapted by [other projects](http://www.commonwl.org/user_guide/). It would be good to continue discussions on how coordinate such efforts on a broader range of research materials.

### Iterating

```

Tobias Schlauch: can you elaborate at all on iterating?

```


<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">What it takes to build a successful, supportive and responsive bioinformatics community by <a href="https://twitter.com/tbyhdgs?ref_src=twsrc%5Etfw">@tbyhdgs</a> <br><br>❌ ban loneliness in research ❌ <a href="https://twitter.com/hashtag/RSE17?src=hash&amp;ref_src=twsrc%5Etfw">#RSE17</a> <a href="https://t.co/VdIeZS8Gyj">pic.twitter.com/VdIeZS8Gyj</a></p>&mdash; annakrystalli (@annakrystalli) <a href="https://twitter.com/annakrystalli/status/906139603140214785?ref_src=twsrc%5Etfw">September 8, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
