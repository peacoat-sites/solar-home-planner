---
title: "Time-Of-Use Rates: The Hidden Solar And EV Advantage"
date: 2026-06-22T23:49:44.608893+00:00
draft: false
description: "Learn how time of use rates work with solar panels and EVs to slash your electricity bill by charging and exporting power at the right hours."
image: "/img/heroes/9800026.jpg"
categories: ["Solar and EV Charging"]
tags: ["time", "rates", "solar", "optimization"]
author: "Tom Bradley"
author_slug: "tom-bradley"
author_title: "DIY Solar Specialist"
author_bio: "Tom Bradley designed and installed DIY solar for his own home and has helped other homeowners do the same. He writes for the hands-on owner who wants the wiring, permitting, and system-sizing details, not a sales pitch. At Solar Home Planner he covers DIY solar, permits, and homeowner installation."
slug: "time-of-use-rates-solar-and-ev-optimization"
affiliate_disclosure: true
faqs:
 - q: "Can I charge my EV from solar panels during peak hours without getting hit by TOU rates?"
   a: "If you're pulling solar directly into your home and using it to charge your EV, you're not importing from the grid, so peak rates don't apply to that portion. The catch is that you're also giving up export credits you'd have earned by sending that solar to the grid, so whether it's financially better depends on your specific export compensation rate versus your EV charging cost."
 - q: "Does battery storage actually pay off under TOU rates alone?"
   a: "For most homeowners with a significant rate differential (more than $0.20/kWh between peak and off-peak), a battery system sized to cover 3 to 5 hours of evening load can meaningfully improve payback. It's not a slam dunk without storage incentives, but in states like California, Hawaii, and New York where both rates and incentives are favorable, the economics work."
 - q: "What's the best way to find out if my utility's TOU rate is right for my household?"
   a: "Download your interval usage data (hourly or 15-minute consumption) from your utility and run it against each available rate schedule manually, or use a tool like WattPlan. Don't rely solely on the utility's built-in comparison tool, which sometimes uses simplified assumptions."
 - q: "Will my solar inverter automatically work with my utility's TOU schedule?"
   a: "Most modern inverters with integrated battery management (Enphase, SolarEdge, Tesla) have TOU programming options, but they require manual setup. You have to input your utility's schedule, and you should check it every time your utility revises its tariff, which happens more often than you'd think."
 - q: "Is it worth switching to TOU if I have solar but no battery storage?"
   a: "Possibly, but it's not automatic. If your peak window overlaps with your midday solar production window, you can offset peak imports naturally. If the peak window is evening-only and your export rate is low, TOU could actually cost you more. Model it first with your actual usage data."
lastmod: 2026-07-08
---

Most articles about time-of-use rates spend three paragraphs explaining what a rate schedule is, then tell you to "shift your loads to off-peak hours." Thanks. Very helpful. What they skip is the actual math, the tricky interactions between solar production and TOU windows, and why an EV charger can either be your best weapon or quietly wreck your bill if you're not paying attention.

Let me fix that.

## What TOU Rates Actually Do to Your Solar Math

Here's the part installers often gloss over: going solar doesn't automatically mean TOU rates help you. It depends entirely on when your utility's peak window falls.

The classic California TOU structure (think PG&E's E-TOU-C or SCE's TOU-D-PRIME) puts peak rates between 4 p.m. and 9 p.m. Your solar panels are still producing something at 4 p.m., but output is dropping fast. By 6 p.m. in winter, you're at zero. So you spent the sunniest part of the day pumping cheap, off-peak power onto the grid, and now you're buying it back at $0.45 to $0.55 per kWh during peak hours. Net metering credits don't always save you here either, because most utilities currently compensate your exported solar at a rate far below what you pay to import during peak.

This is exactly the scenario that makes battery storage go from "nice to have" to "actually pays for itself." A 10 kWh battery charged on solar during midday, then discharged into your house from 4 to 9 p.m., lets you dodge that $0.50/kWh window entirely. NREL's modeling on residential storage economics consistently shows the best returns come from precisely this peak-shaving use case, not from backup power, which is what most salespeople lead with.

