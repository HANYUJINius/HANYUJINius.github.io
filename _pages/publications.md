---
layout: page
permalink: /publications/
title: Publications
description: Selected journal and conference publications.
nav: true
nav_order: 2
---

<style>
/* Publication typography */
.publications ol.bibliography li .title {
  font-size: 1rem !important;
  font-weight: 700 !important;
  line-height: 1.45;
}

/* Coauthors: lighter and regular */
.publications ol.bibliography li .author,
.publications ol.bibliography li .author a {
  font-size: 0.92rem !important;
  font-weight: 400 !important;
  color: var(--global-text-color-light, #999) !important;
  line-height: 1.55;
}

/* Highlighted author: bold + single underline */
.publications ol.bibliography li .author em {
  font-style: normal !important;
  font-weight: 700 !important;
  color: var(--global-text-color) !important;
  text-decoration: none !important;
  border: none !important;
  box-shadow: none !important;
}

.publications ol.bibliography li .author em a,
.publications ol.bibliography li .author em * {
  font-weight: 700 !important;
  color: inherit !important;
  text-decoration: none !important;
  border: none !important;
  box-shadow: none !important;
}

.publications ol.bibliography li .author em {
  border-bottom: 1px solid currentColor !important;
}

/* Conference and journal names */
.publications ol.bibliography li .periodical,
.publications ol.bibliography li .periodical em,
.publications ol.bibliography li .periodical span {
  font-size: 0.88rem !important;
  font-weight: 400 !important;
  font-style: italic !important;
  color: var(--global-text-color-light, #999) !important;
  line-height: 1.5;
}

/* Conference badges: muted blue */
.publications ol.bibliography li .abbr .badge {
  background-color: #5b91ad !important;
  color: #fff !important;
  font-size: 0.72rem !important;
  font-weight: 600 !important;
  padding: 4px 9px !important;
  border-radius: 4px !important;
  border: none !important;
}

/* Small buttons */
.publications ol.bibliography li .links .btn {
  font-size: 0.78rem !important;
  font-weight: 400 !important;
  border-radius: 4px;
}

/* Spacing */
.publications ol.bibliography li {
  margin-bottom: 1.3rem;
}

.publications ol.bibliography li .links {
  margin-top: 0.5rem;
}
</style>

<div class="publications">
  {% bibliography %}
</div>
