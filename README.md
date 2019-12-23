## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/rangsaritv/rangsaritv.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rangsaritv/rangsaritv.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


### Test

$$mean = \frac{\displaystyle\sum_{i=1}^{n} x_{i}}{n}$$

$$mean = \frac{\displaystyle\sum_{i=1}^{n} x_{i}}{n}$$

Use k_{n+1} = n^2 + k_n^2 - k_{n-1} to write

Example (1): $h_\theta(x) = \Large\frac{1}{1 + \mathcal{e}^{(-\theta^\top x)}}$ ; example (2): $a^2 + b^2 = c^2$ ; example (3): $\sum_{i=1}^m y^{(i)}$


{% raw %}
  $$a^2 + b^2 = c^2$$ --> note that all equations between these tags will not need escaping! 
 {% endraw %}
