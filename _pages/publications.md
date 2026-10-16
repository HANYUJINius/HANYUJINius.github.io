
---
layout: page
permalink: /publications/
title: Publications
description: Selected journal and conference publications.
nav: true
nav_order: 2
---

<style>
/* ========================================
   PUBLICATIONS — CLEAN ACADEMIC STYLE
   ======================================== */

/* Paper title: strongest emphasis */
.publications ol.bibliography li .title {
  font-size: 1rem !important;
  font-weight: 700 !important;
  line-height: 1.5;
}

/* Coauthors: light, regular weight */
.publications ol.bibliography li .author {
  font-size: 0.92rem !important;
  font-weight: 400 !important;
  color: var(--global-text-color-light, #999) !important;
  line-height: 1.6;
}

.publications ol.bibliography li .author a {
  font-weight: 400 !important;
  color: inherit !important;
}

/* Your name: bold + single underline */
.publications ol.bibliography li .author em {
  font-style: normal !important;
  font-weight: 700 !important;
  color: var(--global-text-color) !important;
  text-decoration: none !important;
  border: 0 !important;
  border-bottom: 1px solid currentColor !important;
  box-shadow: none !important;
}

.publications ol.bibliography li .author em *,
.publications ol.bibliography li .author em a {
  font-weight: 700 !important;
  color: inherit !important;
  text-decoration: none !important;
  border: 0 !important;
  box-shadow: none !important;
}

/* Conference/journal: smaller and muted */
.publications ol.bibliography li .periodical,
.publications ol.bibliography li .periodical em {
  font-size: 0.88rem !important;
  font-weight: 400 !important;
  font-style: italic !important;
  color: var(--global-text-color-light, #999) !important;
  line-height: 1.5;
}

/* Conference labels: muted academic blue */
.publications ol.bibliography li .abbr .badge,
.publications ol.bibliography li .abbr abbr {
  display: inline-block;
  background-color: #5b91ad !important;
  color: #ffffff !important;
  font-size: 0.72rem !important;
  font-weight: 600 !important;
  border: none !important;
  border-radius: 4px !important;
  padding: 4px 9px !important;
  text-align: center;
}

/* Publication link buttons */
.publications ol.bibliography li .links a.btn,
.publications ol.bibliography li .links .btn {
  font-size: 0.78rem !important;
  font-weight: 400 !important;
  border-radius: 4px;
  margin-right: 5px;
  margin-bottom: 5px;
}

/* Publication spacing */
.publications ol.bibliography li {
  margin-bottom: 1.3rem;
}

.publications ol.bibliography li .links {
  margin-top: 0.55rem;
}

/* Mobile typography */
@media (max-width: 576px) {
  .publications ol.bibliography li .title {
    font-size: 0.95rem !important;
  }

  .publications ol.bibliography li .author {
    font-size: 0.85rem !important;
  }

  .publications ol.bibliography li .periodical {
    font-size: 0.82rem !important;
  }
}
</style>

