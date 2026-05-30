# Points Valuator

## Purpose
Tell users the real-world value of their points and miles in plain dollars, whether a redemption is good or terrible, and what the smartest use of their current stash is right now.

## Trigger Phrases
- "Are my points worth redeeming for this?"
- "How much are my [airline/hotel/bank] points worth?"
- "Is [X] points for [Y flight/hotel] a good deal?"
- "Should I transfer my points to [program]?"
- "I have [X] points — what can I get?"
- "Should I use points or pay cash?"

## Current Point Valuations (Cents Per Point)

### Bank Points (Most Flexible)
| Program | Conservative | Optimal Transfer |
|---------|-------------|-----------------|
| Chase Ultimate Rewards | 1.5¢ | 1.8-2.2¢ |
| Amex Membership Rewards | 1.4¢ | 1.8-2.2¢ |
| Citi ThankYou Points | 1.3¢ | 1.6-1.9¢ |
| Capital One Miles | 1.0¢ | 1.4-1.7¢ |
| Bilt Rewards | 1.5¢ | 1.8-2.2¢ |

### Airline Miles
| Program | Conservative | Sweet Spot |
|---------|-------------|------------|
| ANA Mileage Club | 1.5¢ | 3.5-5.0¢ (first class) |
| Air Canada Aeroplan | 1.4¢ | 2.5-3.5¢ |
| Turkish Miles&Smiles | 1.3¢ | 2.5-4.0¢ |
| Alaska Mileage Plan | 1.3¢ | 2.0-3.0¢ |
| United MileagePlus | 1.2¢ | 1.8-2.5¢ |
| American AAdvantage | 1.2¢ | 1.8-2.5¢ |
| British Airways Avios | 1.2¢ | 1.5-3.0¢ (short-haul) |
| Air France Flying Blue | 1.1¢ | 1.6-2.5¢ |
| Delta SkyMiles | 0.9¢ | 1.0-1.5¢ |
| Southwest Rapid Rewards | 1.4¢ | 1.4¢ (fixed) |

### Hotel Points
| Program | Conservative | Sweet Spot |
|---------|-------------|------------|
| World of Hyatt | 1.7¢ | 2.0-3.0¢ |
| IHG One Rewards | 0.6¢ | 0.8-1.2¢ |
| Marriott Bonvoy | 0.7¢ | 0.9-1.5¢ |
| Hilton Honors | 0.4¢ | 0.5-0.8¢ |
| Wyndham Rewards | 0.9¢ | 1.0-1.3¢ |

## The Redemption Evaluation Formula

When a user presents a specific redemption, calculate:

**Step 1:** Find cash price of the same flight/hotel
**Step 2:** Divide cash price by points required × 100 = cents per point (CPP)
**Step 3:** Compare to program benchmark above

**Example:**
- Business class flight: $3,200 cash
- Award cost: 65,000 Aeroplan miles
- CPP = ($3,200 / 65,000) × 100 = **4.9¢ per point — EXCEPTIONAL, book immediately**

**Example (bad redemption):**
- Economy flight: $280 cash
- Award cost: 25,000 Delta SkyMiles
- CPP = ($280 / 25,000) × 100 = **1.1¢ per point — POOR, pay cash instead**

## Verdict Framework

| CPP Achieved | Verdict | Recommendation |
|-------------|---------|----------------|
| 4¢+ | 🏆 Exceptional | Book immediately |
| 2.5-4¢ | ✅ Excellent | Strong yes |
| 1.8-2.5¢ | 👍 Good | Yes, solid use |
| 1.2-1.8¢ | 😐 Average | Acceptable |
| 0.8-1.2¢ | ⚠️ Below average | Consider paying cash |
| Under 0.8¢ | ❌ Poor | Pay cash, save points |

## The "Pay Cash or Points?" Decision Tree

**Use points when:**
- CPP achieved is above 1.5¢ for economy
- CPP achieved is above 2.0¢ for business/first class
- You're booking premium cabins (points discount is proportionally massive)
- You have more points than upcoming travel needs (risk of devaluation)
- Cash price is high (holiday travel, peak season)

**Pay cash when:**
- CPP achieved is below 1.2¢
- Economy flight under $200 (rarely worth burning points)
- You're close to earning status and need paid ticket to qualify
- Cash price is unusually low (mistake fare, sale)
- Points toward a specific redemption goal are nearly complete

## Transfer Bonus Opportunities

Banks periodically offer transfer bonuses (25-50% extra points when transferring):
- Amex frequently runs 25-40% bonuses to select partners
- Citi occasionally offers bonuses to Flying Blue, Avianca
- These turn already-good redemptions into exceptional ones

**Rule:** Never transfer points speculatively without a specific booking in mind. Points in a bank account are more flexible than in an airline account.

## Portfolio Assessment

When a user shares all their points, provide:

```
YOUR POINTS PORTFOLIO ASSESSMENT:

Chase Ultimate Rewards: [X] points = ~$[value at 1.9¢]
Amex MR: [X] points = ~$[value at 1.9¢]
[Airline]: [X] miles = ~$[value]
[Hotel]: [X] points = ~$[value]

TOTAL ESTIMATED VALUE: $[X]

BEST REDEMPTION OPPORTUNITIES RIGHT NOW:
1. [Specific redemption based on their stash]
2. [Second option]
3. [Third option]

CONSOLIDATION RECOMMENDATION:
[Whether to transfer, combine, or keep separate]

EARNING GAPS:
[What cards/programs would boost their portfolio]
```

## Devaluation Risk Assessment

Points are a depreciating currency. Assess risk:

**High devaluation risk (use sooner):**
- Delta SkyMiles (already dynamic, unpredictable)
- Marriott Bonvoy (has devalued repeatedly)
- Hilton Honors (already low value)

**Medium risk:**
- United MileagePlus
- American AAdvantage

**Lower risk (but no guarantee):**
- World of Hyatt (devalued rarely, communicates changes)
- Air Canada Aeroplan
- Chase/Amex bank points (flexibility protects them)

**Rule of thumb:** Don't hoard points for more than 18-24 months without a redemption plan.
