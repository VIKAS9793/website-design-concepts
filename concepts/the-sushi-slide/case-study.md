# Case study: The Sushi Slide

**[Visit the website](https://the-sushi-slide.netlify.app)** · [All concepts](../../README.md)

*Fictional restaurant website, built as a portfolio project.*

## The problem

The (fictional) owner runs a traditional sushi restaurant with a 50-year story. Their concern was not visibility but **comprehension**. Many potential guests know "sushi" as one category. They can't tell nigiri from makizushi, don't know what's in a dish and aren't sure what to order, and that uncertainty stops them from visiting. A standard menu-and-photos page doesn't fix it.

**Problem statement:** guests who want to try traditional sushi lack clear information about the restaurant's identity, sushi styles, ingredients and preparation, so they feel unsure what to order and whether the restaurant is right for them.

## The approach

The page follows the decision a visitor is making (*discover → understand → explore → evaluate → trust → act*) and removes one source of doubt at each step.

| Doubt | Section that answers it |
|---|---|
| "What is this place?" | Hero: positioning + two clear actions (menu, story) |
| "Why trust it?" | Story and Craft: heritage and preparation, described concretely rather than with superlatives |
| "What are these names?" | **Know Your Sushi**: four cards (what it is, the key difference, how to eat it) plus an at-a-glance comparison table |
| "Isn't all sushi the same as what I get elsewhere?" | **Traditional & modern** panel: what "traditional" means in practice, set against common modern styles, without putting either down |
| "What should I order?" | **First visit** suggestions: three starter orders (gentle, vegetarian, curious) built from menu data, so items and totals always match the menu |
| "What will I actually get?" | Menu: every item lists ingredients, portion and dietary tags (vegetarian, vegan, raw fish, egg, shellfish) |
| "Can I eat here with my diet?" | FAQ, generated from the same menu data so answers always match the menu |
| "How do I go?" | Visit: reserve, call and directions buttons, hours, address |

## Key decisions

- **Education comes before the menu.** The sushi guide sits ahead of the menu, so dish names already make sense by the time visitors read them.
- **Honest content.** No reviews, awards or historical "evidence" were invented, and fictional details are labelled on the page. The phone number and email use reserved fictional ranges. Search indexing is off by default so a fictional business can't show up in local results.
- **Static and light.** Astro outputs plain HTML, and the only JavaScript (~2 kB) is progressive enhancement. Images are served as responsive WebP.
- **Data-driven content.** Business details, menu and FAQs live in three typed data files. The template can be reused for a real client without touching any components.
- **Asset QA.** The AI-generated asset package had two defects: a transparency checkerboard painted into the logo, and generator watermarks on two photos. A repeatable script fixes both instead of hand edits.

## Measuring success

Clicks are tracked through `data-track` hooks on the hero CTAs, menu, sushi guide/FAQ opens, reservation, phone and directions. These show interest and intent, **not** revenue or actual visits. A real launch would need booking-system or in-restaurant attribution data to show business impact.

## What I'd do next for a real client

- Use real photos of each dish. Right now each menu category shares one photo.
- Replace the email request with a booking provider.
- Add Restaurant structured data with verified details.
- Run a short usability test with first-time sushi diners to check whether the guide actually changes what they order.
