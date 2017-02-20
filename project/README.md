# Final Project Guidelines

In addition to programming assignments, students will complete a final project that represents a significant implementation and/or application of NLP techniques. Here’s what to expect:
- You can work on the project in a group of up to 3 students. Solo projects are also fine, but we strongly encourage you to collaborate.  While we expect high _quality_ of work from all groups, we expect a higher _quantity_ of work from teams with more members.
- The project can be on anything within the scope of the class, although it need not be something covered explicitly in lecture.
- At the end, you’ll turn in a writeup in the style of a research paper, and give a short presentation to the class. You’ll also submit your code.

## Timeline and Logistics
The project is expected to be significantly more work than each of the assignments, as you’ll need to do planning and research as well as implement much of the code framework to process data, run experiments, generate plots, etc. How to manage all of this? Start early! (and, ask lots of questions!)

We’ll set several milestones to check in along the way:
- [10%] **Project proposal** (and groups), due at end of Week 5 (Sunday February 12 @ 11:59 PM Pacific)
- [30%] **Milestone** due end Week 11 (Sunday March 26 @ 11:59 PM Pacific)
- [10%] **Final presentations** in class Week 15 (April 24 - April 28)
- [50%] **Project writeup** due last day of classes (April 28 @ 11:59 PM Pacific)

## Project Scope and Ideas
The project is very open-ended, but we do require it to be an NLP project. This means that, at its core, your project should be about processing text, speech, or other form of language. It need not be completely novel in the way that academic research is, but should attempt to do something non-trivial or non-obvious with the data and/or algorithm. For example, you could:
- Apply existing (well-known or otherwise) NLP algorithm(s) to a new dataset
- Develop a new NLP algorithm and apply it to a well-known dataset
- Implement an algorithm from a recent paper and apply it to a new domain or dataset
- Use NLP algorithms in a descriptive way to find trends or patterns of practical or linguistic interest

As for scope: an ambitious project for a group of 2-3 would be similar in scope and depth of experiments to a conference paper.

