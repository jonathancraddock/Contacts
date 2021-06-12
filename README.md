# Contacts v0.4

I first created **Contacts** in November 2015. It became a permanent prototype ([live demo here](https://mootparadox.com/contacts/)) of a contacts list app, that has now been in use for nearly 6 years.

![Permanent Prototype](https://github.com/jonathancraddock/Contacts/blob/c545418e8e369fd2b466ffc9c7ea8d778684e653/images/title-image.jpg)

There were a few iterations, one of which introduced the now deprecated use of `cache.manifest`, but it has remained mostly unchanged for 6 years. It's been my first, and so far only, experiment with AngularJS.

```
<!-- DTV Contacts -->
<!-- by Jonathan Craddock -->
<!-- v0.1 : Prototype/Demo Version, 25/11/2015 -->
<!-- v0.2 : Prototype/Demo with live data, 17/4/2015 -->
<!-- v0.3 : Updated for cache to mobile, 9/4/2018 -->
<!-- v0.4 : Switched for dummy data and preserving on personal site, 11/06/2021 -->
```

It's arguably out of date, the codebase is partially deprecated, but it's super-simple and works great. The linked demo has 105 names, but my live implementation had 400+ names and the response was still instantaneous.

## Introduction

Contacts are divided into four categories.

* Colleagues (regular staff)
* Managers (managers)
* External (third party contacts, non-employees)
* Resources (reception, rooms, and so on)

You can filter by category using the dropdown, or enter a few letters from a name into the search bar for instant realtime filtering. Leading and trailing spaces are ignored, but spaces within a name can form a valid search string. For example `fox m` would filter `Fox Mulder`, but not `Foxmo...`, or whatever funny name someone might have! ;-)

![Screenshot-1](https://github.com/jonathancraddock/Contacts/blob/bd6297716be6dc52242b2980131b28c8c0e7b039/images/screenshot-1.jpg)

It would be easy enough to add an email address, job title, or other fields if needed.

&nbsp;
---

### Resources and Links

**CSV to JSON** -> https://csvjson.com/csv2json  
^- *Excellent resource for converting CSV to JSON but, even better, you can paste text straight from a spreadsheet, and it still manages to convert it into valid JSON.*

**Live Demo** -> https://mootparadox.com/contacts/  
^- *Working demo, with dummy names.*

**AngularJS** -> https://en.wikipedia.org/wiki/AngularJS  
^- *Official support ends soon. See: https://angular.io/*

**Bootstrap** -> https://getbootstrap.com/  
