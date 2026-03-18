                                    Automatic Payout Trigger Design

All triggers are based on real-world thresholds that meaningfully impact gig workers’ earnings, not minor fluctuations.

                  Weather Triggers

Rainfall threshold:

Trigger if rainfall exceeds 30–50 mm within 1–2 hours, indicating heavy rain that disrupts delivery flow

Temperature threshold:

Trigger if temperature exceeds 40–42°C (heat stress) or drops below 5–8°C (extreme cold conditions)

Storm alerts:

Trigger on official severe weather alerts (orange/red level), not general warnings

Flood alerts:

Trigger when waterlogging or flood warnings are issued at city/zone level

                         Pollution Triggers

AQI threshold:

Trigger if AQI exceeds 300 (very poor) or 400+ (severe), where outdoor work becomes unsafe

                           Platform Triggers

App outage duration:

Trigger if platform is down for more than 45–60 minutes during active working hours

Order system downtime:

Trigger if no orders are received for 60–90 minutes during peak hours (lunch/dinner), indicating demand/system failure

                                  Government Triggers

Curfew announcements:

Trigger when official movement restrictions are enforced in the worker’s active area

Public mobility restrictions:

Trigger when transport or delivery operations are partially or fully restricted

                                Smart Trigger Layer (Critical Differentiator)

To avoid false payouts and make the system realistic:

Combine triggers with worker activity (GPS + login status)

Apply peak-hour logic (loss matters most during high-demand periods)

Introduce minimum duration filters (ignore short disruptions)

                                                combined logic:

IF (rainfall > threshold OR AQI > threshold OR platform_outage > 45 min)
AND worker_active = TRUE
AND peak_hours = TRUE
THEN payout
