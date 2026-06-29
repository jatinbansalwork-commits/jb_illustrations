# Character Roles

Use when an article or case study needs **who does what** — not just a single abstract worker.

All roles are the same **JB** base (pointy ears, dot eyes, white outline on dark / solid-dark on light). Differentiate with **one prop + posture + label**.

Prefer **Bangalore everyday settings** when casting roles: filter coffee tapri, auto stand with locality board, BMTC bus stop, kirana counter, KR Market stall, post-office window.

## Bangalore visual shorthand (use 1–2 per image)

These read as Bengaluru instantly — even to someone who has never visited:

- **Filter coffee set** — steel tumbler + davara, decoction flask, coffee filter
- **Yellow-black auto** — rickshaw with locality signboard ("Koramangala", "Indiranagar")
- **BMTC bus stop** — route number board (e.g. "335", "500")
- **Tapri counter** — small South Indian coffee counter, steel tumblers lined up

## When to cast roles

- Before/after with a human in the loop
- Handoff workflows (vendor packs → hub sorts → owner approves)
- Daily grind (worker overwhelmed, owner unaware)
- Multi-stakeholder systems (runner, sorter, approver)
- Customer → service → gatekeeper scenes

Skip role casting when one anonymous worker is enough (metaphors, abstract flows, single-state diagrams).

## Role library

### Worker / Vendor / Auto driver

**Looks like:** JB beside a yellow auto, carrying decoction flasks, or lining up steel tumblers. Optional simple shoulder bag.

**Feels like:** Too many stops, wrong locality board, juggling coffee runs across the city.

**Labels:** "Too many stops" / "Wrong route" / "Auto queue full" / "Still running"

**Example scenes:**
- Buried in a pile of mismatched locality boards and route cards
- Running between auto stand and coffee tapri
- Stuck at a breakpoint with five Bangalore area labels

### Owner / Approver / Tapri manager

**Looks like:** JB behind a tapri counter or stamp pad, holding a **hand stamp** or weighing scale. Optional apron outline.

**Feels like:** Final check before the coffee run goes out — right area, right decoction, right auto.

**Labels:** "Owner signs off" / "Decoction ready" / "Route approved" / "Send the auto"

**Example scenes:**
- Stamping a route card at an auto stand hub (Koramangala, Indiranagar, Whitefield)
- Approving orders at a filter coffee tapri counter
- Green checkmark on "Out for delivery" after stamp

### Runner / Hub sorter

**Looks like:** JB in profile, pulling auto queue rope or sorting steel tumblers into area slots.

**Feels like:** Keeps the daily coffee run moving — not the owner, not the customer.

**Labels:** "Sorts by area" / "Runs the route" / "Fills the auto queue"

### Fixer / Back-office

**Looks like:** JB with clipboard, jugaad wire, or warning sign at a tangled setup.

**Feels like:** Manual fixes, wrong locality label, meter dispute.

**Labels:** "Jugaad fix" / "Wrong board?" / "Meter off?" / "Queue too long?"

### Customer / Requester

**Looks like:** JB with a speech bubble — often smaller, off to the side.

**Feels like:** The order enters the system.

**Labels:** "Strong filter coffee" / "Coffee to Koramangala" / "The order" / "What I need"

## Multi-character rules

1. **Max 3 JBs** per frame — more reads as clutter.
2. **Same silhouette** for every instance — ears, dot eyes, hand-drawn outline.
3. **One distinguishing prop each** — stamp for owner, tumbler for worker, bubble for customer.
4. **Spatial story** — left = ask/chaos, center = sort/run, right = approve/send.
5. **English role labels** only when ambiguity would confuse ("Worker", "Owner approves").
6. On dark backgrounds, use white-outline JB. On light backgrounds, use solid-dark JB.
7. **Bangalore flavor understated** — filter coffee + auto + locality name is enough; never kitsch.

## Prompt snippet (copy into dark-mode generation)

```text
Cast JB in role: {Worker / Owner-Approver / Runner / Fixer / Customer}.
Same base character: pointy ears, two dot eyes, hand-drawn outline.
Bangalore setting cue: {filter coffee tapri / auto stand hub / BMTC stop / kirana counter / none}.
Role prop: {stamp / steel tumbler / yellow auto / speech bubble / decoction flask}.
Posture: {specific action}.
Optional English role label: "{label}".
Localities: Koramangala, Indiranagar, Whitefield, HSR, Jayanagar.
```
