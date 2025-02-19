This repository contains documents for data stories currently being worked on by the myDataStory team.

#### Links

- [Style Guide](https://github.com/mydatastory/stories/blob/master/doc/style_guide.pptx)
- [Coding Standards](https://github.com/mydatastory/shared_projects/blob/master/doc/coding_standards.docx)
- [DataStory Presentation](https://github.com/danielsmaxwell/presentations/blob/master/_datastory/data_story_presentation.pptx)
- [Data Story Rubric](https://github.com/danielsmaxwell/mcb4934/blob/master/doc/mini_project_rubric.docx)
- [Embedded Videos](https://stackoverflow.com/questions/43840742/how-to-embed-local-video-in-r-markdown)

----------------------------------------------------------------------------------------
#### Linking to Sections in the Core Explanatory Learning Experiences

Anchor tags are embedded in the RMarkdown or Jupyter Notebook documents.  These should match the section name and are formatted as follows: \<a id="getting_help_on_packages"></a>

This anchor can then be called by specifying the section name after the # character, as follows:  

https://rawcdn.githack.com/mydatastory/r_intro_class/9eb06a608223e7a34721bab4ae627612a496cb28/_episodes_html/seeking_help_toc.html#getting_help_on_packages

Because we use githack to render GitHub .html pages, you must go to their site to obtain a unique url for the resource and then append a specific section name to it if you want to link to a location within the document.

---------------------------------------------------------------------------
#### HTML5 Hide/Show
[HTML5 Hide/Show](http://html5doctor.com/the-details-and-summary-elements/)

The HTML5 hide/show code is not presently supported by IE Explorer.  Both Chrome and Firefox, on the other hand, properly hide and show sections.  Also, this code works in RMarkdown when knitting to a .html document but does not work when knitting to Markdown.  When using this code in a Jupyter Notebook, export it to Markdown.  Place the .html code in two sections, one above and one below the section to be hidden and displayed. 
