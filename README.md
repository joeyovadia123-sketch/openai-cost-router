# openai-cost-router
openAI-compatible API that routes to cheaper SLMs with automatic GPT-4 fallback
# OpenAI Cost Router (Early Access)

Drop-in replacement for OpenAI Chat Completions.

### What it does
- Routes requests to cheaper SLMs (via NScale)
- Automatically falls back to GPT-4o on failure or timeout
- Fully OpenAI-compatible (swap `base_url`, keep your code)

### Why
Teams love GPT-4 quality but hate GPT-4 bills.

Early tests show **60–80% cost reduction** with no reliability loss.

### Example use cases
- AI SaaS products
- Chatbots & copilots
- Customer support automation
- Lead qualification bots

### Status
🚧 MVP in progress  
Looking for **early users running GPT-4 in production**.

### Early access
If you want to test this on a small % of traffic:
- DM me on LinkedIn
- Or email: yosefovadia123@gmail.com
