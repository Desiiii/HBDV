# Conventions
*In sum, the boring stuff.*

## Tags

Be aware of the ``{%char %}`` tags. In sum, they turn ``{%char David%}`` into "<span style="color: #35b100;">David</span>", providing name highlighting.

## Front-Matters

### Post

```yaml
# Example Front-matter
---

layout: post
comments: true
ref: "hbdv1-jan-01-01" # "$series-$month-$day-$year" format, being month/day/year relative to the CHAPTER'S datetime
lang: "en" # Set this according to the language

title: "Monday, January 01, Year 01" # The title format is language-based
categories: "hbdv1" # Categories == Series

series: "hbdv1" # Categories == Series
chapter: 1

#These two are optional and I (AdrianTodt) may help you fill it.
keywords: "hybridverse, hbdv, david, lotus, diary, book, anna, cendres, lucian, beginning, wolfs" # Clickbait
description: "FIXME" # Twitter/Facebook/Discord cards/embeds

---
```

### Page

```yaml
# Example Front-matter
---

layout: page
comments: true
ref: "characters" # this reference is always based on the english post
lang: "en" # Set this according to the language

title: "Characters"
permalink: /en/characters/ # "$lang/$ref" format

#These two are optional and I (AdrianTodt) may help you fill it.
keywords: "hybridverse, hbdv, nightny, royale, diary, book, dragons, david, lotus, viktor, anna, cendres, felipe, kaotine, characters" # Clickbait
description: "FIXME"# Twitter/Facebook/Discord cards/embeds

---
```