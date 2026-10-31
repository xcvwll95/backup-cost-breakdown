# backup for small business: Real Cost Math, What $4/Month Actually Buys, and Who Should Look Elsewhere

Most people searching for backup for small business aren't shopping for a feature checklist. They want two questions answered: what will this actually cost me, and where's the catch. So here are the short versions. Cost, for most small setups, comes down to how much data you have and how many machines need agents. And the catch, in this corner of the market, is usually in the billing structure — which is exactly where most roundups stop explaining.

One concrete option worth understanding before you compare anything: Sharktech, a hosting company that's been running its own data centers since 2003, resells Acronis Cyber Protect as a managed cloud backup. It starts at **$4/month with 200 GB of storage included**, and you configure the exact price in their cart. That entry price is real, but how the billing cycles and overage rates work is the part almost nobody lays out clearly. This article does.

> **Quick pick:** If you run one or two servers and your data sits around 200 GB, the annual cycle works out to about **$2/month** effective. Not sure yet? Start monthly at $4 — it caps your exposure while you verify the setup fits. 👉 [Open the Acronis backup configurator and see your real price](https://portal.sharktech.net/aff.php?aff=1626&pid=648)

## What small-business backup actually has to cover

A workable backup plan has to cover every place your data lives, survive a ransomware event, and end in a restore you've actually tested. The first part trips up more businesses than the technical stuff ever will. Data rarely sits in one spot: laptops, a file server or NAS, Microsoft 365 or Google Workspace mailboxes, whatever accounting or CRM system you pay for. Write the list down before you look at any plan, then check each item against what the plan actually protects. The systems that nobody listed are the ones that surface during a recovery, usually at the worst possible time.

Sharktech's Acronis plan covers machines — physical servers, virtual machines, workstations, and cloud workloads running Windows, Linux, or macOS. It does **not** cover SaaS platforms. If your critical data lives mostly in Microsoft 365 mailboxes or Google Drive, this plan won't touch it, and you'd need a separate SaaS-backup product regardless of which provider you choose. That alone disqualifies it for some businesses, and it's better to know now than after checkout.

## The full pricing table: one product, four billing cycles

Sharktech sells this as a single configurable product rather than a set of named tiers. Every configuration starts with 200 GB of cloud storage, and the only difference between the four "plans" is the billing cycle and the per-GB rate for storage beyond that base:

| Billing cycle | Included storage | Price | Effective monthly cost | Overage rate | Order |
| --- | --- | --- | --- | --- | --- |
| Monthly | 200 GB | $4/month | $4.00 | $0.02/GB | [Configure & order](https://portal.sharktech.net/aff.php?aff=1626&pid=648) |
| Quarterly | 200 GB | $8/quarter | ~$2.67 | $0.04/GB | [Configure & order](https://portal.sharktech.net/aff.php?aff=1626&pid=648) |
| Semi-annual | 200 GB | $12/6 months | $2.00 | $0.06/GB | [Configure & order](https://portal.sharktech.net/aff.php?aff=1626&pid=648) |
| Annual | 200 GB | $24/year | $2.00 | $0.12/GB | [Configure & order](https://portal.sharktech.net/aff.php?aff=1626&pid=648) |

Each link opens the same product configurator, where you pick the billing cycle, storage amount, and data center. All order links in this article go there for that reason.

Two things about this table that most articles quoting "$4/month" never mention.

First, the base-price math is simple and worth internalizing: the annual cycle halves your effective cost from $4/month to $2/month if your storage stays near the 200 GB base. Note that semi-annual and annual land on the same $2.00 effective monthly figure — the difference between them is entirely in the overage rate, which matters only if you grow past the base.

Second, the overage rates are quoted per cycle, which makes them confusing to compare at a glance. A $0.12/GB rate on the annual plan sounds scary next to $0.02/GB on monthly, but those figures apply over different time spans, so don't compare them directly. What you should do is estimate your realistic storage — more protected systems, longer retention windows, and bigger datasets all push the number up — and let the cart configurator price it. The final recurring price only appears in checkout, and Sharktech's own product page says as much.

There's also an optional **Files Sync & Share** add-on that turns the backup target into a Dropbox-style shared drive, priced at $0.03/GB monthly, $0.06/GB quarterly, $0.12/GB semi-annually, or $0.24/GB annually. Pure backup users can skip it; it only earns its cost if your team actually needs collaborative file access on top of backups.

You'll also pick a data center location during configuration: Los Angeles, Las Vegas, Denver, Chicago, or Amsterdam. If your servers already sit in one of those regions, keeping backups nearby shortens restore times.

👉 [Price out your own storage and cycle combination in the configurator](https://portal.sharktech.net/aff.php?aff=1626&pid=648) before committing to anything.

## How the price stacks up

On the entry tier, the "half the cost" claim Sharktech makes on its own blog holds up against the published numbers — though it's worth seeing the comparison laid out.

**Direct from Acronis**, Cyber Backup starts at **$59.67/year** according to PCMag's review, with licensing calculated per type of system backed up. PCMag also flagged that using it as a cloud backup tool can require at least two subscriptions, which is the kind of licensing complexity Sharktech's flat per-GB model sidesteps. Direct Acronis does come with a 30-day free trial, something Sharktech doesn't advertise — a genuine point in Acronis's favor if you want to test before paying anything.

**Liquid Web**, another host offering managed Acronis backups, charges a **$11/month base price plus a storage tier** according to its own pricing page: 100 GB runs $6/month on its own cloud or $11/month on Acronis Backup Cloud, and 1 TB runs $62 or $134/month respectively. Its dedicated-server plans can't go below the 500 GB tier. Do the arithmetic at the entry point: roughly $17/month for 100 GB on the cheapest combination, versus $4/month for 200 GB at Sharktech. Liquid Web bundles more hands-on managed support and 24/7 security staff for disaster recovery, so the premium buys service depth as much as storage.

**Carbonite**, which shows up in most small-business backup roundups, works differently again: it backs up a predefined set of user folders on each connected computer by default, which suits laptop-heavy offices but doesn't give you the full-image, whole-machine recovery Acronis is built around.

The honest summary: if you want the Acronis engine — and some businesses need it on the invoice for compliance or client-trust reasons — Sharktech is the cheapest hosted route to it at small scale, with the tradeoff being a more self-serve experience.

## What you actually get for the money

The service runs on the full Acronis Cyber Protect platform, with Sharktech handling the hosting and support layer. In practice that means:

- **Cross-platform agents** for Windows, Linux, and macOS, plus virtualization environments, all managed from one web console that operates independently of your server control panel.
- **Custom schedules and retention** — you decide when backups run and how long recovery points are kept, with different plans for different systems.
- **Granular recovery**, from a single deleted file to folders to an entire machine, from a recovery point you choose.
- **Ransomware defense on the restore side**: Acronis Cyber Protect scans backups for malware before you restore, so a backup taken after an infection doesn't become a second disaster. Acronis's anti-ransomware technology hooks into the filesystem and blocks malicious tampering in real time — PCMag's coverage notes it was demonstrated blocking WannaCry infections on protected systems. For a small business, this is arguably the feature that justifies paying for Acronis over generic file backup at all.
- **Encryption, compression, and deduplication** to keep storage bills down as datasets grow.

On the infrastructure side, your backups land in Sharktech's own data centers, where DDoS protection is built into the network architecture rather than bolted on, and engineering teams are on-site around the clock. Sharktech's technical support runs 24/7, which matters more for backup than for most services — the moment you need it is the moment a restore is going sideways.

One expectation to set before you buy: recovery time has no fixed guarantee. Sharktech's product page states plainly that it depends on data size and the method you choose. If your business needs a contractual RTO, ask before ordering.

## Who should skip it

Being clear about the fit saves everyone time. Skip this plan if:

- **Your data lives in SaaS.** No Microsoft 365, Google Workspace, or CRM coverage here. You need a SaaS-specific backup product, full stop.
- **You need continuous, real-time backup.** Acronis runs on schedules with incremental backups — PCMag notes it lacks the continuous protection some cloud competitors offer. If files change by the minute and you can't tolerate losing the day's work, look at continuous-protection tools instead.
- **You want a trial or refund window.** Sharktech publishes neither a free trial nor a money-back guarantee for this service, and the absence of refunds is a recurring complaint in its Trustpilot reviews, which sit in the mid-3s out of 5 on a small review base. This is precisely why the $4 monthly cycle exists: it caps your exposure at four dollars while you verify the setup works. If a trial is non-negotiable for you, Acronis's own 30-day trial is the alternative route in.
- **You're at multi-TB or MSP scale.** The per-GB model is built for small workloads. At several terabytes or across many client sites, contact Sharktech for custom pricing rather than assuming the published rates.

## FAQ

**Does the Sharktech Acronis plan back up Microsoft 365 or Google Workspace?**
No. It protects physical servers, VMs, workstations, and cloud workloads through installed agents. SaaS platform data needs a separate backup service.

**How much storage should I actually configure?**
Start from your current data footprint, then add headroom for the three things Sharktech's own page says drive consumption: more protected systems, longer retention periods, and larger datasets. If you're unsure, configure conservatively, watch the usage reports in the Acronis console for a month or two, and adjust capacity as your backup footprint grows — the monthly cycle makes that trial cheap.

**Is there a free trial or refund?**
Neither is published on the product pages. Trustpilot reviewers have flagged the no-refund policy as a consistent complaint. The practical workaround is the monthly cycle — $4 is the cost of finding out.

**Can I restore a single file, or only entire machines?**
Both. You can recover individual files, selected folders, or a complete machine from any retained recovery point, via the Acronis web console or mobile app.

**Where are my backups stored?**
In the Sharktech data center you choose at configuration — Los Angeles, Las Vegas, Denver, Chicago, or Amsterdam — on redundant, high-availability storage behind a DDoS-protected network.

## Before you order

Match the plan to your situation and the decision mostly makes itself. One server, storage steady near 200 GB, and you're confident in the setup → the annual cycle at $24/year is the cheapest credible backup deal in this price class. Storage likely to grow, or you're not sure the workflow fits yet → monthly at $4, then switch cycles once you've watched your real usage in the console. Data in Microsoft 365 → different product category entirely.

The only thing left to check is your own number: total up the machines you're protecting and your realistic storage footprint, then price it in the configurator rather than trusting any article's example — including this one. 👉 [Configure your Acronis backup plan and see the final price](https://portal.sharktech.net/aff.php?aff=1626&pid=648)
