---
permalink: /
title: "Qingqiang Sun (孙庆强)"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<font color=#0099ff><h2 id="biography"> Biography</h2></font>
I received the BEng degree from Xiamen University, China, in 2017, and the MEng degree under the supervision of Prof. [Zhiqiang Ge](https://scholar.google.com.hk/citations?user=g_EMkuMAAAAJ&hl=zh-CN&oi=ao) from the Department of Control Science and Engineering, Zhejiang University, China, in 2020. I am currently a PhD candidate under the joint supervision of Prof. [Xuemin Lin](https://www.cse.unsw.edu.au/~lxue/) and Prof. [Wenjie Zhang](https://www.cse.unsw.edu.au/~zhangw/) in the Data and Knowledge Research Group ([DKR](https://unswdb.github.io/index.html)), School of Computer Science and Engineering, University of New South Wales, Australia. My research interests include graph representation learning, semi/un/self-supervised learning, and data-driven modeling. 

<h2 id="news"> News</h2>
- 2022.08.26: My paper titled "Towards Higher-order Topological Consistency for Unsupervised Network Alignment" has been accepted by ICDE 2023.


<h2 color=#0099ff id="publications"> Selected Publications</h2>

1. **Qingqiang Sun**, Xuemin Lin<sup>\*</sup>, Ying Zhang, Wenjie Zhang<sup>\*</sup>, Chaoqi Chen. **Towards Higher-order Topological Consistency for Unsupervised Network Alignment**, *IEEE International Conference on Data Engineering (**ICDE**)*, to appear, 2023.  

2. **Qingqiang Sun**, Zhiqiang Ge<sup>\*</sup>. **Gated Stacked Target-Related Autoencoder: A Novel Deep Feature Extraction and Layerwise Ensemble Method for Industrial Soft Sensor Application**, *IEEE Transactions on Cybernetics (**TCyb**)*, 52(5), 3457-3468, 2022. \[IF=19.12\]  

3. **Qingqiang Sun**, Zhiqiang Ge<sup>\*</sup>. **A Survey on Deep Learning for Data-driven Soft Sensors**, *IEEE Transactions on Industrial Informatics (**TII**)*, 17(9), 5853-5866, 2021. \[IF=11.65, <font color=Tomato>ESI Hot Papers (Top 1‰)</font>\]  

4. **Qingqiang Sun**, Zhiqiang Ge<sup>\*</sup>. **Deep Learning for Industrial KPI Prediction: When Ensemble Learning Meets Semi-Supervised Data**, *IEEE Transactions on Industrial Informatics (**TII**)*, 17(1), 260-269, 2021. \[IF=11.65, <font color=Tomato>ESI Highly Cited Papers (Top 1％)</font>\]  

5. **Qingqiang Sun**, Zhiqiang Ge<sup>\*</sup>. **Probabilistic Sequential Network for Deep Learning of Complex Process Data and Soft Sensor Application**, *IEEE Transactions on Industrial Informatics (**TII**)*, 15(5), 2700-2709, 2019. \[IF=11.65\]  


Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
