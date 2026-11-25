---
title: "Solar Production Estimates: 20% Accuracy Gap Explained"
date: 2026-11-22T02:30:00.129040+00:00
draft: false
description: "Learn why solar production estimates often miss the mark by 20-30% and how to get more accurate forecasts for your system."
image: "/img/heroes/13199323.jpg"
categories: ["Solar Planning Tools"]
tags: ["solar", "production", "estimate", "accurate"]
author: "Tom Bradley"
author_slug: "tom-bradley"
author_title: "DIY Solar"
author_bio: "Tom Bradley is the byline used at Solar Home Planner for articles on DIY solar: sizing, wiring and permits for owner-installed systems. It is a pen name; how articles are researched and checked is explained in our editorial standards."
slug: "solar-production-estimate-how-accurate"
affiliate_disclosure: true
faqs:
  - q: "How accurate is the production estimate in a solar proposal?"
    a: "A professionally done estimate using real shading analysis and site-specific data is usually within 10–20% of actual first-year output. Estimates done without proper shading analysis or using default loss assumptions can miss by 25–35%."
  - q: "Can I check my installer's estimate myself for free?"
    a: "Yes. Use NREL's PVWatts Calculator at pvwatts.nrel.gov. Enter your address, system size, roof orientation, and tilt. It won't catch your specific shading losses, but it gives you a solid baseline to compare against whatever you've been quoted."
  - q: "Why does my system produce less in winter than the estimate suggested?"
    a: "Lower sun angles, shorter days, and in many climates more cloud cover all reduce winter output. If your estimate shows flat monthly production across the year, it wasn't built from real irradiance data, which varies significantly by season in most U.S. locations."
  - q: "What's a reasonable annual degradation rate to assume?"
    a: "For tier-one panels from established manufacturers, 0.5% per year is a defensible number. Some manufacturers publish 0.4% in their warranty documents; panels from less established brands sometimes degrade faster. Check the actual product warranty, not just what the installer tells you verbally."
  - q: "Should I trust a 25-year savings estimate?"
    a: "Treat it as a rough planning tool, not a contract. It depends on assumptions about electricity rate inflation, your household consumption staying relatively stable, and accurate degradation modeling. The further out the projection, the wider the real uncertainty range. Focus on the 7–10 year payback calculation first; the long-term numbers are illustrative at best."
---

[Solar production](/why-is-my-solar-production-low-today/) estimates are almost always optimistic. Not wildly off, but consistently skewed in one direction, and that matters when you're deciding whether a $25,000 system actually pencils out for your household. The honest answer: a well-run estimate from a competent installer using good software is typically within 10–20% of actual first-year production, but several variables can push that gap much wider, and most homeowners never find out why.

The gap isn't random noise. It has predictable causes, and once you understand them, you can read a proposal critically instead of just comparing monthly payment quotes.

<div class="kt" style="margin:26px 0;padding:18px 22px;border:1px solid var(--border,#e7e5e4);border-left:4px solid var(--accent,#4338ca);border-radius:12px;background:var(--surface2,#f8fafc)"><div style="font-size:.72rem;font-weight:700;letter-spacing:.09em;text-transform:uppercase;color:var(--accent,#4338ca);margin-bottom:8px">Key takeaways</div><ul style="margin:0;padding-left:1.15em"><li style="margin:5px 0">Good estimates land within 10–20% of actual production; poor ones can miss by 30% or more.</li><li style="margin:5px 0">PVWatts (free, from NREL) lets you independently check any installer's production claim in minutes.</li><li style="margin:5px 0">Shading is the most commonly underestimated loss factor in residential proposals.</li><li style="margin:5px 0">Year-one production is usually the highest; output degrades roughly 0.5% per year after that.</li><li style="margin:5px 0">If an installer won't share their derate factor assumptions, that's a problem worth pressing on.</li></ul></div>

## How These Estimates Are Built

