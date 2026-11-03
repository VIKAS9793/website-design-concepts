# Case study: Sthira Physiotherapy

**[Visit the website](https://sthira-physio.netlify.app)** · [Research behind it](research.md) · [All concepts](../../README.md)

*Fictional Bengaluru physiotherapy clinic, built as a portfolio project.*

## The problem

Sthira (fictional) is a three-therapist physiotherapy clinic in HSR Layout, Bengaluru. Most of its patients are desk workers with neck and back pain, plus weekend runners and players. It loses money and results in three quiet ways:

- **Missed appointments.** Most physio patients miss at least one visit, and the most common reason is forgetting. An empty hour can't be resold.
- **Hesitation over cost.** Patients can't tell how many sessions they'll need or what the total will be, so some never book.
- **Exercises abandoned between sessions.** Only about a third of patients fully keep up their home programme, which slows recovery.

**Problem statement:** patients forget, hesitate over unknown costs, and drop their home exercises; the clinic pays for all three in empty slots and slower results.

## The approach

Make the right action the easiest one at each point: booking, keeping or moving the appointment, and doing the exercises.

| Doubt | What answers it |
|---|---|
| "When can I come?" | **Next free slot** on the home page, and a slot picker that opens on the first day with space |
| "Will physio help, and is it safe?" | **Where does it hurt?** in plain words, and a **safety check** that sends warning signs to a doctor first |
| "What if I can't make it?" | A **booking code**: move or cancel in two taps, with the 24-hour rule shown before you confirm; a **calendar file** with an alarm; reminders |
| "What will it cost?" | **Prices up front**, and a written plan with the total after the first visit |
| "I forget my exercises" | A **daily checklist** with the dose and the reason for each exercise |
| "How's today?" (staff) | A **clinic view** with unconfirmed bookings to call and cancelled slots to refill |

## Key decisions

- **A different stack for a different job.** Booking is an application, so this concept uses Next.js, React and TypeScript, with a server route for availability. The content-led concepts in the portfolio use Astro. The stack follows the problem.
- **Make moving easier than missing.** Cancelling asks "would moving it work instead?" first, and moving takes the same slot picker as booking. A rescheduled patient is still a patient.
- **Show the rule before it applies.** The 24-hour charge appears on the price list, at confirmation, and again before any late change, so it never feels like a trap.
- **Safety before sales.** The booking flow stops for warning signs such as loss of bladder control or worsening weakness, and says to see a doctor or call 112. A clinic that turns away the wrong patient earns trust from the right ones.
- **No personal data in a public demo.** Bookings stay in the visitor's browser and only a first name is asked for. For a real clinic, the same flows would write to a database and send the reminders from the server.
- **Honest about weight.** The app needs about 148 KB of JavaScript, far more than the Astro concepts. It still shows its main content in about 0.65 s on a slow phone connection, because pages are pre-rendered and only the interactive parts run in the browser.

## Measuring success

For a real clinic, the measures would be:
- the no-show rate, before and after reminders and the booking page;
- the share of changes made by reschedule rather than cancellation;
- first-visit bookings per week from the website;
- exercise checklist completion, and whether it tracks with recovery.

## What I'd do next for a real clinic

- Connect bookings to a database and the clinic's calendar, and send WhatsApp reminders with confirm and move replies.
- Add the written treatment plan from the first visit to the patient's booking page.
- Replace the demo exercises with each patient's own plan, with short videos recorded by the therapists.
- Test the booking flow with five patients over 40, to check the date and time picker is easy enough for everyone.
