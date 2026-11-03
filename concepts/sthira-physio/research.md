# Sthira Physiotherapy: patient and clinic research (desk study)

**[Visit the website](https://sthira-physio.netlify.app)** · [Case study](case-study.md) · [All concepts](../../README.md)

*Fictional Bengaluru physiotherapy clinic, portfolio demonstration.*

This is desk research, not user research: published studies and price listings about physiotherapy attendance, home exercise and musculoskeletal pain among office workers in India. Most attendance studies are from the US, Canada or the Middle East, and price figures come from directories and provider pages. Each finding is an assumption to test with a real clinic, not market data.

## Findings

### 1. Desk workers are the core patient group (Moderate)

- A 2024 to 2025 study of 200 software professionals in multinational companies in India found 72% reported musculoskeletal disorders in the previous 12 months, most often the lower back (66.7%) and neck (56.9%).
- A literature review of Indian IT studies found prevalence varies between studies, but software engineers and computer operators appear more prone to neck, shoulder and back pain.

**For the site:** start from "where does it hurt?" in plain words (neck, back, shoulder, knee, sports injury), not from a list of treatments.

### 2. Missed appointments are common, and mostly forgotten (Moderate)

- A study of about 445,000 US physical therapy patients found 73% missed at least one appointment in an episode of care.
- A survey of 634 US outpatient physical therapists gave a mean no-show rate of 10.4% of visits. The most common reason was forgetting. Clinics that used several reminder methods together with a 24-hour cancellation notice averaged about 6.1%.
- A Calgary clinic recorded about 21% no-shows and cancellations combined; the main reasons were forgetting, emergencies, transport and scheduling conflicts.

**For the site:** make moving a booking easier than missing it. Booking code, reschedule and cancel in two taps, calendar file, reminder the day before and two hours before, and a clear 24-hour policy.

### 3. Patients stop doing their home exercises (Moderate)

- Full adherence to home exercise programmes ranged from about a third (35% in Ethiopia, 2022; 31 to 37% in low back pain studies) to 39% (Turkey). Measured as the share of exercises done, adherence was higher, around 72 to 73%.
- Better explanation by the therapist and patient understanding were linked to better adherence.

**For the site:** a simple daily checklist for the plan the physio gives, with how many reps, how often, and a short "why".

### 4. Patients can't tell what it will cost (Weak to moderate)

- A 2026 Bengaluru guide quotes home physiotherapy at about ₹1,200 to ₹2,500 a session, with refund and pause policies varying widely between providers. Individual listings range from ₹400 consultations to ₹800 home visits and 10-session packages.
- The number of sessions is rarely stated up front, so the total cost is unknown.

**For the site:** prices for the first visit, follow-ups, home visits and packages on the page, and a written plan with the number of sessions and the total cost at the end of the first visit.

### 5. Some symptoms need a doctor, not a booking (Strong, clinical guidance)

Clinical guidelines for back and neck pain list warning signs that need urgent medical assessment first, such as loss of bladder or bowel control, numbness around the groin or buttocks, worsening leg weakness, fever or unexplained weight loss with back pain, and pain after a major fall or accident.

**For the site:** a short safety check before booking. If any warning sign applies, the site says to see a doctor or call 112, instead of offering a slot.

## What this means for the site

| Patient or clinic doubt | Feature |
|---|---|
| "Will physio help with my problem?" | **Where does it hurt?** Problem areas in plain words, and what the first visit involves |
| "Is this safe for me?" | **Safety check** before booking, with "see a doctor first" for warning signs |
| "When can I come?" | **Live slots**, clinic or home visit, by therapist |
| "What if I can't make it?" | **Booking page**: reschedule or cancel with a code, calendar file, reminders, 24-hour policy |
| "What will it cost in total?" | **Prices up front**, packages, and a written plan with the total after the first visit |
| "I keep forgetting my exercises" | **Exercise plan** checklist with reps and reasons |
| "How is today looking?" (clinic) | **Clinic view**: today's schedule, unconfirmed bookings, gaps to fill from a waitlist |

## Assumptions to test with a real clinic

1. Most missed appointments are forgotten, not avoided.
2. Patients reschedule instead of skipping when it takes less than a minute.
3. Showing prices and a total plan cost increases first bookings.
4. A checklist raises the share of home exercises done.

## Sources

- [Musculoskeletal disorders among software professionals in India (PMC)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12349777)
- [Review: work-related musculoskeletal disorders among IT professionals in India](https://www.msjonline.org/index.php/ijrms/article/view/8604)
- [Predicting no-shows in physical therapy, 444,995 patients (PLOS One)](https://ideas.repec.org/a/plo/pone00/0251336.html)
- [Survey of outpatient physical therapists on no-show rates and policies (PMC)](https://pmc.ncbi.nlm.nih.gov/articles/PMC8162651)
- [Reasons for no-shows in an outpatient rehabilitation department, Riyadh (PMC)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12041131/)
- [Home exercise adherence among physiotherapy outpatients, Ethiopia 2022](https://doaj.org/article/5410a4da8b0a49fba9d223ad65e346db)
- [Adherence to home exercise in low back pain (University of Brighton)](https://blogs.brighton.ac.uk/musculoskeletalphysiotherapy/?p=160)
- [Patients' adherence to physical therapy home exercises (Hacettepe University)](https://avesis.hacettepe.edu.tr/yayin/9df8c562-fde7-470f-9666-09885b58b1be/patients-adherence-compliance-to-physical-therapy-home-exercises)
- [Home physiotherapy cost in Bangalore, 2026](https://care.samarth.community/?p=135804)
