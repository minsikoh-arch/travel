---
name: yeohaeng-skill
description: Build practical, current three-day, two-night travel itineraries for any destination by default, with nearby food stops, indoor rainy-day alternatives, and relevant local travel blog links. Adapt when the user gives a different trip length.
metadata:
  short-description: Plan destination-flexible trips
---

# 여행스킬

Create useful, realistic travel itineraries for the destination and dates the user gives. Unless the user specifies another duration, plan a 3-day, 2-night trip. Do not assume or hard-code Tokyo, Japan, or any other destination. Adapt the plan to the user's interests, pace, food preferences, mobility needs, budget, lodging area, and transport details when supplied.

## Plan the trip

- Use the exact dates supplied. If the year is omitted, infer the next upcoming occurrence when reasonable and state the assumption. Verify weekdays and date-sensitive details.
- If important preferences are missing, make a sensible first draft and state its assumptions. Ask only when the missing detail would materially change the itinerary; keep planning what can be planned in the meantime.
- Cluster attractions and meals by neighborhood to reduce backtracking. Include realistic transfer and walking time, breaks, and meal windows. Avoid packing every hour.
- Pair food recommendations with nearby sights. Give a specific dish or cuisine to try, and include at least one practical alternative when a venue may be crowded, closed, or unsuitable.
- For overnight trips, account for check-in/check-out, luggage storage, and the likely departure point where known.
- For the default 3-day, 2-night format, plan arrival and check-in on Day 1, two full sightseeing days as suitable, and check-out/departure on Day 3. Keep the final day lighter when luggage or departure timing is unknown. If the user gives different dates or duration, follow those instead.
- Distinguish researched facts from flexible suggestions. Do not imply that a restaurant, attraction, or reservation is guaranteed.

## Verify current details

When browsing is available, research time-sensitive details before recommending them: opening hours, weekly closure days, seasonal schedules, admission and reservation rules, transport disruptions, and current weather forecasts when useful. Prefer official attraction, transit, and restaurant sources for operational facts. Use reputable destination guides for neighborhood context. Link sources near the claims they support and label any estimate or inference.

For dates too far away for a reliable forecast, say that the forecast is not yet dependable and provide a weather contingency instead. Never present a seasonal norm as a confirmed forecast.

## Rainy-day alternatives

For outdoor-heavy itineraries, provide a distinct indoor alternative for each day, or for each major area when that is more practical. Keep the substitute geographically close to the original route where possible. Consider museums, covered shopping streets, department stores, aquariums, galleries, food halls, indoor markets, and booked experiences. Verify opening days and hours, especially for museums that close weekly. Mark timed-entry activities that need advance booking. Keep a light-rain option when outdoor visits remain practical.

## Travel blogs

Finish with three relevant travel blog links when the user requests blog references or the itinerary workflow calls for them. Prefer the requested local platform (for Korean users, Naver Blog) and choose posts that directly match the destination, neighborhoods, trip duration, food, or rainy-day activities. Search for real posts and use their direct URLs; never invent post titles, authors, URLs, or claim firsthand verification. If a platform blocks direct inspection, use search-result information only, disclose that limitation briefly if it affects confidence, and choose clearly relevant results. Blog posts are personal experiences, so advise checking current hours, prices, and reservation rules with official sources.

## Present the itinerary

Use the user's language. Start with the date range and a short description of the route. Present each day in a time-based table or concise chronological list with neighborhood, activity, meal, and travel notes. Put rainy-day alternatives in their own clearly labeled section. Add a short practical note for bookings, transit, or luggage when relevant. Put the three blog links at the very bottom, each with a one-line explanation of what it covers. Use clickable source links and avoid unsupported precise claims.
