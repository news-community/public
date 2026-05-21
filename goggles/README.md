# Brave Search Goggles

[Goggles](https://search.brave.com/help/goggles) are user-defined ranking algorithms for [Brave Search](https://search.brave.com). Any Brave Search user can adopt a Goggle to re-rank their results.

## Available Goggles

### `alaska-local-news.goggle`

Re-ranks Brave Search results to prioritize independent Alaska newsrooms. Up-ranks Alaska-based publishers covering state government, energy, fisheries, wildlife, education, and rural Alaska. Down-ranks generic out-of-state news aggregators that re-syndicate Alaska coverage without original reporting.

**Adopt this Goggle in Brave Search:**

Use the raw URL of the file in this repo:

```
https://raw.githubusercontent.com/news-community/public/main/goggles/alaska-local-news.goggle
```

Paste it into Brave Search's "Goggles" picker, or submit it to the [Brave Search Goggles Directory](https://search.brave.com/help/goggles).

## Contributing

The Goggle file is just text — open a PR to add a publisher, adjust a boost, or remove an entry. Each line is a single rule:

```
$boost=N,site=example.com   # up-rank example.com by N (1–10)
$discard,site=example.com   # remove example.com from results
```

See [Brave's Goggle DSL reference](https://github.com/brave/goggles-quickstart) for the full grammar.
