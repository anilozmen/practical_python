## Working with Hugo

Creating new chapters

`hugo new --kind chapter basics/_index.md`

Creating new content pages

```
hugo new basics/first-content.md
hugo new basics/second-content/_index.md
```

Launching the website locally

`hugo serve`

### Content

To specify custom titles for menu entries:

```
+++
title = "Install on Linux"
menuTitle = "Linux"
+++
```

## License


[![CC BY 4.0][cc-by-nc-nd-shield]][cc-by-nc-nd]

The content of the Practical Python Course Website by Nina Zakharenko (c) 2020 is licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](cc-by-nc-nd).

The underlying source code used to format and display that content, along with the code exercises is licensed under the MIT license.

The intent of this restrictive license is to give individual learners free access to the course materials. Do not use this material to teach your own Python course or workshop. Instead, please consider supporting my work and significant effort by watching the course on [Front End Masters](https://frontendmasters.com/teachers/nina-zakharenko/) instead.

[![CC BY NC ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: https://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/3.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY%20NC%20ND4.0-lightgrey.svg