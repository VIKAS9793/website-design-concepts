# Teen Kona Chaat Bhandar: customer and owner research (desk study)

**[Visit the website](https://teen-kona-chaat.netlify.app)** · [Case study](case-study.md) · [All concepts](../../README.md)

*Fictional Banaras chaat shop, portfolio demonstration.*

This is desk research, not field research: travel guides, news, platform reporting and a few surveys about how people find and order street food in Varanasi. Many figures come from guides, vendor blogs or surveys paid for by the platforms themselves, so each finding is graded and treated as **an assumption to test with a real shop owner**, not as market data.

## The starting point

A busy chaat shop in Banaras doesn't lack customers. There is a queue every evening. So "get more customers online" is the wrong pitch, and an owner would be right to ignore it. The research looks for money the shop already loses, or trouble its customers already have.

## Findings

### 1. Visitors are many, and they don't know the lanes (Moderate)

- The UP Tourism Department reported about **7.27 crore visitors to Varanasi in 2025**. Other reports give 11 crore for 2024, so counting methods clearly differ. Either way, the city sees a very large number of first-time visitors.
- Foreign arrivals rose from about 2.0 lakh (2023) to 3.1 lakh (2024).
- Guides describe famous food shops as hidden in narrow lanes near the ghats. A food blogger describes a lane where the shop next door had the same name as the famous one.
- A small student study (eight interviews) notes that Google Maps has no clear category for street food vendors, and that finding them on social media takes time.

**For the site:** step-by-step directions from a landmark visitors already know, a way to recognise the real shop, and plain-English menu notes for people who've never eaten tamatar chaat.

### 2. What's served depends on the hour and the season (Moderate)

- Guides agree that **kachori sabzi and jalebi are morning food** (about 6:30 to 10 am, best stalls sell out by late morning) and **chaat is evening food**.
- **Malaiyo is a winter item**, made from about November to February, sold early in the morning and often gone by mid-morning.
- One guide warns most stalls keep a three to five hour window.

**For the site:** a board that shows what's on **right now**, from the Indian clock, and when the next menu starts. A visitor who turns up at 2 pm for kachori is a lost sale and a bad review.

### 3. Delivery apps are a poor fit for chaat (Moderate)

- Reporting puts Swiggy and Zomato commissions at **about 16 to 30%** of the order, plus fees. Bengaluru restaurant owners threatened to leave both apps in 2026 over commissions.
- Chaat doesn't travel: golgappe go soggy and tikki loses its crunch.

**For the site:** don't push delivery. Push **pickup pre-orders** ("ready when you arrive") and **bulk orders**, both on WhatsApp, with no commission.

### 4. Bulk orders are the money, and they arrive at the worst time (Weak to moderate)

- Wedding catering is quoted per plate, commonly **about ₹500 to ₹1,500 per plate** for full meals. Chaat counters are listed separately on wedding platforms, at prices that vary widely.
- No source measures how many bulk enquiries a chaat shop misses. The assumption is that phone enquiries during the evening rush get short answers or are forgotten.

**For the site:** a bulk order calculator (guests, items, date) that sends a complete, written enquiry on WhatsApp. The owner replies after the rush with all the details in front of them.

### 5. Customers already message businesses on WhatsApp (Moderate, self-interested sources)

- A Meta-commissioned Kantar survey (2022) found 70% of surveyed online adults in India prefer messaging over emails or calls.
- A Meta-commissioned Ipsos survey (2022) found 91% of surveyed small businesses using digital tools called messaging very important for reaching customers.
- Payments: street vendors increasingly accept UPI.

**For the site:** every action ends in a pre-written WhatsApp message. No forms, no accounts, no app.

### 6. A website alone won't bring reach (Weak, vendor sources)

- Vendor blogs claim large growth in "near me" and "open now" food searches, and more calls and direction requests for complete Google profiles. None cite primary data.
- Google Maps is where a hungry visitor searches. The website is what that listing should link to.

**For the site:** pitch it as a set: website, Google Business Profile and WhatsApp Business, with the website as the place the other two point to.

## Constraints from the owner's side

| Constraint | Design decision |
|---|---|
| The owner won't update a website | Content that rarely changes: hours, menu, seasons. Prices live in one data file |
| Customers read Hindi first; tourists need English | Hindi home page, full English version at `/en/` |
| Cheap phones on weak 4G | Almost no JavaScript, small images, subset fonts |
| Small budget | Static site on free hosting, no server, no monthly fees |

## What this means for the site

| Visitor or owner doubt | Section or feature |
|---|---|
| "Is it open, and what's on now?" | **Now board**: live from the Indian clock, with the next menu's start time and the malaiyo season |
| "What do I order?" | **Menu** with prices, spice level and "first time? start with these" |
| "Where exactly is it?" | **Directions** from the nearest ghat, landmark by landmark |
| "Is this the original shop?" | **How to recognise us**, and "no other branch" |
| "Can you cater my function?" | **Bulk order calculator** to WhatsApp |
| "I don't want to queue" | **Pickup pre-order** on WhatsApp |

## Assumptions to test with a real shop

1. The owner misses or under-answers bulk enquiries during the rush.
2. Visitors arrive at the wrong time for what they want.
3. Visitors go to the wrong shop, or can't find the right one.
4. Customers will pre-order pickup on WhatsApp if the message is written for them.

## Sources

- [Varanasi tourism 2025: 7.27 crore visitors (Tourism Department, via news report)](https://194.32.77.254.sslip.io/news/record-growth-in-kashi-tourism-over-72-6-million-devotees-visited-in-2025-80-were-youth/articleshow/126324969.html)
- [Organiser: 11 crore visitors in 2024, foreign arrivals](https://organiser.org/2025/10/07/319729/bharat/up-varanasi-surpasses-goa-and-shimla-to-become-indias-fastest-growing-tourism-hub-over-11-crore-visitors-in-2024/)
- [India Mapped: Varanasi chaat, kachori and lassi trail](https://indiamapped.in/varanasi-food-guide-chaat-kachori-lassi-trail/)
- [Moha-mushkil food blog: same-name shops in Kachori Gali](https://moha-mushkil.com/?p=5462)
- [NextLeap student study: street food discovery](https://assets.nextleap.app/submissions/NLStreetBite-d55c559e-5e98-40b9-b9d8-0e09ee4cb7e3.pdf)
- [30 Stades: ten street foods of Varanasi, malaiyo season](https://30stades.com/society/ten-street-foods-of-varanasi-tamatar-chaat-chenna-dahi-vada-malaiyo-choora-matar-1684901)
- [Lonely Planet: what to eat and drink in Varanasi](https://www.lonelyplanet.com/articles/what-to-eat-and-drink-in-varanasi-india)
- [Outlook Business: delivery commissions of 16 to 30%](https://www.outlookbusiness.com/corporate/rapido-bets-on-low-commission-to-challenge-swiggy-zomato-duo)
- [Free Press Journal: Bengaluru restaurants and commissions (2026)](https://www.freepressjournal.in/tech/bengaluru-restaurants-threaten-to-boycott-swiggy-zomato-from-august-15-over-high-commissions)
- [magicpin: wedding catering cost per plate in India](https://magicpin.com/blog/wedding-catering-cost-india/)
- [Entrepreneur India: WhatsApp and small businesses (Meta-commissioned surveys)](https://entrepreneur.com/article/363068)
- [The Click: street food payments go digital](https://theclick.news/indian-street-food-payments-go-digital)
- [Restroworks: Google restaurant search statistics (vendor blog)](https://www.restroworks.com/blog/?p=12693)
