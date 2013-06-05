---
layout: default
title: "Jekyll Docs Template"
---

<p class=lead>The jekyll-docs-template provides a minimal template for writing
documentation-based sites for projects.</p>

The primary feature is making use of the post `category` defined in the
post's Front Matter header. The navigation is built based on the sections
listed in the `_config.yml`.

```yaml
sections: [
    ['doc', 'Documentation'],
    ['tut', 'Tutorial'],
    ['ref', 'Reference'],
    ['dev', 'Developers'],
    ['post', 'Posts']
]
```

Create a new post/page the same way, just specify the category and it will
show up in the navigation.

```html
---
layout: page
title: New Reference Page
category: ref
---

...
```