If you don't have storage yet, the first move is to understand your specific utility's TOU structure cold. Not just "peak vs. off-peak." Know the exact hours, know the rate differential, and know what your net metering compensation rate is for exports. That number is often buried in a tariff sheet, not on the marketing page.

## Building the EV Charging Strategy Around Your Rate Schedule

| Scenario | Rate | Annual Cost (60 kWh fill-up) | Notes |
| --- | --- | --- | --- |
| Peak-hour charging (4-9 p.m.) | $0.50/kWh | $30 per fill-up (~$800-$1,100/year) | Single fill-up cost; repeated daily across commuting |
| Off-peak charging (overnight) | $0.13/kWh | $7.80 per fill-up | Recommended strategy for most TOU plans |
| Solar export credit (typical) | $0.08/kWh | N/A | Used for net metering compensation |
| Daytime grid import (comparison) | $0.13/kWh | N/A | Off-peak rate; often cheaper than solar export value |

> **Helpful resource:** [Jackery Explorer 300 Portable Power Station](https://www.amazon.com/dp/B08B4C9R5J?tag=contentportfo-20) is a top-rated option for this. *(As an Amazon Associate this site earns from qualifying purchases.)*



An EV is either a liability or an asset on a TOU plan. Nothing in between.

A 60 kWh battery pack (a standard Model 3 Long Range or a Chevy Equinox EV) that you charge from empty during peak hours at $0.50/kWh costs $30 just for that fill-up. Charge the same car overnight at $0.13/kWh and you spent $7.80. That delta, repeated across a year of commuting, is roughly $800 to $1,100 difference on your electric bill. Annually. For one behavior change.

Every Level 2 charger worth buying has scheduling built in. The [Emporia Vue Level 2 Smart Charger](https://www.amazon.com/s?k=emporia+vue+level+2+ev+charger&tag=contentportfo-20) lets you set charge windows down to 15-minute increments and integrates with home energy monitoring. The ChargePoint Home Flex does the same and connects to most smart home platforms. Set it to start charging at the beginning of your utility's off-peak window and stop before peak returns. Done. This is one of the rare cases where "set it and forget it" is genuinely the right call.

The contrarian take: solar-owners often assume they should charge their EV from solar during the day rather than from the grid overnight. I've seen this advice repeated constantly, and for most people, it's wrong. Here's why. If your net metering rate gives you credit at, say, $0.08/kWh for solar exports, but overnight grid power costs $0.13/kWh, you're better off exporting that solar and charging from cheap off-peak grid power at night. The math closes only if you have battery storage, your export rate is very low (below $0.10), and your overnight rate is not much cheaper than your export rate. Run those specific numbers for your utility before you commit to a daytime EV charging habit.

## Stacking the Advantages: Solar + Storage + EV on One TOU Plan

Once you have all three, the strategy gets more intentional. And more interesting.

Your daily dispatch priority should look roughly like this:

1. Solar production covers the house loads during the day.
2. Excess solar charges the battery first, then the EV if the battery is above 80%.
3. Battery discharges into house loads from 4 p.m. through 9 p.m. (or whatever your peak window is), avoiding grid imports entirely.
4. EV finishes charging from the grid after peak ends, typically 9 p.m. to midnight.

Most modern inverter/battery systems (the SolarEdge Energy Hub, the Enphase IQ System Controller, the Tesla Powerwall 3) have a "time-based control" or "self-consumption" mode that handles much of this automatically once you program your rate schedule. The Powerwall's app literally lets you input your TOU schedule and it optimizes dispatch accordingly. That said, don't trust the default settings out of the box. Verify the schedule actually matches your utility's current tariff. I've seen installs where the system was still running on a rate schedule from two years ago because nobody updated it after the utility revised its peak hours.

A [home energy monitor like the Emporia Vue 3](https://www.amazon.com/s?k=emporia+vue+3+energy+monitor&tag=contentportfo-20) (around $90) is worth every cent here. It gives you real-time circuit-level visibility so you can see exactly when and where your household is drawing power. Without it, you're guessing. With it, you can confirm that your battery is actually holding charge through peak hours, that your EV charger kicked on at 9:05 p.m. like scheduled, and that your HVAC isn't spiking during the expensive window.

EnergySage's market data shows the average [solar-plus-storage system](/solar-ev-charging-home-setup/) in 2026 runs between $25,000 and $40,000 installed before incentives. The federal Investment Tax Credit (currently 30%) makes a significant dent, and several states stack additional credits on top. If you're in that system, TOU optimization is one of the few ways to actively improve your return on investment post-install, rather than just waiting for the payback clock to tick down.

## The Rate Schedule Trap Nobody Warns You About

Switching to a TOU rate isn't always a win, even with solar and an EV. Some households have flat usage patterns that can't easily shift: medical equipment running continuously, elderly family members home during peak hours, a home-based business operating 9 to 5. A household pulling 2 kWh during peak hours on a flat rate at $0.28/kWh might do better than the same household pulling the same load at $0.52/kWh on TOU, even if they save a little overnight.

Request 12 months of interval usage data from your utility (most provide this now as a downloadable CSV or through Green Button Connect) and model it against your TOU options before switching. California utilities are required to give you this. Many others are too, under FERC Order 878. If your utility offers an online rate comparison tool, use it, but also verify the underlying assumptions, because I've seen those tools undercount peak loads.

---


---

## Sources

- [Jackery Explorer 300 Portable Power Station](https://www.amazon.com/dp/B08B4C9R5J?tag=contentportfo-20)
- [Emporia Vue Level 2 Smart Charger](https://www.amazon.com/s?k=emporia+vue+level+2+ev+charger&tag=contentportfo-20)
- [home energy monitor like the Emporia Vue 3](https://www.amazon.com/s?k=emporia+vue+3+energy+monitor&tag=contentportfo-20)
- [Jackery SolarSaga 100W Solar Panel](https://www.amazon.com/dp/B08FX9QHLP?tag=contentportfo-20)
- [Solar Panel Cleaning Brush Kit with Extension Handle](https://www.amazon.com/dp/B0BVXGN3WK?tag=contentportfo-20)


> **Disclosure:** *As an Amazon Associate, we earn a small commission from qualifying purchases at no extra cost to you. We only recommend products that genuinely support the topics covered in this article.*

- **[Renogy 200W Solar Starter Kit + 30A Charge Controller](https://www.amazon.com/dp/B00BCRG22A/?tag=contentportfo-20)** (~$169), Complete beginner solar kit, 200W monocrystalline panel, charge controller, and mounting hardware included.
- **[Renogy 2×100W Monocrystalline Solar Panels](https://www.amazon.com/dp/B07JXYTFF7/?tag=contentportfo-20)** (~$99), Expandable 200W panel set from the most trusted DIY solar brand, used widely in off-grid and home backup systems.
- **[First-Time Home Buyer: The Complete Playbook](https://www.amazon.com/dp/0997584785/?tag=contentportfo-20)** (~$18), The #1 Amazon bestseller in homebuying, covers down payment strategies, mortgage pre-approval, and avoiding rookie mistakes.

---

## Recommended Resources

> **Disclosure:** *As an Amazon Associate, we earn a small commission from qualifying purchases at no extra cost to you. We only recommend products that genuinely support the topics covered in this article.*

- **[Renogy 200W Solar Starter Kit + 30A Charge Controller](https://www.amazon.com/dp/B00BCRG22A/?tag=contentportfo-20)** (~$169), Complete beginner solar kit, 200W monocrystalline panel, charge controller, and mounting hardware included.
- **[Renogy 2×100W Monocrystalline Solar Panels](https://www.amazon.com/dp/B07JXYTFF7/?tag=contentportfo-20)** (~$99), Expandable 200W panel set from the most trusted DIY solar brand, used widely in off-grid and home backup systems.

