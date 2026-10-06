# Maljan documentation

The source of the documentation site for
[Maljan](https://github.com/Root0ne/Maljan), a multi-agent malware analysis
platform in which every claim in the report resolves back to the tool call it
came from.

The pages are MDX files with YAML frontmatter; `docs.json` holds the site's
configuration and navigation, and `images/` holds the diagrams and the logo.

## Local preview

From the root of this repository, where `docs.json` is:

```bash
npx mint dev
```

The preview serves on `http://localhost:3000`.

## Publishing

The site builds from `main`: a change merged there is live once the build
finishes. Work on a branch and open a pull request into `main`.

## Source of truth

These pages track the code in the
[Maljan repository](https://github.com/Root0ne/Maljan); a page that describes
behaviour changes alongside the change in Maljan that alters it.

## License

[MIT](LICENSE), as Maljan itself.
