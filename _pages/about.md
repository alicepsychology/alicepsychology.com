---
permalink: /
title: "Alice Gao (高千惠) Applied Psychology Researcher"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

Education
======
**East China Normal University-NYU Shanghai – Shanghai, China**
PhD, Applied Psychology                                                       Sep 2020 - Dec 2024
**Syracuse University – Syracuse, NY**
Master of Arts, Marriage and Family Therapy                                   Aug 2017 - Aug 2019
**Syracuse University – Syracuse, NY**
Certificate Advanced Study, Child Therapy                                     Jan 2018 - Aug 2019
**Dalian Medical University – Dalian, China**
Bachelor of Science, Applied Psychology                                       Sep 2013 - July 2017

Publications
======
[1] [Gao, Q., Antfolk, J., & Santtila, P. (2023). An experimental study using a sexual strategies explanation to reduce homophobia toward gay men among lay people and healthcare professionals in China. Frontiers in Psychology, 14.] (https://doi.org/10.3389/fpsyg.2023.1143584)
[2] [Gao, Q., Antfolk, J., & Santtila, P. (2023). An Experiment Using a Sexual Strategies Explanation to Alleviate Internalized Homophobia Among Men Who Have Sex With Men in China. Evol Psychol, 21(2).] (https://doi.org/10.1177/14747049231179151) 
[3] [Gangamma, R., Tor, S., Whitt, V., Hollie, B., Gao, Q., Stephens, A., Hutchings, R., & Stone Fish, L. (2020). Perceived Discrimination as a Mediator of ACEs and Psychological Distress. The American Journal of Family Therapy, 49(3), 282-298.](https://doi.org/10.1080/01926187.2020.1813656)
[4] [Ya Zheng, Qi Li, YuanYuan Zhuang, Qi Li, Huijuan Shen, Qianhui Gao, Shiyu Zhou. Reward processing in gain versus loss context: An ERP study. PSYCHOPHYSIOLOGY. Publication status: Corrections received by production editor on 7 March 2017] 
[5] [袁翠, 高千惠, 刘雪林, 周世昱, 靳媛. 抑郁症的嗅觉功能缺陷：发现与观点. 医学与哲学. 第37卷8B期, 60-63页 (8月, 2016) ]

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
