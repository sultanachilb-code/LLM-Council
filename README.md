# ⚖️ LLM Council — 100% Free

> Five real AIs. One key. Zero cost.

## The Council (All Free Models)

| Member | Model | Role |
|--------|-------|------|
| 🟢 Llama 4 Maverick | Meta via OpenRouter | The Analyst |
| 🟠 Gemma 3 27B | Google via OpenRouter | The Philosopher |
| 🟣 Mistral Small 3.1 | Mistral via OpenRouter | Devil's Advocate |
| 🔵 DeepSeek V3 | DeepSeek via OpenRouter | The Researcher |
| 🟡 Gemini 2.5 Pro Exp | Google via OpenRouter | The Pragmatist |

## What It Costs

**$0.** All models use the `:free` suffix on OpenRouter.

OpenRouter free tier limits:
- 50 requests/day
- 20 requests/minute
- No credit card required

One full council session uses ~12–15 API calls (5 opening + 5 challenge + 5 scoring + 1 verdict).
That's roughly **3–4 full sessions per day** on the free tier.

## Deploy to GitHub Pages

1. Create a new **public** GitHub repo (e.g. `llm-council`)
2. Upload `index.html` to the root
3. Go to **Settings → Pages → Branch: main → Save**
4. Live at: `https://your-username.github.io/llm-council/`

## Get Your Free OpenRouter Key

1. Go to [openrouter.ai](https://openrouter.ai)
2. Sign up (email only, no credit card)
3. Go to **Keys → Create Key**
4. Copy your `sk-or-v1-...` key
5. Paste it into the Council setup screen

## Council Flow

```
📋 Opening Statements  →  ⚔️ Cross-Examination  →  🗳️ Scoring Round  →  ⚖️ Verdict
```

1. **Opening Statements** — All 5 models answer in parallel
2. **Cross-Examination** — Each model challenges the next one's position  
3. **Scoring Round** — Each model scores all others 1–10
4. **Verdict** — Synthesized final answer + winner by total score
