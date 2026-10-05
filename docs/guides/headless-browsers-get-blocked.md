# Why a headless browser gets a 403

Same machine, same cookies, wildly different result. Why headless Chromium gets refused where a real browser sails through — and what that means.

**Canonical page:** [https://askfinz.com/guides/headless-browsers-get-blocked](https://askfinz.com/guides/headless-browsers-get-blocked)

## Key points

### What actually gets checked

A "headless browser" is a real browser engine — Chromium, usually — running without a visible window, driven by code instead of a person clicking around. It executes JavaScript, renders pages, and can look almost identical to an ordinary visit at the network level.

### Why this happens before anything else

The important detail is the ordering. It's tempting to think of a block as the last line of defence — a check that happens after the site has looked at what you're asking for and decided you're not welcome.

### What doesn't fix it

A lot of the usual advice — rotate your headers, spoof a user-agent string, add a random delay between requests — treats the symptom rather than the cause.

### What actually works

A real browser gets the page. That's the whole answer, unglamorous as it is.

### More on this kind of work

Same cluster first, so the next page carries on from where this one stops.

### Put this to work

See how askFinz fits the way you already work, then ask for access.

## Related

- [AI guides: workspaces, search, agents and models](https://askfinz.com/guides)
- [Crawling vs indexing vs scraping](https://askfinz.com/guides/crawling-vs-indexing-vs-scraping)
- [How to get your site indexed by AI search](https://askfinz.com/guides/get-my-site-indexed-by-ai)
- [How a search index is actually built](https://askfinz.com/guides/how-a-search-index-is-built)
- [How AI search actually finds an answer](https://askfinz.com/guides/how-ai-search-finds-answers)
- [What web data actually costs](https://askfinz.com/guides/how-much-does-web-data-cost)

---

Summary of [https://askfinz.com/guides/headless-browsers-get-blocked](https://askfinz.com/guides/headless-browsers-get-blocked), generated from the page itself. The page is the source of truth. Contact: hello@askfinz.com
