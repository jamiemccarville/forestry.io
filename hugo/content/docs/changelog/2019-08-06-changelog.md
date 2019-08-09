---
authors:
- team forestry
date: 2019-08-06T09:34:25.000+00:00
title: 2019/08/06 Changelog
cta:
  headline: ''
  textline: ''
  calls_to_action: []
draft: true

---
### Enhancements

* Better search for pages and in select fields options.  
  We even wrote a [blog post about how Forestry does search](/blog/full-text-searching-with-postgres/)
* **Instant Previews hibernation**
* Display last sign in date for organization users.
* Added latest [**Hugo 0.56.3**](https://gohugo.io/news/0.56.3-relnotes/)

### Bug fixes

* Fix a bug preventing to use **Create template from Page**.
* Sanitize media filenames to **prevent failed media uploads.**

### Deprecation

* **Deployments:** New sites can no longer be deployed by Forestry. Existing sites have until the end of the year to move to a dedicated CI/CD platform. [Read the sunset notice](https://forestry.io/docs/sunset/deployments/).
* As a result, **Standard Previews** are also deprecated in favor of [**Instant Previews**](https://forestry.io/docs/previews/instant-previews/) for new sites**.** Existing sites still using standard previews have until the end of the year to make the switch.