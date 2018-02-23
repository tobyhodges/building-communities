# Building communities to support RSE

## Background

So many of us were fired up by the [UK RSE initiative](http://rse.ac.uk) and it's spread throughout further European Countries. The spark for this particular meeting started at the [2nd RSE conference](http://rse.ac.uk/conf2017/). For me, the initiatives described by [Toby Hodges](https://twitter.com/tbyhdgs) at [EMBL](https://www.embl.de/) and [Tobias Schlauch](https://twitter.com/TobiasSchlauch) at the [DLR](http://www.dlr.de/sc/en/desktopdefault.aspx/tabid-1177/) had been two of my favourite talks and motivated me to find out more. I kept in touch with Toby and we informally swapped notes over online meetings. In the meantime Toby and Tobias had already been synthesising some of their experiences, the results of with can be found in this [SSI blogpost](https://www.software.ac.uk/blog/2017-12-13-encouraging-good-software-development-practice-research-teams). I was delighted by such positive outcome but was slightly saddened by some of the results of the [German RSE](http://www.de-rse.org/en/) survey presented by [Stephan Janosch at FORCE17](http://www.de-rse.org/en/blog.html).

![](assets/vibes.png)

source: ['Results of RSE-de 2017 survey' presented at FORCE17 by Stephan Janosch](https://presentations.copernicus.org/FORCE2017-30_presentation.pdf)

In particular, many German RSEs in that first survey do not look forward to another day's work or see RSE as a long-term career option (...what?!). I wanted to give each one a giant hug! While there's surely a whole host of reasons, we feel an important aspect of the UK RSE initiative has been to gather us up into a community. With that in mind, an interesting question arose: 

> How can we leverage community to spread better research software development practice?

And how better to answer it than to get around a table and swap notes on our experiences of community building so far? Motivated by a need to learn more about building remote communities, with a view to expanding the community beyond their locale, [EMBL Bio-IT](https://www.embl.de/research/interdisciplinary_research/bioinformatics/community/bio-it/) made arrangements to host us all at their site in Heidelberg and set the date for 24 Jan 2018. Myself and Stephan were also gratefully supported by the SSI and EMBL Bio-IT respectively who covered our costs for the trip.

## participants

![](assets/peeps.jpeg)
<br>
_Clockwise from bottom-left: Anna Krystalli, Stefan Helfrich, Toby Hodges, Stephan Janosch, Michael Meinel, Malvika Sharan_

Toby Hodges, Malvika Sharan, and Georg Zeller shared experiences from EMBL Bio-IT, with a brief appearance (via video call) from Aidan Budd to provide details of the early days; Michael representing the DLR took Tobias' place who sadly could not join; Stefan Janosch brought experiences in a number of initiatives, spanning from his local institution Max Planck Institute of Molecular Cell Biology and Genetics ([MPI-CBG](https://www.mpi-cbg.de/en/home/), via the [Dresden Concept](http://www.dresden-concept.de/en/home.html), a research alliance among 24 Dresden based research institutions and at the national level, to the de-RSE network of German RSEs; Stefan Helfrich, an excellent impromptu addition resulting from Toby's involvement in [the Carpentries' mentorship groups program](https://github.com/carpentries/mentoring/tree/master/mentoring-groups), represented the Network of European Bioimage Analysts ([NEUBIAS](https://eubias.org/NEUBIAS/)) as well as German BioImaging ([GerBI](http://germanbioimaging.org)).

My own interest came from exploring the literature on **communities of practise** for a proposal I was writing and it struck me that I'd already had experience of some very successful such examples. As a member of the [Mozilla Open Leaders mentorship program](https://mozilla.github.io/leadership-training/), the [rOpenSci](https://ropensci.org/) and wider [R programming community](https://www.r-project.org/) but also more locally as a co-organiser of the R Users group, we've also recently been trying to apply many of these ideas on a cross-departmental team charged with building community around data visualisation across the University of Sheffield.

The role of a community builder or manager is to facilitate a domain specific platform, bringing outsiders in through practice and participation. Their magic lies in the social capital they create, the network of collaborative relationships and a shared, codified repertoire of best practice, supplemented by channels of tacit knowledge flow.

Some of the most successful modern communities of practice are digital open source communities. They leverage the internet and digital tools to codify, document, develop, share and communicate community knowledge, expand networks and culture, and actively invite and encourage participation. In turn they have made the interenet the rich place it is today. As community builders hoping seeking to facilitate broad culture change and capacity building in computational research practice, there is much to emulate from open source approaches. But once we've showing our researchers some of the tools at their disposal, how to use them and some best practice guidelines, success depends very much on their response to the challenge we are effectively posing, articulated in the intro to [**open advice**]():

> Yes, users. Even if you did not realize it or "never signed up for no community," you in fact are already a part of this community. The question is whether you'll choose to participate actively.

A lot more is possible if they are willing to participate.

## On the Day

The motivation for this meeting was to swap notes on what we've tried already to build community, what worked particularly well and identify challenges and steps for the future. *Please note that the examples and people mentioned in this blog are by no means exhaustive*. Here we try and pull together some recurring threads in our experiences.

### what works

#### Knowing your community

This should be close to the first step in building any community and is imperative for adding value which in turn is what drives voluntary participation.

*And it all started with a survey*: we all started with some form of surveying our communities. An important aspect of surveying for information is to find out both where the community is at and where they want to go. Activities can then be targeted towards the wishes and needs of the community to generate a higher rate of engagement and voluntary participation.

#### Effective communication channels

Community == communication

Effective communication channels are vital for both the transfer and processing of information, particularly of tacit knowledge, but also for fostering social, collaborative relationships. To be successful, they'll need to be diverse, including the option for private communication, but to be most effective they're better when they are integrated. Across the various initiatives, approaches tried include mailing lists, slack channels, google groups and other discussion forums.

More open channels like [Slack](https://slack.com) and [Glip](https://glip.com) are being successfully used to power all sorts of open source and data science communities including the UK RSE are really important for making people feel connected to each other. The beauty of many such tools are beginning to crossover into self-documentation due to message archiving and searchability. Discussion boards, whether through Google groups or the awesome [discourse](https://www.discourse.org/), e.g., [rOpenSci](https://discuss.ropensci.org/), can balance the instant nature of chat-based systems. Great moderators can channel useful discussions on chat channels to better curated discussion boards.

#### Codifying and documenting community practice. Tooling


An excellent example is the [mattermost](https://about.mattermost.com/) based internal chat system, developed by the community members of Bio-IT for the communication within the organisation. The control of the features and privacy of the system is a huge driver of adapting it to best serving the community. Coupled with an internally hosted gitlab based repository system, they've managed to build a thriving complementary online community actively engaged in sharing, co-developing, reviewing and discussing their software. The only drawbacks are that it can be difficult to open up discussion to the outside world. 

But it's important to note that it's often good to signpost between communities. For example, for R questions beginners might have, I would unhesitantly guide learners to the [R for Data Science (#R4DS)]() slack community. The 800+ strong slack team of mentors and learners is a constant hive of discussion and trouble shouting while worthing through [R for Data Science](). For slightly more technical questions, I might guide someone to the [rOpenSci]() [slack community]() or the [rOpenSci](https://discuss.ropensci.org/) or [Rstudio]() discussion boards (powered by another nice open source community building resource.


#### Codifying and documenting community practice. Tooling

A foundational aspect of building of a community of practice is the codification and dissemination of standards and guidelines. The DLR approach is a particular great example. They make use of wikis and check lists in a variety of formats (eg markdown & word) to help guide software development and follow a tiered level approach to recommendations, as well as a minimum requirement for all software. They are determined by a project's application class, dependent on the research project scope and size.  linked to reasoning and further advice next to each point.


![](assets/ts-guidelines.png)


community practice feedback into each other.While tasked with developing a framework for sustainable software development, the group work with contacts at each institute of the DLR from which they gain feedback on the direction of both the requirement for guidelines, new tools and training. 

We are all eagerly awaiting the translation of the DLR documentation materials into English.

Community documentation is actually much broader than that and can take many forms, including blogs, wikis, READMEs and websites, discussion forums, papers and standards. There is likely much scope for development here to support the kind of documentation. Again, it's hard to quantify quite the effect that sites like stack overflow, and indeed the flash bombing of the site with R, but their foundational role in proving foundations for which a knowledge exchange community can be built upon. 




Clearly there is a lot well deserved effort into Guidelines of Best Practice and documentation, and we feel good foundations are being laid, for example the Netherlands eScience Centre Guide. With all these, building upon rather than duplicating would serves us well. From there, as Research Software engineers we can support by customisable templating.


The beauty of many such tools are beginning to crossover into self-documentation. Great moderators can channel useful discussions on chat channels to better curated discussion boards. 





#### Actively fostering engagement and participation

Successful communities thrive on diverse contributions from a wide range of their members. Most of the attendees at this particular meeting were representing the efforts of a much broader selection of contributors to their respective communities. The role of a community coordinator is often to encourage and facilitate the voluntary efforts of the larger group, and it is this engagement across the whole community that, in turn, produces the most amazing results. To get some idea of the number of individual contributions that it can take to create a successful community, check out the Acknowledgments slide from [Toby's talk at RSE17](http://rse.ac.uk/conf2017/wp-content/uploads/sites/2/2017/11/Bioinformatics_Community_Hodges_RSE17_2.pdf)!

A lot of this however falls in the least recognised and appreciated category. The importance of community catalysts.
Friendly, supportive active community catalysts make a huge impact, and can be the deciding factor on whether a community succeeds. It's no surprise we routinely ended up back at Bio-IT t~0~, and **Aidan Budd**'s initial vision and drive and ability to be the hub that drew other people together. Other great examples include **Maëlle Salmon** ([@ma_salmon](https://twitter.com/ma_salmon)) as an **rOpensci** package review editor, **Stefanie Butland** ([@StefanieButland](https://twitter.com/StefanieButland)) as **rOpensci** community manager and **Jesse Maegan** [@kierisi](https://twitter.com/kierisi) for establishing [#R4DS](https://medium.com/@kierisi/r4ds-january-challenge-69324561ef2b). 

Ultimately, though, it's about member participation, so the superpower of great community catalysts is to actively acknowledge and promote member contributions and help them share their stories, ideas and questions. We could all benefit from aspiring to be better catalysts ourselves.

#### Training

 
We all identified providing training, developing materials and workshops still fundamental to baseline computational skill development. Initiatives like the Carpentries or Elixir are making huge strides in providing scaling training foundations. We also all recognised the importance of flexibility and hearing from your community and being able to adaptively develop training according to identified domain needs. 

But to make researchers effective nodes, it's important not to neglect the development of digital citizenship skills. The ability to access and recycle material, share through and post to the web are incredibly empowering, but only up to a point. Being able to effectively propose an idea, share it, build it in the open, get feedback, onboard collaborators and incorporate contribution underpin the emergent community social capital and knowldege flow we see in open source communities today. So skills in collaboration, leadership, mentorship and even asking for and giving help are critical. Even more so, skills in just being a good peer. An ability to iterate in response to user feedback requires humility, openness and transparency. As community leaders, we set the precedent and the tone for any community so effective leadership must be driven from the position of a peer. 
 
 
#### Events!
 
 

The important is to provide variety and rhythm.
 
There is no doubt that the RSE conferences have been a huge spring board for the RSE community. Traditional venues for knowledge exchange and network building are still important and the NEUBIAS conferences also demonstrate that it is important to provide these opportunities for technical disciplines of science. 

 hacks: I love hacks! Academic "fun" hacks can be really fun but also very effective in getting people to learn/practice new things and tackle challenges in their field without pressure. Food and drink always helps! With the dataviz team we regularly schedule work hacks, where we hammer out a bit of work, or prototype something. 
 
 But jumping onto wider events, like running a Global Sprint site or some hacktoberfest sessions. They are great opportunities to practice more fundamental skills like collaborating online and get a feel for open source. You can make your own events more accessible by providing ways for remote participation. 

 

 - *conferences*: There is no doubt that the RSE conferences have been a huge spring board for the RSE community. Traditional venues for knowledge exchange and network building are still important and the NEUBIAS conferences also demonstrate that it is important to provide these opportunities for technical disciplines of science.. But jumping onto wider events, like running a Global Sprint site or some hacktoberfest sessions. They are great opportunities to practice more fundamental skills like collaborating online and get a feel for open source.
 - *coding clubs*: Great ways to provide opportunity to learn, practice (after training?) and get feedback. Works best when sessions are focused, like working through a book, training program or even blogposts. 
 - *training schools/learnathons*: Learnathons/Training schools are a great way to bring people together to learn and work on more advanced topics. Since lessons have to moderated/prepared by someone, those kind of events have the side-effect of bringing together not only learners but also trainers over a period of time that facilitates fruitful discussions.

Note that local events can now relatively easily open up proceedings. Live streaming or recording and posting events and setting up open, live communication channels around the event are great ways to engage remote participants and indeed, I've recently been calling in to the EMBL Bio-IT [D3.js coding club]()!
 Streaming or recording events, allowing call ins or even just opening a gitter channel or posting links to live documents could help broaden engagement.
 But bringing people together in physical space still the most effective way of building community.
 
 

#### Buy in from upper management

One of the key drivers of the longest standing and most developed communities is buy in and support form upper management. Bio-IT benefited by this being flagged early on in the process and lead to them now having nearly 8 years of well-resourced effort. Similarly, the DLR initiative was driven by first raising awareness in management level which subsequently lead to upper management support.

**SH: The definition of upper management actually depends on how localized or how decentralized a community is. Sometimes there is nothing like an "upper management".

#### Funding!

Related to buy in is financial support of activities. At the very least, funding for dedicated community building personnel can provide an important start. e.g. EMBL and DLR and Mike Croucher's EPSRC Fellowship supported such roles. Since research is an inherently international and/or multi-organization endeavor, financial support from umbrella organization can be sought. The European Union, for instance, has established a programme (COST) for setting up international research networks. NEUBIAS has setup aforementioned events (conferences, training schools, short scientific exchanges) and networking activities from COST funding.

Additional information can on funding schemes is described in [Eisfeld-Reschke J., Herb U., Wenzlaff K. (2014) Research Funding in Open Science. In: Bartling S., Friesike S. (eds) Opening Science. Springer, Cham](https://doi.org/10.1007/978-3-319-00026-8_16).

### continuing challenges?

#### moving from a top down to a decentralised model. 

Ie a self-sustaining community. volunteers to contribute content. It is not news to anyone that one of the most challenging aspects of sustaining community is enlisting contributions, mainly in the form of contributions. 

To a certain extent, dedicated seed staff will likely be an important determinant of whether a community succeeds. But making the most of available tools can really help with the decentralisation. Automation, reusable templates and open sharing of resources can really help with compiling and spreading best practice and useful tools while the plethora of communication means put to good use can break down physical barriers and link people into communities while, if done in the open, also acting as an archive. 

#### lack of funding & recognition.

- Important point I found interesting:
    * both (Toby) EMBL and (Tobias) DLR had not realised how far ahead they were in the areas they were leading. 

Tobias just saw it as part of his job and assumed everyone did the same.

RSE UK has definitely been a big driver of raising awareness and our experiences here it Sheffield with having 2 of the first fellows has shown it can work as a start. But ultimately without buying and support for activities that push forward, it's hard to build momentum. 

Many of the activities are often undervalued and therefore difficult to attract funding.

#### Measuring success.

Time and again, and related to why these skills aren't appreciated, we find it difficult to measure and promote the effect of such community and capacity building efforts. Hard to link to publications. A particular difficulty raised by the DLR team is how to measure improvements in the **quality** of software produced. Ultimately, this is what determines whether research software is more dependable and indeed more reusable.

**SH: I guess this is one of the important re-occuring schemes with respect to funding. How do we actually determine, if a community is successful in the context of a proposal/call.

#### people still feel isolated (especially when disparate in physical location). This is particularly the case of the NEUBIAS disconnected (SJ & SH). Result:

> Because as Ḱevin Ottens rightly said during the Desktop Summit 2011 in Berlin: "Community building is family and friendship building."

## Future

### Community calls

- Ultimately, we had to start somewhere and started with a few folks that had co-expressed an interest to each other of learning more about each other's work. However, much talk centered around many others that have inspired us push community forward and would likely have much to contribute to things we discussed.

- Also, while UK RSE is bringing people together, German RSEs still feel isolated

So, it's key to open our discussions up. In the coming weeks, Toby and Malvika hope to organise the first in a series of open calls for anyone interested in building communities. The first call planned will focus on strategies to bring geographically isolated individuals into a community, addressing the feelings of loneliness and lack of in-person contact described above. Anyone reading this is welcome to attend: watch this space for further updates!

### Reusable, customisable templates (ie stop re-inventing the wheel)

### iterating

- measuring the impact, in particular the QUALITY of the code, something the DLR had had to grapple with more so due to the production nature of alot of their software.

> two types of community man- agers; those who go out and give presentations and wave their hands around talking about a product or service, and those who work with a community of volunteers to help them to have a fun, productive and enjoyable collaborative experience. 

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">What it takes to build a successful, supportive and responsive bioinformatics community by <a href="https://twitter.com/tbyhdgs?ref_src=twsrc%5Etfw">@tbyhdgs</a> <br><br>❌ ban loneliness in research ❌ <a href="https://twitter.com/hashtag/RSE17?src=hash&amp;ref_src=twsrc%5Etfw">#RSE17</a> <a href="https://t.co/VdIeZS8Gyj">pic.twitter.com/VdIeZS8Gyj</a></p>&mdash; annakrystalli (@annakrystalli) <a href="https://twitter.com/annakrystalli/status/906139603140214785?ref_src=twsrc%5Etfw">September 8, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
