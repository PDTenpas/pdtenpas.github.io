---
layout: page
title: Cortical Homunculi
subtitle: Metadata Newsletter - Issue 3
---

![MetaData Banner]({{ site.url }}/img/metadata_banner.png)

**Content \| Source**

- **TL;DR:** Summary.
- My thoughts.

> Quotes.

---

# Tools

[**Introducing kepler.gl for Jupyter**](https://medium.com/vis-gl/introducing-kepler-gl-for-jupyter-f72d41659fbf) | [**Data Elixir**](https://dataelixir.com/)

- **TL;DR:** Uber's geospatial data viz tool now supports Jupyter.

[**Open-sourcing PyRobot to accelerate AI robotics research**](https://ai.facebook.com/blog/open-sourcing-pyrobot-to-accelerate-ai-robotics-research/) | [**Data Science Community Newsletter**](https://cds.nyu.edu/newsletter/)

- **TL;DR:** Facebook has released PyRobot, a simple python interface for robotics work.

- More side projects with robots, please.

[**Recommendations for how to get started with front-end development**](https://threader.app/thread/1144173215293591555) | [**Conor Dewey's Newsletter**](https://www.conordewey.com/newsletter)

> "Unsolicited data science career advice: learn Flask + just enough React to be able to build functional front-ends for your DS work + just enough CSS to make it look not-horrible, it's like having a superpower (and it's not that hard)" - [Joel Grus](https://twitter.com/joelgrus)

---

# Approaches

[**Building Lyft’s Marketing Automation Platform**](https://eng.lyft.com/lyft-marketing-automation-b43b7b7537cc) | [**@seanjtaylor**](https://twitter.com/seanjtaylor) - Decision Science Products at Lyft

- **TL;DR:** Lyft has automated a substantial amount of marketing work with an end-to-end system that handles LTV forecasting, budget allocation, and bidding, yet still leaves marketers in the loop where it counts.

[**Using Causal Inference to Improve the Uber User Experience**](https://eng.uber.com/causal-inference-at-uber/) | [**O'Reilly Data Newsletter**](https://www.oreilly.com/data/newsletter.html)

- Uber has gone hardcore into causal inference judging by their recent blog posts. This is so different from the magic machine learning dust so many other companies are sprinkling that it's worth keeping an eye on.

[**How Superhuman Built an Engine to Find Product/Market Fit**](https://firstround.com/review/how-superhuman-built-an-engine-to-find-product-market-fit/) | [**Conor Dewey's Newsletter**](https://www.conordewey.com/newsletter)

> Just ask users “how would you feel if you could no longer use the product?” and measure the percent who answer “very disappointed.”

- The simplicity here reminds me of the question behind the now standard NPS score.

---

# Industry

[**Apple, Google, and Facebook Are Raiding Animal Research Labs**](https://www.bloomberg.com/news/features/2019-06-18/apple-google-and-facebook-are-raiding-animal-research-labs) | [**Benedict's Newsletter**](https://www.ben-evans.com/newsletter)

> Birdsong researchers are among the hottest hires in a wide range of AI fields.

- **TL;DR:** The tough problems in animal research actually have a lot in common with those facing ML research; big tech has noticed and is poaching talent.

- I.e. "Hey, this is wrong but he's the President."

[**Testifying at the Senate about A.I.-Selected Content on the Internet**](https://blog.stephenwolfram.com/2019/06/testifying-at-the-senate-about-a-i-selected-content-on-the-internet/) | [**Benedict's Newsletter**](https://www.ben-evans.com/newsletter)

- Stephen Wolfram spent some time thinking and writing about the problems of "A.I. Selected Content," i.e. Facebook / Twitter / Youtube, as well as potential solutions. Stephen is an interesting writer and rarely covers things this current.

[**Top AI researchers race to detect ‘deepfake’ videos**](https://www.washingtonpost.com/technology/2019/06/12/top-ai-researchers-race-detect-deepfake-videos-we-are-outgunned/) | [**Data Science Community Newsletter**](https://cds.nyu.edu/newsletter/)

> We are outgunned... Farid said, "The number of people working on the video-synthesis side, as opposed to the detector side, is 100 to 1." This is sociological warfare. We haven't even figured out that we should attempt to put up a fight.

- **TL;DR:** Progress in fake media generation continues to accelerate and no one is prepared.

- See the latest case-in-point: [DeepNudes](https://www.theverge.com/2019/6/27/18760896/deepfake-nude-ai-app-women-deepnude-non-consensual-pornography).

- [Wolfram also recently wrote about DeepFakes](https://blog.stephenwolfram.com/2019/06/a-few-thoughts-about-deep-fakes) if you liked his other post.

---

# Old but more relevant than ever

[**Ads Don't Work That Way**](https://meltingasphalt.com/ads-dont-work-that-way/) | [**How It Actually Works**](https://www.howitactuallyworks.com/)

> Cultural imprinting is the mechanism whereby an ad, rather than trying to change our minds individually, instead changes the landscape of cultural meanings — which in turn changes how we are perceived by others when we use a product.

- This may change some of your beliefs on how ads work.

[**Understanding the Job**](https://www.youtube.com/watch?v=sfGtw2C95Ms) | [**How It Actually Works**](https://www.howitactuallyworks.com/)

> Once you understand the job that needs to be done, improvements become obvious.

[**Choose Boring Technology**](http://boringtechnology.club/) | [**Data Science Roundup**](http://roundup.fishtownanalytics.com/)

- A needed reminder as the data science bubble grows on. This recently [re-surfaced on Hacker News](https://news.ycombinator.com/item?id=20323246) as well and there was some good discussion.

---

# Cortical Homunculi

![Brain]({{ site.url }}/img/brain.png)

> "A cortical homunculus, or 'cortex man', illustrates the concept of a representation of the body lying within the brain." - [Wikipedia](https://en.wikipedia.org/wiki/Cortical_homunculus)

It turns out that the regions of the brain that control or sense body parts aren't proportionate with those parts. To detect this, experimenters do things like measure the [minimal perceptible distance between two points](https://en.wikipedia.org/wiki/Two-point_discrimination) across the body or watch brain the light up in an FMRI during motor tasks. These measurements can then be used to help visualize the difference in proportions by creating a cortical homunculus— a distorted mapping of the body according to its relative instrumentation in the brain.

![homunculus]({{ site.url }}/img/homunculus.png){: .center-block :}

[*More Homunculi*](https://www.google.com/search?q=cortical+homunculus&tbm=isch){: .center-block :}

So, depending on what function we're talking about, you're mostly just a pair of hands and a face as far as your brain's perception is concerned. Every nuance in those parts is picked up as compared to your legs or back where things are much more conservative and the data more coarse.

It's interesting to think of analogies to this in the code or databases behind apps and websites. Which parts of the front-end have disproportionate monitoring? Which have the most fine-grained data collection, test coverage, or logging? Do those proportions align with what's actually important to the function of the system? Put another way, what is the back-end's perception of the front?

Like the homunculus, it could be useful to visualize this distortion and it could even help guide improvements. I'm imagining a view of all of a website's pages at once where each is distorted by a metric related to its relative instrumentation. Take ecommerce as an example. I'd expect the checkout experience to be like the hands of the homunculus pictured above, over instrumented to pick up every nuance, while other pages are much more barebones. I would not expect any part of the system to be completely unmonitored or all parts to be monitored equally. I.e. something has gone horribly wrong if your homunculus has a floating limb and otherwise looks like a bodybuilder that's skipping leg day.

---

[Subscribe](https://metadata.substack.com/)

[View Past Favorites in the Bookmarks](https://pdtenpas.github.io/)

[Newsletters / Blogs / Podcasts I Follow](https://pdtenpas.github.io/pages/newsletter/sources/)

[How I Write the Newsletter](https://pdtenpas.github.io/pages/newsletter/read_newsletters/)
