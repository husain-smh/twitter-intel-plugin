# TwitterAPI Scraping Plugin for Claude Code

Natural language Twitter/X analytics. Describe what you want in plain English, get Excel output.

## Install

```
/plugin marketplace add husain-smh/twitter-intel-plugin
/plugin install twitterapi@twitter-intel-marketplace
```

## Usage

```
/twitterapi:scraping get engagement metrics for @anthropic @openai
/twitterapi:scraping fetch followers of @cursor_ai
/twitterapi:scraping find who quoted this tweet https://x.com/...
/twitterapi:scraping search twitter for "AI agents" min_faves:1000 since:2026-01-01
```

## What it can do

- **Engagement metrics** — avg/median views, likes, RTs for any list of accounts
- **Profile reports** — full profile info + engagement + content mix
- **Fetch followers/followings** — export all followers of any account
- **Tweet metrics** — stats for specific tweet URLs
- **Quote tweeters** — find everyone who quoted a tweet + their engagement
- **Advanced search** — search Twitter with any query, export results
- **Viral discovery** — find viral creators in any topic over time

## Safety

- Shows estimated cost before running
- Phase 0 recon for expensive operations
- $5 hard cap with runtime cost guard
- Shows actual cost after every run

## First Run

On first use, it will ask for your Twitter API key and install dependencies automatically.
