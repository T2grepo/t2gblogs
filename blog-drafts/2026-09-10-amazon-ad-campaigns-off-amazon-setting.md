---
title: "Amazon Quietly Added a Campaign Setting That's Already Changing Your ACOS — Here's How to Rebuild Around It"
date: 2026-09-10
topic: "How to enhance sales through more effective Amazon ad campaigns (targeting, keyword strategy, creative, dayparting, etc.)"
status: draft
---

**Meta description:** Amazon's new "off-Amazon spend" campaign setting and its ROAS auto-bidding beta are reshaping how Sponsored Products budgets get spent. Here's what changed and how to restructure campaigns around it.

Most sellers who logged into Seller Central this month scrolled right past a small, easy-to-miss addition buried in campaign settings: a new group called "Settings for ads served off Amazon," with two options — "Increase reach" (the default) and "Limit off-Amazon spend." If you haven't touched it, Amazon already made the decision for you, and it's been spending your budget accordingly since every existing campaign was auto-enrolled.

This is the kind of change that doesn't show up in a press release but shows up in your ACOS. It's also a useful forcing function to revisit how your campaigns are actually structured, not just how they're bid.

## The Off-Amazon Setting You Didn't Choose

Here's the backstory: in August, Sponsored Products ads started appearing inside content published by creators in the Amazon Influencer Program — reviews, buying guides, roundup posts. Amazon has now formalized control over that exposure at the campaign level. "Increase reach" lets your ads keep showing in that off-Amazon creator content and other off-Amazon placements; "Limit off-Amazon spend" pulls back to on-Amazon placements only.

Two details matter more than the toggle itself:

1. **Amazon infers search terms for off-Amazon impressions.** When your ad shows inside a piece of content with no actual search query behind it, Amazon assigns an inferred term matching your product so it can still report and optimize against something. Your search term report now contains queries no shopper ever typed — and if you're mining that report for negative keywords or new match-type candidates the way you always have, you're now mining partly synthetic data unless you filter it out.
2. **The default favors reach, not efficiency.** Every campaign you haven't touched is running "Increase reach." That's a defensible choice for a brand-awareness or top-of-funnel campaign. It's a bad default for a bottom-funnel, tight-margin ASIN where you're already fighting to keep ACOS under control.

**What to do this week:** Go through your campaigns and make this an explicit, per-campaign decision rather than an inherited default. Flip "Limit off-Amazon spend" on for your efficiency-focused, low-margin, or defensive campaigns; leave "Increase reach" on for the campaigns where incremental visibility is genuinely worth a wider net — new launches, high-margin hero ASINs, categories where you want share of shelf beyond Amazon's own results pages. Then go into your search term reports and strip out anything that looks like an inferred, off-Amazon term before you act on it — treating it as a real shopper query will pollute your negative-keyword list and your keyword harvesting for weeks.

## ROAS Auto-Bidding: Worth Testing, Not Worth Trusting Blindly Yet

The second relevant shift is a bidding option Amazon is beta-testing on select US accounts: a Sponsored Products strategy that drops the base bid entirely. You set a daily budget, no bid and no ROAS target, and Amazon controls bid amount auction-by-auction, optimizing purely for ROAS within that budget ceiling.

It's a meaningfully different animal from the "dynamic bids — up and down" option most sellers already use, which still adjusts a base bid you set by up to 100%. Here, there is no base bid to anchor against — you're handing over the entire targeting-to-bid decision chain for that campaign.

If it's available on your account, this is worth a controlled test, not a wholesale switch:

- Run it on one or two mid-performing campaigns with enough historical conversion data for Amazon's algorithm to have something to work with — not a new launch with zero history.
- Keep a manually-bid control campaign live on a comparable ASIN so you have a real comparison, not a before/after on the same campaign where seasonality or price changes muddy the read.
- Watch impression share and placement mix, not just ACOS. An algorithm optimizing purely for ROAS within a budget cap can quietly shrink your reach to hit the number, which shows up as a great efficiency metric and a shrinking sales base.

## Rebuild Campaign Structure Around What's Actually Changed

Both of these changes point at the same underlying lesson: campaign structure decisions that used to be "set once and revisit quarterly" now need a faster review cadence, because Amazon is shipping placement and bidding changes at the campaign-settings level more frequently than it used to ship changes to the auction itself. Concretely:

1. **Segment campaigns by strategic intent, not just by ASIN or keyword theme**, so a setting like "Increase reach" can be applied to a whole intent-based group (awareness vs. defense vs. harvest) in one pass instead of one campaign at a time.
2. **Separate exact-match harvesting campaigns from broad/discovery campaigns** if you haven't already — this makes the off-Amazon inferred-term noise easier to isolate, since it's far more likely to show up mixed into broad and auto campaigns than into a tightly scoped exact-match harvesting campaign.
3. **Refresh creative before you touch bids.** Off-Amazon placements inside creator content and video-heavy formats reward strong lifestyle imagery and clear value props more than they reward a marginally better bid — if your main image and A+ content haven't been updated in six months, that's a higher-leverage fix than another round of bid adjustments.
4. **Use budget-based dayparting as your interim lever.** Amazon still doesn't offer native hourly bid scheduling, so if you're not already using schedule-based budget rules (or a third-party tool layered on Marketing Stream data) to shift spend toward your highest-converting hours, you're leaving the one dayparting tool Amazon does give you unused.
5. **Put a recurring 30-minute campaign-settings audit on the calendar.** Not a full account audit — just a pass through placement and bidding toggles, since that's where Amazon has been shipping quiet defaults that materially move your ACOS.

## The Takeaway

None of this requires an account overhaul. It requires treating campaign settings as something that changes underneath you and checking them on purpose, rather than assuming today's defaults match the strategy you set six months ago. The sellers who catch changes like the off-Amazon toggle early get a few weeks of cleaner data and tighter spend before the rest of the market notices and average CPCs adjust.

If you'd rather have someone watching these settings, testing new bidding options safely, and keeping your creative and catalog aligned with what's actually converting, that's the daily work of our ads management, catalog and listing optimization, and product graphics teams at Tech2globe. Reach out at info@tech2globe.com and we'll take a look at your account setup and tell you honestly where the quick wins are.
