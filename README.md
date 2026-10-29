# simple-common-sites-page
A simple reusable HTML dashboard for organizing frequently used websites, project resources, tools, and team links.
# Common Sites Simple Template

A simple, reusable HTML dashboard for organizing frequently used webpages, project resources, tools, and team links in one place instead of relying only on browser favorites.

## Features

- Single HTML file
- Three-column desktop layout
- Responsive tablet and mobile layout
- Reusable category and link placeholders
- Keyboard focus styling
- No JavaScript, frameworks, packages, or external dependencies

## Files

- `common-sites-simple-template.html` - reusable webpage template
- `README.md` - setup and GitHub documentation

## Customize the Template

Open `common-sites-simple-template.html` in a text editor such as Visual Studio Code or Notepad++.

Replace all values enclosed in double braces. Examples:

- `{{PAGE_TITLE}}`
- `{{PAGE_DESCRIPTION}}`
- `{{NAV_LINK_1_URL}}`
- `{{NAV_LINK_1_LABEL}}`
- `{{CATEGORY_1_TITLE}}`
- `{{CATEGORY_1_LINK_1_URL}}`
- `{{CATEGORY_1_LINK_1_LABEL}}`
- `{{YEAR}}`
- `{{OWNER_OR_TEAM_NAME}}`

Example replacement:

```html
<li>
  <a href="https://example.com" target="_blank" rel="noopener noreferrer">
    Example Resource
  </a>
</li>
```

## Add a Link

Copy an existing list item and update its URL and label:

```html
<li>
  <a href="{{NEW_LINK_URL}}" target="_blank" rel="noopener noreferrer">
    {{NEW_LINK_LABEL}}
  </a>
</li>
```

## Add a Category

Copy an entire `<section class="column">...</section>` block and replace its title and links. The grid automatically wraps additional categories.

## Preview Locally

1. Save the HTML file.
2. Double-click it in Windows File Explorer.
3. It will open in your default browser.

## Suggested GitHub Repository

Repository name: `common-sites-simple-template`

Suggested description:

> A simple reusable HTML dashboard for organizing frequently used websites, project resources, tools, and team links.

Suggested first release tag: `v1.0.0`

## Security and Privacy

This public template contains placeholders only. Before committing changes to a public repository, verify that the file does not contain:

- Internal company URLs
- Personal SharePoint or OneDrive links
- User IDs or tenant IDs
- Session values or access tokens
- Confidential project names
- Vendor billing or authentication links

Keep a separate private copy if you need a personalized version containing internal resources.

## License

Add the license approved for your organization or intended use before distributing the project.
