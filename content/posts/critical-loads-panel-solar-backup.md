---
title: "Critical Loads Panel Solar Backup"
date: 2026-06-29T00:36:30.546320+00:00
draft: false
description: "Learn how a critical loads panel works with solar backup systems to keep essential home circuits powered during outages and reduce energy costs."
image: "https://images.pexels.com/photos/8853509/pexels-photo-8853509.jpeg?auto=compress&cs=tinysrgb&h=650&w=940"
categories: ["Off-Grid & Backup Power"]
tags: ["critical", "loads", "panel", "solar", "backup"]
author: "Rachel Kim"
author_slug: "rachel-kim"
author_title: "Energy Analyst"
author_bio: "Rachel Kim is a certified home energy auditor who has assessed hundreds of homes for solar readiness and efficiency. She understands that a solar installation is only as effective as the home beneath it, and her writing reflects that systems-level thinking. At Solar Home Planner, she covers energy audits, efficiency upgrades, and how to prep a home before going solar."
slug: "critical-loads-panel-solar-backup"
affiliate_disclosure: true
faqs:
  - q: "Can I add a critical loads panel to an existing solar system without batteries?"
    a: "No. The critical loads panel only powers circuits when there's a battery (or generator) to supply the backup power. Solar panels alone don't work during grid outages because grid-tied inverters shut down for safety. You need storage."
  - q: "How many circuits can I put on a critical loads panel?"
    a: "It depends on your inverter's output capacity and your subpanel's amperage rating, but practically speaking, most homeowners fit 6-12 circuits on a 100A critical loads subpanel. The real constraint is total wattage draw, not circuit count."
  - q: "Does a critical loads panel affect my solar production or net metering?"
    a: "No. During normal grid-connected operation, everything works exactly as it would without the backup subpanel. The transfer switch only activates during an outage, routing your battery output to the critical circuits instead of the grid."
  - q: "What happens if my critical loads panel gets overloaded during an outage?"
    a: "The battery inverter will either throttle output or trip an overcurrent protection device on the critical loads panel, depending on the inverter model. You won't damage the battery, but you might trip a breaker and lose power to those circuits until you reset it and reduce the load."
  - q: "Do I need a separate permit for the critical loads panel versus the solar and battery permit?"
    a: "Usually it's covered under a single permit application for the entire solar-plus-storage system, but this varies by jurisdiction. Some municipalities issue separate electrical permits for the subpanel work. Ask your installer to confirm what permits they're pulling before work starts, and verify with your local building department if they can't give you a straight answer."
---

Most homeowners shopping for solar-plus-storage think "backup" means the whole house stays on. It doesn't. What you actually get with a standard battery install, unless someone specifically sets up a critical loads panel, is a dead house during an outage even if you have a fully charged battery sitting right there in your garage. I've watched this happen to a reader named Marcus from Sacramento who installed a 10 kWh system in 2024, lost power in a grid outage, and his battery did absolutely nothing for him. His installer never explained the difference.

That's the gap this article closes.

## What a Critical Loads Panel Actually Is

A critical loads panel (sometimes called a backup subpanel or essential loads panel) is a secondary electrical panel that gets fed by your battery inverter during a grid outage. You move specific circuits off your main panel onto this subpanel: the refrigerator, a few lights, the internet router, maybe a well pump or medical equipment. When the grid goes down, the inverter disconnects from the grid and powers only those circuits. Everything still on the main panel goes dark.

This is distinct from "whole-home backup," which requires either a large battery system (usually 20+ kWh, sometimes multiple batteries) or a properly sized generator with an automatic transfer switch. A critical loads panel is the practical middle ground: real backup power for the things that matter, at a cost that doesn't require refinancing your house.

The hardware itself isn't exotic. You're typically looking at a 100A or 125A subpanel (Square D, Leviton, and Siemens all make suitable units for $80-$200 at any big-box store), plus the wiring and labor to move circuits. The inverter, not the panel itself, is what controls the switchover. Enphase's IQ Battery system, SolarEdge with its Energy Bank, and Tesla Powerwall 3 all handle this automatically through their inverter software.

## Sizing It Right: Don't Guess at This

