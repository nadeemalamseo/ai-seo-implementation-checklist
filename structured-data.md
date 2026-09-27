# Structured Data Implementation Guide

A practical guide to planning, implementing, validating, and maintaining structured data on websites.

> Scope: Structured data helps describe page and entity information in a machine-readable format. Correct implementation does not guarantee rankings, indexing, rich results, or inclusion in search or AI-generated answers.

---

## 1. Understand What Structured Data Does

Structured data provides machine-readable information about content and entities on a webpage.

It can help systems understand information such as:

- Organizations
- People
- Articles
- Products
- Services
- Local businesses
- Websites
- Web pages
- Breadcrumbs
- Events
- Other supported entities

Structured data should describe information that is accurate and relevant to the page.

It should not be treated as a method for forcing a particular search result.

---

## 2. Start With the Page and Its Purpose

Before selecting a schema type, understand the page.

Record:

- Page URL
- Page type
- Primary purpose
- Main entity
- Supporting entities
- Visible information
- Author or organization
- Important dates
- Relevant relationships

For example:

```text
Page
│
├── Primary entity
│   └── Article
│
├── Author
│   └── Person
│
├── Publisher
│   └── Organization
│
└── Topic
    └── SEO
