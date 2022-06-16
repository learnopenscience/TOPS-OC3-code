# Lesson 1: using Markdown

In the module template, we use the `lesson1.md` file as a sample lesson, and introduce you to the flavor of Markdown that you will use to write the content, called **MyST Markdown**.

Whether you write module content content in Jupyter Notebooks (`.ipynb`) or
in regular markdown files (`.md`), you'll write in the same flavor of Markdown.
This file shows some example syntax.

## What is MyST?

MyST stands for "Markedly Structured Text". It
is a variation on so-called "CommonMark" markdown,
with some syntax extensions to allow you to write **roles** and **directives**.
These offer customization and styling for the final content.
For example, you can use a directive to get a nicely formatted *Note*  box in the final document like this:

````
```{note}
Here is a note
```
````

Other directives can produce styled boxes for: *Warning*, *Caution*, *See also*, and *Tip*.

Roles are like in-line commands, for example to introduce citations (see below) or internal links to other parts of the lessons. If you know LaTeX, you can think of directives as environments and roles as macros.

:::{seealso}
Learn more about MyST by exploring the JupyterBook documentation: [MyST Markdown Overview](https://jupyterbook.org/content/myst.html).
:::


## Citations

You can cite references from a `bibtex` file using `{cite}` roles. Several in-line citation styles are possible.
See the variations in the JupyterBook documentation: [Change the in-line citation style](https://jupyterbook.org/en/stable/content/citations.html#change-the-in-line-citation-style).

To insert a bibliography into your page, you will use the `{bibliography}` directive. For example, if the references for your module are stored in `references.bib`, you indicate this file name in the `_config.yml` and
then insert the bibliography with:

````
```{bibliography}
```
````