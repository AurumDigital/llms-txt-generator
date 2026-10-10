# llms.txt generator

A free, single-file, client-side generator for [llms.txt](https://llmstxt.org/) files. Fill in your site name, a one-sentence summary and your key pages, and it writes a correctly formatted llms.txt you can copy or download.

- No build step, no dependencies, no tracking: open `index.html` in a browser.
- Nothing you type leaves your browser.
- Hosted version: **[aurumdigital.org/tools/llms-txt-generator](https://aurumdigital.org/tools/llms-txt-generator/)**

## Usage

1. Open `index.html` locally, or enable GitHub Pages for this repository.
2. Add your pages, one per line, in the format `Title | URL | short description`.
3. Copy or download the result and upload it to the root of your domain, so it is served at `https://yourdomain.com/llms.txt`.

## Output format

```markdown
# Site name

> One-sentence summary.

Optional context.

## Key pages

- [Pricing](https://www.example.com/pricing/): Plans and what each includes

## Optional

- [Careers](https://www.example.com/careers/): Open roles
```

## A note on llms.txt

llms.txt is a community proposal, not an official standard, and there is little public evidence that major AI assistants rely on it today. It is quick to add, but crawlable pages, clear content and structured data matter more. Read more in [What is Generative Engine Optimization?](https://aurumdigital.org/insights/what-is-generative-engine-optimization/)

## License

MIT. Built by [Aurum Digital](https://aurumdigital.org).
