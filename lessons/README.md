# Lessons

Use this folder to add the module content, separated into one file per lesson (a top-level section division for the module). 

The lessons can be in Markdown files (`.md`) or Jupyter notebooks (`.ipynb`). Use the sample files here to get started, replacing the guidance text by your own content.

List the content files in the `_toc.yml` file, in the order they should appear. For example, this template has:

```
chapters:
- file: learningobjectives
- file: lesson1
- file: lesson2
- file: lesson3
- file: lesson4
- file: references
```
You can add more files in the list, as needed.

The TOPS curriculum team will build the modules from your source files, so you do not have to worry about that.

Do add any Python package dependencies to the requirements.txt in the parent directory.


**Recommend** that all content be shared under a dual license: [BSD-3](https://opensource.org/licenses/BSD-3-Clause) or [MIT](https://opensource.org/licenses/MIT) license for code, and [CC-BY](https://creativecommons.org/licenses/by/2.0/) license for text and media.
