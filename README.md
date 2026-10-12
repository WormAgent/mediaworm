# 🪱 SocialWorm

**An open-source AI agent that manages your social media — with you in control.**

SocialWorm helps you plan content, write posts adapted to each platform, schedule them and learn what works. It drafts; you approve. Nothing gets published without your OK.

Part of the [<org>](https://github.com/<org>) family of open-source AI agents, alongside [WorkWorm](https://github.com/<org>/workworm), [InvestWorm](https://github.com/<org>/investworm) and [LoveWorm](https://github.com/<org>/loveworm).

---

## Features

- 🗓️ **Content planner** — builds a weekly content calendar from your goals and topics
- ✍️ **Post writer** — adapts one idea to each platform's format and tone (X, LinkedIn, Instagram…)
- ⏰ **Scheduler** — queues approved posts and publishes them at the best time
- 📈 **Analytics digest** — summarizes what performed well and suggests what to try next
- 💬 **Reply assistant** — drafts responses to comments and mentions for you to review
- 🔌 **Bring your own model** — works with <Claude / OpenAI / local models>

> 🚧 Early development. Some features may be in progress.

## Principles

- **Human in the loop.** Every post and reply needs your approval before it goes out.
- **Official APIs only.** SocialWorm uses each platform's official API. No scraping, no browser automation.
- **No fake engagement.** No bot likes, follows, fake accounts or spam. It helps you create better content, not game the algorithm.
- **Your data stays yours.** Tokens and content are stored locally.

## Quickstart

```bash
git clone https://github.com/<org>/socialworm.git
cd socialworm
pip install -r requirements.txt
cp .env.example .env   # add your API keys
python -m socialworm
```

## Configuration

| Variable | Description |
|---|---|
| `ANTHROPIC_API_KEY` | API key for the LLM provider |
| `<PLATFORM>_API_KEY` | API credentials for each connected platform |

## Roadmap

- [ ] Post writer (multi-platform)
- [ ] Content calendar
- [ ] Scheduler (LinkedIn, X)
- [ ] Analytics digest
- [ ] Web UI

## Contributing

Contributions are welcome! Open an issue to discuss what you'd like to change, or send a PR. See [CONTRIBUTING.md](https://github.com/<org>/.github/blob/main/CONTRIBUTING.md).

## License

[Apache-2.0](LICENSE)
