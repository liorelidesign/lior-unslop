# UI copy and typography

Use these checks when creating, revising, or auditing a user interface.

## Identify ornamental labels

A small label above a heading is suspect when it merely announces a category that the heading already conveys.

Avoid:

```tsx
<div>
  <p className="text-[10px] font-semibold uppercase tracking-[0.24em]">
    WORKSPACE INTELLIGENCE
  </p>
  <h2 className="text-2xl font-semibold">Workspace overview</h2>
</div>
```

Prefer:

```tsx
<h2 className="text-2xl font-semibold">Workspace overview</h2>
```

If the category is important, use a normal label with sentence case, readable sizing, and no artificial tracking.

## Look beyond casing

- A 10px caption with weak contrast remains hard to read even in sentence case.
- A redundant kicker remains redundant after changing its typography.
- Generic headings such as “Powerful insights” should be replaced with headings that name the data.
- A list of features should not become a grid of tiny uppercase labels merely for visual variety.
- Button copy must describe what actually happens after click.

## Exceptions

Do not rewrite these simply to satisfy a style preference:

- `API`, `HTTP`, `SSO`, `UX`, `SOC 2` and similar established acronyms.
- Case-sensitive tokens, environment values, code, and file names.
- Trademarks and approved brand typography.
- User-provided exact text, required legal notices, and mandated compliance wording.
- An existing product design the user specifically asked to reproduce faithfully.

## Implementation boundaries

- Prefer component-local edits over global CSS overrides.
- Inspect existing design tokens and type styles before adding new ones.
- Do not create unrelated spacing, color, or typography changes while fixing UI copy.
- Preserve accessibility names, testing selectors, localization keys, and responsive behavior.
- When auditing, report the issue and the smallest useful fix.
