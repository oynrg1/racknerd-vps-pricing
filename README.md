# Cheap virtual private server hosting: what does $11.29 a year actually buy, will the renewal price jump, and which plan fits one small site? (Full RackNerd plan table, plus the add-on fees most comparison lists skip)

Cheap virtual private server hosting starts around $2 to $4 a month in most comparison lists, and the plans people keep running long-term usually sit between $4 and $100 a month. RackNerd's current KVM specials land under that floor. The smallest is **$11.29 for a full year**, which is $0.94 a month, and the largest of the five is $59.99 a year at $5.00 a month.

Two numbers decide whether a price that low is a good deal or a trap: what the second invoice says, and what the plan cannot do. Both are below.

> **Most readers should take the 2 GB KVM special at $18.29 a year.** It is the cheapest plan in the lineup with enough RAM to run n8n, Coolify, or a small Docker stack next to a website, and every plan includes full root access, a dedicated IPv4, a 1 Gbps port, and the ctrl control panel.
> 👉 [Check the 2 GB KVM special at $18.29/year](https://bit.ly/RacKnerd)

## The full RackNerd VPS specials lineup

Five plans are listed, all KVM virtualized, all billed annually, all with a 1 Gbps network port and one dedicated IPv4 address.

| Plan | vCPU / RAM | SSD storage | Bandwidth | Price (billed yearly) | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM | 1 vCore / 1 GB | 24 GB | 2,000 GB/mo | **$11.29/yr** (≈$0.94/mo) | [1 GB special](https://bit.ly/RacKnerd) |
| 2 GB KVM | 1 vCore / 2 GB | 40 GB | 3,500 GB/mo | **$18.29/yr** (≈$1.52/mo) | [2 GB special](https://bit.ly/RacKnerd) |
| 3.5 GB KVM | 2 vCores / 3.5 GB | 65 GB | 7,000 GB/mo | **$32.49/yr** (≈$2.71/mo) | [3.5 GB special](https://bit.ly/RacKnerd) |
| 4 GB KVM | 3 vCores / 4 GB | 105 GB | 9,000 GB/mo | **$43.88/yr** (≈$3.66/mo) | [4 GB special](https://bit.ly/RacKnerd) |
| 6 GB KVM | 4 vCores / 6 GB | 140 GB | 12,000 GB/mo | **$59.99/yr** (≈$5.00/mo) | [6 GB special](https://bit.ly/RacKnerd) |

Two things about that table are worth pausing on.

The bandwidth allowances are unusually generous. Around 1 TB a month is a normal ceiling on budget plans, and RackNerd's smallest gives you double that, with the bigger plans going far past it. For a personal site, a small store, or a self-hosted app serving a handful of users, you will not approach these limits.

The step from 1 GB to 2 GB costs $7 a year. That is the single best-value upgrade in the lineup, and it is the reason the recommendation above is not the cheapest plan.

### What every RackNerd special includes

The control panel is called ctrl, and it ships with every plan. From it you can reboot, reinstall the operating system, open an out-of-band HTML5 VNC console, reset the root password, set inbound firewall rules, install one-click apps, and upgrade the plan later. If you prefer the command line, full root SSH access is there and nothing forces you through the panel.

Operating system choices are CentOS, Rocky Linux, AlmaLinux, Fedora, Debian, and Ubuntu. A custom ISO install can be requested through a support ticket, and the VNC console means you can install from your own media if you need something outside the list.

The one-click catalogue covers the apps people actually self-host right now: AdminBolt, CyberPanel, and CloudPanel for WordPress, plus n8n, Coolify, Ollama, LibreChat, AnythingLLM, Hermes Agent, and OpenClaw. Docker with Portainer installs in a click, and a custom stack over SSH is always an option.

These are unmanaged servers. You get root and the panel; you do not get someone to debug your WordPress plugin. Support runs 24/7 for platform issues.

## The starting price is not the bill

Hostinger's KVM 1 is the cleanest example of why the sticker price misleads. The plan shows $19.49 discounted to $6.49/mo, and the checkout line reads: you pay **$155.76 for 24 months today, renewing at $11.99/mo for the same term**. Two years at the renewal rate is $287.76, or $132 more than the first two years. The advertised $6.49 sits 85% below what the plan actually costs once the intro period ends.

That is a normal trade of discount for commitment, not a trick. It does mean any "cheapest VPS" list ranking providers on the headline number is measuring the wrong figure.

RackNerd's arrangement is described differently by people who have stayed. Long-term customers report that the promo rate carries into renewal as long as you renew before the expiry date, and that letting a plan lapse and buying again puts you on standard pricing instead. One reviewer describes paying a fifth annual renewal without a change. Treat that as a reported pattern rather than a written guarantee, and confirm the renewal figure at checkout, but it is the opposite of the Hostinger model and it changes the three-year math completely: $18.29 once versus $18.29 every year is the whole cost, not a teaser.

👉 [See the current RackNerd specials in full](https://bit.ly/RacKnerd)

### Add-ons that quietly raise a cheap bill

Prepaid price is only one line on the invoice. IONOS, which advertises VPS hosting from $4/mo, prices the extras separately:

- Cloud Backup from **$0.065/GB/month**, so backing up a 60 GB server adds roughly $3.90 a month, which is close to the cost of the server itself
- Plesk Obsidian Web Host Edition at **$6/month**, and it needs at least 20 GB of storage on Linux or 32 GB on Windows
- Additional IPv4 addresses at **$5/month each**

Liquid Web charges extra for cPanel on top of its $11/mo entry plan, and Hostwinds' cheapest tier ships without an SSL certificate. None of these are dealbreakers, but a $4 plan with $8 of backup and panel fees is a $12 plan.

RackNerd's ctrl panel is included rather than licensed on top, which removes one of those line items. Nothing on the specials page describes a trial or a money-back window, so treat the annual prepay as committed spend and read the terms on the order page before paying. If a refund window matters more to you than price, Hostinger offers 30 days and Hostwinds three days, while a Liquid Web comparison list records DigitalOcean as not offering refunds at all.

👉 [Order the 1 GB special at $11.29/year for a single small site](https://bit.ly/RacKnerd)

## What a sub-$1 VPS actually gives you

A plan this cheap is not a smaller version of a $40 server. It is a different class of hardware allocation, and knowing which class you are buying prevents most of the disappointment.

**Shared CPU, not a reserved core.** DigitalOcean's $4 tier and its $7 Premium tier both run on shared CPU, where the host adds capacity as load rises and you compete with other tenants on the same physical machine. Dedicated CPU at DigitalOcean starts at $42/mo for a CPU-optimized droplet. RackNerd does not publish a per-core reservation for these specials, and at $0.94 a month you should assume shared-class compute with guaranteed RAM and disk. Brief CPU steal during peak hours on busy nodes is the tradeoff long-term reviewers mention. For a website or a light app that is fine. For video encoding or a busy database it is not, and no $1 plan from anyone will be.

**Storage varies more than the price suggests.** Entry plans across the budget market run from 10 GB to 120 GB of SSD, and 24 GB on the $11.29 plan is on the smaller side of that spread. The 4 GB and 6 GB plans at 105 GB and 140 GB are where storage stops being a constraint.

**You are buying isolation and control, not raw speed.** The reason to move off shared hosting is root access, your own OS, and memory that another customer's traffic spike cannot consume. DigitalOcean draws the same line: shared hosting gives no root access, a VPS gives you a dedicated virtual server you configure yourself.

**Disk performance is not uniform across nodes.** Reviewers of these specials report sequential writes above 1 GB/s on some nodes and around 125 MB/s on others, with monitored uptime in the 99.9% to 99.993% range. That is normal variance for budget infrastructure, and it is why the plan you land on matters as much as the plan you buy.

## Which plan fits which job

RackNerd publishes RAM minimums for its one-click apps, which turns plan selection into arithmetic instead of guesswork:

- **OpenClaw needs at least 8 GB.** That is above every plan in this lineup, so it is not a fit here.
- **Ollama, LibreChat, AnythingLLM, and Hermes Agent need at least 4 GB.** The 4 GB plan at $43.88/yr is the cheapest option that clears the bar. The 3.5 GB plan at $32.49 will install and may run a small model, but you are under the stated minimum from day one.
- **n8n and Coolify are comfortable from 2 GB.** The $18.29/yr plan handles either one alongside a website.
- **A static site, a small WordPress install, a VPN endpoint, a DNS server, or a monitoring node** runs fine on the 1 GB plan at $11.29.
- **Multiple apps on one box, or a site with real traffic**, is where the 6 GB plan at $59.99 starts earning its price.

## How RackNerd compares with the bigger names

The point of this table is what each entry price actually covers, not a ranking.

| Provider | Entry price | What the entry plan includes | Catch worth knowing |
| --- | --- | --- | --- |
| RackNerd | $11.29/yr (≈$0.94/mo) | 1 vCore, 1 GB RAM, 24 GB SSD, 2,000 GB/mo, 1 Gbps | Unmanaged, Linux only, annual prepay |
| IONOS | $4/mo | NVMe SSD, unlimited traffic up to 1 Gbps, 99.99% availability, Windows Server 2022/2025 available | Backup from $0.065/GB/mo, Plesk $6/mo, extra IPv4 $5/mo |
| DigitalOcean | $4/mo | Shared-CPU droplet; $7/mo for 1 GB RAM, 1 vCPU, 25 GB NVMe, 1 TB transfer | Entry tier shares CPU; one comparison list records no refunds |
| Hostinger | $6.49/mo | KVM 1 on a 24-month prepay of **$155.76** | Renews at $11.99/mo; no Windows VPS; unmanaged |
| Liquid Web | $11/mo | 1 vCPU, 2 GB RAM, 60 GB SSD, 2 TB bandwidth | cPanel billed separately; CPU-optimized tiers run to $392/mo |

One number in this table deserves a note: a Liquid Web comparison list records IONOS starting at $2, while the IONOS site itself shows $4. The two figures likely reflect a promo price and a standard price, and the comparison list does not describe the $2 configuration, so the official $4 is the safe reference.

## Who should not buy one of these

**You need Windows.** The RackNerd OS list is Linux. Custom ISOs are available by ticket, but if you want a licensed Windows Server 2022 or 2025 image as part of the product, IONOS offers both and RackNerd does not advertise it.

**You want a managed server.** These are unmanaged. If you would rather not run updates and troubleshoot a stack, Hostinger's own documentation draws the distinction clearly: their managed cloud hosting handles security, while their VPS plans give you root and leave the administration to you.

**You need hourly billing or elastic scaling.** Liquid Web bills cloud VPS hourly from $0.015, and DigitalOcean bills by the second with automatic scaling on some plans. Yearly prepay is a poor fit for a two-week experiment.

**You want a free trial first.** Kamatera's 30-day trial (up to $100 of resources) and Mikr.us' free 256 MB plan exist precisely for testing before paying. Nothing on RackNerd's specials page matches that.

## FAQ

**Is $11.29 a year real, or is something missing?**
It is a real annual price for a 1 vCore, 1 GB RAM, 24 GB SSD KVM server with 2,000 GB monthly transfer, a dedicated IPv4, and root access. What is missing is management and a Windows option, not hardware.

**Do I have to pay for a full year?**
These specials are listed with annual prices, so budget the full year upfront. The flip side is that $18.29 once covers twelve months, which is what makes the monthly equivalent $1.52.

**Can I upgrade the plan later without losing data?**
ctrl includes an upgrade option, and you can reinstall the OS from the same panel or boot the HTML5 VNC console for a custom install. Upgrading is a normal operation on these plans rather than a migration project.

**Will it run WordPress?**
Yes. AdminBolt, CyberPanel, and CloudPanel are one-click installs, or you can install your own stack over SSH. On 1 GB, keep plugins lean; on 2 GB you have room to breathe.

**Is 1 GB of RAM enough?**
For a single small site, a VPN, or a DNS server, yes. For n8n, Coolify, or anything running Ollama, no: the published minimums are 2 GB and 4 GB respectively.

**What happens if I let the plan expire?**
Reviewers describe the promo rate applying when you renew before expiry, with standard pricing applying if you let it lapse and repurchase. Set a calendar reminder rather than relying on a grace period.

## Before you order

Match the plan to the app, not to the price. A single site or a lightweight service takes the 1 GB special at $11.29. Anything involving n8n, Coolify, or Docker deserves the 2 GB at $18.29, which is $7 more for the year. A local model or an AI agent stack with a 4 GB minimum means the $43.88 plan, and OpenClaw's 8 GB requirement puts it outside this lineup entirely.

Then confirm two things at checkout: the total annual charge with the renewal terms attached to it, and whether anything you assumed was included is actually a paid add-on. RackNerd bundles ctrl, which covers the panel line item; backup and control panel licensing are where other providers add $4 to $9 a month to a $4 plan.

👉 [Compare the RackNerd plans starting at $11.29/year](https://bit.ly/RacKnerd)
