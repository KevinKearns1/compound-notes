---
layout: post
title: "What Is Cost Basis? The Number That Decides What You Actually Owe"
date: 2026-10-14
description: >-
  The capital gains post talked about "profit" on a sale without
  ever naming the number that defines it — cost basis. Get it wrong,
  especially with reinvested dividends, and you can pay tax twice on
  the same money.
tags: [fundamentals, taxes]
reading_time: 6
cover: /assets/images/covers/cost-basis.svg
image: /assets/images/covers/cost-basis.png
cover_alt: "A receipt with a growing stack of smaller receipts stapled behind it, each one raising the total, illustrating how reinvested dividends keep adding to an investment's cost basis over time"
related: [capital-gains-tax-explained]
---

I [explained capital gains tax]({{ '/capital-gains-tax-explained/' | relative_url }}) — the tax on selling for more than you paid — without ever naming the number that actually defines "more than you paid." That number is cost basis, and getting it wrong is one of the few mistakes in investing that can genuinely cost you money on April's tax bill, not just in theory.

## The one-sentence version

Cost basis is what you actually paid for an investment (including reinvested dividends added over time), and it's the number subtracted from your sale price to determine your taxable gain or loss — get the basis wrong, and you get the tax wrong.

<!--more-->

## The simple case, where basis is obvious

Buy 10 shares of a stock at $50 each: your cost basis is $500. Sell those same 10 shares later for $600: your gain is $100 ($600 − $500), and that's the number [capital gains tax]({{ '/capital-gains-tax-explained/' | relative_url }}) actually applies to. Nothing complicated here — basis is just what you paid, full stop.

## Where it actually gets confusing: reinvested dividends

This is the single most common cost-basis mistake, and it can mean paying tax twice on the same money if you get it wrong. Say you buy 10 shares at $50 (a $500 basis), and the stock pays a $20 dividend that automatically reinvests, buying 0.4 more shares at $50. Your basis isn't still $500 — **it's now $520**, because that $20 dividend was money you already received and already paid income tax on in the year it was paid, then used to buy more shares.

Sell everything later at $55/share (10.4 shares, $572 total):

| | If basis is correctly updated to $520 | If basis is wrongly left at $500 |
|---|---|---|
| Gain | $52 | $72 |

That $20 difference is exactly the dividend — if you forget to add reinvested dividends to your basis, you pay capital gains tax on that $20 a second time, on top of the income tax you already paid on it the year it was received. Most brokerages track this automatically now and report an adjusted basis on your tax forms, but it's worth understanding why the number moves, especially if you're reconciling records from an older account or one that didn't track it for you.

## Buying the same stock at different times

If you bought shares of the same stock in multiple purchases at different prices, each batch has its own basis, and selling only part of your position means choosing which shares you're actually selling:

- **Specific identification**: you choose exactly which shares (by purchase date/price) to sell — useful for deliberately selling the higher-basis (lower-gain) shares first to minimize tax, or the longer-held shares to get long-term treatment.
- **FIFO (first-in, first-out)**: the default at most brokerages if you don't specify — the oldest shares are treated as sold first.
- **Average cost**: common for mutual funds specifically — all your purchases get averaged into a single basis per share, rather than tracked individually.

The method matters because it changes your reported gain on a partial sale — selling the same number of shares can produce a meaningfully different tax bill depending on which specific shares (by original purchase price) the sale is treated as coming from.

## Inherited and gifted stock: basis works differently

Two situations worth knowing exist outside the normal "what you paid" rule:

**Inherited stock generally gets a "stepped-up" basis** — the basis resets to the stock's value on the date of the original owner's death, not what they originally paid. This can eliminate decades of unrealized gain from ever being taxed, which is a significant and commonly underused fact in estate and inheritance situations.

**Gifted stock generally keeps the giver's original basis** (with some added complexity if the stock had lost value) — the recipient doesn't get a fresh basis, they inherit the giver's cost and holding period, which matters if they sell soon after receiving it.

## Why this is mostly invisible until you need it

Modern brokerages report cost basis automatically on the tax forms they issue (1099-B), including basis adjustments for reinvested dividends, for most investments bought through them — which is exactly why this rarely requires manual tracking today. It becomes relevant when: records transferred from an older account or a different brokerage are incomplete, you're dealing with inherited or gifted shares, or you're deliberately choosing which specific shares to sell for tax reasons. In all of those cases, understanding what basis actually is — not just trusting a number on a form — is the difference between catching an error and not knowing one exists.

## The takeaway

Cost basis isn't just "what you paid" in the simple sense — it's what you paid, adjusted for reinvested dividends and other additions, and it's the one number standing between your sale price and your actual taxable gain. The mechanism rarely needs your attention directly, but the one case worth remembering is the dividend trap: money already taxed as income that quietly becomes part of your basis, and taxed again if you — or an incomplete record — forget it's there.
