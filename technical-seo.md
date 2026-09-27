# Technical SEO Implementation Guide

A practical guide for reviewing the technical foundations that affect crawling, rendering, indexing, site architecture, performance, and search accessibility.

> **Scope:** This guide focuses on technical implementation. It does not guarantee rankings or indexing. Search systems evaluate many signals, and technical fixes should be prioritized according to the actual problems found on a website.

---

## 1. Establish the Technical Baseline

Before changing anything, document the current state of the website.

Record:

- Primary domain
- Preferred hostname
- HTTPS status
- CMS
- Hosting environment
- CDN, if applicable
- XML sitemap URL
- robots.txt URL
- Approximate number of important pages
- Search Console property
- Analytics configuration
- Major URL structures
- Known indexing issues
- Known performance issues

### Why this matters

Technical SEO changes can create unintended consequences.

A baseline allows you to determine whether a change actually improved the site or introduced a new problem.

---

# 2. HTTPS & Canonical Domain

Confirm that the website consistently uses its intended secure URL.

Check:

- [ ] HTTPS loads correctly
- [ ] HTTP requests redirect appropriately
- [ ] The preferred hostname is consistent
- [ ] Internal links use the preferred URL format
- [ ] Canonical URLs use the preferred protocol
- [ ] XML sitemaps use the preferred protocol
- [ ] Important structured-data URLs use the preferred protocol
- [ ] No unnecessary HTTP/HTTPS duplication exists

### Common problem

A site may technically support several versions:

```text
http://example.com
https://example.com
http://www.example.com
https://www.example.com
