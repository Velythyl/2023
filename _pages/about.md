---
layout: about
title: about
permalink: /about
nav: true
nav_order: 1
subtitle:

# profile:
#   align: right
#   image: 
#   image_circular: false # crops the image to make it circular
#   address: 

# news: false  # includes a list of news items
# selected_papers: false # includes a list of papers marked as "selected={true}"
# social: false  # includes social icons at the bottom of the page
---


# ICLR 2023 Blogposts Track

The Machine Learning community is currently experiencing a
[reproducibility crisis](https://neuripsconf.medium.com/designing-the-reproducibility-program-for-neurips-2020-7fcccaa5c6ad)
and a reviewing crisis [[Littman, 2021]](#Litt). Because of the highly competitive and noisy
reviewing process of ML conferences [[Tran et al., 2020]](#Tran), researchers have an incentive to
oversell their results, slowing down the progress and diminishing the
integrity of the scientific community. Moreover with the growing number
of papers published and submitted at the main ML conferences [[Lin et al., 2020]](#Lin), it has
become more challenging to keep track of the latest advances in the
field.

Blog posts are becoming an increasingly popular and useful way to talk
about science [[Brown and Woolston, 2018]](#Brow).
They offer substantial value to the scientific community
by providing a flexible platform to foster open, human, and transparent
discussions about new insights or limitations of a scientific
publication. However, because they are not as recognized as standard
scientific publications, only a minority of researchers manage to
maintain an active blog and get visibility for their efforts. Many are
well-established researchers ([Francis Bach](https://francisbach.com/),
[Ben Recht](https://www.argmin.net/), [Ferenc
Huszár](https://www.inference.vc/), [Lilian
Weng](https://lilianweng.github.io/lil-log/)) or big corporations that
leverage entire teams of graphic designers designer and writers to
polish their blogs ([Facebook AI](https://ai.facebook.com/blog/?page=1),
[Google AI](https://ai.googleblog.com/),
[DeepMind](https://deepmind.com/blog),
[OpenAI](https://openai.com/blog/)). As a result, the incentives for
writing scientific blog posts are largely personal; it is unreasonable
to expect a significant portion of the machine learning community to
contribute to such an initiative when everyone is trying to establish
themselves through publications.

## A Blog Post Conference Track

Last year, we ran the first iteration of the [Blogpost track at ICLR 2022](https://iclr-blog-track.github.io/home/)!
It was very successful, attracting over 60 submissions and 20 accepted posts.

Our goal is to create a formal call for blog posts at ICLR to
incentivize and reward researchers to review past work and summarize the
outcomes, develop new intuitions, or highlight some shortcomings. A very
influential initiative of this kind happened after the second world war
in France. Because of the lack of up-to-date textbooks, a collective of
mathematicians under the pseudonym Nicolas Bourbaki [[Halmos 1957]](#Halm), decided to start a
series of textbooks about the foundations of mathematics [[Bourbaki, 1939]](#Bour).
In the same vein, we aim at providing a new way to summarize scientific knowledge in
the ML community.

Due to the large diversity of topics that can be discussed in a blog
post, we decided to restrict the range of topics for this call for blog
posts. We identified that the blog posts that would bring to most value
to the community and the conference would be posts that distill and
discuss *previously published papers*.

## Key Dates

- **Submission deadline**: February 2nd, 2023
&nbsp;

- **Notification of acceptance**: March 31st, 2023
&nbsp;

- **Camera-ready merge**: *TBD*

### A call for blog posts discussing work previously published at ICLR

The format and process for this blog post track is as follows:


- Write a post on a subject that has been published at ICLR relatively recently.
    The authors of the blog posts will have to declare their conflicts of interest (positive nor negative) with the paper (and their authors) they write about. 
    Conflicts of interest include:
    - Recent collaborators (less than 3 years)
    - Current institution.

    Blog Posts must not be used to highlight or advertise past publications of the authors of of their lab. 
    Previously, we did not accept submissions with a conflict of interest, however this year we will only ask the authors to report if they have such a conflict. 
    If so, reviewers will be asked to judge if the submission is sufficiently critical and objective of the papers addressed in the blog post. 

- The posts will be created and published under a unified template; see [the submission instructions]({{ '/submitting' | relative_url }})
    and the [sample post]({{ '/blog/2022/distill-example' | relative_url }}) hosted on the blog of this website.

- Blogs will be peer-reviewed (double-blind) for quality and novelty of the content: clarity and pedagogy of the exposition, new theoretical or practical insights, reproduction/extension of experiments, etc.
We are slightly relaxing the double-blind constraints by assuming good faith from both submitters and reviewers (see [the submission instructions]({{ '/submitting' | relative_url }}) for more details).

## Submissions

Our goal is to avoid heavily engineered, professionally-made
blog-posts---Such as the “100+ hours” mentioned as a standard by the [Distill
guidelines](https://distill.pub/journal/)---to entice ideas and clear writing rather than dynamic
visualizations or embedded javascript engines.

As a result, we restrict submissions to the Markdown format. We believe
this is a good trade-off between complexity and flexibility. Markdown
enables users to easily embed media such as images, gifs, audio, and
video as well as write mathematical equations using MathJax, without
requiring users to know how to create HTML web pages. This (mostly)
static format is also fairly portable; users can download the blog post
without much effort for offline reading or archival purposes. More
importantly, this format can be easily hosted and maintained through
GitHub.

## Organizers

<div class="row row-cols-2 projects pt-3 pb-3">
  {% include people_horizontal.html name="Gauthier Gidel" affiliation="Mila, Université de Montréal" url="https://gauthiergidel.github.io/" img="assets/img/organizers/gg.jpg" %}
  {% include people_horizontal.html name="Charlie Gauthier" affiliation="Mila, Université de Montréal" url="https://velythyl.github.io/" img="assets/img/organizers/cg.jpg" %}
  {% include people_horizontal.html name="David Dobre" affiliation="Mila, Université de Montréal" url="" img="assets/img/organizers/dd.jpg" %}
  {% include people_horizontal.html name="Claire Vernade" affiliation="University of Tuebingen" url="https://www.cvernade.com/" img="assets/img/organizers/cv.jpg" %}
  {% include people_horizontal.html name="Joan Bruna" affiliation="New York University" url="https://cims.nyu.edu/~bruna/" img="assets/img/organizers/jb.jpg" %}
</div>

---

## References

<a name="Litt">Michael L Littman. Collusion rings threaten the integrity of computer science research. Communications of the ACM, 2021.</a>

<a name="Tran">David Tran, Alex Valtchanov, Keshav Ganapathy, Raymond Feng, Eric Slud, Micah Goldblum, and Tom Goldstein. An open review of openreview: A critical analysis of the machine learning conference review process. arXiv, 2020. </a>

<a name="Lin">Hsuan-Tien Lin, Maria-Florina Balcan, Raia Hadsell, and Marc’Aurelio Ranzato. What we learned from neurips2020 reviewing process. Medium https://medium.com/@NeurIPSConf/what-we-learned-from-neurips-2020-reviewing-process-e24549eea38f, 2020. </a>

<a name="Brow">Eryn Brown and Chris Woolston. Why science blogging still matters. Nature, 2018.</a>

<a name="Halm">Paul R Halmos. Nicolas bourbaki. Scientific American, 1957.<a>

<a name="Bour">Nicolas Bourbaki. Elements of mathematics. Éditions Hermann, 1939.</a>