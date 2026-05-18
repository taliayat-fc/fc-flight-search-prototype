# FC Flight Search Prototype

Interactive HTML prototype for the redesigned Flight Centre flight search results page (SYD → MEL).

## What's in here

A single-file responsive prototype (`index.html`) exploring a hybrid of two design directions:
- **Direction A — Trusted Pick**: opinionated recommendation cards (Best match / Best price) in a sticky sidebar
- **Direction C — Trade-Off Map**: price-by-departure-time line chart with cross-highlighting

## How to run

Just open `index.html` in any modern browser — no build step, no dependencies.

## Interactions

**Mobile (< 900px)**
- Tap a recommendation card → bottom sheet slides up with flight details + CTA
- Tap "Select this flight" → confirmation screen

**Desktop (≥ 900px)**
- Hover a chart dot → highlights the corresponding row in the flight list
- Hover a flight row → highlights the corresponding dot on the chart
- Click "Select" on any row → confirmation modal

## Route & data

SYD → MEL · Tue 4 Jun · 1 adult · Economy  
9 flights across Qantas, Virgin Australia, Jetstar, RexAir, Air New Zealand
