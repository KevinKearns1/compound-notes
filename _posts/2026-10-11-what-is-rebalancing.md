---
layout: post
title: "What Is Rebalancing, and How Often Should You Actually Do It?"
date: 2026-10-11
description: >-
  I've mentioned rebalancing in two posts now as something you
  either do yourself or a target-date fund does for you, without
  ever explaining the actual mechanism. Here's what it is, worked
  through with a real drift example.
tags: [fundamentals, retirement]
reading_time: 6
cover: /assets/images/covers/rebalancing.svg
image: /assets/images/covers/rebalancing.png
cover_alt: "A tilted scale being nudged back level by a hand adjusting weights on each side, illustrating rebalancing a portfolio back to its target allocation"
related: [stocks-vs-bonds-by-age, what-is-a-target-date-fund, what-is-diversification, what-is-a-brokerage-account]
---

I've mentioned rebalancing in both the [stock-vs-bond allocation post]({{ '/stocks-vs-bonds-by-age/' | relative_url }}) and the [target-date fund post]({{ '/what-is-a-target-date-fund/' | relative_url }}) as something you either do yourself or a fund does automatically on your behalf, without ever explaining what it actually is or why it matters enough to build entire funds around doing it for you.

## The one-sentence version

Rebalancing means periodically buying and selling within your portfolio to bring your stock-to-bond (or other asset) mix back to your original target percentages, because different investments grow at different rates and will drift away from your intended allocation if left alone.

<!--more-->

## Why a portfolio drifts on its own, even if you never touch it

Say you start with a [diversified]({{ '/what-is-diversification/' | relative_url }}) portfolio at 80% stocks, 20% bonds. Stocks and bonds don't grow at the same rate — over any given stretch, stocks tend to grow faster (with more volatility), bonds slower (with more stability). Here's that same 80/20 split, $10,000 total, after 10 years of stocks growing at 10%/year and bonds at 3%/year, with no rebalancing at all:

| | Starting mix | After 10 years, untouched |
|---|---|---|
| Stocks | 80% ($8,000) | **88.5%** ($20,750) |
| Bonds | 20% ($2,000) | **11.5%** ($2,688) |

Nobody made a decision to get more aggressive. The portfolio just drifted there, because the faster-growing asset naturally becomes a bigger share of the total over time. By year 10, this portfolio is meaningfully riskier than the person originally chose — not because their risk tolerance changed, but because nobody corrected for the drift.

## What rebalancing actually does about it

Rebalancing means periodically selling some of what's grown into an oversized share and buying more of what's shrunk, to get back to the original target. In the example above, rebalancing back to 80/20 means selling some stocks and buying more bonds — which sounds backwards ("sell the thing that's doing well?") until you remember the entire point of choosing a mix in the first place: matching your risk level to your actual time horizon and tolerance, not chasing whatever's currently performing best.

This is also, not incidentally, a disciplined version of "buy low, sell high" — rebalancing systematically trims the asset that's gotten relatively expensive (by having grown more) and adds to the one that's relatively cheaper, without requiring you to predict anything about where either is headed next.

## How often to actually do it

There's no single correct schedule, but two common approaches cover most of what people actually do:

- **Calendar-based**: rebalance on a fixed schedule — once a year is common, since it's infrequent enough to avoid overreacting to short-term swings and frequent enough to keep the drift from compounding into something significant.
- **Threshold-based**: rebalance whenever an allocation drifts more than a set amount from its target — for example, whenever stocks drift more than 5 percentage points off target, regardless of how much time has passed.

Either approach beats no plan at all, which is really the actual failure mode: not picking the wrong schedule, but never checking and letting a portfolio drift for a decade, the way the example above shows happening by default.

## Why rebalancing too often is also a mistake

More frequent isn't better here. Rebalancing has real costs — in a [taxable brokerage account]({{ '/what-is-a-brokerage-account/' | relative_url }}), selling an appreciated investment to rebalance can trigger [capital gains tax]({{ '/capital-gains-tax-explained/' | relative_url }}), and frequent trading can rack up transaction costs depending on the brokerage. Rebalancing monthly chases noise, not drift — most of a portfolio's month-to-month movement is random fluctuation, not a meaningful shift in allocation, and reacting to it constantly mostly just adds cost and complexity without a real benefit.

**Rebalancing inside a retirement account (a [Roth or Traditional IRA]({{ '/traditional-vs-roth-ira/' | relative_url }}) or 401(k)) avoids the tax problem entirely** — buying and selling inside these accounts doesn't trigger capital gains tax the way it does in a taxable account, which is part of why rebalancing is specifically easier and cheaper to do inside a retirement account than a regular brokerage account holding the same investments.

## Why this is exactly what a target-date fund automates

This entire post describes the mechanism [target-date funds]({{ '/what-is-a-target-date-fund/' | relative_url }}) run automatically and invisibly — the fund rebalances its own internal mix on an ongoing basis so you never have to check a calendar or calculate a drift percentage yourself. Choosing a target-date fund over a DIY two-fund approach is, in large part, choosing to pay a (hopefully small) fee specifically to never have to think about any of the above.

## The takeaway

A portfolio that's never rebalanced doesn't stay the way you set it — it drifts toward whatever's grown the most, quietly becoming riskier or more conservative than you actually chose. Rebalancing isn't a complicated strategy, it's routine maintenance: pick a schedule or a drift threshold, stick to it, and do it inside a tax-advantaged account when you can to avoid triggering unnecessary tax along the way.