> **Helpful resource:** [Emporia Vue 2 Home Energy Monitor](https://www.amazon.com/dp/B09ZJ1WVGK?tag=contentportfo-20) is a top-rated option for this. *(As an Amazon Associate this site earns from qualifying purchases.)*



Here's where I see the most expensive mistakes. People overload their critical loads panel because they treat it like an opportunity to back up everything "important." Then they wonder why their battery drains in three hours.

The math is straightforward but requires honesty about your actual loads.

Start by listing every circuit you want to back up. Get the amperage rating from the breaker and look up (or measure) the wattage of the actual device. A 20A circuit doesn't mean you're pulling 20A continuously. Your refrigerator might draw 150W running, 400W on compressor startup. A chest freezer, similar. Your furnace blower (if gas heat) might be 400-600W. Add a few lights at 60W LED equivalent each, the router at 20W, and you're probably at 1,200 to 2,000W continuous draw if everything runs at once.

Take that continuous load estimate and multiply by how many hours you want backup coverage. If you want 24 hours of protection during a winter outage at 1,500W average: that's 36 kWh. One Powerwall 3 at 13.5 kWh won't cover that. Two will. This is why EnergySage's market data consistently shows homeowners buying two batteries when serious about backup rather than just peak shaving.

What I tell people: if you're only funding one battery for now, keep your critical loads panel ruthlessly lean. Refrigerator, one bathroom outlet, three or four lights, router, phone charging. That's it. You can always add circuits to the subpanel later.

**Worked example 1:** A client in Phoenix wanted to run her refrigerator, two ceiling fans, a CPAP machine, and four LED circuits during monsoon outages. Calculated load: ~900W continuous. One 10 kWh battery. Duration estimate at 900W average: roughly 10-11 hours, accounting for inverter efficiency losses (usually 93-95%). She added a second battery six months later and now has 22+ hours of realistic coverage.

**Worked example 2:** Family in Austin, post-2021 winter storm trauma. They wanted to keep the gas furnace blower, refrigerator, a few lights, and the garage door (for an EV that doubles as emergency vehicle). Continuous draw came to about 1,800W. With one 13.5 kWh Powerwall 3: about 7.5 hours. Not enough. They went with two Powerwalls and now have 15 hours of winter night coverage without any solar recharge. With daytime solar recharging factored in, they're effectively indefinite during a non-cloudy outage.

**Worked example 3:** Reader in rural Vermont. Well pump added complexity because pump startup surge hit 3,500W for about two seconds. His original installer said one battery couldn't handle it. The Powerwall 3 and the Enphase IQ Battery 5P both specify surge handling above 7,000W, so actually they can. He switched installers, got the system right, and the well pump now runs on backup without issue.

## The Permit and Install Reality

I'll be direct: this is not a DIY project for most homeowners, even capable ones. Modifying your electrical panel requires a permit in virtually every jurisdiction, and your utility has to sign off on the grid-disconnect arrangement. The U.S. Department of Energy's homeowner solar guide spells out that battery storage systems connected to the grid require compliance with IEEE 1547 and UL 9540 standards. Those aren't suggestions.

What you can do yourself: plan the circuit list, calculate your loads (I'd use a basic energy monitor like the Emporia Vue 3 to measure actual consumption before you commit), and specify exactly what you want to the installer. Going in with a planned critical loads list instead of "just back up whatever makes sense" will save you money and prevent the installer from oversizing unnecessarily.

Red flags to watch for during contractor conversations: any installer who doesn't discuss critical loads versus whole-home backup is being sloppy or is hoping you don't ask. Any quote that doesn't specify inverter model, battery capacity in usable kWh (not nameplate), and critical panel amperage is incomplete. Walk away from anyone who talks in vague "backup hours" without asking about your actual loads first.

As of June 2026, a typical critical loads panel install, including subpanel, wiring, and labor but not including the battery and inverter, runs $800 to $2,500 depending on complexity and your local market. Manhattan will cost more than Omaha. That's not the expensive part. The battery is the expensive part.

## Inverter Choice Shapes Your Options

The battery brand you choose largely determines how your critical loads panel behaves, so this decision matters more than most salespeople let on.

Tesla Powerwall 3 integrates the inverter into the battery unit, which simplifies installation but means you're locked into Tesla's ecosystem. The Gateway 3 (the external transfer switch unit) handles grid-disconnect automatically and cleanly. I've seen these work very smoothly in outage situations.

Enphase's IQ system uses microinverters on the panels and a separate IQ Battery for storage. The backup system requires their IQ System Controller 3, which manages the transfer. It's reliable, but the install is more component-heavy.

SolarEdge with the Energy Bank uses a string inverter with backup capability. More affordable entry point in many cases, and the installer community is large, so competitive quotes are easier to get.

The practical difference in most outage scenarios is small. Where it matters: if you want to size up later, make sure your chosen system supports battery stacking. Powerwall 3 supports up to 4 units on a single Gateway 3. Enphase supports additional batteries through the same controller. SolarEdge has its own expansion limits. Check before you commit.

## Sources

- [U.S. Department of Energy - Homeowner's Guide to Going Solar](https://www.energy.gov/eere/solar/homeowners-guide-going-solar): Official guidance on interconnection, permits, and battery storage standards including IEEE 1547 and UL 9540 compliance.
- [EnergySage Market Data](https://news.energysage.com/): Aggregated installer pricing, battery sizing trends, and consumer quote comparisons updated quarterly.
- [National Electrical Code (NEC) Article 706](https://www.nfpa.org/codes-and-standards/nfpa-70-standard-for-electrical-code): Governs energy storage systems in residential applications, including critical loads panel wiring requirements.
- Tesla Powerwall 3 Installation Manual (2025): Specifies Gateway 3 transfer switch behavior, surge capacity, and critical loads panel wiring configurations.
- Enphase IQ System Controller 3 Installation and Operation Manual (2025): Covers microgrid interconnection, backup circuit configuration, and multi-battery expansion.

---


## Helpful Resources

*As an Amazon Associate this site earns from qualifying purchases.*

- **[Emporia Vue 2 Home Energy Monitor](https://www.amazon.com/dp/B09ZJ1WVGK?tag=contentportfo-20)**
- **[P3 Kill A Watt Electricity Usage Monitor](https://www.amazon.com/dp/B098PPB3TN?tag=contentportfo-20)**
- **[Govee WiFi Smart Plug with Energy Monitoring](https://www.amazon.com/dp/B09MVHVL1G?tag=contentportfo-20)**


*Photo: [Los Muertos Crew](https://www.pexels.com/@cristian-rojas) via Pexels*