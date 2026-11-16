# ClosetCast by StyleCast

**[Try the interactive prototype](https://adharshusa.github.io/closetcast/)**: a rule-based demo with preset weather scenarios, not live forecasts.

**Know what to wear from the clothes you already own, based on the weather and how you feel in it.**

Group project for **IE 590 Technical Product Management** (Purdue, Fall 2026), taken through three stages: market study, business case, and an engineering handoff with a launch plan. ClosetCast is a concept app. Every forward-looking figure below is a planning assumption, not a measured result. Team: Ranganath Ravichandran, Ritu Munshi, Prerana Rajeshvar Kharat, Tsu-Chieh Weng and Adharsh Rajasekar.

## The product

Weather apps say "38°F and windy" and closet apps organize clothes, but neither learns how each person actually feels in the weather. ClosetCast picks today's outfit from the user's own wardrobe and adapts to comfort feedback.

1. **Build the closet:** start with 10 everyday pieces
2. **Read the day:** temperature, rain, snow, wind and occasion
3. **Get the outfit:** ranked combinations from owned clothes, each with a reason
4. **Rate the comfort:** too warm, too cold or not my style, and the next suggestion adapts

Free tier: a daily suggestion and basic feedback. Premium ($39.99 per year or $3.99 per month): comfort history, rediscovery of seldom-worn items and seasonal planning.

## What the case recommends

The base case does not pay back, so the recommendation is a staged decision, not a launch.

- **Ask:** approve an eight-week, 100-user pilot for $25K, stage one of a $100K development estimate, and hold the other $75K
- **Base case (planning assumptions):** five-year NPV of about -$1.02M at a 15% discount rate, cumulative operating profit of about -$1.42M, and no full payback in 2027 to 2031
- **Sensitivity:** even the upside case (8% conversion, 90% retention) stays loss-making over five years
- **What would have to be true:** a different economic model, through more volume, a leaner fixed-cost base or higher monetization. The pilot is designed to test willingness to pay, retention and real operating cost first.

### The four pilot gates

| Gate | Measure | Pass threshold |
|---|---|---|
| Setup | Enrolled users who save 10 eligible items within 7 days | 60% or more |
| Return | Enrolled users active on days 22 to 28 | 35% or more |
| Paid demand | Users completing a real paid web purchase by day 28 | 5% or more |
| Comfort lift | "Comfortable" rating rate, personalization minus weather-only (users randomized 1:1) | 10 percentage points or more |

Remaining funding is released only if the gates pass and a revised model shows a positive NPV and a credible cash payback.

## What is in the work

| Stage | Contents |
|---|---|
| Market study | Target segments (students 18 to 30, commuters 30 to 45), three personas, TAM and SAM sizing, competitor positioning against weather apps, closet apps and general AI chatbots |
| Business case | Five-year forecast, unit economics ($28 contribution per paid unit), NPV, ROI, breakeven, sensitivity analysis, FMEA-style risk scoring (probability x impact x detectability), and the staged funding request |
| Engineering handoff | Product charter, functional and technical requirements with acceptance checks, privacy and billing checklist, IP protection by asset, legal and release requirements, acquisition channels, pilot roadmap, and product and commercial metrics |

## Interactive prototype

A single-page HTML prototype demonstrates the core loop. It uses simulated weather and **explainable rules, not a trained model**: it scores wardrobe combinations against an effective temperature (adjusted for wind and the user's comfort setting), penalizes missing waterproofing in rain or snow, respects smart-casual versus casual occasions, and shifts future picks based on comfort feedback. Data stays in the browser, and there is no account sync, live forecast or payment. Garment images are AI-generated illustrations.

## Skills demonstrated

Product requirements and acceptance criteria, pilot and experiment design (gates, randomization, cohort definitions), market sizing, unit economics and NPV modeling, sensitivity and risk analysis, privacy-by-design and compliance planning, and go-to-market sequencing.

## Note

These are course deliverables for a concept product. Market, cost and conversion figures are team assumptions, benchmarked against public sources where cited in the documents, and nothing here reflects a launched product.
