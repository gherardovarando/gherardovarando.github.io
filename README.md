## gherardovarando.github.io

Personal page built using Jekyll. 
Feel free to copy and use the present Jekyll template. 

### layout structure

The site consists of a simple interface with a fixed top menu and 
a main area for content display. 

### top menu 

The links in the top menu are automatically generated 
to link the pages available. 
If you want to exclude one of the page from the menu 
just place `hide: true` in the YAML front matter block
of the page.

The personal links (github, social networks, ...) are 
parsed from the `_data/info.yaml` file.

### pages layouts


#### default 

the default layout just place the top menu and the main content 
area. 


#### front

the `front` layout include a picture, position and interests 
(from the `_data/indo.yaml`), and lists the news (from `_posts`). 

#### research

the `research` layout list publications parsed 
from the `_data/papers.yaml` file. 
This file can be created from a `.bib` file using the 
`pandoc-citeproc` filter. 
`URL`, `DOI`, `arxiv` and `pdf` fields will be parsed into 
respective links. 
In particular `pdf` will link to a file in the `pdf/` folder.   


### responsive 

* the top menu will adapt to smaller screen. 
* the arrangements of some elements will fit better small screen.
* the main content area has a light and a dark mode, the mode 
is selected based on os preferences. 
