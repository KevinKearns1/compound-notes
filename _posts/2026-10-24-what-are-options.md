---
layout: post
title: "What Are Options? Calls, Puts, and Why I Don't Recommend Starting Here"
date: 2026-10-24
description: >-
  Options came up in the Robinhood review without an explanation.
  Here's what a call and a put actually are, the leverage that makes
  them tempting, and the honest reason this blog's advice stays
  index funds first.
tags: [fundamentals, getting started]
reading_time: 7
cover: /assets/images/covers/options.svg
image: /assets/images/covers/options.png
cover_alt: "A small lever magnifying both a large upward arrow and a large downward arrow from a small input motion, illustrating how options amplify both gains and losses relative to owning the stock directly"
---

I mentioned that [Robinhood]({{ '/robinhood-review/' | relative_url }}) supports trading options without ever explaining what one actually is. They come up constantly in investing content, they're genuinely more complex than anything else covered on this blog, and the honest short version is: understand the mechanism before you decide whether they belong in your strategy, which for most people reading this, they shouldn't yet.

## The one-sentence version

An option is a contract that gives you the right — not the obligation — to buy or sell 100 shares of a stock at a specific price (the "strike price") before a specific date, and that right itself has a price (the "premium") that moves far more sharply, in percentage terms, than the underlying stock does.

<!--more-->

## Calls and puts, plainly

**A call option** gives you the right to **buy** 100 shares at the strike price before expiration. You'd buy a call if you expect the stock to rise — if it rises above the strike price, the option becomes valuable; if it doesn't, the option can expire worthless.

**A put option** gives you the right to **sell** 100 shares at the strike price before expiration. You'd buy a put if you expect the stock to fall — it becomes valuable as the stock drops below the strike price.

In both cases, you pay a **premium** upfront for the contract — that's the actual price of the option, and it's what you're risking, not the full value of 100 shares of stock.

## Why the leverage is the whole appeal — and the whole risk

Here's a $100 stock, compared to buying a call option with a $100 strike price and a $3-per-share premium ($300 total for one contract, which always covers 100 shares):

| | Buy 100 shares ($10,000) | Buy 1 call contract ($300) |
|---|---|---|
| Stock rises to $110 (+10%) | Gain: $1,000 (**+10%**) | Gain: $700 (**+233%**) |
| Stock drops to $98 at expiration | Loss: $200 (**-2%**) | Loss: $300 (**-100%, total**) |

Same stock, same price move, wildly different outcomes. A 10% stock move turned into a 233% option gain — this is the leverage that makes options genuinely exciting to talk about. But look at the second row: the stock only needs to fail to rise above the strike by expiration for the **entire premium to be lost**, even on a move that would have been a minor, forgettable 2% dip for a stockholder. That's not a worse version of the same risk — it's a structurally different risk, where being "a little wrong" and "completely wrong" often cost the same amount: the whole premium.

## Why this blog's advice stays index funds first

Everything else here — [index funds]({{ '/etf-vs-mutual-fund-vs-index-fund/' | relative_url }}), [diversification]({{ '/what-is-diversification/' | relative_url }}), [dollar-cost averaging]({{ '/dollar-cost-averaging/' | relative_url }}) — is built around a long time horizon and a return that doesn't depend on correctly predicting short-term price movement or timing. Options are the opposite of that on both counts: most options have expiration dates measured in weeks or months, not decades, and being right about direction isn't enough — you also have to be right about timing, since a move that happens after expiration doesn't help you at all. That's a fundamentally different, much harder skill than "buy a broad fund and hold it," and it's why options don't fit the approach this blog has argued for in every other post.

## What options are actually for, beyond speculation

It's worth being fair here: options aren't only a speculative tool. They're also used for **hedging** — buying a put to protect an existing stock position against a drop, similar in spirit to insurance — and for generating income through strategies like selling **covered calls** against stock you already own. These are real, legitimate uses, generally considered more conservative than buying options outright, and they're also exactly the kind of strategy that requires understanding the mechanism deeply before using it, not a shortcut around that requirement.

## The actual risk, stated plainly

Buying an option risks, at most, the premium you paid — you can't lose more than that by simply buying a call or put. The deeper risk is behavioral: because the leverage can produce dramatic percentage gains, options attract exactly the "I can beat the market with better timing" instinct that [the lessons-learned post]({{ '/investing-lessons-learned-late/' | relative_url }}) already warned against — and because premiums can go to zero quickly, repeated losses can erode an account far faster than a losing stock position ever would, which is a different kind of risk than most beginners have actually priced in before they start.

## The takeaway

An option is a contract on a stock's future price, not the stock itself — leveraged, time-limited, and capable of producing both outsized gains and total losses on the same size of underlying move. Understanding the mechanism is worthwhile, if only because the word gets used constantly; using them as a beginner strategy is a different decision, and the honest answer for most people reading a blog that starts with "buy a broad index fund" is: not yet, and maybe not ever, depending on what you're actually trying to accomplish.
