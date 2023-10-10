---
permalink: /
title: "Profile 个人简介"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

胡恩岭博士，西南大学副教授、硕士生导师。自2009年始，供职于香港理工大学近十年，先后担任研究助理、助理研究员、博士后等职位，从事功能材料、催化反应等领域的研究。2018年7月，入职西南大学，在蚕桑纺织与生物质科学学院开展科研与教学工作。在研究生培养上，同时担任生物与医药（专硕）与纺织科学与工程（学硕）两个专业的硕士生导师；在本科生培养上，担任纺织工程系、轻化工程系、生物质科学与工程系、蚕学和生物技术系学业导师、创新实验导师、毕业设计导师、以及大学生“互联网+”创新创业竞赛导师。


**研究方向**：
1. 智能递送止血材料
1. 交互响应性组织修复材料
1. 精准靶向溶栓与携栓血管修复材料
   

研究生课程：
1. 《中外主文献研读》
1. 《染整技术前沿》
   

本科生课程：
1. 《纺织化学》
1. 《功能纺织品》
1. 《染整仪器操作实践》
1. 《学位论文写作与学术规范》
1. 《时尚的未来趋势》（国际课程）


## 西大在读本科生“科研小超人”招募 Recruitment of in-campus college students

---
长期招募对本课题组的研究有兴趣与热情的在校大一、大二本科生同学（理工科、农科），引导优秀本科生同学尽早参与科研活动。为有志于进一步提升自我的本科生同学提供研究平台， “领先”一步产出科研成果，成为同龄人中的佼佼者。助力免试攻读硕士学位研究生（保研），助力海外高校深造（留学）。成果形式包括：
1. 发表高水平英文学术论文
1. 竞逐中国国际“互联网+”大学生创新创业大赛
1. 申报大学生创新创业训练计划国家级、市级、校级项目


**写给青涩如你的心灵小鸡汤**
------
成长绝非易事，蜕变更是难上加难。
没有金刚钻，揽不下瓷器活。人生需要规划，更需要提早规划。
要在同级的竞争者中脱颖而出，既要有内心强大的进取心，更要有外部提供的助力平台。
如果你的内心足够强大，如果你的意志足够坚定，何不加入我们华丽变身，
**成为别人眼中的科研“小超人”**。


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