Every installer's production estimate starts with solar irradiance data: how much sunlight, measured in peak sun hours, hits your specific location over a year. The industry standard source for this is NREL's PVWatts Calculator, which the [U.S. Department of Energy](https://www.energy.gov/eere/solar/homeowners-guide-going-solar) explicitly points homeowners toward. PVWatts pulls from the National Solar Radiation Database, which uses decades of satellite and ground-station measurements. That part of the estimate is reasonably solid.

The shakier part is the "derate factor," sometimes called the system losses percentage. This is a combined adjustment for real-world inefficiencies: inverter efficiency, wiring resistance, panel soiling, mismatch between panels, temperature effects, and shading. PVWatts defaults to a 14% total system loss, which is a reasonable starting point, but it's just a starting point. An installer who leaves that number at default without actually measuring your site conditions is cutting corners.

Here's what the major loss contributors typically look like, and how much an installer can reasonably control or measure each:

| Loss Factor | Typical Range | Commonly Underestimated? |
|---|---|---|
| Inverter efficiency | 2–4% | Rarely |
| Wiring / DC losses | 1–3% | Occasionally |
| Panel temperature derating | 2–8% (climate-dependent) | Sometimes |
| Soiling (dust, debris) | 1–5% | Often |
| Shading | 0–30%+ | Frequently |
| Panel mismatch | 1–3% | Rarely |
| System availability (downtime) | 1–3% | Occasionally |

Shading deserves a separate conversation entirely.

## The Shading Problem

Shading is where estimates go wrong most often and most severely. A tree branch that covers 15% of one panel for two hours a day doesn't just reduce that panel's output by 15%. With string inverters, shading on a single panel pulls down the whole string. With microinverters or DC optimizers (like SolarEdge or Enphase), the damage is contained at the panel level, but it's still real.

Good installers use shading analysis tools: Solmetric SunEye, the Aurora Solar platform, or similar software that maps shadow patterns across your roof over the full year, not just at noon in July. If your installer's site visit took 20 minutes and consisted of standing in your yard and "eyeballing it," ask specifically what shading [analysis tool](/shade-analysis-tool-for-solar/) they used and what annual shading loss percentage they applied. If they can't answer that question directly, the estimate is a guess.

A realistic shading loss for a suburban roof with one or two mature trees nearby often runs 8–15%. Many proposals show 2–4%. That difference alone can mean 10% lower annual production than promised.

## What PVWatts Can Tell You (And What It Can't)

You can run your own independent estimate at pvwatts.nrel.gov in about five minutes. Enter your address, your [system size](/diy-solar-panel-system-sizing/) in DC kilowatts, your panel tilt and azimuth (the compass direction your roof faces), and PVWatts returns an estimated annual kWh. This is genuinely useful as a sanity check on any proposal.

**Example:** Assume a 8 kW DC system in Phoenix, Arizona, roof pitch of 20 degrees, south-facing (180° azimuth), using PVWatts default losses of 14%. PVWatts would return roughly 14,000–15,000 kWh per year. If your installer's proposal shows 18,000 kWh for the same system in the same location, ask them to walk you through their assumptions, because something isn't matching up.

What PVWatts can't tell you: actual shading losses specific to your property, the precise efficiency of the panels you're being quoted, or how your production will degrade over a 25-year period. It's a baseline, not a full analysis.

## Year-Over-Year Degradation

A production estimate that shows the same kWh output in year 25 as year one is fiction. Solar panels lose efficiency over time, typically around 0.5% per year for quality panels from established manufacturers (Qcell, REC Group, Jinko Solar, Canadian Solar, and others have published degradation data in their warranty documentation). Most tier-one panel manufacturers now guarantee no more than 80–87% of rated output at year 25.

That means a system that produces 12,000 kWh in year one might produce around 10,500–11,000 kWh in year 25, all else equal. When an installer gives you a 25-year "lifetime savings" figure, check whether it accounts for this. Many proposals either ignore degradation or use an overly optimistic 0.3% rate. The [Solar Energy Industries Association (SEIA)](https://www.seia.org/) notes that degradation rates vary by technology and manufacturing quality, so get the specific warranty language for whatever panel brand you're being quoted.

**Example:** Assume 12,000 kWh in year one, 0.5% annual degradation. By year 10, production is roughly 12,000 × (0.995^10) ≈ 11,415 kWh. By year 20, roughly 12,000 × (0.995^20) ≈ 10,860 kWh. Over 25 years, cumulative production sums to something meaningfully lower than "year-one output × 25."

## Red Flags in a Solar Proposal

A few specific things worth scrutinizing before you sign anything:

No mention of a derate factor or system losses percentage. If a proposal just says "10 kW system = X kWh per year" without showing its assumptions, the number is marketing, not engineering.

Production guarantees with no measurement mechanism. Some installers offer "production guarantees" but define them as credits against future work rather than cash back, and there's no monitoring system installed that could even verify underperformance. Real production guarantees require real monitoring data, typically via the inverter's cloud portal (Enphase Enlighten, SolarEdge mySolarEdge, or similar).

Estimates based on your current electricity bill rather than your roof. Using your monthly bill to size a system is a common shortcut. It can work, but it doesn't account for how you use electricity, what happens if you add an EV, or whether your roof actually has the space and orientation to deliver what's needed.

## Sources

- **NREL PVWatts Calculator**: Free online tool from the National Renewable Energy Laboratory for estimating residential solar output by location, system size, and orientation. Available at pvwatts.nrel.gov.
- **U.S. Department of Energy, Office of Energy Efficiency and Renewable Energy**: "A Homeowner's Guide to Going Solar" covers production estimation, installer selection, and monitoring.
- **Solar Energy Industries Association (SEIA)**: Industry research and consumer resources on panel technology and degradation, available at seia.org.
- **National Solar Radiation Database (NSRDB)**: The underlying irradiance dataset behind PVWatts, maintained by NREL.
- **Aurora Solar**: Commercial software documentation on shading analysis methods used by residential installers.

---

*Photo: [Raze Solar](https://www.pexels.com/@razesolarfl) via Pexels*

---

## Recommended Resources

> **Disclosure:** *As an Amazon Associate, we earn a small commission from qualifying purchases at no extra cost to you. We only recommend products that genuinely support the topics covered in this article.*

- **[Renogy 200W Solar Starter Kit + 30A Charge Controller](https://www.amazon.com/dp/B00BCRG22A/?tag=contentportfo-20)** (~$169), Complete beginner solar kit, 200W monocrystalline panel, charge controller, and mounting hardware included.
- **[Renogy 2×100W Monocrystalline Solar Panels](https://www.amazon.com/dp/B07JXYTFF7/?tag=contentportfo-20)** (~$99), Expandable 200W panel set from the most trusted DIY solar brand, used widely in off-grid and home backup systems.
