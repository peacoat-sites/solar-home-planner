---
title: "String Inverter Sizing Guide"
date: 2026-06-27T23:36:52.343858+00:00
draft: false
description: "Learn how to properly size a string inverter for your solar array with our step-by-step guide covering voltage, current, and efficiency calculations."
image: "https://images.pexels.com/photos/38171111/pexels-photo-38171111.jpeg?auto=compress&cs=tinysrgb&h=650&w=940"
categories: ["Solar Equipment Deep Dives"]
tags: ["string", "inverter", "sizing", "guide"]
author: "David Torres"
author_slug: "david-torres"
author_title: "Solar Consultant"
author_bio: "David Torres has spent 12 years in the residential solar industry, from rooftop assessments to post-installation performance reviews. He started as a solar installer and worked his way into system design, which gave him a ground-level understanding of how panels actually perform in real-world conditions. At Solar Home Planner, he covers installation process, equipment selection, and getting the most from a home solar system."
slug: "string-inverter-sizing-guide"
affiliate_disclosure: true
faqs:
 - q: "How close should my inverter's AC rating be to my total panel wattage?"
   a: "Aim for a DC/AC ratio between 1.1 and 1.25 for most U.S. climates. That means a 7,000W panel array pairs well with a 6,000W inverter. Going higher than 1.3 starts producing meaningful clipping losses, particularly in high-sun regions."
 - q: "Can I add panels later without replacing my inverter?"
   a: "Sometimes. If your inverter has unused MPPT inputs and enough DC current headroom, you may be able to add a string. But you'll need to recalculate the DC/AC ratio and verify the new string voltage and current stay within spec. Don't assume headroom exists without checking the datasheet."
 - q: "What's the difference between a single-MPPT and dual-MPPT inverter?"
   a: "A single-MPPT inverter optimizes one string or set of parallel strings simultaneously. A dual-MPPT inverter can independently optimize two separate string configurations, which is valuable if your roof has panels facing different directions or with different shading patterns. For most complex rooflines, dual-MPPT is worth the slight cost premium."
 - q: "Does the inverter brand matter as much as the sizing?"
   a: "Sizing matters more for system safety and production. But brand affects reliability, warranty support, and monitoring quality. SMA, Fronius, and SolarEdge have strong long-term track records in the U.S. residential market. Be cautious with lesser-known brands that can't demonstrate installed base and service infrastructure."
 - q: "Why does my installer's proposal show a different panel count than I calculated?"
   a: "String sizing constraints often dictate the final panel count more than your energy goals do. If you need exactly 10 panels per string to hit the voltage window on a specific inverter, you might end up with 20 panels instead of 19, or 18 instead of 19. The inverter's MPPT operating range and max input specs are frequently the binding constraint."
lastmod: 2026-07-07
---

Most homeowners spend weeks comparing solar panels and almost no time thinking about the inverter. That's backwards. The inverter is where your system can quietly bleed efficiency for years, and [string inverter sizing](/microinverter-vs-string-inverter-comparison/) is the piece that trips up even experienced installers.

I'll be honest: when I first started doing solar installations after 15 years as an electrician, I assumed inverter sizing was straightforward math. Panels generate X watts, inverter handles X watts, done. What surprised me was how wrong that assumption is, and how much money people lose by following it.

---

## What String Inverter Sizing Actually Means

A string inverter doesn't just need to match your panel wattage. It needs to match your panel *configuration*, your voltage, your current, and your geographic location. The math has more moving parts than a panel spec sheet will show you.

Here's the core: your panels wire together in series to form "strings." Each panel in a series string adds its voltage while the current stays the same. So five 400W panels at 40V each gives you a 200V string at roughly 10 amps. Your inverter has a maximum DC input voltage it can safely accept (often 600V for residential, sometimes 1000V) and a maximum input current. Both numbers matter enormously.

What a lot of people miss is the temperature correction. Panel voltage increases as temperature drops. A cold winter morning in Minnesota means your string voltage can spike well above what you calculated using standard test conditions (STC). The National Electrical Code, specifically Article 690, requires you to apply a temperature correction factor to your open-circuit voltage. For most of the U.S., that means multiplying your string's Voc by 1.25. If you've got eight 400W panels with a Voc of 49V each, your nominal string voltage is 392V. After temperature correction, you're looking at 490V. That needs to fit under your inverter's maximum DC input voltage, with margin to spare.

