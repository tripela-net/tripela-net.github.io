+++
title = 'AI Dispatch Systems Cut Transit Operating Costs in Half'
date = 2025-07-14T13:30:58+02:00
authors = "Tripela Authors"
description = "How AI-powered dispatch platforms are replacing fixed routes with demand-responsive services that double ridership per vehicle while cutting subsidies by 50%."
+++

**DART replaced a failing bus route in Plano, Texas with AI dispatch and cut per-ride subsidies from $33.71 to $16.37. The new service covers 85% of the area with 11-13 minute rides, and nearly half the passengers connect to rail. This isn't a pilot. It's been running since 2018.**

## What This Actually Means

Instead of buses running empty on fixed schedules, AI figures out where people want to go and sends vehicles there. When someone books a ride, algorithms look at all the other requests, current traffic, and where vehicles are positioned to create the best routes.

Traditional buses run whether they have 2 passengers or 20. AI dispatch only sends vehicles when and where people need them. Multiple passengers going in similar directions get pooled together.

[VIA Link in San Antonio](https://www.gerad.ca/fr/papers/G-2024-28.pdf) ditched three fixed routes and now covers 19 square miles with AI zones. Results: 36% lower cost per passenger and 5.0 passengers per vehicle-hour. They handle 650 weekday trips at $1.30 per ride.

## The Numbers That Matter

These aren't small improvements:

**Cost Cuts:**
- DART GoLink: 51% less subsidy per ride
- VIA Link: 36% lower cost per passenger  
- Collin County: 52% savings by mixing agency vehicles with Lyft

**Better Service:**
- Passengers per vehicle went from 1-2 to 4-6 through pooling
- Smaller vans cut fuel and maintenance costs 40-60% vs big buses
- Paratransit wait times dropped 50%

**More Coverage:**
- Arlington serves the whole city with 15 vans (1.2M trips since 2017)
- [Sioux Falls runs full buses on-demand](https://www.siouxfalls.gov/files/assets/public/v/1/city-government/boards-amp-commissions/public-transit-advisory-board/2023-transit-dev-plan.pdf) citywide on Saturdays

## How It Works

### The Data
AI dispatch pulls from multiple sources:
- GPS showing where vehicles are right now
- Passenger booking requests with pickup and dropoff spots
- Traffic data showing current delays
- Service alerts when routes are disrupted
- Weather affecting travel times

### The Algorithms
The system solves a giant puzzle: how to get everyone where they're going while using the fewest vehicles and driver hours. [RideCo's system](https://gohrt.com/wp-content/uploads/2019/12/RideCo-Overview.pdf) recalculates routes every 30 seconds as new ride requests come in.

Factors it considers:
- How long people wait and how long their rides take
- Vehicle costs and driver hour limits
- Energy use and charging needs for electric buses

### Getting It to Drivers
Drivers get route updates on tablets showing:
- Turn-by-turn directions with stop order
- Who to pick up and drop off where
- Contact info for passengers
- Automatic rerouting when things change

## Connecting to What You Already Have

### Your Current AVL System
Most agencies have vehicle tracking systems. AI dispatch connects through middleware that translates your GPS data into formats the algorithms can use.

Sioux Falls kept their existing vehicle tracking and added middleware to convert GPS feeds for RideCo's system. No need to rip out working infrastructure.

### GTFS and Real-Time Data
Modern systems work with [GTFS-RT feeds](https://www.transit.dot.gov/sites/fta.dot.gov/files/2024-09/FTA-Report-No-0269.pdf) for passenger apps and trip planners. When storms hit Dallas, GoLink automatically reroutes using traffic data and service alerts.

### Ride-Hailing Backup
Systems like Spare can automatically call Lyft or Uber when your vehicles are swamped. Collin County saves 47% per ride during busy periods by sending overflow to ride-hailing instead of buying more vehicles.

## Who's Selling This Stuff

**Via Transportation**
- Does the whole package: dispatch, booking, driver apps
- Running in Arlington TX, Sioux Falls, West Sacramento
- Connects with trip planning apps

**Spare Labs**
- Handles regular service and paratransit
- Can mix your vehicles with Uber/Lyft automatically
- Working with DART, Collin County, others

**RideCo**
- Good at cramming lots of passengers per vehicle
- Complex routing for tricky service areas
- Running in San Antonio, Calgary, Guelph

**Pantonium**
- Uses full-size buses instead of vans
- Good for agencies that want to keep big vehicles
- Running Saturday service in Sioux Falls

## What It Costs

### Getting Started
- Software and setup: $200k-$500k per service zone
- Tablets for drivers: $2k-$5k per vehicle
- Training staff: $50k-$150k
- Marketing to passengers: $25k-$75k

### Payback Timeline
Most agencies see results fast:
- **Year 1**: 25-35% lower subsidies as vehicles work harder
- **Year 2**: Another 10% improvement from fine-tuning
- **Ongoing**: Opportunities to shrink fleet or expand service

Plano paid back their tech investment in 18 months through lower operating costs.

### Environmental Benefits
AI dispatch cuts environmental impact several ways:
- 20% fewer vehicle miles (San Antonio)
- 13% less deadheading in paratransit (Plano)
- Better charging schedules cut depot electricity bills 15%
- Batteries last longer with smarter charging

## Problems and How to Fix Them

### When Systems Go Down
**Problem**: Internet hiccups delay routing decisions
**Fix**: Store backup routes on vehicle tablets

**Problem**: Whole system crashes
**Fix**: Keep emergency schedules stored locally on tablets

### Driver Pushback
**Problem**: Drivers don't trust AI routing
**Fix**: Good training plus automated help. GoLink cut radio chatter 85% with "ask SAM" feature for quick questions

### Connecting Old Systems
**Problem**: Your 15-year-old AVL doesn't talk to modern AI
**Fix**: Middleware boxes that translate between old and new systems

## How to Do This Right

Learn from agencies that got it working:

1. **Replace your worst routes first**: Pick low-ridership services where anything is an improvement
2. **Keep your options open**: Make sure you can switch vendors if needed
3. **Mix fixed and flexible**: Keep busy trunk routes, add AI zones for coverage
4. **Plan for busy times**: Set up ride-hailing backup so you don't need tons of vehicles sitting idle
5. **Think about electric early**: If you're going electric, plan charging around AI dispatch

### Service Design Tips
Things that work:
- Keep some scheduled service for people who like predictability
- Give real-time arrival info through apps
- Use flat fares to encourage people to share rides
- Set clear standards for wait times and ride length

## What's Next

The technology keeps getting better:

**Smarter algorithms** that learn your specific demand patterns over time

**Better connections** between on-demand zones and regular bus routes

**Autonomous vehicle ready** systems that can handle mixed fleets

**Demand prediction** that positions vehicles before people even request rides

## Reality Check

AI dispatch isn't some future concept. Agencies are using it right now to cut costs and improve service. The trick is starting with routes that already struggle with low ridership and high costs.

If you're running near-empty buses on expensive routes, AI dispatch might cut your losses while giving better service. The technology works, vendors know what they're doing, and you can measure the results.

The real question: can you afford to keep running expensive, empty buses while other agencies are cutting costs with this stuff?
