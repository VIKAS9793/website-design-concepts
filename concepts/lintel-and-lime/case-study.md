# Case study: Lintel & Lime

**[Visit the website](https://lintel-and-lime.netlify.app)** · [Research behind it](research.md) · [All concepts](../../README.md)

*Fictional interior design and renovation studio, built as a portfolio project.*

## The problem

Lintel & Lime (fictional) is a small studio in Pune with a strong Instagram following that rarely turns into projects. Homeowners love the photos but can't tell what a room will cost, how long it will take or whether the result will match the 3D visuals. Published Indian prices range from about ₹1,000 to over ₹6,000 per sq ft, and the fear of advances taken for unfinished work is well founded. So people hesitate, or choose on price alone. The studio also loses hours on calls with people whose budgets don't fit.

**Problem statement:** homeowners can't judge the cost, timeline or reliability of interior work before talking to a studio, so they hesitate or shop on price. The studio spends time on enquiries that were never going to fit.

## The approach

Answer the money and trust questions before the first call, so the studio's enquiries arrive already knowing roughly what they'll spend.

| Visitor's doubt | What answers it |
|---|---|
| "What will it cost?" | A **cost estimator** using the studio's own rates, with GST shown separately |
| "How long will it take?" | The estimator's timeline, and every project's **planned versus actual weeks** |
| "Will you take my money and vanish?" | **Payments tied to finished stages**: 10% to start, the last 10% after the snag list is closed |
| "Will it look like the render?" | A **drag-to-compare slider** between the 3D visual and the built room |
| "What's the catch?" | **Included and not-included** lists |
| "What do the finish levels mean?" | Three levels with their **rates and the actual materials** |

## Key decisions

- **Numbers are the brand.** Every figure is set in a monospaced typeface, on a layout styled like an architect's drawing sheet. The design itself says "measured and specified".
- **Honesty as proof.** One featured project ran a week late, and the site says why and what came off the final payment. That earns more trust than a perfect record no one believes.
- **One source of truth.** The estimator and the projects read the same rates. A check confirms that every project's budget and planned time fall inside what the estimator would quote.
- **Only the images the content needs.** Five images: three rooms, one render-versus-built pair (generated as a single split image, so the two halves line up), and the material samples. The logo is drawn in code.
- **Performance built in from the start.** AVIF images, subset fonts and deferred rendering of offscreen sections were applied from the first build: 141 KB before the first screen on a phone, and the main content visible in about 1 second on a slow connection.

## Measuring success

The estimator's "send" button, the site-visit buttons and the hero buttons carry `data-track` labels. For a real studio, the measures would be:
- estimates sent per visitor,
- the share of site visits that come from an estimate,
- how closely final quotes match the estimate range.

The last one shows whether the estimator's rates are honest.

## What I'd do next for a real studio

- Use the studio's real project photos and their real render-and-built pairs.
- Calibrate the rates against the studio's last ten projects.
- Add the business's WhatsApp number.
- Test the estimator with five homeowners: do they trust the range, and does it change whether they'd call?
