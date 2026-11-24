# Buy RDP Cheap: What $2.99/Month Actually Gets You, Whether the Renewal Price Jumps, and Which Plan You Need (Full Evoxt Plan Table)

Cheap Windows RDP splits into two price bands today. Entry-level virtual machines run **$2.99 to $7.71 a month**. The 1 GB to 4 GB plans from better-known hosts sit at **$14 to $23**, and Cloudzy's $14.48 promotional rate reverts to $28.95 once the promo ends. Evoxt occupies the floor of the first band: **$2.99/month for a 512 MB VM**, $5.99 for 2 GB of RAM with 20 GB storage, and the same price at renewal on every plan it sells.

That last detail decides whether "cheap" survives into year two, and most comparison pages quietly skip it. Below: the full plan table, the renewal math worked out in dollars, and three limits that never appear on a pricing page.

> **Most buyers should take Evoxt's VM-1.** 1 vCore, 2 GB RAM, 20 GB storage, $5.99/month, renewal also $5.99, deployable in the US, UK, Canada, Germany, Poland, the Netherlands, Japan, Hong Kong, Malaysia or Australia. It handles one or two MT4/MT5 terminals, a handful of browser profiles, or a small self-hosted tool. Anyone running several trading terminals or eight-plus browsers should move up to VM-2 at $11.99.
> 👉 [See every Evoxt RDP plan and its current price](https://bit.ly/EvoXt)

## Evoxt's full Windows RDP plan lineup

Nine configurations are published on Evoxt's Windows RDP plan page. Prices are monthly, in US dollars, and the company states it charges no separate bandwidth fees or CPU burst fees on top.

| Plan | vCore / RAM / Storage | Price (monthly) | Best for | Order |
| --- | --- | --- | --- | --- |
| VM-0.5 | 1 / 512 MB / 5 GB | $2.99 | A single lightweight app, a test box, a bot that idles | [Order](https://bit.ly/EvoXt) |
| VM-0.75 | 1 / 1 GB / 10 GB | $4.99 | One trading terminal with little headroom | [Order](https://bit.ly/EvoXt) |
| VM-1 | 1 / 2 GB / 20 GB | $5.99 | The default pick: MT4/MT5, a few browser profiles | [Order](https://bit.ly/EvoXt) |
| VM-1.5 | 2 / 2 GB / 20 GB | $6.95 | Same RAM with a second core for one busy program | [Order](https://bit.ly/EvoXt) |
| VM-2 | 2 / 4 GB / 30 GB | $11.99 | Several terminals or EAs, more browser profiles | [Order](https://bit.ly/EvoXt) |
| VM-3 | 4 / 4 GB / 30 GB | $14.99 | CPU-heavy automation that still fits in 4 GB | [Order](https://bit.ly/EvoXt) |
| VM-4 | 4 / 8 GB / 60 GB | $23.99 | Many browsers at once, SEO crawlers, rank trackers | [Order](https://bit.ly/EvoXt) |
| VM-6 | 8 / 8 GB / 60 GB | $29.99 | Parallel jobs that need cores rather than clock speed | [Order](https://bit.ly/EvoXt) |
| VM-8 | 8 / 16 GB / 80 GB | $47.99 | QuickBooks Desktop for several users, heavy multitasking | [Order](https://bit.ly/EvoXt) |

Every plan includes a weekly offsite backup at no extra cost, an IPv6 address, private networking between your own VMs, a browser-based VNC console for when RDP itself won't connect, and free VM cloning. Evoxt states deployment completes within 2.5 minutes and advertises 99.99% uptime.

Evoxt runs a wider VM catalogue than these nine; the list above is the configuration set published on its Windows RDP page, which is the relevant one when the box exists to serve a Remote Desktop session.

## What "cheap" costs you in year two

A first-invoice price tells you almost nothing. Two verified examples show the range.

Cloudzy advertises **$14.48/month** for 4 GB RAM, 2 vCPU and 120 GB NVMe. The regular rate on the same page is **$28.95**, so a year at the standard price is **$347.40**. That plan also ships with a 180-day Windows evaluation licence only, and you buy a Windows Server licence yourself when it expires.

Evoxt's 4 GB configuration, VM-2, is 2 vCore, 4 GB RAM and 30 GB storage at **$11.99 with the same price at renewal**, or **$143.88** over twelve months. The gap is roughly $200 a year before you count a Windows licence, and the storage difference (30 GB against 120 GB) is the trade you make for it.

Cloudzy is not a bad product; it is a bad fit if the number on the homepage is the number you budgeted for. Promotional pricing that doubles at renewal is common in this market, which is why the renewal line deserves the same attention as the entry price.

Evoxt is not the cheapest line item in every scenario. BearHost sells 2 GB RAM, 1 vCPU and 20 GB NVMe for **$5.49** with a Windows Server licence explicitly included, the same renewal price, and a 30-day money-back guarantee. That is $0.50 below Evoxt's VM-1 and a far longer refund window. BearHost's servers sit in the Netherlands and France and it has no US location at all, so the comparison only favours it if a European IP suits you. If your broker, platform or client needs a US address, Evoxt has one and BearHost does not.

👉 [Compare Evoxt's plans at the renewal price you'll actually pay](https://bit.ly/EvoXt)

## Three limits nobody puts on the pricing page

**Windows allows two concurrent admin sessions by default.** Buy any Windows Server RDP box and a third person connecting at the same time needs RDS licences on top. Two people sharing one machine is fine on the base price. A small team of four is not, and the licence cost can exceed the server cost.

**Crypto payments are often excluded from refunds.** OperaVPS and Hostwinds both refuse refunds on cryptocurrency payments, and their refund windows are short anyway: 72 hours at both. Evoxt accepts card, PayPal and crypto, and offers a **7-day money-back window on 11 of its 17 plans**, with the six dedicated servers carrying no refund. Seven days is enough to install your software, check latency from your actual connection, and confirm the machine behaves. It is not enough to discover a problem in week three, so do the testing immediately.

**Shared RDP is a different product from admin RDP.** On a shared plan the provider's administrator can see the files on the machine, the IP is shared with other customers, and you generally cannot install software, change firewall rules, create users or reboot on your own schedule. Every Evoxt plan listed above is a full VM with administrator access, which is what you want if the box is going to run your trading terminal or hold your data.

| Capability | Admin RDP (Evoxt VM) | Shared RDP |
| --- | --- | --- |
| Install any software | Yes | Usually no |
| Reboot on demand | Yes | No |
| Dedicated IPv4 | Yes | Often shared |
| Other admins can read your files | No | Yes, the host admin can |
| Multiple simultaneous users | 2 by default, more with RDS licences | Sold per seat |

## Pick the location before the plan

Server location changes the experience more than an extra gigabyte of RAM does. Latency to your broker or your own desktop is what you feel every minute of the day.

Evoxt lists 17 regions. The standard network covers the United States, United Kingdom, Canada, Germany, Poland, Amsterdam, Japan (Tokyo), Malaysia and Australia. Hong Kong and Japan (Osaka) sit on a premium network tier, and Malaysia has a premium-plus tier. If you specifically need a US IP for a platform that geo-restricts, that is available on the standard network.

Worth knowing about the alternatives: OperaVPS runs Dallas, Chicago, New York, Los Angeles, Miami and Tampa. Cloudzy has Utah, Dallas, Los Angeles, New York and Miami. Hostwinds covers Seattle and Dallas. Kamatera lists eight US cities, and AWS Lightsail offers Northern Virginia, Ohio and Oregon. BearHost has no US presence.

If nothing in your workflow requires a US address, choose the region closest to you and ignore the rest. A European buyer connecting to Amsterdam will see less lag than one connecting to Virginia, at the same price.

👉 [Deploy a Windows RDP VM in your nearest Evoxt region](https://bit.ly/EvoXt)

## Match the plan to the workload

These minimums are a reasonable rule of thumb regardless of which host you use.

- **One or two MT4/MT5 terminals** → 2 GB RAM. Evoxt VM-1 at $5.99. VM-0.5's 512 MB will not carry a trading platform plus Windows itself.
- **Several terminals, EAs, or a few browser profiles** → 4 GB RAM. Evoxt VM-2 at $11.99, or VM-3 at $14.99 if the workload is CPU-bound rather than memory-bound.
- **Browser automation with many profiles open at once, or a crawler on a large site** → 8 GB RAM. Evoxt VM-4 at $23.99.
- **QuickBooks Desktop for one user** → 8 GB RAM. For multiple simultaneous users → 16 GB, which is Evoxt VM-8 at $47.99.
- **Short-term projects** → hourly billing exists elsewhere (LightNode quotes $0.012/hour, Kamatera bills hourly), but Evoxt's monthly rates at the low end are hard to beat for anything running longer than a few weeks.

Two cores and 2 GB (VM-1.5, $6.95) only makes sense when a single program is CPU-hungry. If you are short on memory, the extra core does not help.

## What Evoxt is and what it isn't

Evoxt has operated since 2020 and is headquartered in Malaysia, which makes it a younger company than the established US hosts in this market. Its selling point is single-core clock speed rather than core count: the company's own comparison puts its processors around 6.0 GHz against 2.2 to 2.4 GHz for typical alternatives, based on data it collected in 2020. Fast single cores suit trading terminals, compile steps and small databases better than many slow cores do.

The practical features are all there: firewall rules, floating IP reassignment between servers, VM cloning, a VNC console, weekly offsite backups, IPv6, and cryptocurrency payment. Deployment is quick enough that ordering a second VM to test a region costs you a few minutes.

The honest caveats are the short refund window, at 7 days versus 14 at Cloudzy and 30 at BearHost, and the six-year operating history. Dedicated servers, which carry no refund, are Malaysia-only.

## FAQ

**How long do I have to ask for a refund?**
It varies enormously. AmazingRDP offers 24 hours. OperaVPS and Hostwinds give 72 hours. Evoxt gives 7 days on its VPS plans. Cloudzy gives 14 days. BearHost gives 30 days. AWS Lightsail and Kamatera have no standard money-back guarantee at all. Test the machine inside the first day regardless of the policy.

**Can I pay with Bitcoin?**
Evoxt accepts credit or debit card, PayPal and cryptocurrency. Note that crypto payments are commonly excluded from refunds elsewhere in this market, so confirm the terms on the payment page before you send funds.

**How fast is setup?**
Evoxt states 2.5 minutes from payment to a running VM. Some cheaper providers take 15 to 30 minutes, and a few take up to 24 hours for manual provisioning.

**Do I need to buy a Windows licence separately?**
Confirm this at checkout on whichever host you choose. Some providers include a Windows Server licence in the price, some ship a 180-day evaluation copy and leave you to license it afterwards, and some sell the VM with Windows as a selectable OS without spelling out the licence position. The licence can cost more than a year of the server, so read the order line.

**Will the price go up after the first term?**
At Evoxt, no. The renewal price equals the introductory price on all 17 plans. That is not the norm. Cloudzy's $14.48 becomes $28.95.

## Before you pay

Pick by workload, not by the smallest number on the page. A single trading terminal or a light automation job: **Evoxt VM-1 at $5.99**. Several terminals or a stack of browser profiles: **VM-2 at $11.99**. Multi-user QuickBooks or a genuinely heavy desktop workload: **VM-8 at $47.99**. Skip VM-0.5 unless you know exactly what 512 MB will hold.

Then confirm two things on the order page: whether a Windows licence is included in the price you are looking at, and what the invoice will read at renewal. Those two lines decide the real annual cost far more than the headline monthly figure does.

👉 [Start with Evoxt's VM-1 at $5.99/month](https://bit.ly/EvoXt)
