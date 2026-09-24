# Awesome Screenshot Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of screenshot APIs, tools, libraries, and resources for capturing, comparing, and automating web screenshots.

Whether you're building OG image generators, visual regression tests, website monitoring, or PDF reports -- this list has you covered.

## Contents

- [Screenshot APIs](#screenshot-apis)
- [Open Source Libraries](#open-source-libraries)
- [Browser Automation](#browser-automation)
- [Visual Regression Testing](#visual-regression-testing)
- [PDF Generation](#pdf-generation)
- [OG Image Generation](#og-image-generation)
- [Browser Extensions](#browser-extensions)
- [CLI Tools](#cli-tools)
- [SaaS Platforms](#saas-platforms)
- [Tutorials & Articles](#tutorials--articles)

## Screenshot APIs

Cloud-hosted APIs for capturing website screenshots programmatically.

| Service | Free Tier | Pricing | Features |
|---------|-----------|---------|----------|
| [GrabShot](https://grabshot.dev) | 25/mo | From $9/mo | Full page, device frames, AI cleanup, OG images, multiple formats |
| [ScreenshotOne](https://screenshotone.com) | 100/mo | From $39/mo | Full page, animations, ad blocking |
| [URLBox](https://urlbox.io) | 7-day trial | From $39/mo | Retina, full page, PDF, custom CSS |
| [Screenshotlayer](https://screenshotlayer.com) | 100/mo | From $9.99/mo | Viewport config, full page, thumbnail |
| [ApiFlash](https://apiflash.com) | 100/mo | From $7/mo | Full page, custom viewport, fresh captures |
| [Microlink](https://microlink.io) | 50/day | From $12/mo | Screenshot, PDF, meta extraction, lighthouse |
| [Stillio](https://stillio.com) | None | From $29/mo | Automated scheduled captures, archiving |
| [PagePeeker](https://pagepeeker.com) | Yes (watermark) | From $5/mo | Thumbnail generation, bulk capture |
| [Thum.io](https://www.thum.io) | Yes | Custom | Real-time website thumbnails |
| [Screenshot Happy](https://screenshot-api-production-ffd7.up.railway.app) | 200/mo | From €9/mo | Full page, CSS selector, custom viewport, PNG/JPEG/PDF, visual change monitoring with webhooks |

## Open Source Libraries

Self-hosted solutions for full control.

- [Puppeteer](https://github.com/puppeteer/puppeteer) - Chrome headless browser automation by Google. The gold standard for screenshots.
- [Playwright](https://github.com/microsoft/playwright) - Cross-browser automation by Microsoft. Chromium, Firefox, WebKit.
- [Selenium](https://github.com/SeleniumHQ/selenium) - Browser automation framework supporting all major browsers.
- [Shot-scraper](https://github.com/simonw/shot-scraper) - Command-line tool by Simon Willison for taking screenshots with Playwright.
- [Pageres](https://github.com/sindresorhus/pageres) - Capture screenshots of websites at various resolutions.
- [Capture Website](https://github.com/sindresorhus/capture-website) - Capture screenshots using Puppeteer with a simple API.
- [Maim](https://github.com/naelstrof/maim) - Linux desktop screenshot utility.
- [Carbon](https://github.com/carbon-app/carbon) - Create beautiful images of source code.

## Browser Automation

Frameworks for controlling browsers programmatically.

- [Puppeteer](https://pptr.dev) - Node.js library for Chrome/Chromium DevTools Protocol.
- [Playwright](https://playwright.dev) - Reliable end-to-end testing and automation for modern web apps.
- [Cypress](https://www.cypress.io) - JavaScript end-to-end testing with built-in screenshot support.
- [Selenium WebDriver](https://www.selenium.dev) - W3C standard for browser automation.
- [Splash](https://github.com/scrapinghub/splash) - JavaScript rendering service with HTTP API (Lua scripting).
- [Browserless](https://www.browserless.io) - Hosted Chrome-as-a-Service for headless browser tasks.

## Visual Regression Testing

Tools for detecting unintended visual changes.

- [Percy](https://percy.io) - Visual testing platform with CI integration. BrowserStack product.
- [Chromatic](https://www.chromatic.com) - Visual testing for Storybook components.
- [BackstopJS](https://github.com/garris/BackstopJS) - CSS regression testing using Puppeteer/Playwright.
- [Reg-suit](https://github.com/reg-viz/reg-suit) - Visual regression testing tool for any CI.
- [Loki](https://github.com/oblador/loki) - Visual regression testing for Storybook.
- [Wraith](https://github.com/BBC-News/wraith) - Screenshot comparison tool by BBC News.
- [GrabShot Action](https://github.com/aitaskorchestra/grabshot-action) - GitHub Action for visual regression testing with GrabShot API.

## PDF Generation

Convert web pages and HTML to PDF documents.

- [PDFMagic](https://pdf.grabshot.dev) - HTML-to-PDF API with custom headers/footers, margins, and formats.
- [Puppeteer PDF](https://pptr.dev/guides/pdf-generation) - Built-in PDF generation in Puppeteer.
- [wkhtmltopdf](https://github.com/wkhtmltopdf/wkhtmltopdf) - Convert HTML to PDF using WebKit.
- [WeasyPrint](https://github.com/Kozea/WeasyPrint) - Python library for HTML/CSS to PDF conversion.
- [Gotenberg](https://github.com/gotenberg/gotenberg) - Docker-powered API for converting documents to PDF.
- [DocRaptor](https://docraptor.com) - HTML-to-PDF API using PrinceXML engine.
- [PDFShift](https://pdfshift.io) - API for converting HTML documents to PDF.

## OG Image Generation

Generate Open Graph images dynamically for social sharing.

- [GrabShot OG](https://grabshot.dev) - Generate OG images from any URL or custom HTML template.
- [Vercel OG](https://vercel.com/docs/functions/og-image-generation) - Generate OG images at the edge with React components.
- [Satori](https://github.com/vercel/satori) - Convert JSX to SVG for OG image generation.
- [Cloudinary](https://cloudinary.com/documentation/social_media_overlays) - Dynamic image transformations including OG images.
- [imgix](https://imgix.com) - Real-time image processing with text overlay support.

## Browser Extensions

Screenshot tools for manual use.

- [GoFullPage](https://gofullpage.com) - Full page screen capture for Chrome.
- [Fireshot](https://getfireshot.com) - Full page screenshots with annotation.
- [Nimbus Screenshot](https://nimbusweb.me) - Screenshot and screencast tool.
- [Awesome Screenshot](https://www.awesomescreenshot.com) - Screenshot and annotation extension.

## CLI Tools

Command-line tools for screenshots.

- [shot-scraper](https://github.com/simonw/shot-scraper) - Playwright-based CLI for screenshots and scraping.
- [pageres-cli](https://github.com/sindresorhus/pageres-cli) - Capture website screenshots from the terminal.
- [webkit2png](https://github.com/paulhammond/webkit2png) - macOS command-line tool for website screenshots.
- [cutycapt](https://cutycapt.sourceforge.net) - Qt WebKit-based command-line screenshot tool.
- [grabshot-cli](https://www.npmjs.com/package/@grabshot/sdk) - Node.js SDK with CLI support for GrabShot API.

## SaaS Platforms

Full platforms for website monitoring and archiving with screenshot features.

- [Visualping](https://visualping.io) - Website change detection with visual comparisons.
- [ChangeTower](https://changetower.com) - Monitor web page changes with screenshots.
- [Hexowatch](https://hexowatch.com) - AI-powered website monitoring.
- [Stillio](https://stillio.com) - Automated website screenshot archiving.
- [Archive.org Wayback Machine](https://web.archive.org) - Historical snapshots of the entire web.

## Tutorials & Articles

Learn about web screenshots and automation.

- [Capturing Screenshots with Puppeteer](https://pptr.dev/guides/screenshots) - Official Puppeteer guide.
- [Playwright Screenshots](https://playwright.dev/docs/screenshots) - Official Playwright documentation.
- [How to Generate OG Images Automatically](https://blog.grabshot.dev/automated-og-images.html) - Tutorial using GrabShot API.
- [Best Screenshot API Comparison 2026](https://blog.grabshot.dev/best-screenshot-api-2026.html) - Detailed comparison of screenshot API services.
- [Visual Regression Testing Guide](https://blog.grabshot.dev/visual-regression-testing-api.html) - Setting up automated visual testing.
- [Building an OG Image Service](https://vercel.com/guides/introducing-vercel-og-image-generation) - Vercel's approach to OG images.

## Meta Extraction

Tools for extracting metadata, Open Graph tags, and structured data from URLs.

- [MetaPeek](https://metapeek.grabshot.dev) - API for extracting meta tags, OG data, and structured data from any URL.
- [Microlink](https://microlink.io) - Link preview and meta extraction API.
- [Open Graph Ninja](https://opengraph.ninja) - Free OG tag preview tool.
- [iframely](https://iframely.com) - oEmbed/Open Graph meta extraction service.

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
