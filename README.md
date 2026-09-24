# Coppermine Meadowbrook — Pool Relay embed preview

A five-page replica of the [Coppermine Meadowbrook](https://www.gocoppermine.com/meadowbrook) pages — the
Meadowbrook home, the Lane Schedule, Swim Lessons, Swim Team and Fitness — each with a live
[Pool Relay](https://www.poolrelay.com) calendar scoped to what that page is about.

Not an official Coppermine page. It says so in a ribbon across the top.

Built with `python3 build.py` (edit it, not the HTML) and served by GitHub Pages.

## The five pages

| Page | Calendar | Scoped to |
|---|---|---|
| `index.html` — Meadowbrook | [`uG9BcxGJ…`](https://www.poolrelay.com/v/uG9BcxGJkfV0NwQSC5PC2o) | the whole club, a week at a time, **Pools** menu |
| `lane-schedule.html` | [`FIPvohrJ…`](https://www.poolrelay.com/v/FIPvohrJDuTwwf7MQbrcsm) | the main pool, lane by lane (D1 D2 D5 D6 · S1 S2 S5 S6 · L3 L4), a day at a time |
| `swim-lessons.html` | [`XLkX6NFM…`](https://www.poolrelay.com/v/XLkX6NFMUWScUH74uqyar0) | Swim Lessons |
| `swim-team.html` | [`wfvJeARS…`](https://www.poolrelay.com/v/wfvJeARSms5bthReYCVcVq) | Swim Team and Masters |
| `fitness.html` | [`Ll7hNgxm…`](https://www.poolrelay.com/v/Ll7hNgxmoFmsajp4On5kYO) | Aqua Fitness and Rec Swim |

## Source

The [Meadowbrook Lane Schedule](https://www.gocoppermine.com/elements/meadowbrook/meadowbrook-lane-schedule_2_19_2026.pdf)
PDF (named for February 19, 2026; last modified February 24; still the linked schedule on 2026-09-23), four
pages: Deep 25M lanes, Shallow 25Y lanes, 50M lanes, Therapy Pool.

## How the pool is modeled

The main pool is ONE layout used three ways at once, not alternative configurations: a deep end of
25-meter lanes (D1, D2, D5, D6), a shallow end of 25-yard lanes (S1, S2, S5, S6) past the bulkhead,
and two full 50-meter lanes (L3, L4). In Pool Relay they are three areas under Main Pool, with the
lanes named as the club names them. The Therapy Pool is a whole-pool area.

## What is ours

- Series start the Monday after the PDF's date (February 23, 2026) and are open-ended.
- Aqua Fitness in lanes 1–2 at both ends (M/W/F 9–11) is one class.
- The PDF's white cells — presumably member lap swim — are NOT booked.

## Open questions (also on the pages)

Is the February schedule still the fall schedule? · Are the white cells open lap swim? · "Recreational swim
begins at 10AM" on the site vs Rec Swim only Sat/Sun 2–6 in the Therapy Pool · Masters in 50 m lane 3 on
Tue/Thu/Sat — a separate long-course group?