For project ideas, take a look at the final projects from [last](example-comment-quality.pdf) [semester](example-grammar.pdf), [Stanford cs224n](http://nlp.stanford.edu/courses/cs224n/) (all years), or for deep-learning projects, [cs224d](http://cs224d.stanford.edu/) ([2015](http://cs224d.stanford.edu/reports_2015.html), [2016](http://cs224d.stanford.edu/reports_2016.html)). A few examples, as a place to start:
- Abstractive summarization of news articles
- Restaurant menu extraction from user reviews
- Question-answering with neural attention or memory models
- Image captioning (language generation)
- Analysis of gender roles or power dynamics in movie dialogues
- Explore techniques for interpreting “black box” / neural models for language

Two groups from the Fall 2016 iteration of this course have also graciously agreed to share their project reports:
- [Automated Comment Scoring](example-comment-quality.pdf) by Tom Yedwab, Kyle Hamilton, and Cory Kind
- [Essay Scoring with Grammatical Error Detection](example-grammar.pdf) by Ross Katz, Drew Plant, and Nina Kuklisova

Also see below for NLP conferences - [ACL](http://acl2016.org/index.php?article_id=68) and [EMNLP](http://www.emnlp2016.net/accepted-papers.html) are the top two, and you can find plenty of interesting ideas from the recent proceedings!

## Project Proposal
**10% of project grade**

This is the most important deliverable.  Take time to get it right! A concrete idea at this early stage will help you build a stronger project and help you in the course overall. 

Each group will submit a proposal.  We’ll read each one and give you detailed feedback. The proposal should be concise, 200-300 words. Quality is valued here far more than quantity!

Be sure to address:
- What do you plan to do?
- Why is it important, and why is it challenging?
- What dataset(s) will you use?
- What algorithms might you use? Are good implementations available, or will you need to write your own? (Don’t worry if you can’t answer this well at this stage of the course.)
- References to _at least_ four papers related to your proposal

You must include four references to relevant papers for the technique and/or dataset you’ll be using. Projects should be well-situated with respect to existing work, and so we do require that references be research papers or technical publications of similar scope. While you may also want to cite reference works, textbooks, or code documentation, these don’t count toward the total. Some resources that may be helpful:
- (start here) [The Association of Computational Linguistics (ACL) Anthology](http://aclweb.org/anthology/), which indexes papers from most of the top NLP conferences.
- The [ACM Digital Library](http://dl.acm.org/) is also a great resource, indexing across a number of CS conferences. In particular, [SigKDD](http://www.kdd.org/) (Knowledge Discovery and Data Mining) and [WSDM](http://www.wsdm-conference.org/) (Web Search and Data Mining) might be useful.
- [NIPS](https://nips.cc/Conferences/2015) and [ICML](http://icml.cc/2016/) are the top machine learning conferences; these are good places to look if you want to use neural networks.
- [Google Scholar](https://scholar.google.com/) and the [arXiv](https://arxiv.org/) are great to find specific papers.

This year’s NLP conferences might be good for inspiration as well, or if you just want a sense of what people in the field are working on: [NAACL](http://aclweb.org/anthology/N/N16/), [ACL](http://aclweb.org/anthology/P/P16/), [EMNLP](http://aclweb.org/anthology/D/D16/).

Please send your proposal to mids-nlp-instructors@googlegroups.com, either as a PDF or (preferably) a Google Doc. If the latter, we'll provide feedback as in-line comments, which can be more convenient than an email thread.  
_Please no Microsoft Word documents!_

## Milestone
**30% of project grade**

You’ll submit a partial report (3-5 pages) and implementation of your project. This should include:
- Evidence that you’ve been able to obtain, load, and play around a bit with your data.  (For example,  some simple exploratory data analysis.)
- Results from a baseline model. This can be very simple, such as random predictor, most-common-class, or a bag-of-words model.

Your report should be the working/rough draft of your final project report (see below), although it’s expected that you won’t have fleshed-out results or conclusion sections. It’s also okay if your report changes substantially between here and the final, especially if you have exciting results in the interim!  

For the milestone, your writeup should have sections similar to the following, in the vein of a proper research paper:
- **Abstract**
- **Introduction** (motivation for your work)
- **Background** (literature review, or related work)
- **Methods** (include a description of any proposed work here, even if you haven’t done it yet)
- **Results and discussion** (for your baseline model, though feel free to include material for anything else you’ve done)
- **Next Steps** section for work you plan to do before submitting the final version (you’ll remove this section and replace it with your conclusions, final results and analysis in your final report)

The easiest way to write your report is LaTeX; the standard ACL template is available [here](http://acl2015.org/call_for_papers.html) (or, on Overleaf [here](https://www.overleaf.com/latex/templates/template-for-2-columns-acl-proceedings-style/bdxxrbqzsmpv#.WGV0frYrLdR)). However, you’re welcome to typeset in Microsoft Word or IPython/Jupyter Notebooks as well.

You should also share your code with us via GitHub. Either include a link in your email to your own repository, or you can create one under the course organization using this link: [GitHub classroom - 2017-spring-project](https://classroom.github.com/group-assignment-invitations/4caa36f0aacdbf7dd8a4105d4e79e2b4)

Please send your write-up in PDF format to mids-nlp-instructors@googlegroups.com.

## Presentations 
**10% of project grade**

Expect that your group will give a short (5-10min) presentation summarizing your project during live session in the last week. We’ll announce a schedule and further details of the presentation format closer to the end of the term.

## Final Submission
**50% of project grade**

This will be a final report in the style of a research paper. Aim for something between an ACL [short paper](http://aclweb.org/anthology/P/P16/#2000) and [long paper](http://aclweb.org/anthology/P/P16/#1000) in length (4-6 pages), with sections similar to the following:
- **Abstract**
- **Introduction** (motivation for your work)
- **Background** (literature review, or related work)
- **Methods** (design and implementation)
- **Results and discussion** (include plots & figures, and detailed analysis in comparison to baseline and the literature, if applicable)
- **Conclusion**

Again, please send your write-up PDF by email to mids-nlp-instructors@googlegroups.com and include a link to all the code you wrote.

