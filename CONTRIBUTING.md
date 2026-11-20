# Contributing

Thanks for helping keep this list useful.

## What belongs here

- Resources directly about Cedar (language, engines, bindings, tools, articles, talks).
- Projects that are maintained or still clearly useful; articles and videos should be current enough to be accurate.
- Vendor-owned resources are fine if they are marked (e.g. *(Vendor.)*) and genuinely useful.

## Entry format

`- [Name](https://example.com) - Short description ending with a period.`

- Keep items alphabetical or logically ordered within their section, one resource per line.
- Use https links to the canonical page; no link shorteners or tracking parameters.
- Put each entry in the most fitting section.

## Pull request checklist

- [ ] Link works and goes to the canonical destination
- [ ] Entry follows the format above, with a description
- [ ] No duplicates
- [ ] Spelling checked

## Checking links

CI runs [lychee](https://github.com/lycheeverse/lychee) on every PR and weekly. Locally: `lychee --config lychee.toml README.md CONTRIBUTING.md`.
