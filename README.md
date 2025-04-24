# Electronic Quill V2

A blog website built on [Hugo](https://github.com/gohugoio/hugo), using the [Hugo Theme Stack by CaiJimmy](https://github.com/CaiJimmy/hugo-theme-stack).

# Development

## Building the site

Build the static site:
```bash
hugo
# OR
hugo build
```
- `hugo -D`: include content marked as drafts.
- `hugo -F`: include content with a `publishDate` in the future.
- `hugo -E`: include content with an `expiryDate` in the past.

Start the Hugo Development Server:

```bash
hugo server
```

## Creating content

Create a new content file at the specified path:
```bash
hugo new <path>
```

- `hugo new site <path>`: create a new Hugo site with basic directory structure at given path:
- `hugo new theme <path>`: creates a new theme skeleton in the themes directory. If you're looking to develop your own theme.

