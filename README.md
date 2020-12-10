# NF Data Portal Docs: nf-osi.github.io

Visit the docs site at [https://nf-osi.github.io/](https://nf-osi.github.io/).

### Contribution
Contribution/workflow strategy to come!

### How to Add a Doc to Navigation Sidebar
For top-level (parent) docs, add the following items, one on each line: `title`, `has_children` (`true` | `false`), and `nav_order` (integer); and enclose with `---` before and after.
For mid-level (child) docs, add add the following items, one on each line: `title`, `parent` (`title` of child doc above it), `has_children` (`true` | `false`), and `nav_order` (integer); and enclose with `---` before and after.
For bottom-level (grandchild) docs, add the following items, one on each line: `title`, `parent` (`title` of child doc above it), `grand_parent` (`title` of parent doc two levels above), `has_children` (`true` | `false`), and `nav_order` (integer); and enclose with `---` before and after.
See examples:
- [Parent doc](https://github.com/nf-osi/nf-osi.github.io/blob/main/about.md)
- [Child doc](https://github.com/nf-osi/nf-osi.github.io/blob/main/about_portal_lifecycle.md)

### Powered By
* [jekyll](https://jekyllrb.com/)
* [just-the-docs](https://pmarsceill.github.io/just-the-docs/)
* Modeled after the HTAN Data Ingress Docs ([repo](https://github.com/ncihtan/HTAN-Data-Ingress-Docs/tree/gh-pages) | [site](https://ncihtan.github.io/HTAN-Data-Ingress-Docs/step-1.html)) and the [Just-the-Docs Remote repo](https://github.com/pmarsceill/jtd-remote).
