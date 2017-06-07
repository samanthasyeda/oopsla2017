## Exploiting Implicit Beliefs to Resolve Sparse Usage Problem in Usage-based Specification Mining

Frameworks and libraries provide application programming interfaces (APIs) that serve as building blocks in modern sofware development. As APIs present the opportunity of increased productivity, it also calls for correct use to avoid buggy code. Usage-based specifcation mining technique has shown great promise in solving this problem through a data-driven approach. Tese techniques leverage the use of the API in large corpora to understand the recurring usage of the API and infer behavioral specifcations (preconditions and postconditions) from such usage. A challenge for such technique is thus inference in the presence of insufcient usage, in terms of both frequency and richness. We refer to this as a "sparse usage problem". This paper presents the frst technique to solve the sparse usage problem in usage-based precondition mining. Our key insight is to leverage implicit beliefs to overcome sparse usage. An implicit belief is a fact about language structure and semantics known to the programmer, and thus not explicitly documented in code. Te technical underpinnings of our new precondition mining technique include a technique to observe the semantics of code structures leading to an API call to infer preconditions that are implicitly present in the code corpus, a strategy to detect these implicit beliefs in this paper based on the data and control fow related properties, a catalog of 35 code elements in total that can be used to derive implicit belief from a program, and empirical evaluation of all of these ideas. We have analyzed over 350 millions lines of code and 7 libraries that sufer from sparse usage problem. Our approach realizes 6 implicit beliefs and we have observed that addition of single level context sensitivity can further improve the result of usage based precondition mining. Te result shows that we achieve overall 60% in precision and 69% in recall and the results relatively improved by 32% in precision and 78% in recall compared to base usage-based mining approach for these libraries.

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/doubleblinddoubleblind/oopsla2017/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/doubleblinddoubleblind/oopsla2017/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

