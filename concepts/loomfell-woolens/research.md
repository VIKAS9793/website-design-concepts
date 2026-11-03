# Loomfell: buyer research (desk study)

**[Visit the website](https://loomfell-woolens.netlify.app)** · [Case study](case-study.md) · [All concepts](../../README.md)

*Fictional brand, portfolio demonstration. Prepared while the photo assets are being generated.*

## What this is, and what it is not

This is **desk research**: published studies, regulator records and industry reports about how people buy wool clothing online. It is **not user research**. Nobody who would buy a Loomfell jacket has been asked anything yet.

So every finding below is an **assumption to design against and then test**, not a fact about Loomfell's customers. Each one is rated by how much the evidence deserves to be trusted:

- **Strong:** regulator, government or peer-reviewed source.
- **Moderate:** consistent across several independent sources, but not primary data.
- **Weak:** vendor or agency marketing; directional only.

---

## Key findings

### 1. Fit is the biggest reason clothing bought online comes back (Strong to Moderate)

- Online apparel return rates in the US were estimated at about 23% in 2025.
- Size and fit is the most cited reason. Retailer surveys put it at about 53% of returns, and shopper surveys at up to about 70%. The 70% figure comes from a survey sponsored by a sizing-technology company.

**For Loomfell:** a jacket is a fit-sensitive purchase, and hand-woven cloth has little stretch. Returns also cost a small workshop more, because each piece is slow to make. **A clear size guide is a conversion feature, not a footnote.**

### 2. Shoppers want to touch fabric, and online shopping removes that (Moderate)

- Studies consistently find that not being able to touch fabric makes people hesitate to buy clothes online. People vary in how much they need touch.
- Richer sensory descriptions, close-up and zoomable images, and showing how the fabric moves all help shoppers imagine the feel. One study found this raised perceived quality and purchase intent.

**For Loomfell:** the product's main advantage, the hand-woven cloth, is exactly what a screen hides. **Macro fabric photos and plain-language descriptions of the feel (weight, softness, drape, whether it itches) are the core of the site, not decoration.**

### 3. "Wool" labels are often wrong, so buyers have reason to doubt (Strong)

- An EU market check in 2025 found incorrect fibre labels on 37% of 132 clothing items, especially blends and items sold online.
- Regulators in the US (FTC) and Australia (ACCC) have acted against products sold as wool or mohair that were mostly acrylic.
- Fibre blends are hard to identify even in labs: in one test, only 12 of 28 labs identified a cashmere-wool sample correctly.

**For Loomfell:** buyers have learned that "wool" on a label may not mean wool. **State the exact fibre content of every jacket (for example "100% wool" or "80% wool, 20% cotton lining"), and explain how to tell real wool from imitations**, rather than only saying "pure" or "premium".

### 4. "Handloom" claims are being regulated in India (Strong; current status needs checking)

- Powerloom fabric is regularly sold as handloom.
- India's Handloom Mark (since 2006) certifies genuinely hand-woven products, and misusing it can be prosecuted under trademark law.
- Draft regulations would make the Handloom Mark label **mandatory** for anything sold as "handloom", and selling without it would count as misleading. The draft named April 2026 as a date, but its final status was not confirmed in this research.

**For Loomfell (demo):** describe the process honestly ("woven on a wooden hand loom"), and don't show or imply a Handloom Mark the fictional brand does not have.
**For a real client:** check the current rules, and get Handloom Mark registration before using the word "handloom" in marketing.

### 5. Care worries are a real buying barrier for wool (Moderate)

- In a 2023 survey of 198 wool buyers (trade, not consumers) across 27 countries, price, look and feel, and care were the main challenges. Animal welfare ranked lower.
- Wool can shrink noticeably even when washed gently. Moth damage comes from larvae, and clean, sealed storage prevents it.
- No consumer survey measuring how much the itch puts people off was found. This remains an assumption.

**For Loomfell:** a short, practical care guide (washing, drying, storing through summer, dealing with moths) answers a real objection. It also gives the site useful content in the off-season.

### 6. Ordering by WhatsApp suits small Indian sellers, but the numbers are soft (Weak)

- A government source (IndiaAI) estimates that only about 15% of roughly 30 million registered small businesses in India sell online. Cost and complexity hold them back.
- Vendor sources claim very high conversion rates for WhatsApp ordering (40 to 60%). These come from marketing blogs and are likely inflated.

**For Loomfell:** **catalogue plus WhatsApp ordering** is the right scope for a small workshop. It costs little and lets the maker answer fit questions personally. Don't promise conversion numbers based on these sources.

---

## What this means for the site

Each customer doubt maps to a section or feature, as with The Sushi Slide.

| Customer doubt | Section or feature |
|---|---|
| "Will it fit?" | **Size guide** with measurement diagrams (drawn as SVG), a garment measurement table for each jacket, and "Not sure? Send us your measurements on WhatsApp" |
| "What does it feel like?" | **Fabric close-ups** and a plain "How it feels" line on every jacket: weight, softness, drape, itch |
| "Is it really wool?" | **Exact fibre content** on every jacket, plus a short "How to tell real wool" guide |
| "Is it really hand-woven?" | **From fleece to jacket**: the process (raw wool, spinning, weaving, sewing) told honestly, with no certification claims |
| "Is it warm enough for where I live?" | A **warmth scale** (for example light, mid and heavy), with typical temperatures for each |
| "Can I look after it?" | **Care and storage guide**, including moths and summer storage |
| "What if it doesn't fit?" | **Exchange and returns policy** stated up front, near the order button |
| "It's summer, why is this site still here?" | **Waitlist or pre-order** for the next season, plus care content |
| "How do I order?" | **Order on WhatsApp**, with the jacket name and size already filled into the message; a sticky bar on mobile |

---

## Assumptions to test with real people

When there is a real client, these are the beliefs to check first, most important first:

1. Fit uncertainty is the main reason people hesitate to buy a wool jacket online.
2. Buyers doubt that "wool" and "hand-woven" claims are true, and stating the exact fibre content makes them more confident.
3. Close-up fabric photos and "how it feels" descriptions reduce hesitation more than lifestyle photos do.
4. Buyers would rather confirm size and order on WhatsApp than use a checkout.
5. A warmth scale helps people choose between jackets.
6. Itchiness is a strong objection to wool. (No evidence was found either way.)

---

## Research plan for a real client

| Step | Method | Who | Size | Time |
|---|---|---|---|---|
| 1 | Owner interview | The owner, using the discovery questionnaire (Part A, plus the clothing questions in Part C) | 1 | 1 meeting |
| 2 | Customer interviews | Recent buyers, plus people who asked about a jacket but didn't buy | 5 to 8 | 1 to 2 weeks |
| 3 | Review existing messages | Past WhatsApp or Instagram questions from customers, sorted by theme | All available | 1 to 2 days |
| 4 | Usability test of the built site | People in the target group, on their own phones | 5 | 1 week |
| 5 | Measure after launch | WhatsApp order clicks, size-guide opens, fabric-photo zooms, waitlist signups, exchange rate | Everyone | Ongoing |

Step 3 is the cheapest and often the most useful: the questions customers already send are the doubts the site has to answer.

---

## Interview guide: wool jacket buyers (45 minutes)

**1. Warm-up (5 min)**
- Thanks for your time. There are no right or wrong answers; I'm learning how people buy winter jackets.
- What's the coldest place you regularly spend time in winter?

**2. Context (10 min)**
- Tell me about the last winter jacket you bought. Where did you buy it, and why that one?
- How did you decide it would be warm enough?
- Have you ever bought a jacket online? How did it go?

**3. Deep dive (20 min)**
- *Fit:* How do you work out your size when buying clothes online? Has it gone wrong? What happened next?
- *Material:* When a product says "wool", how sure are you that it is? What would make you more sure?
- *Hand-made:* Does "hand-woven" matter to you? Why? How would you know it's true?
- *Feel:* What do you worry about with wool? (Listen for itch, weight, shrinking, moths. Don't suggest them first.)
- *Price:* What would you expect to pay for a hand-woven wool jacket? What would make that price feel fair?
- *Ordering:* Would you be comfortable ordering by WhatsApp? What would you want to ask before paying?

**4. Reaction (10 min)**, once there's a prototype
- Show one jacket page on their phone. Ask them to think aloud: "You're deciding whether to buy this. Talk me through it."
- Watch, without helping: do they find the size guide? Do they zoom into the fabric? Where do they hesitate?

**5. Wrap-up (5 min)**
- Is there anything you'd need to know before buying that we haven't talked about?
- Thank them.

**Listen for** specific past stories, not opinions about the future ("Last year I returned..." is worth more than "I would probably..."), and for the exact words people use about fit and feel. Those words become the site's copy.

---

## Sources

- [Coresight Research: apparel return rates](https://coresight.com/?p=225159) and summaries in [size.ly](https://www.size.ly/blog/ecommerce-return-statistics) and [Branvas fit-issue report](https://branvas.com/blogs/news/apparel-returns-fit-issue-report)
- [Retail Insider: sizing drives most clothing returns (2026)](https://retail-insider.com/retail-insider/2026/07/online-clothing-leads-e-commerce-returns-with-sizing-driving-most-send-backs-overnight-glasses/)
- [Anglia Ruskin University: more detail about the feel of clothes](https://aru.ac.uk/news/more-detail-about-feel-of-clothes-could-be-a-win-win)
- [Sensory product information and purchase intent (Universidade Católica Portuguesa)](https://repositorio.ucp.pt/entities/publication/7134d272-8dba-47dd-b3bc-752c9a0e37e7/full)
- [Fabric hand in physical vs virtual environments (UiTM)](https://ir.uitm.edu.my/id/eprint/49536)
- [Need for touch in fashion (Chalmers University)](https://research.chalmers.se/publication/553162/file/553162_Fulltext.pdf)
- [Intertek: EU surveillance finds high non-compliance in fibre labels (2026)](https://www.intertek.com/products-retail/insight-bulletins/2026/1547-eu-market-surveillance-finds-high-non-compliance-fibre-composition-labels/)
- [FTC comment on the Wool Products Labeling Act rules](https://www.ftc.gov/sites/default/files/documents/public_comments/16-cfr-part-300-rules-and-regulations-under-wool-products-labeling-act-1939-project-no.p124201-00004%C2%A0/00004-82839.pdf)
- [ACCC: EziBuy corrective action on fabric labelling](https://www.accc.gov.au/media-release/ezibuy-ltd-takes-corrective-action-for-inaccurate-fabric-descriptions-and-labelling)
- [ELP: new marking requirements for handlooms (2026)](https://elplaw.in/leadership/new-marking-requirements-for-handlooms-key-features-and-implications-for-stakeholders/)
- [Handloom economy (India Together)](https://www.indiatogether.org/handloom-economy--2)
- [Assam handloom authenticity (Sentinel Assam)](https://www.sentinelassam.com/amp/story/more-news/editorial/leveraging-authenticity-tag-to-promote-assam-handloom)
- [AWI: wool buyer views survey (2023)](https://rop.wool.com/globalassets/wool/about-awi/how-we-consult/review-of-performance/accordion/buyer-views-on-mulesed-wool-survey.pdf)
- [Wool blanket care and shrinkage (Crazy Crow)](https://www.crazycrow.com/site/?p=1590)
- [Protecting wool from moths (Socosy)](https://www.socosy.co.uk/our-blog/protecting-wool-from-moths/)
- [IndiaAI: conversational AI and small businesses](https://indiaai.gov.in/article/indian-enterprises-plan-to-increase-spending-on-conversational-and-generative-ai)
- [GrowthHQ: WhatsApp commerce claims (vendor, weak)](https://www.growthhq.io/our-thinking/how-jaipurs-smbs-are-outpacing-rivals-the-2026-whatsapp-commerce-playbook-driving-60-conversions-300-roi-in-india)
