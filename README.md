# KPS Agile Playbook

#### [Visit](https://knightpointsystems.github.io/kps_playbook/)

### Understanding Jekyll

This project uses a library called Jekyll and Jekyll Now. Jekyll Now is simply a Jekyll template that can be used
for super easy startup and editing. This gives us almost all the configuration that is needed for Jekyll, this allows
us to focus on making the content of the site awesome! That being said, here are some of the basics of Jekyll you'll
want to understand:

- [Directory Structure](https://jekyllrb.com/docs/structure/)
- Your Content
    - [Front Matter](https://jekyllrb.com/docs/frontmatter/)
    - [Writing Posts](https://jekyllrb.com/docs/posts/)
    - [Creating Pages](https://jekyllrb.com/docs/pages/)
    - [Data Files](https://jekyllrb.com/docs/datafiles/)
    - [Assets](https://jekyllrb.com/docs/assets/)

### Contributing

Contributing to this guide follows the common KPS pull request model. To contribute, simply make any changes you
would like on a separate branch, create a pull request with those changes, another member of KPS will then
review and approve or add comments to those changes, then the changes will get merged into the project!

#### Understanding Front matter

Front matter is something that should be added to every page on this site. It is something that allows you
to utilize a lot of the power that Jekyll gives you. For reference, front matter is the content at the beginning
of our files that starts and ends with: `---`.

Everything between sets of `---` is called front matter, and this is where an infinite number of properties
can be defined that can be used programmatically within our templates.

For example, if you would like to set the title and route of a markdown page you are writing, it could
look something like:

```
---
title: This is my title
permalink: /this/is/my/route
---
```
