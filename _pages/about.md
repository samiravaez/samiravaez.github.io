---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a PhD student in <a href="https://drexel.edu/cci/academics/information-science-department/" target="_blank">Information Science</a> at Drexel University, where I work under the supervision of Dr. Michael Ekstrand at the <a href="https://inertial.science" target="_blank">INERTIAL Lab</a>. My research focuses on studying and evaluating information access systems, particularly recommender systems, to ensure they are used effectively and equitably for the benefit of the diverse stakeholders involved. Before joining Drexel, I earned my MSc in <a href="https://en.ce.kntu.ac.ir/" target="_blank">Computer Engineering</a> (AI specialization) from <a href="https://en.kntu.ac.ir/" target="_blank">K. N. Toosi University of Technology</a>. During my time there, I studied bias in ranking and recommendation at the <a href="https://www.linkedin.com/company/kntu-tis" target="_blank">Textual Intelligent Systems Lab</a>.

Publications
======
<ul>
                    <li><b>DIPT: Diversified Personalized Transformer for QAC systems</b>
                        <h5 style="margin-bottom:0; margin-top:0">Mahdi Dehghani, Samira Vaez Barenji, Saeed Farzi</h5>
                        <h6 style="margin-top:0"><i>In 13th International Conference on Computer and Knowledge Engineering (ICCKE 2023)</i></h6>
                    </li>
                    <li><b>Managing multi-faceted bias in collaborative filtering recommender systems</b>
                        <h5 style="margin-bottom:0; margin-top:0">Samira Vaez Barenji, Saeed Farzi</h5>
                        <h6 style="margin-top:0"><i>arXiv preprint arXiv:2302.10575</i></h6>
                    </li>
                </ul>

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
