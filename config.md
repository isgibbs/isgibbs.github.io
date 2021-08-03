<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Isaac Gibbs"
hasicons = true
mintoclevel = 2

ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "Isaac Gibbs"
website_descr = "Isaac's Personal Website"
website_url   = "isgibbs.github.io/isgibbs.github.io/"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}

\newcommand{\arXiv}[1]{
~~~
<span class="tooltip">
<a href=#1><i class="ai ai-arxiv ai-lg"></i></a>
<span class="tooltiptext">arXiv</span>
</span>
~~~
}
