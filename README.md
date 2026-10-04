<h1 align="center">Prism Theme</h1>

<p align="center"><em>A modern purple-accented override stylesheet that refines an existing dark theme rather than replacing it.</em></p>

<p align="center">
  <img alt="Type" src="https://img.shields.io/badge/Type-Stylesheet-3B82F6?style=for-the-badge">
  <img alt="CSS" src="https://img.shields.io/badge/CSS-Override%20Layer-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img alt="Font" src="https://img.shields.io/badge/Font-Inter-000000?style=for-the-badge">
  <img alt="Delivery" src="https://img.shields.io/badge/Delivery-GitLab%20Pages-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white">
</p>

---

## Overview

An external override stylesheet that loads on top of a site's own dark theme. It
refines colour, typography, spacing, radius and depth only — it does not replace or
alter site functionality.

Because it layers rather than replaces, it stays small and survives upstream changes
to the site's own CSS.

## Install

1. Host `style.css` at a public URL, or use the published GitLab Pages URL.
2. Paste that URL into **Settings → General → External CSS Stylesheet**.
3. Save and hard-refresh.

## Customising

All colours are declared as design tokens in the `:root` block at the top of
`style.css` — surfaces, text, borders and accents. Change the tokens and the rest of
the sheet follows.

## Contents

| File | Purpose |
|---|---|
| `style.css` | The override stylesheet |
| `index.html` | Landing page for the published Pages site |
