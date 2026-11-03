# Case study: Teen Kona Chaat Bhandar

**[Visit the website](https://teen-kona-chaat.netlify.app)** · [Research behind it](research.md) · [All concepts](../../README.md)

*Fictional Banaras chaat shop, built as a portfolio project.*

## The problem

Teen Kona Chaat Bhandar (fictional) has sold tamatar chaat at the corner of three Banaras lanes since 1971. There's a queue every evening, so the owner doesn't feel a need to "go digital", and a pitch built on that phrase would fail. The money it loses is quieter:

- **Bulk orders** for weddings, pujas and office parties arrive as phone calls during the evening rush and get half an answer.
- **Visitors come at the wrong hour.** Kachori is a morning dish, chaat an evening one, and malaiyo only exists in winter, gone by mid-morning.
- **Tourists can't find the lane**, or stop at a same-name shop nearby.
- **Delivery apps** take about 16 to 30% commission, and chaat goes soggy on the way.

**Problem statement:** a busy, much-loved shop loses its largest orders and many first-time visitors to timing, distance and confusion, not to a lack of demand.

## The approach

Don't sell "a website". Sell the fixes for these losses, using tools the owner and customers already use: WhatsApp and Google Maps.

| Doubt | What answers it |
|---|---|
| "Is it open, and what's on now?" | A **now board** that reads the Indian clock and the season |
| "What do I order?" | A **rate board** with prices, spice level and three first-timer picks |
| "I don't want to queue" | **Pickup pre-orders** sent on WhatsApp, paid at the shop |
| "Can you cater my function?" | A **bulk order calculator** that turns a phone call into a complete written order |
| "Where is it?" | **Directions from a landmark Maps can find**, then four landmark turns |
| "Is this the real one?" | **How to recognise the shop**, and "no other branch" |

## Key decisions

- **Hindi first, and no Hinglish.** The home page is Hindi; English is a full second version for tourists, not a toggle that swaps text with JavaScript. Each language reads natively: everyday Hindi instead of English loanwords, plain English instead of Hindi words, with only brand, dish and place names shared.
- **Indian through materials, not motifs.** The design borrows from the shop's own street: a marigold toran, a painted signboard, a green rate board, indigo lane walls, a namaste greeting. No mandalas, paisley or monuments.
- **No text in generated images.** Image generators garble Devanagari, so the photograph's signboard was generated blank and the name is painted onto it in code, fitted to the board's position and slope. The same goes for the map: a painted aerial view with no labels, with the route, pins and names drawn over it in code.
- **WhatsApp, not forms.** Every action ends in a pre-written WhatsApp message. Nothing to sign up for, nothing for the owner to log into.
- **Full bill before the call.** The bulk calculator shows cooks needed, per-guest cost, advance and notice period. The owner gets a complete order, and the customer knows the cost before asking.
- **Maps for the hard part, the site for the last part.** Maps can find Kedar Ghat; the site handles the four lane turns Maps gets wrong.
- **Weight where it matters.** Devanagari fonts can't be cut much (their conjunct rules reach most glyphs), so the site uses just two families. The rupee sign has its own 2 KB file, so English pages skip Devanagari entirely: about 40 KB of fonts instead of 270 KB.

## Measuring success

The pickup and bulk WhatsApp buttons carry `data-track` labels. For a real shop, the measures would be:
- bulk enquiries per month, and the share that arrive complete;
- pickup pre-orders per evening;
- how often first-time visitors mention the site or the directions.

## What I'd do next for a real shop

- Photograph the real shop, its signboard and the four turns of the walk.
- Set up the Google Business Profile with the same hours, menu and photos, linking to the site.
- Put the website and WhatsApp number on the shop's own board, so the "real shop" check works both ways.
- Test the bulk calculator with three customers who've ordered for a function before: is the bill clear, and is anything missing?
