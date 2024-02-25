Images fail to render / produce the right `src` attribute for their HTML `<img>` tag in a repository's README.md if the image is put in a table with a header containing LaTeX.

`test.jpg` provided by Alvesgaspar CC-BY-SA

### No LaTeX in header, works fine:

| Begin z = 4 End |
| - |
| ![](test.jpg) |

### LaTeX in header, fails to render image:

| Begin $z = 4$ End |
| - |
| ![](test.jpg) |

Both render fine in VSCode but the latter fails on [GitHub's website](https://github.com/jb2170/Github-LaTeX-In-Markdown-Table-Header-Prevents-Image)
