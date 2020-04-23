## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/raoelg/Random-notes/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/raoelg/Random-notes/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

## Tests

Can I do $\LaTeX$? The distribution function $F_X(x)$ and the density function $f_X(x)$, if it exists, are related by the equation

\\[F_X(x) = \int_{-\infty}^x f_X(y)dy.\\]

In R for a range of frequently encountered random variables both the distribution and the density function are defined, and follow the naming convention `p<name>` for the distribution function (because $F_X(x) = P(X\le x)$, hence, the p for probability), and `d<name>` for the density function. For example for a normally distributed random variable the corresponding functions are called `pnorm` and `dnorm`, while for an exponetially distributed random variable the functions are called `pexp` and `dexp`.
