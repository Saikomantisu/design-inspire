# Contributing

Suggest resources that help developers find useful design references.

## Add a resource

1. Check the collection for an existing entry with the same name or URL.
2. Visit the resource and confirm that the link works and its content fits this collection.
3. Add it to the most relevant file in `collections/`. Give each resource one primary category and use tags for overlapping topics.
4. Write a short description in your own words. Explain what someone can use it for.
5. Keep individual resource names in the collection files; the `README.md` lists categories only.

Use this format:

```markdown
## [Site Name](https://example.com/)

A short description of the resource.

- **Useful for:** Specific design tasks or reference material.
- **Tags:** relevant, searchable, topics
```

Prefer curated, useful resources over long lists of unexplained links. If access requires an account or payment, mention any limits you have verified without including prices that can quickly become outdated.

## Categories and tags

Use one of these four categories:

- [Full websites](collections/full-websites.md): Galleries focused on complete website designs, visual styles, and layouts.
- [Landing pages](collections/landing-pages.md): Resources focused on product marketing pages and supporting sections, such as pricing and features.
- [App interfaces](collections/app-interfaces.md): Resources focused on mobile and web app screens, dashboards, and user flows.
- [Components and patterns](collections/components-and-patterns.md): Resources focused on individual sections or UI patterns, such as footers and navigation.

Give each resource exactly one primary category based on its main purpose. When a resource covers several areas, choose its strongest focus and describe the overlap with tags instead of duplicating the entry.

Tags are flexible. Use short, lowercase terms with hyphens between words, such as `typography`, `saas`, `mobile`, and `user-flows`. Reuse existing tags when they fit.

Keep the category list small. Propose a new category only when several resources need it and none of the existing categories fit. Include the proposed scope and example resources. When adding a category, update this list and the category links in `README.md` together.

## Report a problem

Open an issue or pull request for broken links, duplicate entries, or descriptions that no longer match a resource. Include the affected URL and the correction when possible.
