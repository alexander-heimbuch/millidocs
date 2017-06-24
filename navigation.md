---
layout: page
title: Navigation
navigation: 2
---

# Navigation

The navigation supports especially only one level. If you need deep nested structures you propably should use a larger documentation system like [GitBook](https://www.gitbook.com/).

## Adding a Page to Navigation

Not every page by default is part of the navigation. If you want to add a page to the navigation you have to add the `navigation` attribute with a desired `index`:

```
---
layout: page
title: Navigation
navigation: 2
---
```

The navigation `index` is starting with 1 representing the first item. 