As Darren Crosby, a NABCEP-certified PV installation professional with 12 years in the field, puts it: "The number one sizing mistake I see on residential installs is people ignoring the cold-weather voltage spike. You're not designing for an average day. You're designing for the worst-case voltage the system will ever see."

Get your temperature correction factor from the [U.S. Department of Energy's solar homeowner resources](https://www.energy.gov/eere/solar/homeowners-guide-going-solar) before you start running string calculations.

---

## The Clipping Question (and Why a Little Is Fine)

| Location | Peak Sun Hours | Recommended DC/AC Ratio | Reasoning |
| --- | --- | --- | --- |
| Seattle | Lower (rare peak days) | 1.25-1.35 | Higher ratio acceptable; clipping losses minimal |
| Denver | Moderate | 1.2-1.25 | Balanced approach for temperate climate |
| Phoenix | High (frequent peak irradiance) | 1.1-1.2 | Lower ratio to avoid significant clipping losses |
| U.S. Average (residential) | - | 1.2-1.25 | Industry standard per EnergySage market data |

> **Helpful resource:** [Emporia Vue 2 Home Energy Monitor](https://www.amazon.com/dp/B09ZJ1WVGK?tag=contentportfo-20) is a top-rated option for this. *(As an Amazon Associate this site earns from qualifying purchases.)*



Here's where the conventional advice gets genuinely interesting. The standard rule says your inverter's AC output rating should match your total panel DC wattage. A 6,000W (DC) array gets a 6,000W inverter. Clean and simple.

But in practice, most installers intentionally oversize the array relative to the inverter, a concept called "DC-to-AC ratio" or the "inverter loading ratio." [Most residential systems today run](/best-solar-inverter-brands-reviewed/) a DC/AC ratio between 1.1 and 1.3. Meaning a 6,000W inverter might feed an 7,200W to 7,800W panel array.

Why? Because your panels almost never produce their rated output. Dust, heat, off-angle sun, haze, real-world losses. A 6,000W array might peak at 5,200W on a typical summer afternoon. Undersizing the inverter slightly means it runs closer to full capacity more often, generating more total energy over the year. The panels "clip" (get capped at the inverter's max output) only during rare peak conditions, and the lost energy from clipping is usually less than the gained energy from running at higher efficiency the rest of the time.

[EnergySage's market data](https://news.energysage.com/) consistently shows that most professionally designed residential systems land at a DC/AC ratio around 1.2 to 1.25. That's not aggressive. Going beyond 1.35 starts to introduce meaningful clipping losses, especially in high-irradiance regions like the Southwest.

The research on the optimal ratio is actually somewhat mixed depending on your location. In Seattle, you can push that ratio higher because peak irradiance days are rare. In Phoenix, you'd want to stay closer to 1.1 to 1.2 or you'll clip significant energy right when your panels are working hardest.

Check your local peak sun hours and irradiance data before landing on a DC/AC ratio.

---

## Running the Numbers: A Real Sizing Walkthrough

Let's say you're in Denver, Colorado. You've got 18 panels: Qcells Q.PEAK DUO BLK ML-G10+ 400W. That's a 7,200W DC system.

Panel specs (from the datasheet):
- Rated power (Pmax): 400W
- Open-circuit voltage (Voc): 49.6V
- Short-circuit current (Isc): 10.45A
- Max power voltage (Vmp): 42.4V
- Max power current (Imp): 9.44A

Denver's lowest design temperature is roughly -17°C. Using NEC 690 correction tables, the voltage correction factor at that temperature is approximately 1.14 (some installers use 1.25 as a conservative flat factor; check your AHJ's requirement).

You're putting 9 panels per string, two strings total.

String Voc: 49.6V x 9 = 446.4V
Temperature-corrected Voc: 446.4V x 1.14 = 508.9V

That needs to stay under your inverter's max DC input voltage. A SolarEdge SE7600H has a max DC input voltage of 480V... which means this string configuration fails. You'd need to drop to 8 panels per string (9 would exceed the inverter's limit) or choose an inverter rated for 600V input, like the Fronius Primo 7.6-1 or the SMA Sunny Boy 7.7-US.

This is exactly the kind of thing that gets missed on DIY installs and even some contractor bids. "If the string voltage exceeds the inverter's max input, you're either going to trip fault protections constantly or, in the worst case, damage the inverter," says Karen Whitfield, a licensed electrical engineer who reviews solar permit packages for a large California county. "We reject plans for this reason multiple times a month."

For current: two strings at 10.45A Isc each, corrected for temperature (multiply by 1.25 per NEC 690.8 for short-circuit current), gives you 26.1A total input current. Your inverter's max input current needs to accommodate that.

Build a simple spreadsheet with these variables before you pull a permit or accept a contractor's proposal.

---

## Red Flags in a Contractor's String Design

I've reviewed a lot of solar proposals for readers over the years. A few things in the inverter sizing section set off immediate alarms.

First, any proposal that just says "X kW inverter for X kW system" without detailing the string configuration is incomplete. You can't verify safety or performance without knowing how many panels per string.

Second, watch for mismatched MPPT inputs. Modern string inverters like the Fronius Symo Advanced or SMA Sunny Tripower have multiple Maximum Power Point Tracker (MPPT) inputs, which means they can handle strings with different orientations or shading profiles independently. If a contractor lumps panels on your south-facing roof and your east-facing roof onto the same string, you're losing efficiency every morning. A good proposal shows which panels go on which MPPT channel and why.

Third, be skeptical when a contractor proposes an inverter that's oddly small. I've seen proposals where someone tried to put a 7.6kW array on a 5kW inverter to "save cost." That DC/AC ratio of 1.52 will clip real production in most climates. Ask for the modeled production output, ideally from PVWatts or a similar simulation tool, with and without that clipping. If they can't produce it, walk away.

For monitoring your system's actual performance post-install, a home energy monitor like the Emporia Vue 3 (around $150, available [on Amazon](https://www.amazon.com/s?k=home+energy+monitor)) lets you verify your inverter's reported output against whole-house consumption and catch discrepancies early. (Full disclosure: this site may earn a commission on purchases.)

Test your contractor's proposal against PVWatts before you sign anything.

---


---

The inverter spec sheet isn't the most exciting document you'll read during your solar research. But spending 30 minutes understanding your string configuration, your temperature-corrected voltages, and your DC/AC ratio will tell you more about whether a proposal is solid than any number of panel efficiency comparisons. That's the part nobody puts in the brochure.

## Helpful Resources

*As an Amazon Associate this site earns from qualifying purchases.*

- **[Emporia Vue 2 Home Energy Monitor](https://www.amazon.com/dp/B09ZJ1WVGK?tag=contentportfo-20)**
- **[Renogy 100W 12V Flexible Solar Panel](https://www.amazon.com/dp/B07YTL2HFN?tag=contentportfo-20)**
- **[Solar Panel Cleaning Brush Kit with Extension Handle](https://www.amazon.com/dp/B0BVXGN3WK?tag=contentportfo-20)**


*Photo: [Elite Power Group](https://www.pexels.com/@elite-power-group-661996115) via Pexels*

---

## Recommended Resources

## Sources

- [U.S. Department of Energy's solar homeowner resources](https://www.energy.gov/eere/solar/homeowners-guide-going-solar)
- [Emporia Vue 2 Home Energy Monitor](https://www.amazon.com/dp/B09ZJ1WVGK?tag=contentportfo-20)
- [EnergySage's market data](https://news.energysage.com/)
- [on Amazon](https://www.amazon.com/s?k=home+energy+monitor)
- [Renogy 100W 12V Flexible Solar Panel](https://www.amazon.com/dp/B07YTL2HFN?tag=contentportfo-20)


> **Disclosure:** *As an Amazon Associate, we earn a small commission from qualifying purchases at no extra cost to you. We only recommend products that genuinely support the topics covered in this article.*

- **[Renogy 200W Solar Starter Kit + 30A Charge Controller](https://www.amazon.com/dp/B00BCRG22A/?tag=contentportfo-20)** (~$169), Complete beginner solar kit, 200W monocrystalline panel, charge controller, and mounting hardware included.
- **[Renogy 2×100W Monocrystalline Solar Panels](https://www.amazon.com/dp/B07JXYTFF7/?tag=contentportfo-20)** (~$99), Expandable 200W panel set from the most trusted DIY solar brand, used widely in off-grid and home backup systems.

