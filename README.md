# News Community

Building decentralized, transparent community newsrooms where AI handles the structural work and humans bring the judgment.

The platform is live at **[alaskanews.news](https://alaskanews.news)**.

This repo is the public-facing surface for the project. The platform code itself is private, but stars, general issues, feature requests, and contributions to any open-sourced pieces all land here.

## What is News Community

Over 1,800 counties in America have zero local news. Public meetings happen, decisions get made, and nobody covers them because nobody can afford to. The legacy media cost structure does not work at the grain of a borough assembly meeting in Cordova or a school board hearing in Nome.

News Community is a different cost structure. LLMs do the structural work that used to need a reporter at every meeting (transcribing audio, surfacing patterns, drafting against a verified evidence pool). A small editorial team, supplemented by community contributors, does the judgment work. The result is more coverage of more meetings, with the same standards of accuracy and attribution as legacy journalism, at a cost that actually closes for towns that legacy media abandoned.

Live in Alaska today. Designed to expand to any community that wants it.

## How to participate

**Read the news for free at [alaskanews.news](https://alaskanews.news).** No paywall, no signup required to read, ever. If you want to follow specific topics, locations, or speakers, [create a free account](https://alaskanews.news/signup).

### Become a citizen journalist

If you know your community and want to cover the meetings, decisions, and stories that matter, write for News Community. You work from AI-generated transcripts and drafts, get peer reviewed by your community, and earn credits when readers value your work.

[**Become a journalist**](https://alaskanews.news/journalist)

### Become a compute volunteer

The platform processes audio and video from public meetings on volunteer computers running our desktop app. If you have a Mac or PC that's online a lot and you want to help cover meetings without writing a word, this is the path.

[**Apply to be a compute volunteer**](https://alaskanews.news/worker/apply)

### Support journalists with credits

Reader credits flow directly to the journalists whose work you value. No subscription required to read, but if you want to support local coverage, credits are how that happens.

Sign up at [alaskanews.news/signup](https://alaskanews.news/signup) and click any author's photo to send credits.

## Issues, feedback, feature requests

If you find a bug, have a feature idea, or want to flag something about the platform: [**open an issue here**](https://github.com/news-community/public/issues/new).

This is the public-facing repo for project-level feedback. Code-specific issues from internal collaborators go to the private platform repo; everything else lands here.

## Following the project

- **[News Community newsroom](https://alaskanews.news)** — the platform itself
- **[About the project](https://alaskanews.news/about)** — vision, principles, who we are
- **[How it works](https://alaskanews.news/how-it-works)** — what happens between a meeting and an article

## Repo structure

The News Community project spans four GitHub repos:

| Repo | Visibility | Purpose |
|------|------------|---------|
| [`news-community/news-community`](https://github.com/news-community/news-community) | private | Umbrella repo, ties the components together via git submodules |
| [`news-community/platform`](https://github.com/news-community/platform) | private | The platform code (Next.js + Supabase + Effect web app, pipeline worker, Electron compute-volunteer app) |
| [`news-community/openclaw`](https://github.com/news-community/openclaw) | private | An agent built for the project (TBD) |
| `news-community/public` (this repo) | **public** | Public-facing surface: stars, general issues, any open-sourced pieces extracted from the platform |

The platform code itself is closed-source today. Some pieces may be extracted to this repo as open-source down the road; that's deferred for now.

## Contact

- **Apply as a journalist:** [alaskanews.news/journalist](https://alaskanews.news/journalist)
- **Apply as a compute volunteer:** [alaskanews.news/worker/apply](https://alaskanews.news/worker/apply)
- **General contact:** [alaskanews.news/contact](https://alaskanews.news/contact)

Built by [Geeks in the Woods](https://geeksinthewoods.com) in Anchorage, Alaska. Humans and AI agents alike welcome.

## License

License terms TBD per any pieces extracted to this public repo. The platform code itself is closed-source.
