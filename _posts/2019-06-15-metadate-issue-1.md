---
layout: page
title: MetaData Newsletter
subtitle: Issue 1 - The Garden of Forking Paths
---

[![MetaData Banner]({{ site.url }}/img/metadata_banner.png)]({{ site.url }}/img/metadata_banner.png)

[Subscribe](https://metadata.substack.com/)

**Content \| Source**

- **TL;DR:** Summary.
- My thoughts.

> Quotes.

---

# Tools

[**Releasing lookml-tools: better Looker code, user experience, and data governance**](https://medium.com/ww-tech-blog/releasing-lookml-tools-better-looker-code-user-experience-and-data-governance-a24c0324257c) \| [**Data Science Weekly**](https://www.datascienceweekly.org/)

- The library contains three tools: Linter for styling, Grapher for network diagrams, and Updater dimension description changes.

[**Usage of Asterisks in Python**](https://www.datacamp.com/community/tutorials/usage-asterisks-python) \| [**DataCamp Weekly**](https://www.datacamp.com/)

> Asterisks have many particular use cases in Python. In general, we are familiar with the multiplication and power operators. It can perform some other operations like unpacking, arguments passing, etc.., in different situations

[**How to Implement a Python Stack**](https://realpython.com/how-to-implement-python-stack/) \| [**PyCoder's Weekly**](https://pycoders.com/)

> A stack is a data structure that stores items in an Last-In/First-Out manner. This is frequently referred to as LIFO. This is in contrast to a queue, which stores items in a First-In/First-Out (FIFO) manner.

---

# Approaches

[**How We Helped Our Reporters Learn to Love Spreadsheets**](https://open.nytimes.com/how-we-helped-our-reporters-learn-to-love-spreadsheets-adc43a93b919) \| [**NYC Data**](https://tinyletter.com/nycdatajobs)

- TL;DR: The New York Times has open-sourced it’s data training program based on Google Sheets.

- Spreadsheets continue to be the gateway drug of choice to data literacy. TBD on how this works out in the long run as a common struggle among analysts is _untraining_ stakeholder's bad habits from extensive spreadsheet use.

[**Research quality data and research quality databases**](https://simplystatistics.org/2019/05/29/research-quality-data-and-research-quality-databases/) \| [**O'Reilly Data Newsletter**](https://www.oreilly.com/data/newsletter.html)

> No matter where you are doing data science - in academia, in a non-profit, or in a company - you are doing research.

> Research quality data is data that:
> 1. Is summarized the right amount
> 2. Is formatted to work with the tools you are going to use
> 3. Is easy to manipulate and use
> 4. Is valid and accurately reflects the underlying data collection
> 5. Has potential biases clearly documented.
> 6. Combines all the relevant data types you need to answer questions

[**Testing Statistical Software**](https://www.alexpghayes.com/blog/testing-statistical-software) \| [**Data Elixir**](https://dataelixir.com/)

> In this post, I describe how I evaluate the trustworthiness of a modeling package, and in particular what I want from the test suite. If you use statistical software, this post will help you evaluate whether a package is worth using. If you write statistical software, this post will help you confirm the correctness of the code that you write.

---

# Industry

[**The Truth About Finding Your First Engineering Job**](https://angel.co/blog/the-truth-about-finding-your-first-engineering-job) \| [**AngelList Weekly**](https://angel.co/newsletters)

> How many jobs should I apply to? What kind of companies do I have the best odds with? Do I apply to roles I'm not qualified for? Which roles are the most open to junior-level candidates? Am I a failure if I don't make $200,000? What do you want?

[**A Wave of Acquisitions in Business Intelligence**](https://blog.fishtownanalytics.com/a-wave-of-acquisitions-in-business-intelligence-93ef319089d8) \| [**The Data Science Roundup**](http://roundup.fishtownanalytics.com)

- Tristan Handy riffs on what all the recent BI acquisitions mean for the data stack.

> My personal opinion is that the underlying tech—the ingestion, transformation, and warehouse layers—actually matter more than the BI layer, but buyers rarely see it this way. Buyers in this space buy the front-end. It’s how they, and how most of an organization’s users, interact with the underlying technology.

[**Big Mood Machine: Spotify pursues emotional surveillance for global profit**](https://thebaffler.com/downstream/big-mood-machine-pelly) \| [**Pocket Hits**](https://getpocket.com/explore/pocket-hits)

> But a more careful look into Spotify’s history shows that the decision to define audiences by their moods was part of a strategic push to grow Spotify’s advertising business in the years leading up to its IPO—and today, Spotify’s enormous access to mood-based data is a pillar of its value to brands and advertisers, allowing them to target ads on Spotify by moods and emotions.

[**Justin Kan: 10+1 Lessons from a Serial Entrepreneur**](https://a16z.com/2019/06/10/lessons-from-serial-entrepreneur-justin-kan/) \| [**a16z Podcast**](https://a16z.com/podcasts/)

> I had a huge ego attachment to the outcome of the company. My identity and the companies were very intertwined... what I realized was that I need to start reminding myself that no matter what happens with this company, I'm not going to be any happier or any less happy in the long run.

> Culture eats strategy... when you're not intentional about your culture, or what type of company you want to be, then the culture ends up being the accidental collection of good and bad choices, and personality quirks, and good and bad behaviors that your founding and executive teams propagate.

> I think a lot of companies in Silicon Valley succeed despite their management, not because of it. And what I mean by that is the idea was so good that a bunch of 25 year olds could run the company.

---

# From the Real World

[**How to build something that lasts 10,000 years**](http://www.bbc.com/future/story/20190611-how-to-build-something-that-lasts-10000-years) \| [**Pocket Hits**](https://getpocket.com/explore/pocket-hits)

> Alexander Rose and a team of engineers at The Long Now Foundation are building a clock in the Texan desert that will last for 10,000 years. He explains what he's learnt about designing for extreme longevity.

---

**From the Bookmarks...**

# The Garden of Forking Paths

[**The garden of forking paths: Why multiple comparisons can be a problem, even when there is no “fishing expedition” or “p-hacking” and the research hypothesis was posited ahead of time**](http://www.stat.columbia.edu/~gelman/research/unpublished/p_hacking.pdf)

**TL;DR:** The goal of an experiment isn't to find significant results— don't go looking for them and don't decide how to conduct an experimental analysis based on the experimental data.

[![Garden]({{ site.url }}/img/garden.png)]({{ site.url }}/img/garden.png)

At this point, p-hacking is fairly common knowledge in the data world. The story goes something like this:

If the pressure is on to find significant effects, the researcher can crank up the number of dependent and independent measures, examine every possible comparison, and then report on the significant ones and tell a nice post-hoc story about how they theorized this effect would exist and when they looked— there it was. If your goal is to find significant results, you *will* find them. What you won't find is any sort of lasting insight about what's actually happening.

It's an incentive and alignment issue nearly everywhere statistics is done. In the short term, careers are often built on significant effects in both academia and industry. Further, most consumers of statistics simply aren't statisticians and don't understand that there is a substantial difference between producing significant effects and producing good research.

> "If you torture the data long enough, it will confess." - Ronald Coase

Less well-known, and more horrifying, is another significance pitfall coined by Andrew Gelman: The Garden of Forking Paths. There are numerous choices an analyst has to make in experimental analysis from data processing through to the actual model— this is the Garden.

If you choose your path through the Garden based on the data itself, you are in effect making multiple comparisons!— not across segments of the same dataset, but across all possible datasets that could have resulted from the experiment. Put another way, if the experimental data would have turned out differently, you would have chosen a different path which would have led to different conclusions if applied to a dataset that did not nudge you down the same fork.

One way to frame the differences between p-hacking and the Garden is intent. P-hacking is malicious. It explains how, with a bit of effort, a researcher can fool others. The Garden explains how researchers can unknowingly fool themselves. Both pitfalls occur when the analyst makes decisions contingent on the experimental data. This feedback loop simply destroys key assumptions behind the p-value.

> Criticism is easy, doing research is hard.

The authors go on to offer guidelines to avoid this pitfall by defining your methodology beforehand and conducting follow-up experiments when the analysis is unavoidably contingent on the data. This advice follows what is generally a good rule of thumb for experimental analysis— lean into experimental design and analysis methodology *before* conducting the experiment, not afterwards. You can't move fast and break things here.

The paper is a good read with multiple real world examples. A few quotes follow:

> Our key point here is that it is possible to have multiple potential comparisons, in the sense of a data analysis whose details are highly contingent on data, without the researcher performing any conscious procedure of fishing or examining multiple p-values.

> In this garden of forking paths, whatever route you take seems predetermined, but that’s because the choices are done implicitly. The researchers are not trying multiple tests to see which has the best p-value; rather, they are using their scientific common sense to formulate their hypotheses in a reasonable way, given the data they have. The mistake is in thinking that, if the particular path that was chosen yields statistical significance, that this is strong evidence in favor of the hypothesis.

> When we say an analysis was subject to multiple comparisons or “researcher degrees of freedom,” this does not require that the people who did the analysis were actively trying out different tests in a search for statistical significance. Rather, they can be doing an analysis which at each step is contingent on the data. The researcher degrees of freedom do not feel like degrees of freedom because, conditional on the data, each choice appears to be deterministic. But if we average over all possible data that could have occurred, we need to look at the entire garden of forking paths and recognize how each path can lead to statistical significance in its own way. Averaging over all paths is the fundamental principle underlying p-values and statistical significance and has an analogy in path diagrams developed by Feynman to express the indeterminacy in quantum physics.

---

You can view my current sources [here](https://pdtenpas.github.io/pages/newsletter/sources/), learn more about my process for writing the newsletter [here](https://pdtenpas.github.io/pages/newsletter/read_newsletters/), or see my favorite past finds in the bookmarks section of my personal site [here](https://pdtenpas.github.io/).
