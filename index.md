---
title: Katie Despeaux
layout: base
date: 2024-12-02
---


Katie Despeaux, MA, MS

I am a PhD student in Medieval History at the University of New Mexico. My research focuses on the medieval experiences of pregnancy and how they intersected with power. 

---

The cards below are generated automatically from your other pages. Each page that has `homepage: true` in its front matter will appear here as a card. The card's title, summary text, and thumbnail image all come from that page's front matter:

```yaml
homepage: TRUE
summary: A sentence or two describing this page — appears on the card.
thumbnail: assets/images/Despeaux-headshot.jpg
position: 1   # controls the order cards appear (lower numbers first)
```

To add a new card, create a new page and add those fields. To remove a card, delete `homepage: TRUE` from that page's front matter. To reorder cards, adjust the `position` values.

{% assign essays = site.pages | where: "homepage", true %}
{% include nav/card-stack.html cards = essays %}