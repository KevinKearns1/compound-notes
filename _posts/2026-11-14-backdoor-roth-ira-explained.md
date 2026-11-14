---
layout: post
title: "The Backdoor Roth IRA: How It Works, and the Rule That Can Wreck It"
date: 2026-11-14
description: >-
  I said a Roth 401(k) is "close to the only way" a high earner gets
  tax-free retirement growth. There's a second path — a two-step
  workaround most people describe as simple, which has a catch that
  isn't.
tags: [fundamentals, retirement]
reading_time: 7
cover: /assets/images/covers/backdoor-roth.svg
image: /assets/images/covers/backdoor-roth.png
cover_alt: "A locked front door labeled Roth IRA with a side door propped open behind it, with a warning sign on the side door showing a mixed pool of coins, illustrating the backdoor Roth workaround and the pro-rata rule that can tax it"
related: [traditional-vs-roth-401k, what-is-a-roth-ira, traditional-vs-roth-ira]
---

I wrote that a Roth 401(k) is "close to the only way" a high earner locked out of a [Roth IRA]({{ '/what-is-a-roth-ira/' | relative_url }}) gets tax-free retirement growth — which undersold it. There's a second path, commonly called the backdoor Roth IRA, described everywhere as a simple two-step move. It is simple, mechanically. It also has a specific, well-documented way to quietly stop being tax-free, and that part gets left out far more often than it should.

## The one-sentence version

A backdoor Roth IRA contributes money to a Traditional IRA (which has no income limit on contributing) and then converts that balance to a Roth IRA (which has no income limit on converting, unlike contributing directly) — and the conversion is genuinely tax-free only if you have no other pre-tax IRA money anywhere, because of a rule that aggregates every Traditional, SEP, and SIMPLE IRA you own into one pool before calculating what's taxable.

<!--more-->

## The two steps

**Step 1:** Contribute to a Traditional IRA. Unlike a Roth IRA, a Traditional IRA has no income limit on who can contribute — the income limit on a Traditional IRA only affects whether the contribution is *deductible*, not whether it's allowed. A high earner can always put money in; they just can't necessarily deduct it.

**Step 2:** Convert that Traditional IRA balance to a Roth IRA. Conversions have no income limit at all — that's the specific loophole this entire strategy runs through. Since the original contribution was non-deductible (already taxed, never given a deduction), converting it to Roth should, in theory, trigger no additional tax: the money was taxed once, going in, and nothing further is owed converting it.

## Why "in theory" is doing real work in that sentence

Here's the catch, and it's the single most important thing to understand before attempting this: the IRS doesn't look at the new Traditional IRA account in isolation. The **pro-rata rule** aggregates **every Traditional, SEP, and SIMPLE IRA you own** into one combined balance, and calculates the taxable portion of any conversion as a percentage based on that entire pool — not just the account being converted.

Here's the same $7,000 non-deductible contribution and conversion, compared two ways:

| | No other pre-tax IRA balance | $30,000 pre-tax IRA balance (e.g., an old 401(k) rollover) |
|---|---|---|
| Total IRA balance | $7,000 | $37,000 |
| Taxable fraction of the conversion | 0% | 81.1% |
| **Tax owed on converting $7,000** | **$0** | **Tax on $5,676** |

Same contribution, same conversion, same intent — and in the second case, over 80% of what was supposed to be a clean, tax-free move is actually taxable income, because of an entirely separate account that has nothing to do with the backdoor Roth itself.

## The most common way people accidentally disqualify themselves

This isn't a rare edge case. **Rolling an old 401(k) into a Traditional IRA** — one of the most commonly recommended moves when leaving a job — is exactly the kind of balance that gets caught by this rule. Someone who did that years ago, then later tries a "clean" backdoor Roth without realizing the old rollover is still sitting in a Traditional IRA somewhere, gets the pro-rata result above without any warning until the tax bill shows up.

## The fix, if one exists

Because the pro-rata rule only aggregates **IRA** balances — not 401(k) balances — rolling an existing pre-tax Traditional IRA balance **into a current employer's 401(k)** (if that plan accepts incoming rollovers, which many but not all do) removes it from the pro-rata calculation entirely, clearing the way for a genuinely clean backdoor Roth afterward. This only works if an employer plan exists and accepts the rollover — someone without a current 401(k), or with one that doesn't accept rollovers in, doesn't have this option and is stuck with the pro-rata math as-is.

## Where this leaves the "close to the only way" claim

The [Roth 401(k)]({{ '/traditional-vs-roth-401k/' | relative_url }}) is still the more straightforward path for a high earner, specifically because it has no equivalent trap — there's no pro-rata rule lurking inside a 401(k) the way there is across IRAs. A backdoor Roth IRA is a real second option, not a consolation prize, but it comes with a genuine prerequisite: either no existing pre-tax IRA money, or the ability to move it somewhere the pro-rata calculation won't see it. Checking for old rollover balances before assuming the strategy applies cleanly isn't optional due diligence — it's the entire difference between the clean version of this strategy and the expensive one.

## The honest complexity caveat

This is reported on a specific tax form (Form 8606) and the calculation has edge cases beyond what's covered here — timing across tax years, what counts as a "balance" at which date, and state tax treatment all add real complexity. This post explains the mechanism and the main trap, not a substitute for running the actual numbers with a tax professional before converting real money.

## The takeaway

A backdoor Roth IRA is a genuinely useful second path to [Roth-style]({{ '/traditional-vs-roth-ira/' | relative_url }}) tax-free growth for someone locked out of contributing directly — but "simple two-step workaround" undersells the one rule that decides whether it actually works as advertised. Check for other pre-tax IRA balances, including old rollovers from a previous job, before assuming the conversion will be clean. The strategy isn't broken; the assumption that it's automatically tax-free is the part that actually needs checking.
