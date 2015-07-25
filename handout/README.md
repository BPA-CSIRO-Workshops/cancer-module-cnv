This directory contains the LaTeX source and any images which are to be included in a workshop handout.

Take a look at the [`example.tex`](example.tex) file as a guide - it also contains embedded LaTeX comments which you should find helpful when writing LaTeX.

Paragraph Text Environments
===========================

The [`btp-workshop-template`](https://github.com/BPA-CSIRO-Workshops/btp-workshop-template) repository
contains the [`btp-handout-style`](https://github.com/BPA-CSIRO-Workshops/btp-handout-style) as a submodule.
As such, it provides you with several convienient [paragraph text
environments](https://github.com/BPA-CSIRO-Workshops/btp-handout-style#paragraph-text-environments) to make writing 
handout documentation quick and easy. You can simply place your text within one of the paragraph "environments" to
have it styled appropriately. In practice, this means you place a `\begin{environment-name}` before your paragraph
text, and `\end{environment-name}` after your paragraph text.

For a full list of available environments, see the
[`btp-handout-style/README.md`](https://github.com/BPA-CSIRO-Workshops/btp-handout-style/blob/master/README.md) file

Adding a Table
==============

Adding a table in LaTeX is somewhat more difficult than adding standard paragraph text. The most straightforward way to
accomplish this is by using an [online LaTeX table generator](http://www.tablesgenerator.com/latex_tables). It provides a
convienient WYSIWYG editor for customising the content and layout of the table and then generates the LaTeX code to
reproduce it. Simply copy-and-paste this code into your `.tex` file.
