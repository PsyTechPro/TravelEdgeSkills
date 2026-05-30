# TravelEdgeSkills ✈️

> The travel knowledge that frequent flyers, points hobbyists, and airline insiders keep to themselves. Now available as AI agent skills for everyone.

Most people leave **thousands of dollars in free travel** on the table every year because nobody told them how it works.

TravelEdgeSkills gives your AI agent the deep, specific knowledge of a 10-year points obsessive so you can fly business class on economy budgets, get hotel suite upgrades, find mistake fares, and build a credit card strategy that actually works.

---

## What Are Skills?

Skills are markdown files that give AI agents specialized knowledge and step-by-step workflows for specific tasks. When you add these to your setup, your AI assistant can recognize travel hacking tasks and apply expert-level frameworks and real strategies — not generic advice.

---

## Available Skills

| Skill | What It Does |
|-------|-------------|
| [flight-award-finder](skills/flight-award-finder.md) | Find the best award flights using your points — specific routes, programs, and sweet spots most people never discover |
| [credit-card-strategist](skills/credit-card-strategist.md) | Build the optimal card stack, evaluate signup bonuses, know exactly which cards to get and when |
| [hotel-hacker](skills/hotel-hacker.md) | Get free suite upgrades, free nights, and the perks you're entitled to but never claim |
| [points-valuator](skills/points-valuator.md) | Know exactly what your points are worth in dollars and whether any redemption is brilliant or terrible |
| [mistake-fare-hunter](skills/mistake-fare-hunter.md) | Find and book mistake fares and flash sales — business class for economy prices |
| [airport-hacker](skills/airport-hacker.md) | Access lounges, get TSA PreCheck and Global Entry free, and move through airports like a pro |
| [travel-card-optimizer](skills/travel-card-optimizer.md) | Know exactly which card to swipe for every purchase to maximize points earning |
| [points-transfer-optimizer](skills/points-transfer-optimizer.md) | Transfer points to the right partner for your specific route — and avoid the transfers that destroy value |

---

## Installation

### Option 1: CLI Install (Recommended — works in 60 seconds)

```bash
# Install all 8 skills globally
npx skills add TravelEdgeSkills -g -y

# Or install to current project only
npx skills add TravelEdgeSkills -y

# List installed skills
npx skills list
```

### Option 2: Manual Install for Claude.ai

1. Download the `.md` files from the `/skills` folder above
2. Go to [claude.ai](https://claude.ai) on your laptop
3. Click **Customize** at the top left
4. Click **Skills**
5. Click the **+** icon to add a new skill
6. Upload the `.md` file
7. Click **Save**

Repeat for each skill you want. Done — no code required.

### Option 3: Direct Download

Download individual skill files from the `/skills` directory and add them to your AI agent's skills folder.

---

## Supported AI Agents

These skills work with any AI agent that supports markdown skill files:

- **Claude** (claude.ai — no code required)
- **Claude Code** (CLI)
- **Cursor** (IDE)
- **Windsurf**
- **Gemini CLI**
- **Copilot**
- **Codex**
- And 30+ others

---

## Usage Examples

Once installed, just ask your AI assistant naturally:

```
"I have 80,000 Chase points. I want to fly business class to Paris. What's my best move?"
→ Uses flight-award-finder + points-transfer-optimizer

"Which credit card should I get next for travel?"
→ Uses credit-card-strategist

"I'm checking into a Hyatt tomorrow. What upgrades am I entitled to?"
→ Uses hotel-hacker

"Is 60,000 miles for this flight a good deal?"
→ Uses points-valuator

"How do I get into the lounge at JFK without paying?"
→ Uses airport-hacker

"Should I put my groceries on my Amex Gold or Chase Sapphire?"
→ Uses travel-card-optimizer

"I'm seeing a business class flight to Tokyo for $900. Is that real? Should I book it?"
→ Uses mistake-fare-hunter
```

---

## Why This Exists

The travel hacking world is deliberately obscure. Points bloggers bury the best information behind affiliate links. Airlines make their programs confusing on purpose. Credit card companies don't explain how to actually maximize what you're earning.

The result: people who know the system fly business class for free while everyone else pays full price for economy.

TravelEdgeSkills puts that knowledge directly into your AI assistant — specific, actionable, and without the affiliate agenda.

---

## Real Results This Knowledge Unlocks

- ✈️ Business class to Europe: 45,000 points instead of $3,000+ cash
- 🏨 Suite upgrades at luxury hotels just by knowing what to say at check-in
- 💳 $1,000-2,000 extra in travel value annually from optimizing everyday spending
- 🎫 TSA PreCheck + Global Entry: $0 instead of $100+ (credit card reimbursement)
- 🛋️ Lounge access at 1,400+ airports worldwide: $0 instead of $50-80/visit
- ✈️ ANA First Class Tokyo round trip: 75,000 Amex points instead of $10,000+ cash

---

## Contributing

Have a strategy, sweet spot, or hack that belongs here? PRs and issues welcome.

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## License

MIT License — use these skills however you want.

See [LICENSE](LICENSE) for details.

---

*Built for people who believe business class shouldn't be a luxury reserved for the wealthy. Just for the informed.*
