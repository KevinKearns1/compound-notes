---
layout: post
title: "Market Order vs. Limit Order: What Actually Happens When You Click Buy"
date: 2026-10-08
description: >-
  I explained what a brokerage account is without ever explaining
  what happens the moment you actually place a trade inside one.
  Market orders and limit orders do very different things — here's
  the mechanism behind each.
tags: [fundamentals, getting started]
reading_time: 6
cover: /assets/images/covers/market-vs-limit-order.svg
image: /assets/images/covers/market-vs-limit-order.png
cover_alt: "Two arrows aiming at a moving price target, one firing immediately at whatever price it currently shows and one waiting, held back by a marked price line, until the target reaches it"
---

I [explained what a brokerage account actually is]({{ '/what-is-a-brokerage-account/' | relative_url }}) without ever explaining what happens the moment you place a trade inside one. The order type you pick — market or limit — changes what you actually get, and it's not just a technical setting buried in an "advanced" menu.

## The one-sentence version

A **market order** buys or sells immediately at whatever price is currently available, prioritizing speed; a **limit order** only executes at a price you specify or better, prioritizing price control, even if that means it doesn't execute at all.

<!--more-->

## Market orders: fast, but the price isn't guaranteed

A market order says "execute this right now, at whatever the current price is." For a heavily-traded stock during normal market hours, the price you get is usually extremely close to the price you saw when you clicked — the gap is typically small enough not to matter for a long-term buy-and-hold purchase.

The real risk shows up in less liquid situations: a thinly-traded stock, a fast-moving market, or trading right at the market open or close, when prices can be jumping around quickly. A market order in those conditions can fill at a noticeably worse price than what you saw a second earlier — you traded certainty of execution for a guarantee on price, and in a volatile moment, that trade can cost real money.

## Limit orders: price control, with no guarantee of a fill

A limit order says "only buy this at $50 or less" (or "only sell this at $50 or more") — you're trading away the guarantee of an immediate execution in exchange for control over the price. If the stock never trades at your limit price or better, the order simply doesn't execute — it sits unfilled, which is a real possibility, not an edge case.

Say a stock is trading at $52 and you place a limit buy order at $50. Nothing happens until the price actually drops to $50 or below — if it never does, you never buy, even if the stock goes on to rise from $52 without ever touching $50 again. That's the tradeoff: you got price protection, at the cost of potentially missing the trade entirely.

## Why this matters more than it looks like it should

For a simple, planned purchase of a liquid, widely-traded fund during normal market hours — the overwhelming majority of what a long-term, buy-and-hold investor is actually doing — a market order is usually fine, and the practical difference between the two is small. The order type starts mattering a lot more in a few specific situations:

- **Trading a stock with low volume**, where the gap between the best available buy and sell price ("the spread") can be wide enough that a market order fills noticeably worse than expected.
- **Trading right at market open or close**, when prices can swing quickly on relatively little volume.
- **Trading during unusually volatile news events**, where a stock's price can move meaningfully in the seconds it takes an order to execute.
- **Setting a specific price you're willing to pay or accept**, rather than taking whatever the market offers in the moment — useful for anyone who wants to buy on a dip to a specific level, or sell only once a position hits a target price.

## A third option worth knowing: the stop order

A **stop order** isn't a daily-use tool for most long-term investors, but it's common enough to know by name: it sits inactive until a stock hits a specified "stop price," at which point it triggers either a market order (a "stop-loss") or a limit order (a "stop-limit") to execute. It's typically used to automatically sell a position if it drops to a certain level, without requiring you to be watching the price in real time.

## What this doesn't change

Order type has no bearing on what you're actually buying, how it's taxed, or whether it's a good investment — it only controls the mechanics of *how* the trade executes. A market order and a limit order filled at the identical price produce an identical investment outcome from that point forward; the difference only shows up in the moment of the trade itself, and mostly in how predictable that moment's price turns out to be.

## The takeaway

For routine, planned purchases of a widely-traded fund, a market order is simple and usually fine — the price gap is typically too small to matter. The moment you're trading something thinly traded, during a volatile stretch, or with a specific price in mind, a limit order trades the certainty of an immediate fill for control over what you actually pay. Neither is the "correct" default — they're different tools answering different questions: how fast, or how much.
