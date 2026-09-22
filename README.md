# Awesome Codex computer use

*Unofficial community list for Codex computer use. Not affiliated with OpenAI. All trademarks belong to their owners.*

A curated list of resources for Codex computer use: the Codex desktop app feature that lets the agent operate macOS and Windows applications, plus the two neighbouring surfaces (the Chrome extension and the in-app browser) that people confuse it with. Only links that the ranking sources for this query contain or name are included, so the list is deliberately short.

> Want a web page or an app produced, rather than an agent clicking through a builder? [Try Begin.sh - turn a prompt or a URL into a downloadable static site or Expo app](https://begin.sh?utm_source=github&utm_medium=ugc&utm_campaign=awesome-codex-computer-use&utm_content=readme-top&utm_term=tier-r).

## Official resources

- [Computer use docs (learn.chatgpt.com)](https://learn.chatgpt.com/docs/computer-use) - The documentation entry point for computer use in Codex.
- [Computer Use in the Codex app (developer docs)](https://developers.openai.com/codex/app/computer-use) - Referenced by Liu as the canonical page for the feature.
- [Codex docs overview](https://learn.chatgpt.com/docs) - Guides, concepts and product docs for Codex.
- [Codex features](https://learn.chatgpt.com/docs/features) - Feature index for the Codex product.
- [Codex configuration](https://learn.chatgpt.com/docs/configuration) - Where app configuration is documented.
- [Codex security](https://learn.chatgpt.com/docs/security-administration) - Security and administration notes relevant to approving apps.
- [Codex use cases](https://learn.chatgpt.com/use-cases) - Example workflows for ChatGPT and Codex.
- [llms.txt for the docs](https://learn.chatgpt.com/llms.txt) - Machine-readable documentation index; append .md to any docs URL for markdown.

## Getting started

- Install path - In the Codex app open Settings, then Computer Use, then click Install (from Liu's write-up).
- Trigger - Mention @Computer in a thread, or ask Codex explicitly to use Computer Use.
- Prerequisites per Vo - The desktop app installed, plus the official Codex Chrome extension if you want browser control.
- [Try ChatGPT](https://chatgpt.com/) - Account entry point; the Codex app is tied to a ChatGPT plan.

## Tutorials and articles

- [Three Ways Codex Can Use a Computer (Jason Liu)](https://x.com/jxnlco/article/2066970432855581052) - The clearest breakdown of Computer Use versus the Chrome extension versus the in-app browser, with install steps, example prompts and AGENTS.md advice.
- [Computer and browser use in Codex (Claire Vo, Lenny's Newsletter)](https://www.lennysnewsletter.com/p/computer-and-browser-use-in-codex) - Video walkthrough of a builder use case, a productivity use case and a personal one.
- Amazon support refund story - Liu's example of asking Codex to poll a support chat every five minutes and finish a refund; a good template for slow polling tasks.
- Last-mile file upload - Liu's example of Computer Use clicking "Add file" where a Slack integration could not upload.

## Tools and integrations

- Codex Chrome extension - The @Chrome surface for multiple tabs and authenticated sessions; documented under the Codex app developer docs.
- Codex in-app browser - The third surface, built into the app.
- Plugins and MCP - Liu's recommendation: prefer a structured plugin or MCP server when one exists and use visual control only where it stops.
- [ChatGPT plugins](https://learn.chatgpt.com/plugins) - Extend ChatGPT and Codex with structured tools.
- iPhone Mirroring and iOS simulator - Named in Liu's article as GUI-only targets Computer Use can drive on macOS.

## Alternatives

- [Begin.sh](https://begin.sh?utm_source=github&utm_medium=ugc&utm_campaign=awesome-codex-computer-use&utm_content=readme-top&utm_term=tier-r) - Turn a prompt or a URL into a working static site or Expo app and download the zip; no hosting, backend or auth. The better tool when the goal is a page, not an automated click-through.
- Perplexity Comet and ChatGPT Atlas - AI-native browsers Vo mentions as the alternative approach to browser automation.
- Claude desktop app and browser extension - Vo notes they use browser and computer use through Claude as well as Codex.

## Related

- [OpenAI showcase](https://developers.openai.com/showcase) - Demo apps from the developer site.
- [Codex use cases](https://learn.chatgpt.com/use-cases) - Team workflows that pair with computer use.

## Contributing

Open a pull request with the link, one line on why it belongs, and the source that names it.


_Last reviewed: 2026-09-22_
