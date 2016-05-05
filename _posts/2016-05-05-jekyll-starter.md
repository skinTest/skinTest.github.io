---
layout: post
title:  "Wish a Welcome"
categories: jekyll learning
date: 2016-05-05 17:42:54 +0800
---

this article is about how to build your blog with jekyll
<!-- more -->

# Blog Building

### Jekyll
* text transform engine. based on ruby, and ...
* jekyll is executable

```bash
jekyll build [src/dest options] [watch options]
jekyll serve
```

* 'config.yml' is the [config](https://jekyllrb.com/docs/configuration/) file for jekyll
* YAML Front matter, things like below
    - keys
        1. first thing of file
        2. triple dash line
    - [Front Matter](https://jekyllrb.com/docs/frontmatter/)
    - [YAML](http://my.oschina.net/u/1861837/blog/526142?p={{totalPage}})
        1. indentation should be: 2
        2. `key: value`
        3. nest key value pair
        4. Array specified by dash and a white space

```YAML
---
layout: post
title: Blogging Like a Hacker
---
```

```
1_key:
  2_key: value
```

```YAML
key: - list_value_one- list_value_two- list_value_three
key:
  - list_value_one
  - list_value_two
  - list_value_three
```

### github pages
1. create <username/ orgname>.github.io
2. write file and then push, github will host for you under 1G and 10G
