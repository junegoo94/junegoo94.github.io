---
layout: page
permalink: /publications/
title: publications
description: Publications in reverse chronological order. My name is underlined.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<style>
  /* year headings: theme default uses the divider colour, which is too faint */
  .publications h2.bibliography {
    color: var(--global-text-color-light);
    font-weight: 600;
  }
  .publications h2.pub-section {
    margin-top: 1.5rem;
    padding-bottom: 0.5rem;
    border-bottom: 2px solid var(--global-text-color);
  }
  .publications h2.pub-section + h2.bibliography {
    border-top: none;
  }
  .publications h2.pub-section-gap {
    margin-top: 5rem;
  }
</style>

<div class="publications">

<h2 class="pub-section">First-author publications</h2>

{% bibliography --query @*[firstauthor=true]* %}

<h2 class="pub-section pub-section-gap">Co-authored publications</h2>

{% bibliography --query @*[firstauthor!=true]* %}

</div>
