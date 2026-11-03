# Case study: Loomfell

**[Visit the website](https://loomfell-woolens.netlify.app)** · [Research behind it](research.md) · [All concepts](../../README.md)

*Fictional hand-woven woolen jacket workshop, built as a portfolio project.*

## The problem

Loomfell (fictional) is a three-generation family workshop that weaves wool by hand and cuts it into winter jackets. Its product's main advantage, the cloth itself, is exactly what a screen hides. Online shoppers can't feel the weave, can't tell real wool from the acrylic blends often sold as "wool", can't judge warmth, and aren't sure about fit. So they buy something cheaper, or buy and return. Demand also only lasts about four months a year.

**Problem statement:** buyers who want a genuinely warm, well-made wool jacket can't judge the cloth, warmth or fit online, so they default to cheaper jackets or return what they buy.

## The evidence

Desk research ([`research.md`](research.md)) shaped the design. Each finding is rated by how much the evidence deserves to be trusted:
- **Fit:** it is the most common reason clothing bought online is returned, and hand-woven cloth doesn't stretch.
- **Touch:** not being able to touch fabric holds people back; close-ups and plain descriptions of the feel help.
- **Labels:** fibre labels are often wrong. An EU check found errors on 37% of the clothing it tested.
- **Handloom claims:** these are regulated in India, so the site describes the process without claiming certification.

These are assumptions to test with real customers, not facts about Loomfell's buyers.

## The approach

Every doubt a buyer has becomes a part of the site:

| Doubt | What answers it |
|---|---|
| "Is it really wool?" | A woven-style **label** on every jacket with the exact blend and lining |
| "What does it feel like?" | Fabric close-ups and four **feel meters**: weight, softness, itch, drape |
| "Will it be warm enough?" | A three-level **warmth scale** with temperatures |
| "Will it fit?" | A **pattern-sheet size guide** and each jacket's real measurements; picking a size highlights them |
| "Is it really handmade?" | **From fleece to jacket**: the process in three photographed steps |
| "What if it doesn't fit?" | The **exchange policy** next to the order button; size confirmed before payment |
| "How do I order?" | **WhatsApp**, with the jacket and size already written into the message |
| "It's summer." | Care and storage content, and a message to ask when orders reopen |

## Key decisions

- **A design built from the product.** The jackets' woven border becomes the section divider. The photos' plaster wall becomes the page background, so the jackets hang on the page. The labels are styled like woven garment tags. The type is IM Fell, whose rough, hand-printed texture matches hand-woven cloth.
- **Motion that explains.** On hover, a jacket's photo lifts out of its frame and its label slides out. In the premium wardrobe the doors open once and the pieces hang on a real rail. There's no scroll-jacking: the page scrolls normally, and phones get the same information without hover.
- **Real cut-outs for the wardrobe.** The premium pieces were generated on flat green and keyed out in a repeatable script, so they hang convincingly in any setting.
- **Honest content.** No reviews, awards or certification marks. Fictional details are labelled. No fake WhatsApp number.
- **Data-driven.** One catalogue file feeds every label, price, measurement and order message.

## Measuring success

Order, size-help and wardrobe links carry `data-track` labels, ready for an analytics tool. For a real client, the measures would be:
- order clicks per jacket page view,
- size-help requests,
- the exchange rate after launch.

That last one is the clearest sign of whether the fit information works.

## What I'd do next for a real client

- Use real photography of the actual jackets and cloth.
- Register for the Handloom Mark before using the word "handloom".
- Add the business's WhatsApp number.
- Test the size guide with five buyers on their own phones.
