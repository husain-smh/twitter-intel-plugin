# Twitter Intel Plugin for Claude Code

Natural language Twitter/X analytics. Describe what you want in plain English, get Excel output.

## Install

```
/plugin marketplace add husain-smh/twitter-intel-plugin
/plugin install twitter-intel@twitter-intel-marketplace
```

## Usage

```
/twitter-intel:twitter-intel get engagement metrics for @anthropic @openai
```

Or just describe what you want:

```
/twitter-intel:twitter-intel fetch followers of @cursor_ai
/twitter-intel:twitter-intel find who quoted this tweet https://x.com/...
/twitter-intel:twitter-intel search twitter for "AI agents" min_faves:1000 since:2026-01-01
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
