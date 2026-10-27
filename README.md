# The Long Road to Bitcoin Payments

*Why bitcoin payments haven’t taken off, and a call for moonshot ideas that could change that*

## Summary

“If bitcoin ends up just being digital gold, I think it’s failed,” Jack Dorsey [said in January 2025](https://www.youtube.com/watch?v=KyFkv5DGeUA&t=1250s). “If it ends up being a currency that people can use daily, then it’s succeeded.” Not everyone agrees. Many in bitcoin argue it must first succeed as a store of value, and that demand for payments will follow. So we start with a clear question: does the current path lead to irrelevance, or is it the expected grind of hardening bitcoin for the day it’s needed for payments? This report asks what is holding bitcoin payments back, and what moonshot ideas could speed up adoption.

Bitcoin payments work better than ever. Turning that progress into everyday use remains the challenge, and the time to move is now, as stablecoins are ready to gain rapid adoption.

**Where things stand.** Over the past seven years, bitcoin spending technology has improved dramatically. Lightning infrastructure runs in production, and self-custodial wallets now hide most of their complexity. Seven years ago, building a bitcoin payments app took more than a year and several developers. Today, anyone can build a working first version from a single prompt to an AI coding tool. Custodial bitcoin is now no harder to integrate than custodial stablecoins, though self-custodial bitcoin is still harder to run at scale. More than a million US merchants can accept bitcoin through Square. Yet few people pay with bitcoin in everyday life, a point most in the industry accept. The gap is mostly demand, not technology.

**Why now.** The wider financial system is being updated, raising an open question: will the rails chosen during this shift be hard to change later, or will payments follow what people want to pay and be paid in, with software making it easy to add any payment rail? As large payment providers update their rails, they are choosing stablecoins, not bitcoin. Stripe, Shopify and Coinbase are building stablecoins in, and major consumer products appear likely to follow. Stripe, Visa, American Express and Google have also joined a consortium launching a new stablecoin, OUSD, and the first protocol implementations for AI agent payments settle almost entirely in stablecoins. Developers build on the rails their tools support, and wallets ship with the networks their partners already use. AI agents are the clearest case. They need small, programmable payments, which Lightning suits, yet the first agent payment tools are being built around stablecoins and cards. If early choices do stick, bitcoin’s absence now could be hard to reverse. If they don’t, the question becomes demand alone.

**What’s blocking it?**

- **Demand:** neither side is pulling for it. Holders would rather save than spend, and bitcoin’s culture celebrates holding. Merchants prefer to receive and hold dollars, so few accept bitcoin, and new payment platforms leave it out.
- **Volatility and competition:** price swings make bitcoin hard to price goods in, and dollar stablecoins meet the need for stable payments.
- **Policy:** US tax treatment of every purchase and pending regulation.

**What could change this?** We’re looking for moonshot ideas: changes big enough to shift bitcoin payments, not just improve them. A few possible paths to start the discussion:

- **Shared rails:** let people pay in dollars or bitcoin over the same Lightning network, with a compelling reason to choose it, so bitcoin is one tap away wherever people already pay: in agent payments, merchant checkout and fintech apps.
- **Payments for people who need them most:** self-custodial bitcoin payments that better solve the needs of people facing capital controls or unstable currencies.
- **New reasons to spend:** spending incentives for existing holders.
- **New ways to spend:** product experiences that create entirely new kinds of payments, such as paying creators or AI services per use. The killer app for micropayments probably won’t feel like a traditional payment at all.

We don’t know which, if any, will work. That’s why we want to hear yours.

**What we’re asking.** Our central question: what moonshot ideas would create a believable, viable plan to accelerate bitcoin payments adoption? To make it explicit: what would it take for a major platform such as Meta, Shopify, or OpenAI to accept bitcoin? Builders: propose ideas and test them. Payment providers: share data on how people pay. Funders: back the most promising experiments and help foster demand. 

This is a living document. Share your ideas or data in the [GitHub discussion](../../discussions/1), or reply to our posts on X, Stacker News or Delving Bitcoin. We’ll keep updating the report as we learn.

## The open question

Bitcoin has largely succeeded as a store of value. Whether it becomes everyday money is less clear, and people who care about bitcoin disagree over how worried they should be that so few people use it for payments.

**One view: the current path leads to irrelevance.** Jack Dorsey and others argue that if bitcoin ends up only as digital gold, it will have failed to live up to its promise: becoming peer-to-peer electronic cash. New payment habits are being formed as we speak. Stablecoins are being built into the products people already use, and the longer bitcoin is left out of everyday payments, the harder it will be to add later. A store of value that nobody spends also depends entirely on people continuing to believe in it without daily use cases to anchor it.

**The other view: this is the expected grind.** Many bitcoiners argue that money develops in stages: first as a store of value, then as a medium of exchange, then as a unit of account. People spend the money they trust least and hold the one they trust most, so today’s low spending is expected from an asset people believe is still appreciating. Volatility is also a part of this story. At roughly [$1.3 trillion](https://fortune.com/article/price-of-bitcoin-10-21-2026/) (October 2026), bitcoin is still small enough for large trades to move its price, and [volatility tends to fall as a market grows](https://www.fidelitydigitalassets.com/research-and-insights/closer-look-bitcoins-volatility). In this view, bitcoin becomes usable as everyday money only once it becomes many times larger, with deep, open markets setting its price. Demand for bitcoin payments will come when people need it, such as when local currencies fail or capital controls bite. The job now is to make sure the technology is ready when they do.

**What would tell us which is right? A few potential signals**:

- Whether the share of holders who spend bitcoin is rising or falling
- Whether bitcoin’s price volatility keeps falling as its market grows, as it has so far
- Whether spending is growing faster in countries with high inflation or capital controls
- Whether people keep spending bitcoin once incentives end

Either way, investing in payments now costs little compared with being absent when demand arrives. The rest of this report explains what is blocking bitcoin payments and what could open them up.

## Where things stand

This report covers two related things while spelling out which one each finding applies to:

- **Paying in bitcoin:** people and businesses spending and receiving bitcoin as money.
- **Bitcoin as a payment rail:** using bitcoin and Lightning to transfer value, including dollars and stablecoins. For example, a Cash App customer paying a Lightning invoice with dollars.

To reiterate, we see bitcoin adoption progressing in three stages: store of value, payment rail, and everyday currency. Bitcoin has largely achieved the first. The second is a weaker form of the third, but stronger than any open payment system available today. The long-term goal is the third, and it may take decades to get there.

**The tech has improved a lot** over the past seven years:

- **Infrastructure has matured:** the core software behind bitcoin payments, from Lightning nodes to developer toolkits, is now stable enough to run in production at scale.
- **Self-custodial wallets are easier:** wallets now hide many of the old challenges, such as managing channels and liquidity and receiving payments while offline. A broader ecosystem of bitcoin protocols also offers different trade-offs.
- **Integration is easier:** custodial bitcoin is now no harder to integrate than custodial stablecoins, though self-custodial bitcoin is still harder to run at scale.
- **Building is faster:** a bitcoin wallet or payment app used to take more than a year and several developers. With today's libraries and AI coding tools, you can build a working first version from a single prompt.
- **The user experience has improved:** backup and recovery no longer depend on writing down seed words. Amounts can show as whole numbers with the ₿ symbol. Payment addresses can be human-readable, like an email address, and reusable. One QR code can work for both bitcoin and Lightning.
- **More teams are building:** more teams are building payment products on open-source bitcoin infrastructure, many of which are funded or supported by Spiral.

**Payments already work at scale in places.** Cash App supports Lightning, and more than a million US merchants can accept bitcoin through Square. In some remittance corridors, bitcoin and Lightning can be cheaper and faster than banks and money transfer services, though stablecoins are usually cheaper still.

**But few people spend bitcoin in everyday life,** a point most in the industry accept.

The problem is demand, not technology.

## Why now

The wider financial system is being updated. Dollar stablecoins now have clear US rules under the [GENIUS Act](https://www.whitehouse.gov/briefings-statements/2025/07/the-president-signed-into-law-s-1582), signed in July 2025, and mainstream payment companies are integrating them. As these companies update their rails, they are choosing stablecoins, not bitcoin. So far, stablecoins are being adopted in a few main ways:

- **Stablecoins as consumer money:** PayPal and Venmo let users hold, send and pay with [PYUSD](https://newsroom.paypal-corp.com/2023-09-20-PayPal-USD-is-now-available-on-Venmo). Shopify [added USDC checkout](https://www.shopify.com/news/stablecoins-on-shopify) with Coinbase and Stripe in June 2025.
- **Stablecoins as payment infrastructure:** Stripe [bought stablecoin company Bridge](https://stripe.com/us/newsroom/news/stripe-completes-bridge-acquisition) and now offers stablecoin checkout and stablecoin-backed cards. Open USD, a stablecoin backed by Stripe, Visa, American Express, Google, BlackRock and more than 140 other businesses, was [announced in June 2026](https://joinopenstandard.com/blog/introducing-open-usd/). PayPal and Fiserv are [working to make PYUSD and FIUSD work together](https://investors.fiserv.com/news-releases/news-release-details/fiserv-and-paypal-expand-partnership-advance-stablecoin-payments).
- **Stablecoins as money for AI agents:** [about 99% of payments](https://www.coindesk.com/business/2026/08/23/crypto-s-next-billion-users-might-be-ai-agents-and-they-re-paying-with-stablecoins) over Coinbase’s x402 protocol are in USDC. Google’s [Agent Payments Protocol (AP2)](https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol) supports stablecoins through x402. Stripe’s [Machine Payments Protocol](https://stripe.com/blog/machine-payments-protocol) lets agents pay per API call, at services such as Parallel and Browserbase.

Meta’s Muse launched with [card and wallet partners such as PayPal and Shop Pay](https://thepaypers.com/payments/news/paypal-partners-with-meta-to-bring-checkout-to-muse-ai-agent), not bitcoin, even though agents need the small, programmable payments Lightning was built for.

This raises a question: will the rails chosen during this shift be hard to pivot from later? There are reasons to think they might. Developers build on the rails their tools support, and wallets ship with the networks their partners already use. But software also makes it easier than ever to add a new payment rail, and payments may simply follow what people want to pay and be paid in. If early choices do stick, bitcoin’s absence now could be hard to reverse. If they don’t, the question becomes demand alone.

## What's blocking bitcoin payments

Bitcoin hasn’t delivered peer-to-peer payments that are fully trust-minimized, scalable, and cheap. But stablecoins are being adopted with weaker trust guarantees than bitcoin offers, suggesting technology isn’t what’s holding bitcoin payments back. The blockers fall into three groups. Each is solvable.

**Demand: neither side is pulling for it.**

- **Getting bitcoin in the first place:** bitcoin itself doesn’t require ID checks, but in practice most people get it by signing up for an exchange or app and passing identity checks (KYC) first. Almost nobody is paid in bitcoin, so spending it usually means buying it first, a step that cards and dollar apps don’t require.
- **Holders would rather save than spend:** most holders treat bitcoin as savings and avoid spending an asset they expect to appreciate, and most consumers already have cards that work well.
- **Culture and marketing:** bitcoin is marketed, and celebrated by its own community, as something to buy and hold. “Never sell your bitcoin” leaves little room for spending it, and pitching “bitcoin” to mainstream users carries baggage that a plain payment option doesn’t.
- **Too few customers for merchants:** for merchants, the benefit is lower fees and faster settlement, not holding bitcoin. But with little consumer demand, few see enough volume to justify integrating, and few payment processors and e-commerce platforms offer bitcoin by default.
- **New payment platforms leave it out:** products where digital payments are taking off, such as AI agents, are launching with cards, wallets, and stablecoins rather than bitcoin or Lightning, so users never see bitcoin as an option.

**Volatility and competition**

- **Volatility:** bitcoin’s price swings make it hard to price goods in. People hesitate to spend it when it might rise, and merchants and payment apps convert it to dollars straight away to avoid the risk. Volatility tends to fall as a market grows, so this may ease as bitcoin gets larger.
- **Competition from stablecoins:** where people want to pay and be paid in dollars, stablecoins meet the need directly. Stablecoins also run on blockchains where developers can build payment logic, such as escrow or automatic payouts. Some builders cite this programmability as a reason to choose stablecoins over bitcoin.

**Policy**

- **Tax:** In the US, [spending bitcoin counts as selling it](https://www.irs.gov/pub/irs-drop/n-14-21.pdf), so even buying a coffee creates a gain or loss to report. Congress has introduced bills to exempt small payments, but none have passed.
- **Regulation:** the [CLARITY Act](https://www.congress.gov/bill/119th-congress/house-bill/3633), which would set rules for crypto markets and protect non-custodial developers, stalled in the Senate in September 2026. That leaves companies building payments with higher costs and more uncertainty.

Some technical friction remains. Payment failures make bitcoin payments less predictable, but they don’t explain why so few people try to pay with bitcoin in the first place.

## How bitcoin compares

Bitcoin and stablecoins each have strengths in different areas. The table compares them on the properties that matter for payments. It also shows whether most people care about each one today, and how bitcoin has changed over the past seven years.

| Property | Bitcoin (incl. Lightning) | Stablecoins | Do most people care today? | Bitcoin, past 7 years |
| :--- | :---: | :---: | :---: | :---: |
| **What makes it open money** |  |  |  |  |
| Fixed monetary policy | ✓ | ✗ | No | Holding strong |
| Funds can’t be seized or frozen | ✓ | ✗ | No | Holding strong |
| Anyone can start using it without ID checks | ✓ | ✓ | Yes | Holding strong |
| No issuer can require ID checks later | ✓ | ✗ | No | Holding strong |
| No one can block payments | ✓ | ✗ | No | Holding strong |
| Payments private from the public | Partial | Partial | Yes | Modest improvement |
| Payments private from providers and governments | Partial | ✗ | No | Modest improvement |
| **Ease of use** |  |  |  |  |
| Easy for developers (custodial) | ✓ | ✓ | Yes | Big improvement |
| Easy for developers (self-custodial, at scale) | Partial | ✓ | Yes | Big improvement |
| Easy for users | ✓ | ✓ | Yes | Big improvement |
| Low fees | ✓ | ✓ | Yes | Big improvement |
| Scales to many payments | ✓ | ✓ | Yes | Big improvement |
| Streaming payments | ✓ | ✗ | Not yet? | Big improvement |
| **Adoption** |  |  |  |  |
| Stable value | ✗ | ✓ | Yes | Little change |
| Broad acceptance | ✗ | Growing fast | Yes | Little change |
| Favorable tax and regulation | ✗ | ✓ | Yes | Modest improvement |
| **Other** |  |  |  |  |
| Programmability | ✗ | ✓ | No? | Little change |

Three things stand out:

- **Bitcoin leads on what makes money open.** No issuer can freeze funds, block payments, or change the supply. Most people don’t weigh these properties today, but they matter most to people facing capital controls or unstable currencies.
- **On ease of use, bitcoin has largely caught up.** Fees, scaling, and the developer and user experiences have all improved a lot in seven years.
- **Stablecoins lead on what most people care about today.** Their advantages, stable value, broad acceptance, and policy, are also the areas where bitcoin has moved the least.

In the near term, stablecoins will likely carry most dollar payments on new payment rails, mostly on networks such as Ethereum, Solana, Tron, and Base rather than Lightning. Stablecoins solve volatility, but they bring back issuers who can freeze funds, which is why bitcoin’s open properties still matter.

## What could change this

We’re looking for moonshot ideas: changes big enough to greatly accelerate bitcoin payment adoption, not just improve it. Here are four possible paths to start the discussion, in no particular order, with examples of what each could look like.

**Shared rails.** Let people pay in dollars or bitcoin over the same Lightning network, with a compelling reason to choose it, so bitcoin is one tap away from wherever people already pay. For example:

- **Lightning in agent payments:** partner with agent platforms and payment-standard bodies to ensure Lightning—supporting both bitcoin and stablecoins—is included as an option while key design choices are still being made.
- **Bitcoin on by default in fintech apps:** most people never see bitcoin as a payment option in the apps they already use. A drop-in offering would make it cheap for any fintech app to switch on bitcoin alongside other networks and stablecoins, putting it in front of far more people.
- **Lead with the payment, not the asset:** pitching “bitcoin” to merchants and mainstream users runs into resistance over volatility and reputation. Pitching a cheaper, faster way to pay works better. For example, offer merchants Lightning as a new payment option with lower fees, and let customers pay in dollars through an app like Cash App. Bitcoin runs underneath, alongside stablecoins and other networks, and stays out of sight until more people want to hold and spend it directly.

**Payments for people who need them most.** Self-custodial bitcoin payments that better serve people facing capital controls or unstable currencies. For these people, bitcoin’s open properties matter today, not someday.

**New reasons to spend.** Spending incentives for existing holders, such as discounts or rewards for paying in bitcoin. These would test whether holders spend when given a reason to, and whether they keep spending once the incentive ends.

**New ways to spend.** Product experiences that create entirely new kinds of payments, such as paying creators or AI services per use. The killer app for micropayments probably won’t feel like a traditional payment at all. For example:

- **Streaming payments:** Lightning can pay in very small amounts continuously as a service is used, for example, paying per second for peer-to-peer AI inference.
- **Bolder experiments:** apps that create and transmit value in new ways, to generate demand rather than wait for it.

**How we’d know it’s working.** Experiments should measure how many customers spend bitcoin, how often they pay in bitcoin again, and the number, value, and share of payments they fund in bitcoin. They should track whether use continues after incentives end and, where possible, compare customers offered bitcoin payments with otherwise similar customers who weren’t. Bitcoin used only to route dollar payments doesn’t count as customer spending.

We don’t know which of these, if any, will work. That’s why we want to hear your ideas.

## Questions for readers and how to contribute

We’d especially like your thoughts and recommendations on the following problems: answers to these:

- Does the current path lead to irrelevance, or is it the expected grind toward the day bitcoin is needed for payments?
- Do today’s payment rail choices lock in, or can new rails be added easily once demand exists?
- Which blockers are we missing?
- If you chose stablecoins over bitcoin for payments, was programmability a factor? What would bitcoin or Lightning need to offer?
- Where should bitcoin compete with stablecoins and card networks, and where should it not?
- What would it take for a major platform, such as Meta, Shopify or OpenAI, to accept bitcoin?
- What moonshot ideas could change the course of bitcoin payments?
- What data can you share on payment volumes, growth, active merchants or success rates?

This is a living document. Share your ideas or data in the [GitHub discussion](../../discussions), or reply to our posts on X, Stacker News or Delving Bitcoin. We’ll keep updating the report as we learn. To suggest a correction or edit the report directly, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Sources

- [Abundant Mines: Jack Dorsey on nation-state bitcoin reserves, AI, mining and more (YouTube)](https://www.youtube.com/watch?v=KyFkv5DGeUA&t=1250s)
- [Fortune: Current price of Bitcoin, October 21, 2026](https://fortune.com/article/price-of-bitcoin-10-21-2026/)
- [Fidelity Digital Assets: A Closer Look at Bitcoin’s Volatility](https://www.fidelitydigitalassets.com/research-and-insights/closer-look-bitcoins-volatility)
- [The White House: The President signed into law S. 1582](https://www.whitehouse.gov/briefings-statements/2025/07/the-president-signed-into-law-s-1582)
- [PayPal: PayPal USD is now available on Venmo](https://newsroom.paypal-corp.com/2023-09-20-PayPal-USD-is-now-available-on-Venmo)
- [Shopify: Stablecoins on Shopify](https://www.shopify.com/news/stablecoins-on-shopify)
- [Stripe: Stripe completes Bridge acquisition](https://stripe.com/us/newsroom/news/stripe-completes-bridge-acquisition)
- [Open Standard: Introducing Open USD (OUSD)](https://joinopenstandard.com/blog/introducing-open-usd/)
- [Fiserv: Fiserv and PayPal Expand Partnership to Advance Stablecoin Payments](https://investors.fiserv.com/news-releases/news-release-details/fiserv-and-paypal-expand-partnership-advance-stablecoin-payments)
- [CoinDesk: Crypto’s next billion users might be AI agents, and they’re paying with stablecoins](https://www.coindesk.com/business/2026/08/23/crypto-s-next-billion-users-might-be-ai-agents-and-they-re-paying-with-stablecoins)
- [Google Cloud: Announcing Agent Payments Protocol (AP2)](https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol)
- [Stripe: Introducing the Machine Payments Protocol](https://stripe.com/blog/machine-payments-protocol)
- [The Paypers: PayPal partners with Meta to bring checkout to Muse AI agent](https://thepaypers.com/payments/news/paypal-partners-with-meta-to-bring-checkout-to-muse-ai-agent)
- [IRS: Notice 2014-21](https://www.irs.gov/pub/irs-drop/n-14-21.pdf)
- [Congress.gov: H.R. 3633, CLARITY Act](https://www.congress.gov/bill/119th-congress/house-bill/3633)
