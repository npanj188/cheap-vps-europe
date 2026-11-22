# Best cheap VPS Europe: what €2–€13 a month actually buys, which plan fits Docker or Nextcloud, and the billing details to check before you pay

A €2 monthly plan gets you 1 vCPU, 1 GB RAM and 15 GB NVMe at Ava Hosting. €13.33 gets you 8 vCPU and 24 GB RAM at Contabo. Both are current European prices, and the distance between them explains most of the confusion around cheap VPS shopping in Europe: you are not comparing one market, you are comparing two very different ways of pricing the same box.

Below are the verified plan tables for Ava Hosting (both product lines), a spec-and-price comparison against Contabo, Hetzner, LightNode, IONOS, netcup, OVHcloud and Hostinger, and the parts that most listicles skip: whether an EU data center means anything for GDPR, which providers keep charging you after you shut the server down, and where the cheap plan stops being enough.

> **Quick picks**
> - One small app, a VPN endpoint, a dev box you rebuild often: **Ava Hosting Start, €2/mo** (1 vCPU, 1 GB RAM, 15 GB NVMe, unlimited transfer, free trial).
> - 8 GB RAM with NVMe, ECC memory, weekly backups and DDoS protection: **Ava Hosting VPS Power, €20/mo** (4 vCPU, 8 GB, 90 GB NVMe, 1 Gbps).
> - Cheapest RAM per euro in the EU: **Contabo Cloud VPS 8, €13.33/mo** for 24 GB, verified 10 August 2026, French data center, no EU surcharge.
> - 👉 [See the current Ava Hosting plan list and entry prices](https://my.ava.hosting/aff.php?aff=15562) if you want to compare them side by side before reading further.

## What €2 to €13 a month buys in Europe right now

Cheap European VPS pricing clusters in a band that is wider than most "from $X" ads suggest. HostAdvice's cheap-VPS roundup quotes entry plans at $5–15/month in one place and €2–5/month in its FAQ on the same page, while a separate HostAdvice guide on European providers says many sit at €5–15. Those ranges are not reconcilable, which is why the only numbers worth planning around are the ones a provider prints on its own plan page.

The verified anchors in this market:

- **Ava Hosting Start: €2.00/month** for 1 vCPU, 1 GB RAM, 15 GB NVMe, unlimited transfer, with a free trial offered on the plan page.
- **Ava Hosting VPS One: €5.00/month** for 1 vCPU, 2 GB ECC RAM, 25 GB NVMe, 1 Gbps port, unlimited bandwidth, DDoS protection and weekly backups included.
- **LightNode Start: $7.71/month** for 1 vCPU, 2 GB DDR4, 50 GB NVMe, 1 TB transfer.
- **Contabo Cloud VPS 8: €13.33/month** for 8 vCPU, 24 GB RAM and 400 GB SSD, verified 10 August 2026.

Everything above €15 a month in this segment buys either dedicated cores or a lot more RAM, not a fundamentally different machine.

## Ava Hosting plans and prices

Ava Hosting runs two separate lineups on the same account system, and they are priced identically per gigabyte of RAM. That is the single most useful thing to know before picking one.

### Self-hosted Start: €2 to €40 a month

| Plan | vCPU / RAM | NVMe | Price | Notes | Order |
| --- | --- | --- | --- | --- | --- |
| Start | 1 / 1 GB | 15 GB | €2.00/mo | Unlimited transfer, free trial listed | [Start](https://my.ava.hosting/aff.php?aff=15562) |
| Mini | 1 / 2 GB | 25 GB | €5.00/mo | Unlimited transfer | [Mini](https://my.ava.hosting/aff.php?aff=15562) |
| Basic | 2 / 4 GB | 50 GB | €10.00/mo | Unlimited transfer | [Basic](https://my.ava.hosting/aff.php?aff=15562) |
| Pro | 4 / 8 GB | 100 GB | €20.00/mo | Unlimited transfer | [Pro](https://my.ava.hosting/aff.php?aff=15562) |
| Business | 6 / 12 GB | 150 GB | €30.00/mo | Unlimited transfer | [Business](https://my.ava.hosting/aff.php?aff=15562) |
| Power | 8 / 16 GB | 200 GB | €40.00/mo | Unlimited transfer | [Power](https://my.ava.hosting/aff.php?aff=15562) |

### VPS/VDS: €5 to €40 a month, plus an €11/year plan

| Plan | vCPU / RAM | NVMe | Price | Notes | Order |
| --- | --- | --- | --- | --- | --- |
| VPS Nano | 1 / 512 MB ECC | 20 GB | €11.00/yr | 100 Mbps port, port 25 closed, listed as 0 available | [Nano](https://my.ava.hosting/aff.php?aff=15562) |
| VPS One | 1 / 2 GB ECC | 25 GB | €5.00/mo | 1 Gbps, DDoS, weekly backup, full root | [VPS One](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Basic | 2 / 4 GB ECC | 50 GB | €10.00/mo | 1 Gbps, DDoS, weekly backup, full root | [VPS Basic](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Lucky | 2 / 6 GB ECC | 70 GB | €15.00/mo | 1 Gbps, DDoS, weekly backup, full root | [VPS Lucky](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Power | 4 / 8 GB ECC | 90 GB | €20.00/mo | 1 Gbps, DDoS, weekly backup, full root | [VPS Power](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Extra | 6 / 12 GB ECC | 120 GB | €30.00/mo | 1 Gbps, DDoS, weekly backup, full root | [VPS Extra](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Ultra | 8 / 16 GB ECC | 160 GB | €40.00/mo | 1 Gbps, DDoS, weekly backup, full root | [VPS Ultra](https://my.ava.hosting/aff.php?aff=15562) |

Both lineups work out to **€2.50 per GB of RAM** (VPS One at 2 GB/€5, VPS Power at 8 GB/€20, VPS Ultra at 16 GB/€40), with the €2 Start plan as the single exception at €2.00 per GB.

Data points that follow from that arithmetic:

**The VPS/VDS line is the better buy at almost every level.** At €20 you can have Self-hosted Start's Pro (4 vCPU, 8 GB, 100 GB NVMe) or VPS Power (4 vCPU, 8 GB, 90 GB NVMe). The VPS page additionally lists ECC memory, a 1 Gbps port, free DDoS protection, weekly backups, full root access, a 99.9% SLA and 24/7 support. The Start page lists vCPU, RAM, NVMe and unlimited transfer, and nothing beyond that. Slightly less disk, more stated guarantees, same price.

**VPS Nano is not a usable web server for most people.** €11 a year sounds like the cheapest entry in Europe, but it ships 512 MB RAM, a 100 Mbps port, port 25 closed, and the page showed zero units available at the time of writing. Fine as a DNS or monitoring node if it comes back in stock.

**Ava's prices are listed as "starting from" in euros.** The plan pages do not state whether VAT is included, so the checkout total for your country is the number that matters. 👉 [Open the Ava Hosting plan list](https://my.ava.hosting/aff.php?aff=15562) and compare the price shown for your billing country against the listed figure before you commit to a term.

**The plan pages do not name data center locations.** If a contract or a client requires the server to sit in a specific country, ask support before ordering rather than assuming.

## How the other cheap European providers compare

Prices marked "estimate" come from a Contabo blog comparison published 11 August 2026 that repeatedly tells readers to verify at the provider's own site. Hetzner's own cloud page shows plan specifications but no price figures, only the statement that billing is hourly with a monthly cap, so no Hetzner price is quoted here as fact.

| Provider | Plan and verified specs | Price | Billing and traffic |
| --- | --- | --- | --- |
| Contabo | Cloud VPS 8: 8 vCPU / 24 GB / 400 GB SSD | €13.33/mo (verified 10 Aug 2026) | Shared vCPU, unlimited fair-use traffic, Lauterbourg (France), no EU location surcharge |
| Contabo | Cloud VDS M: dedicated cores | €46.65/mo | Positioned by Contabo itself for production APIs and high-transaction databases |
| Hetzner | CPX32: 4 vCPU / 8 GB / 160 GB | ~€8–12/mo (third-party estimate, not on Hetzner's page) | Hourly billing, monthly price cap, 2 TB traffic, Nuremberg or Helsinki |
| Hetzner | CPX42: 8 vCPU / 16 GB / 320 GB | Not published on the plan page | 3 TB traffic, same billing model |
| LightNode | Premium: 4 vCPU / 8 GB / 50 GB NVMe | $27.70/mo | 3 TB transfer, hourly billing, billing continues after shutdown until the instance is released |
| LightNode | Agency: 2 vCPU / 4 GB / 50 GB NVMe | $14.70/mo | 2 TB transfer |
| IONOS | 8–16 GB tiers | ~€4–8/mo (estimate) | Metered traffic, German/Spanish/UK locations depending on plan |
| netcup | VPS 1000 G10 class | ~€5–9/mo (estimate) | Shared AMD EPYC, roughly 80 TB/month, Nuremberg and Vienna |
| OVHcloud | Entry and Value tiers | ~€7–12/mo (estimate) | Unlimited traffic, anti-DDoS included, France or Poland |
| Hostinger | KVM 4: 8 GB | ~€7–10/mo (estimate) | NVMe, 1–3 TB traffic, Netherlands/Germany/Lithuania |

Hetzner's CPX ladder, for sizing: CPX22 (2 vCPU/4 GB/80 GB), CPX32 (4/8/160), CPX42 (8/16/320), CPX52 (12/24/480), CPX62 (16/32/640), with traffic allowances rising from 1 TB to 5 TB.

The honest summary: **Ava is not the cheapest per gigabyte of RAM in Europe.** Contabo's 24 GB at €13.33 works out to about €0.56 per GB, roughly a quarter of Ava's €2.50. What Ava's price does include at every tier is NVMe rather than SATA SSD, ECC memory on the VPS line, weekly backups, DDoS protection and a 1 Gbps port. If you are buying RAM by the kilo for a Nextcloud instance or a container host, Contabo wins on paper. If you want a smaller box with backups and DDoS filtering already in the price, Ava's €5 to €20 tiers are competitive with what IONOS, netcup and Hostinger are estimated to charge.

## Does an EU data center make you GDPR-compliant?

No. Hosting inside the EU satisfies the data residency question and nothing else. If you process personal data for a client, you still need a data processing agreement under GDPR Article 28, plus access controls, a breach notification path, and a clear answer on where backups and logs physically sit.

Two checks worth doing before you sign, because most "cheap VPS Europe" lists never mention them:

**Corporate ownership matters as much as the rack.** Hetzner's own FAQ puts it plainly: a provider headquartered in the USA remains subject to the US Cloud Act even if the data is stored in Europe, and US authorities can still request access. Their suggested test is to check the provider's headquarters and corporate ownership, not the data center address. A French or German data center run by a US-owned company is a different legal situation from the same rack run by an EU company.

**Location inside the EU is not interchangeable.** Contabo's EU hub is in Lauterbourg on the French-German border, not in Germany. If a contract specifies a German data center, Contabo does not meet it and you need Hetzner (Nuremberg, Falkenstein, Helsinki), IONOS or netcup. Hetzner holds DIN ISO/IEC 27001:2022 certification and states that customer master data is not transferred to third countries, including from its US and Singapore locations.

Worth knowing: Ava Hosting's plan pages do not state a data center country, so this is a question to send to support before you buy if residency is contractual.

## Billing details that change the real monthly cost

**Hourly billing does not always mean you can stop paying by shutting down.** LightNode bills hourly but states in its FAQ that shutting down the VPS stops the server while the resources stay occupied and billing continues; you have to release the instance to stop the meter. If you spin up test boxes and power them off, that distinction is the difference between a $8 month and a $28 month.

**Hetzner bills hourly with a monthly cap.** Its cloud page says the bill never exceeds the plan's monthly price, no minimum contract period, and if you delete a server mid-month you pay only the hourly rate for the hours used. That is the friendlier version of the same model.

**VAT is the missing line in almost every comparison table.** None of the provider tables in circulation, including the ones this article draws on, mark whether the displayed euro or dollar figure includes VAT. EU providers charge VAT based on your billing country, so a €13.33 plan can land noticeably higher at checkout for a private buyer, while a VAT-registered business recovers it.

**"Starting from" usually means the cheapest term, not month-to-month.** Ava lists "starting from" prices, LightNode prices in USD, Contabo in EUR. Check the term length attached to the number you saw before comparing it to another provider's monthly rate.

## Which plan fits your workload

Contabo's own workload table is a fair guide to where shared vCPU plans hold up, and it transfers to any cheap European VPS:

- **Nextcloud, file storage, backup targets:** disk-bound, RAM-hungry. Ava VPS Basic (4 GB, €10) or Contabo Cloud VPS 8 (24 GB, €13.33) if the library is large.
- **Docker with several containers:** 8 GB is the comfortable floor. Ava VPS Power at €20 gives 4 vCPU, 8 GB and 90 GB NVMe with backups included.
- **Development and staging databases:** RAM matters more than cores. 4–8 GB is plenty; CPU steal on shared vCPU barely shows on dev traffic.
- **Self-hosted AI inference on CPU (Ollama, 7B models):** RAM-bound, so Contabo's 24 GB at €13.33 is the value pick here despite the weaker CPU consistency.
- **Production APIs and high-transaction databases:** shared vCPU shows variance under sustained load. Contabo's own guidance points to dedicated cores (Cloud VDS M, €46.65). Ava's VPS line does not advertise dedicated cores, so treat it as shared.
- **Game servers and real-time video:** latency-sensitive workloads want predictable CPU. Cheap shared plans are the wrong category at any price.

## Quick answers

**Is a €2 VPS enough for a website?** For a static site, a small WordPress install with caching, a WireGuard endpoint or a Uptime Kuma instance, yes. 1 GB RAM stops being enough the moment you add a database, a container runtime and a panel on the same box.

**Contabo or Ava for the same money?** At €13 to €20, Contabo gives you three times the RAM and a slower, shared CPU on SATA SSD. Ava gives you NVMe, ECC, weekly backups and DDoS protection on a 1 Gbps port. Pick by whether your bottleneck is memory or I/O and operational peace of mind.

**Do I need a German data center?** Only if a contract, a client or a regulator says so. Otherwise a French, Dutch or Finnish location delivers the same GDPR framework with different latency.

**Can I try before paying?** Ava lists a free trial on the Self-hosted Start page. LightNode bills hourly, which works as a short trial provided you release the instance rather than just powering it off.

## Last checks before you order

Run through these four before entering card details, whichever provider you land on:

1. **The checkout total, not the listed price.** Confirm VAT treatment and the term the price applies to.
2. **The data center country in writing.** Ask support if the plan page does not name it.
3. **Whether shutdown stops billing.** Deletion and power-off are different things at more than one provider.
4. **Whether you need a DPA.** If you handle other people's personal data, the agreement exists before the server does.

For most readers searching this term, the decision comes down to size. A single small service or a VPN box belongs on a €2 or €5 plan and there is no reason to pay more. Anything running Docker with a database, a media library or a handful of containers wants 8 GB, and at that level Ava's VPS Power bundles NVMe, ECC memory, weekly backups and DDoS protection into €20 with no separate add-ons, while Contabo sells you 24 GB for less if raw memory is the whole point.

👉 [Compare Ava Hosting's plans and start with the €5 VPS One or the €20 VPS Power](https://my.ava.hosting/aff.php?aff=15562)
