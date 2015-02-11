---
title: "Services"
---

# Services

We help organizations with production engineering.


## Production Sanity

Reaching sanity in production is the primary goal.  It involves three main areas:

* visibility - requests per second + error rates + duration percentiles
* changeability - automated deployment / configuration
* reliability - understand / plan for basic failure cases, reporting failures


## Post Sanity

Once production sanity is reached, teams can focus on several areas for improvement: resiliency, data flow, and delivery pipeline.

### Resiliency

Resiliency is surviving and recovering from known and unknown events.  Ensuring that all connections are guarded or planned for failure using techniques such as exponential back off, load shedding, request collapsing, fallback caches.

### Data Flow

Modeling the system as a FSM and using write ahead journals to record state changes as the source of record, using consensus to achieve consistency.  This can then be consumed into several data systems for further query and/or analysis.

### Delivery Pipeline

Having a solid, trusted, and automated means of moving software from laptop to production.  This is achieved using techniques like live deployments, canaries, and A/B environments, combined appropriate metrics to gauge deployment success and production health enables groups to practice continuous deployment and go fast and not break.

</div>
