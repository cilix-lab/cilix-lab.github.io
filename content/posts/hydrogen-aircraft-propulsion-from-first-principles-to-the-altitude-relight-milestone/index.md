---
title: "Hydrogen Aircraft Propulsion: The Altitude Relight Milestone"
date: 2026-06-19T12:33:21+00:00
draft: false
author: "C."
tags: ["hydrogen aviation", "hydrogen combustion", "fuel cells", "GE Aerospace", "altitude relight", "Clean Aviation"]
categories: ["Aviation", "Energy"]
summary: "Hydrogen propulsion moves from concept to tested reality as GE Aerospace achieves the first altitude relight of a hydrogen jet engine, a critical certification gate."
---

## Executive Summary

Hydrogen propulsion has moved from a speculative concept to an actively tested engineering discipline. Two distinct technical routes are being pursued in parallel: **hydrogen combustion** (burning H₂ in modified gas turbines) and **hydrogen fuel cells** (electrochemically converting H₂ to electricity that drives electric motors). A third hybrid approach combines both. Each carries a different maturity level, weight penalty, and commercial timeline.

The industry is no longer purely speculative. As of 2024 to 2026, multiple aircraft have flown on hydrogen power, major OEMs (Airbus, GE Aerospace, Rolls-Royce, Pratt and Whitney) have active programs, and a dense network of well-funded startups is accelerating regional and commuter-scale demonstrations. Government backing is substantial: the EU's Clean Aviation Joint Undertaking, NASA's Sustainable Flight National Partnership, and national programs in the UK, Germany, Japan, and South Korea are all funding hydrogen aviation R&D.

In June 2026, GE Aerospace and Avio Aero achieved a landmark: the world's first successful restart of a hydrogen-fueled jet engine under simulated high-altitude conditions. That test, conducted at the DLR Institute of Space Propulsion in Lampoldshausen, Germany, under the EU-funded [HYDEA project](https://www.geaerospace.com/external-funding/hydrogen-demonstrator-for-aviation), addressed one of the most formidable technical barriers on the certification roadmap and is the primary subject of the latter portion of this report.

