# Submission Guide

Instructions for submitting this application to Superteam Earn.

## Listing Details

| Field | Value |
|-------|-------|
| **Title** | Content Creator - Ambassador |
| **Slug** | `nolus-amb` |
| **Listing ID** | `1d037c64-11fc-47de-a8d0-cc722618d07b` |
| **Type** | Project |
| **Sponsor** | Nolus Protocol |
| **Deadline** | 2026-07-09T20:59:59.000Z |
| **Compensation** | Variable (monthly USDC) |
| **POC** | Antonios P ([@tonyler_](https://superteam.fun/earn/t/tonyler_)) — Telegram: [@tonyler](https://t.me/tonyler) |
| **Listing URL** | https://superteam.fun/earn/listing/nolus-amb |

---

## Repository Link (Submission)

```
https://github.com/mykcryptodev/earn-nolus-amb-content-creator-ambassador
```

---

## Agent API Submission

For agent-assisted submissions via the [Superteam Earn Agent API](https://superteam.fun/earn/agents/):

```bash
curl -s -X POST "https://superteam.fun/api/agents/submissions/create" \
  -H "Authorization: Bearer $AGENT_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "listingId": "1d037c64-11fc-47de-a8d0-cc722618d07b",
    "link": "https://github.com/mykcryptodev/earn-nolus-amb-content-creator-ambassador",
    "otherInfo": "Complete ambassador application package: eligibility answers, 30-day content plan, messaging framework, and publish-ready samples for X (thread + 8 standalone posts), Reddit (long-form comparison), and YouTube (90-second explainer script). All content explains Nolus DeFi Lease mechanics accurately — asset-backed leverage, fixed protocol interest, partial liquidations, IBC cross-chain — without hype.",
    "eligibilityAnswers": [
      {
        "question": "Where are you most active and influential (X, Reddit, Telegram/Discord, YouTube, etc.)?",
        "answer": "Primary: X and GitHub (DeFi explainers, Superteam Earn proof of work). Secondary: Reddit (r/solana, r/defi), Discord/Telegram in Solana builder communities. Growing: YouTube short-form explainers. Full details in application/eligibility-answers.md."
      },
      {
        "question": "How large is your reach or presence in those spaces?",
        "answer": "GitHub: 120+ public repos. Superteam Earn: multiple content/dev submissions. X: growing DeFi audience with educational threads targeting 1k+ impressions per post. Building toward 5k+ followers through consistent Nolus/Solana content. Metrics in application/eligibility-answers.md."
      },
      {
        "question": "Are you recognized or trusted in the communities you'\''re part of? Why?",
        "answer": "Trusted through verifiable delivery: public Superteam Earn repos, technical onchain projects (Base/Solana), and accurate DeFi education without hype. Community engagement via substantive Q&A in Discord/Telegram."
      },
      {
        "question": "How comfortable are you naturally bringing up and talking about a project there (the communities you'\''re active in)?",
        "answer": "Very comfortable when the product has real differentiation — Nolus does (asset-backed spot margin, fixed rates, IBC, partial liquidations). I introduce it in context when users ask about leverage alternatives, cross-chain DeFi, or capital efficiency. Educator-first tone per strategy/messaging-framework.md."
      },
      {
        "question": "Share any relevant links to your profiles, posts, or communities.",
        "answer": "GitHub: https://github.com/mykcryptodev | Submission repo: https://github.com/mykcryptodev/earn-nolus-amb-content-creator-ambassador | Sample content: content/x/, content/reddit/, content/youtube/ | Strategy: strategy/30-day-content-plan.md"
      }
    ],
    "ask": 1000,
    "telegram": "http://t.me/YOUR_TELEGRAM_USERNAME"
  }'
```

**Before submitting:**

1. Replace `$AGENT_API_KEY` with your registered agent API key
2. Replace `http://t.me/YOUR_TELEGRAM_USERNAME` with the human operator's Telegram URL (required for project listings)
3. Adjust `ask` (monthly compensation ask in USDC) as needed — default in application is $800–1,200/month

---

## Manual Submission (Human)

1. Go to https://superteam.fun/earn/listing/nolus-amb
2. Click **Apply Now**
3. Paste repository link: `https://github.com/mykcryptodev/earn-nolus-amb-content-creator-ambassador`
4. Copy answers from [`application/eligibility-answers.md`](application/eligibility-answers.md)
5. Include monthly compensation ask
6. Add links to strongest content samples (X thread, Reddit post, YouTube script)

---

## Claim Flow (After Selection)

If submitted via agent API:

1. Human operator visits `https://superteam.fun/earn/claim/<claimCode>`
2. Completes talent profile
3. Links agent submissions for payout eligibility

---

## Pre-Submission Checklist

- [x] Eligibility questions answered (`application/eligibility-answers.md`)
- [x] X thread ready (`content/x/thread-defi-lease-explainer.md`)
- [x] Standalone X posts ready (`content/x/standalone-posts.md`)
- [x] Reddit post ready (`content/reddit/nolus-spot-margin-vs-perps.md`)
- [x] YouTube script ready (`content/youtube/defi-lease-in-90-seconds.md`)
- [x] 30-day content plan (`strategy/30-day-content-plan.md`)
- [x] Messaging framework (`strategy/messaging-framework.md`)
- [ ] Human Telegram URL added to API submission
- [ ] Compensation ask confirmed with operator
- [ ] Optional: publish 1–2 sample posts live before applying (strengthens proof of work)
