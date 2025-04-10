# Writing Guidelines

Check your text for [common bugs in writing](https://www.cs.columbia.edu/%7Ehgs/etc/writing-bugs.html)
## Recommended reading:
[Writing science : how to write papers that get cited and proposals that get funded](https://surf.aau.at/primo-explore/fulldisplay?docid=UKL_alma2153069490003346&context=L&vid=UKL&lang=de_DE)

# LaTeX Guidelines

LaTeX IDEs:
- [Overleaf - LaTeX Online Editor]( https://www.overleaf.com/)
- [TeXstudio - LaTeX Offline Editor](https://www.texstudio.org/)


[LaTeX Documentation](https://www.overleaf.com/learn)

[LaTeX Tutorial - Learn LaTeX in 30 minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)

[DOI to BibTex converter](https://www.bibtex.com/c/doi-to-bibtex-converter/)
# Coding Guidelines

In order for code to be maintainable and suitable for further use, the [conventional coding guidelines](https://www.browserstack.com/guide/coding-standards-best-practices) should be followed.

There exist specific guidelines for different programming languages:

[JAVA](https://google.github.io/styleguide/javaguide.html)

[Python](https://peps.python.org/pep-0008/)

[NetLogo](https://ccl.northwestern.edu/courses/mam2005/styleguide.htm)

[C](https://cs50.readthedocs.io/style/c/)

[MATLAB](https://de.mathworks.com/matlabcentral/fileexchange/46056-matlab-style-guidelines-2-0)

If the preferred programming language is not listed, search the web for "YourProgrammingLanguage Style Guide".

Highly recommended literature for coding guidelines:

[Clean Code - Robert C. Martin](https://www.amazon.de/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882/ref=sr_1_1?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=5LXFTJRLM71C&dib=eyJ2IjoiMSJ9.i4p3dW19fcAaAFBVyg6gegK1pZLaltkc2kbVzU1wD_h6mzt5FrbVOTMW62VC3tHZ42PSOanvjCC2Xn6zZ49QzKxVgn5r1Q9KkeXsNz27Ojtua8KCbAbTeInUeRHUaxQIo_HmF_UqUKmJbVD0gjS_cpAN41ISjVLE8bwZcjFtQJgaNIiSkj0bfZF9alxYsP71v5iycLtDPg4UfVRphzA1-lU636phW8pvKqj9mjzBFbk.QwfO2v84Fmz_2SgYlxOxVA6uSno_DctKXZHHeWmzxR0&dib_tag=se&keywords=Clean+Code&qid=1740053475&sprefix=clean+code%2Caps%2C85&sr=8-1)

[Clean Architecture - Robert C. Martin](https://www.amazon.de/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164/ref=pd_bxgy_thbs_d_sccl_1/262-3193895-1284308?pd_rd_w=M7Lg2&content-id=amzn1.sym.e5049a5e-3c04-4839-b191-b8e7a9a74d34&pf_rd_p=e5049a5e-3c04-4839-b191-b8e7a9a74d34&pf_rd_r=REQE121WMMQA1C52PVWF&pd_rd_wg=iv4Hq&pd_rd_r=450cbe0f-871a-4f00-9a32-f6a7be7809f6&pd_rd_i=0134494164&psc=1)
# Git Guidelines

If you have no experience with Git, the following tutorials are recommended:

[Official Git Tutorial](https://git-scm.com/docs/gittutorial)

[Git Tutorial w3schools with exercises](https://www.w3schools.com/GIT/)

The following git cheat sheets provide an overview of the most important commands and functions:
- [Git-Flow-Cheatsheet](https://danielkummer.github.io/git-flow-cheatsheet/)
- [GitLab-Cheatsheet](https://about.gitlab.com/images/press/git-cheat-sheet.pdf)
- [GitHub-Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)

If you are using a JetBrains product (free license for students) check their documentation for a "git with UI", for example this would be the [Dokumentation for PyCharm](https://www.jetbrains.com/help/pycharm/using-git-integration.html).

## Conventional git commit messages
In order to obtain a good and structured overview of the commits, it makes sense to use the [conventional commit messages](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13#types). These are keywords that are inserted at the beginning of the commit messages. For example:

````
feat: add email notifications on new direct messages
````

Overview of conventional commit messages:
- API relevant changes
    - `feat` Commits, that adds or remove a new feature
    - `fix` Commits, that fixes a bug
- `refactor` Commits, that rewrite/restructure your code, however does not change any API behaviour
    - `perf` Commits are special `refactor` commits, that improve performance
- `style` Commits, that do not affect the meaning (white-space, formatting, missing semi-colons, etc)
- `test` Commits, that add missing tests or correcting existing tests
- `docs` Commits, that affect documentation only
- `build` Commits, that affect build components like build tool, ci pipeline, dependencies, project version, ...
- `ops` Commits, that affect operational components like infrastructure, deployment, backup, recovery, ...
- `chore` Miscellaneous commits e.g. modifying `.gitignore`