The critical bottlenecks are not primarily aeronautical. They are infrastructural and economic: liquid hydrogen storage demands cryogenic tanks that add weight and volume; airport hydrogen fueling infrastructure is nearly nonexistent at scale; and green hydrogen remains 3 to 5 times more expensive per unit energy than jet fuel. The realistic commercial entry point is **regional aircraft (under 100 seats) by the early to mid 2030s**, with narrowbody application (Airbus's stated ambition) targeting 2035 at the earliest.

---

## Part I: The Technology

### 1A. Hydrogen Combustion (H₂ Turbines)

Hydrogen can be burned directly in gas turbine engines, replacing or blending with conventional jet fuel. The combustion chemistry is fundamentally different: H₂ burns hotter and faster, with a much wider flammability range, producing water vapor instead of CO₂ but generating elevated **NOₓ emissions** due to high flame temperatures. Key engineering challenges include:

- **Fuel injector redesign** to handle H₂'s low density and high reactivity
- **NOₓ mitigation** through lean-burn combustor architectures and water injection
- **Materials compatibility** (hydrogen embrittlement of metal alloys is a known risk)
- **Fuel system safety** (H₂ is odorless, colorless, and has a wide explosive range)
- **Altitude relight** (restarting an engine in the thin, cold, dry air at cruise altitude, a certification requirement that only GE has now demonstrated)

**Maturity:** Highest among hydrogen propulsion routes for large aircraft. Rolls-Royce and easyJet completed ground tests of a converted AE 2100 turboprop on 100% hydrogen at MoD Boscombe Down in 2022. In 2023, Rolls-Royce followed up with a full annular combustor test from a Pearl engine at DLR Cologne under conditions representing maximum take-off thrust. In 2026, the pair completed a full simulated flight cycle at NASA's Stennis Space Centre, the first time a modern engine of this class has run on hydrogen across all major operating phases. GE Aerospace and CFM International (GE plus Safran) are running hydrogen combustion rig tests under the RISE program, with the June 2026 altitude relight test representing the most recent and technically significant milestone.

### 1B. Hydrogen Fuel Cells (H₂-Electric)

Proton Exchange Membrane (PEM) fuel cells convert hydrogen and oxygen electrochemically, producing electricity, water, and heat, with zero direct CO₂ or NOₓ emissions. The electricity drives electric motors coupled to propellers or fans. Advantages include high efficiency at partial load and near-zero local emissions. Disadvantages:

- **Power density** of current PEM stacks is insufficient for large aircraft (roughly 2 to 3 kW/kg vs. the ~5 to 8 kW/kg needed for regional viability, ~8 to 10 kW/kg for narrowbodies)
- **Thermal management** (fuel cells generate significant waste heat that must be rejected)
- **Cryogenic liquid hydrogen (LH₂) storage** adds system complexity and boil-off losses
- **Stack durability** under aviation vibration and pressure cycling is unproven at scale

**Maturity:** Demonstrated at commuter/regional scale. [ZeroAvia flew a 19-seat Dornier 228](https://zeroavia.com/do228-first-flight/) on a hydrogen fuel cell powertrain on January 19, 2023, at Cotswold Airport in Gloucestershire, UK, the largest aircraft ever flown on a hydrogen-electric powertrain at the time. [H2FLY (Stuttgart, Germany, Joby-acquired)](https://www.h2fly.de/2023/09/07/h2fly-and-partners-complete-worlds-first-piloted-flight-of-liquid-hydrogen-powered-electric-aircraft/) completed the world's first piloted flights of a liquid hydrogen-powered electric aircraft in September 2023, with their HY4 demonstrator achieving one flight of over three hours at Maribor, Slovenia, not the "6+ hours" that has circulated in some secondary reporting. [Universal Hydrogen](https://www.geekwire.com/2024/report-universal-hydrogen-runs-out-of-runway/) conducted taxi and flight tests of a converted **De Havilland Canada Dash 8-300** (not, as sometimes incorrectly stated, an ATR 72, which was their planned commercial product) in 2023 before the company wound down operations in July 2024 after burning through $100M in funding.

### 1C. Hybrid Systems

Several developers are pursuing architectures that combine a hydrogen fuel cell with a small gas turbine or battery buffer, using the fuel cell for cruise efficiency and the turbine or battery for peak power demands during takeoff and go-around. This approach relaxes the power density requirement on the fuel cell stack and improves overall system resilience. It is particularly relevant for the 2030 to 2040 transition window before pure fuel cell stacks reach the power density needed for larger aircraft. GE Aerospace's AMBER project (detailed below) is a megawatt-class example of this architecture.

### 1D. The Liquid Hydrogen Storage Problem

All three routes converge on the same fundamental constraint: the need to carry liquid hydrogen on board.

- **Gaseous H₂ (GH₂):** Simpler to handle, but volumetrically impractical for meaningful range. Tanks would be prohibitively large.
- **Liquid H₂ (LH₂):** Energy density by volume is far superior, but requires cryogenic storage at −253°C, specialized insulated tanks (typically cylindrical, not wing-integrated), boil-off management, and ground handling infrastructure that does not currently exist at commercial airports.

The tank integration problem is arguably the single largest airframe design challenge: LH₂ tanks cannot fit in conventional wing structures, forcing fuselage redesigns (rear fuselage pods, blended-wing-body concepts, or stretched fuselages) that affect aerodynamics, passenger capacity, and certification. Current cryogenic tank systems add 30 to 50 percent weight overhead compared with kerosene tanks for equivalent energy, eroding hydrogen's energy-density advantage.

---

## Part II: The Competitive Landscape

### 2A. Major OEMs

| Company | Program | Approach | Target |
|---|---|---|---|
| **Airbus** | ZEROe | Combustion plus fuel cell (parallel tracks) | Narrowbody entry ~2035 |
| **Rolls-Royce / easyJet** | H₂ZERO / UltraFan | H₂ combustion, AE2100 plus Pearl plus UltraFan | Ground test to NASA Stennis full cycle 2026 |
| **GE Aerospace / CFM** | RISE plus HYDEA | H₂ combustion rig tests; altitude relight demonstrated | 2030s engine readiness |
| **Pratt & Whitney** | H₂ combustion R&D | Combustor development, H₂-SLATE concept | Research phase |
| **MTU Aero Engines** | Water-Enhanced Turbofan (WET / SWITCH) | H₂ combustion plus steam injection | 2035 and beyond |

### 2B. Startups and Scale-Ups

| Company | Aircraft | Approach | Status (2025 to 2026) |
|---|---|---|---|
| **ZeroAvia** (US/UK) | ZA-600 (19-seat), ZA-2000 (40 to 80 seat) | PEM fuel cell plus electric | Certified demo flown; ZA-2000 in ground test |
| **H2FLY / Joby Aviation** (Germany) | HY4 demonstrator | Liquid H₂ fuel cell | World-first LH₂ flight 2023; commercialization phase |
| **Destinus** (Switzerland) | Supersonic H₂ demonstrator | H₂ combustion | Subscale flight tests |
| **Natilus** | Blended-wing-body cargo | H₂-compatible design | Prototype phase |

Universal Hydrogen's shutdown in July 2024 (despite a $100M raise, backers including GE Aviation, American Airlines, and the venture arms of Airbus, JetBlue, and Toyota, and 13 successful flight tests of their Dash 8-300 testbed) stands as the field's sharpest cautionary data point. The gap between demonstration and commercial certification proved far wider and more capital-intensive than early projections suggested.

### 2C. Government Programs

- **EU Clean Aviation JU:** €1.7B+ program; hydrogen propulsion is a core pillar alongside SAF and hybrid-electric. HYDEA and AMBER are flagship projects.
- **UK Aerospace Technology Institute (ATI):** FlyZero study concluded hydrogen is the most viable zero-emission route for medium-range aircraft; funding ZeroAvia and others through HyEST, RACHEL, and LH2GT programs.
- **NASA (US):** Sustainable Flight National Partnership includes H₂ combustion and fuel cell research; Stennis Space Centre provided infrastructure for the Rolls-Royce/easyJet full flight-cycle test in 2026.
- **Germany (BMBF/BMWi):** Funding H2FLY, DLR hydrogen aviation research, LUFO 6 WOTAN program for Rolls-Royce.
- **Japan (JAXA/NEDO):** Hydrogen aviation roadmap targeting domestic routes by 2030s.
- **South Korea (KARI):** National hydrogen aircraft development initiative launched 2023.

---

## Part III: Demonstrated Milestones

### What Has Flown

| Platform | Operator | Propulsion | Date | Significance |
|---|---|---|---|---|
| DLR Antares DLR-H2 | DLR (Germany) | Fuel cell motorglider | 2009 | Often overlooked proof-of-concept; longest-standing hydrogen aviation heritage |
| Piper Malibu testbed | ZeroAvia | Fuel cell (gaseous H₂) | 2020 | ZeroAvia's 6-seat first-generation demo |
| HY4 demonstrator | H2FLY / Joby | LH₂ fuel cell | 2016 (GH₂), 2023 (LH₂) | World-first piloted LH₂ electric flight; one flight exceeding three hours |
| Dornier 228 (19-seat) | ZeroAvia | PEM fuel cell hybrid | Jan. 19, 2023 | Largest aircraft on H₂-electric at time of flight; Cotswold Airport, UK |
| De Havilland Dash 8-300 | Universal Hydrogen | Fuel cell megawatt-class | Mar. 2, 2023 | 40-seat-class aircraft; Moses Lake, WA; 13 successful flights before company closure |
| AeroDelft Phoenix | AeroDelft (TU Delft) | LH₂ fuel cell | 2023 | Student-built; further broadens the hydrogen-capable developer base |

### What Is in Testing or Near-Term

- **ZeroAvia ZA-2000** powertrain (40 to 80 seat class): Ground testing underway; targeting certification ~2027 to 2028
- **Airbus ZEROe A380 LH₂ testbed**: Cryogenic fueling and tank tests ongoing; flight test window 2026 to 2028 using A380 MSN1
- **CFM RISE open fan A380 flight demonstrator**: Planned for late 2020s through the TAKE OFF and OFELIA Clean Aviation projects
- **Rolls-Royce UltraFan**: Following 2026 Stennis full-cycle hydrogen test, knowledge feeds into UltraFan development targeting service entry ~2030
- **MTU WET engine concept**: Component testing phase

---

## Part IV: Critical Challenges

### Technical

1. **Gravimetric efficiency of LH₂ tanks:** Current cryogenic systems add 30 to 50 percent weight overhead vs. kerosene tanks for equivalent energy, eroding hydrogen's energy-density advantage.
2. **Fuel cell power density gap:** PEM stacks need to reach ~5 to 8 kW/kg (from ~2 to 3 kW/kg today) for regional viability; solid oxide fuel cells (SOFC) offer higher density but slower response.
3. **NOₓ from H₂ combustion:** Burning H₂ at high temperatures still produces NOₓ; lean-burn and catalytic combustion R&D is active but not mature.
4. **Altitude relight** *(now partially addressed, see Part V)*: Restarting a hydrogen-fueled engine in cold, low-pressure, low-humidity cruise conditions is a mandatory certification gate that has historically been the single largest open risk item for hydrogen combustion.
5. **Boil-off and dormancy:** LH₂ continuously evaporates; aircraft cannot sit on the ground for extended periods without venting, creating safety and operational constraints.
6. **Certification pathways:** No comprehensive regulatory framework exists for LH₂ aircraft. EASA and FAA are developing Special Conditions, but the process will take years.

### Infrastructure

1. **Airport hydrogen supply:** Only a handful of airports globally have any hydrogen fueling capability; building out LH₂ infrastructure at even the top 50 airports would require tens of billions in investment. Early movers (Amsterdam Schiphol, London Heathrow, Frankfurt) are in feasibility studies.
2. **Green hydrogen cost:** At $4 to $8/kg (2024 range for green H₂), hydrogen fuel costs are 3 to 5 times jet fuel on an energy basis; the IEA projects green H₂ could reach $1 to $2/kg by 2050 under optimistic electrolyzer scaling scenarios.
3. **Supply chain:** Liquid hydrogen production, liquefaction (energy-intensive), transport, and storage at airports is an entirely new logistics chain with no commercial precedent at aviation scale.

### Competitive Dynamics and Investor Risk

The failure of Universal Hydrogen in 2024 is the industry's clearest signal that demonstration-to-certification costs are systematically underestimated. Investors should calibrate capital requirements accordingly. Conversely, ZeroAvia's continuation of flight testing into 2025 to 2026 (including the first Cotswold-to-Oxford A-to-B flight of the Dornier 228) demonstrates that sustained, well-funded programs can keep advancing. The commercial entry window for fuel-cell regional aircraft (2028 to 2033) is tighter than many realize, and ZeroAvia's ZA-600 certification path remains the most advanced in that space.

---

## Part V: The GE Aerospace / Avio Aero Altitude Relight Milestone

### Context

This is the test result the field has been waiting for. Every hydrogen combustion roadmap carried altitude relight as an unresolved risk item, the one certification requirement for which no hydrogen engine developer had established even a baseline data set. That changed in June 2026.

### The Announcement

On June 10, 2026, at ILA Berlin, [GE Aerospace announced](https://www.geaerospace.com/news/press-releases/avio-aero-and-ge-aerospace-complete-clean-aviation-test-milestones-europe-advance) that Avio Aero and GE Aerospace teams had completed two milestone test campaigns in Germany, both conducted under the EU's Clean Aviation public-private research initiative and both feeding the CFM International RISE technology demonstration program.

> "Avio Aero and GE Aerospace teams in Europe are proud to be at the forefront of new technology innovation. Together with our European partners and research institutions, we're turning ideas into real, tested capability."
>
> Luca Bedon, Head of Research and Technology, Avio Aero

### The HYDEA Test: What Was Achieved and How

The first milestone was the altitude relight test under the [HYDEA (HYdrogen DEmonstrator for Aviation)](https://www.clean-aviation.eu/hydea) project, coordinated by Avio Aero and including 29 consortium members: Airbus Operations SAS, Safran Aircraft Engines, universities, SMEs, and research institutions across Europe.

The test addressed what GE itself described as "one of the most demanding requirements for flying with hydrogen: the ability to relight an engine quickly and reliably in thin, cold air at high altitude." It was conducted at the [DLR Institute of Space Propulsion in Lampoldshausen](https://www.dlr.de/en/ra/about-us/departments/test-facilities), Germany, a facility with unique altitude simulation infrastructure normally used for European space propulsion testing.

**Why altitude relight is the hardest problem in hydrogen combustion:**

Hydrogen's physical properties make it fundamentally more difficult to ignite at altitude than conventional jet fuel. Its high flame speed can cause flashback (flame propagating back into the injector); its wide flammability range complicates ignition timing; its low molecular weight makes fuel system behavior highly sensitive to pressure; and the cold-soaked engine environment at altitude raises the minimum ignition energy. At cruise altitude, air temperatures can fall below −50°C, air pressure is a fraction of sea level, and the air is extremely dry. Jet-A combustion hardware was never designed to tolerate these conditions in reverse (for relight, not just initial start).

Altitude relight is also not an edge case from an operational standpoint. It is a core certification gate: under both EASA CS-E and FAA Part 33, commercial engines must demonstrate the ability to restart after an in-flight shutdown, whether from fuel exhaustion, compressor stall, or intentional shutdown. No certification authority will approve a hydrogen propulsion system that cannot meet this requirement.

**Test design:**

Working with DLR, the team assembled a purpose-built test configuration:

- **Multi-cup hydrogen sector combustor rig**: Unlike earlier single-cup test configurations used in the HYDEA program's first phase, this campaign used a sector rig that more closely represents real engine geometry. This allowed engineers to observe cup-to-cup flame propagation and igniter-to-flame interactions, dynamics critical to a successful engine-wide relight.
- **Synthetic air generator**: A bespoke system vaporized liquid oxygen and nitrogen to replicate the exact atmospheric composition at flight altitude, including the very low humidity that affects combustion chemistry.
- **Unison ignition system**: Designed and manufactured by Unison (a GE Aerospace company) specifically for hydrogen operation, reflecting the reality that hydrogen's distinct ignition energy requirements demand new component-level engineering, not simply fuel substitution.
- **High-speed optical diagnostics**: DLR's camera systems captured transient flame behavior during the relight sequence, producing data to inform computational models for full-scale combustor design.

**Outcome:**

The campaign successfully **mapped a relight operability envelope**, a defined region of altitude, pressure, and temperature within which the engine can be reliably restarted. This envelope now serves as the design basis for the next phase: a full annular hydrogen combustor test rig.

This is arguably the single most significant technical derisking event on the hydrogen combustion roadmap to date. The industry now has an initial dataset to present to EASA and FAA, a necessary first step in defining certification means of compliance for hydrogen propulsion.

### The AMBER Test: Parallel Milestone

The second milestone announced at ILA Berlin was the completion of fuel cell system testing under the [AMBER (AdvancEd Megawatt HyBrid ElectRic propulsion demonstrator)](https://www.geaerospace.com/external-funding/amber) project. At DLR's BALIS test facility, teams validated:

- Dynamic behavior of a megawatt-class fuel cell system from idle to maximum power in short transient times
- System resilience under multiple power modes simulating both short- and long-range flight operations

> "We're proud to partner with DLR and others around the world to advance the building blocks to help make hybrid electric flight a reality."
>
> Roman Seele, Future of Flight Leader, GE Aerospace Germany

The AMBER result reinforces GE's "portfolio" thesis: no single technology (hydrogen combustion, fuel cells, or advanced engine architectures) is likely to decarbonize aviation alone. The path forward integrates multiple solutions across aircraft segments and time horizons.

### The Broader GE / CFM / Clean Aviation Program Architecture

The HYDEA and AMBER tests sit within a larger set of four Clean Aviation projects being advanced in parallel, all feeding the CFM RISE technology demonstration program:

| Project | Technology Focus | Lead | Scope |
|---|---|---|---|
| **HYDEA** | Hydrogen combustion in gas turbines | Avio Aero | Ground test demonstrator; EASA engaged from Phase 1 |
| **AMBER** | Megawatt-class hybrid-electric propulsion | Avio Aero / GE Munich | Fuel cells plus power electronics |
| **TAKE OFF** | Open Fan ground demonstrator | Safran Aircraft Engines | RISE open fan ground test |
| **OFELIA** | Open Fan flight test demonstrator | Safran Aircraft Engines | RISE open fan flight test; Airbus A380 testbed |

### Organizational and Geographic Footprint

The HYDEA test campaign drew on GE Aerospace engineering centers across four countries (Germany, Italy, Poland, and Türkiye) and drew on DLR's unique altitude simulation infrastructure at Lampoldshausen. This distributed model satisfies the political requirements of EU Clean Aviation funding while granting access to specialized national test facilities unavailable at any single site. The HYDEA consortium itself comprises 29 participants (per Avio Aero's own reporting), including Airbus Operations SAS, whose involvement explicitly links the combustor work to the ZEROe hydrogen aircraft concept targeted for 2035.

### Regulatory Engagement

The HYDEA project [incorporates early and ongoing dialogue with EASA](https://www.arttic-innovation.de/en/funded-projects/hydea/). Hydrogen propulsion introduces novel certification questions (fuel system cryogenic safety, hydrogen-specific NOₓ and contrail emissions, ground handling protocols) that existing regulatory frameworks do not fully address. Proactive engagement now, years ahead of entry into service, represents a deliberate strategy to avoid the certification bottlenecks that have delayed other novel propulsion concepts.

---

## Part VI: Implications

### For the Aviation Industry

The successful HYDEA test signals that hydrogen combustion in gas turbines, not only hydrogen fuel cells, remains a viable, actively progressing pathway to zero-CO₂ aviation for narrowbody and potentially widebody aircraft segments. It strengthens the credibility of the Airbus ZEROe 2035 timeline and validates the Clean Aviation Joint Undertaking's decision to fund multiple parallel technology tracks.

**Airlines** face a bifurcated future: SAF-powered conventional aircraft for medium/long-haul through the 2030s to 2040s, with hydrogen potentially viable for short-haul and regional routes by the mid-2030s. Fleet planning decisions made today lock in infrastructure commitments for 20 to 30 years.

**Engine manufacturers** face the most disruptive scenario: hydrogen combustion preserves their core competency (turbomachinery) but requires fundamental redesign; fuel cell adoption could commoditize propulsion and shift value to systems integrators.

**Airports** that do not begin hydrogen infrastructure planning now risk being late movers when hydrogen-capable aircraft enter service.

### For Certification and Regulation

With a relight envelope now established, the industry has an initial dataset to present to regulators. This accelerates the iterative process of defining certification means of compliance for hydrogen propulsion, a process that will require new consensus between EASA, FAA, and industry. The test also provides a benchmark against which other hydrogen combustion developers will need to measure their own progress.

EASA and FAA should publish draft Special Conditions for hydrogen-powered aircraft to give developers regulatory certainty. The current lack of a comprehensive framework is a genuine bottleneck.

### For the Fuel Cell vs. Combustion Debate

The parallel HYDEA and AMBER announcements reframe the conversation: the question is not whether fuel cells or combustion will "win," but how they will coexist across different aircraft segments.

- **Combustion** appears better suited to larger aircraft and longer ranges where the power density of a gas turbine remains unmatched.
- **Fuel cells** may dominate regional and shorter-haul applications where higher efficiency at part-load and zero NOₓ emissions provide a decisive advantage.
- **Hybrid approaches** bridge the gap during the 2030 to 2040 transition window.

### For Competitive Dynamics

GE Aerospace's position contrasts with:

- **Rolls-Royce**, which has focused on proving hydrogen combustion in full engine cycles (the 2026 Stennis test) and also supporting hydrogen-electric architectures for smaller aircraft through its UltraFan roadmap.
- **Pratt & Whitney**, which has pursued hydrogen combustion through its combustor development work and more recently through a Canadian presence in Clean Aviation via Pratt & Whitney Canada's PHARES consortium.

The HYDEA altitude relight gives GE a first-mover claim on one of hydrogen combustion's hardest technical problems, potentially influencing partnership and funding decisions across the European R&D landscape.

### For the Green Hydrogen Economy

The viability of hydrogen aviation is inseparable from the green hydrogen economy. Aviation cannot decarbonize via hydrogen unless renewable electricity and electrolyzer capacity scale dramatically. This creates a co-dependency with the power sector, steel, shipping, and other hard-to-abate industries competing for the same green H₂ supply. Government support is not optional: the cost gap between green hydrogen and jet fuel is too large for market forces alone to close on aviation timelines.

---

## Part VII: Commercial Entry Timelines

| Segment | Technology | Realistic Entry |
|---|---|---|
| Commuter (≤19 seats) | Fuel cell | 2026 to 2028 |
| Regional (20 to 80 seats) | Fuel cell / hybrid | 2030 to 2033 |
| Short-haul narrowbody (100 to 150 seats) | H₂ combustion or advanced fuel cell | 2035 to 2040 |
| Medium/long-haul | H₂ combustion (if at all) | Post-2040, highly uncertain |

---

## Key Source Links

- GE Aerospace / Avio Aero HYDEA and AMBER announcement: [geaerospace.com](https://www.geaerospace.com/news/press-releases/avio-aero-and-ge-aerospace-complete-clean-aviation-test-milestones-europe-advance)
- HYDEA project page (Clean Aviation): [clean-aviation.eu](https://www.clean-aviation.eu/hydea)
- HYDEA project description (GE Aerospace): [geaerospace.com/external-funding](https://www.geaerospace.com/external-funding/hydrogen-demonstrator-for-aviation)
- Aerospace Testing International, HYDEA/AMBER coverage: [aerospacetestinginternational.com](https://www.aerospacetestinginternational.com/news/ge-aerospace-and-avio-aero-reach-hydrogen-relight-and-fuel-cell-test-milestones.html)
- Interesting Engineering, altitude restart coverage: [interestingengineering.com](https://interestingengineering.com/innovation/first-hydrogen-engine-restart-for-altitude)
- ZeroAvia Dornier 228 first flight (Jan. 19, 2023): [zeroavia.com](https://zeroavia.com/do228-first-flight/)
- H2FLY / Joby, world's first LH₂ piloted flight (Sep. 7, 2023): [h2fly.de](https://www.h2fly.de/2023/09/07/h2fly-and-partners-complete-worlds-first-piloted-flight-of-liquid-hydrogen-powered-electric-aircraft/)
- Universal Hydrogen shutdown (Jul. 2024): [geekwire.com](https://www.geekwire.com/2024/report-universal-hydrogen-runs-out-of-runway/)
- Rolls-Royce / easyJet, full engine hydrogen test: [easyjet.com](https://www.easyjet.com/en/news/story/easyjet-and-rolls-royce-complete-successful-100-hydrogen-aero-engine-test-advancing-sustainable-flight-technology)
- Airbus ZEROe / CFM RISE A380 demonstrator: [greenairnews.com](https://www.greenairnews.com/?p=2595)

