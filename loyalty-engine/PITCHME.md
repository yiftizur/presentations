
---?image=assets/gitpitch-audience.jpg
# Business Bookers Backenders

### Loyalty Engine

---?image=assets/gitpitch-audience.jpg

## Motivation

- Current solution does not allow easy scaling of loyalty programs  <!-- .element: class="fragment" -->
- Requires a lot of duplicating code and date  <!-- .element: class="fragment" -->
- No easy way of monitoring, debugging or querying loyalty programs state <!-- .element: class="fragment" -->

---?image=assets/gitpitch-audience.jpg

## Proposed Solution

- Build a new generic LoyaltyEngine™ that will:
 - alow multiple loyalty programs in parallel
 - be scalable to allow increse in traffic and load, as well as experimentation
 - allow monitoring (logs/metrics) for all actions regarding loyalty programs
 - Provide an API for querying state of loyalty programs and owners

---?image=assets/gitpitch-audience.jpg

<p><span class="menu-title slide-title">High Level Design</span></p>

![LoyaltyEngine](assets/LoyaltyEngine.png)


