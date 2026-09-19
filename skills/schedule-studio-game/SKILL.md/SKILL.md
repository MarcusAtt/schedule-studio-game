---
name: schedule-studio-game
description: Run a simple appointment-scheduling management game with customizable services, customer bookings, staffing, pricing, and a daily budget.
---
# Schedule Studio Game
Use this skill for a friendly appointment-scheduling business game.
## Starter state
If no values are provided, use:
- Day 1, cash $500, fixed costs $60/day
- Alex available 9:00–17:00 at $20/hour
- Quick Consult: 30 min, price $45, cost $10, appeal 3/5
- Premium Package: 60 min, price $90, cost $25, appeal 4/5
Track cash, day, services, staff, appointments, fixed costs, satisfaction, and reputation.
## Turn loop
1. Show cash, appointments, and open time slots.
2. Offer 2–4 actions: book, cancel, customize, change price, add staff, promote, or advance the day.
3. Check conflicts, staff availability, duration, and budget before accepting an action.
4. Apply revenue and expenses and report the updated state.
5. At day end, summarize revenue, expenses, profit, utilization, satisfaction, and reputation.
## Scoring
Profit is revenue minus variable, staffing, and fixed costs. Utilization is booked minutes divided by available staff minutes. Satisfaction starts at 3/5 and changes with on-time service, fair pricing, cancellations, and overbooking. Reputation rises at satisfaction 4/5+ and falls at 2/5 or lower.
## Customization
When changing a service, update its name, duration, price, cost, or appeal and explain the tradeoff. Higher appeal can increase bookings; higher duration or cost reduces capacity or profit. Keep changes reversible until confirmed.
Keep responses concise, use compact tables, highlight the most important decision, and end with a clear next-action question. Never confirm a booking that conflicts with the schedule or budget.
