# MoSCoW

MoSCoW sorts requirements into four buckets: **Must have, Should have, Could have, Won't have (this time)**. Its main virtue is forcing clear commitment. Unlike ranked lists where items at position 7 and 8 feel equal, MoSCoW makes you declare whether something is truly essential or merely nice to have.

**1. Agree on scope and release.** MoSCoW is always relative to a specific delivery: a release, a sprint, a quarter. Without a fixed scope, "must have" becomes meaningless.
- _"For the May launch of the cloud management console, what is Must versus Should versus Could versus Won't?"_
- MoSCoW is for the next deliverable, not the three-year roadmap.

**2. List all candidate items.** Pull together the full pool: features, requirements, user stories. Do not prune yet.
- Include items from all stakeholders. Hidden requirements that emerge mid-sprint are the most expensive kind.
- Use the same granularity across items. Mixing a six-month migration with a one-day UI tweak makes the buckets useless.

**3. Define "Must have" strictly.** A **Must** is something without which the release has no value or fails outright.
- Ask: _"If we ship the SaaS portal without this, do we pull the launch?"_ If the honest answer is no, it is not a Must.
- Musts should consume no more than 60% of capacity. The remaining 40% is buffer for discovery, rework, and lower buckets.

**4. Define "Should have" carefully.** A **Should** is important but not essential: painful to leave out, survivable.
- Ask: _"If this slips to next release, can we recover? Will customers accept a follow-up?"_ If yes, it is a Should.
- Shoulds are the first to be cut when timelines compress. Your team needs to accept this before the sprint starts, not during the last week.

**5. Define "Could have" generously.** A **Could** is nice to have, typically small or low-effort, included only if time permits.
- Coulds should be small enough that dropping them causes minimal disruption to the release narrative.
- This bucket is often where morale-boosting work lives: a polished animation, a quality-of-life detail.

**6. Define "Won't have" explicitly.** Items here are not rejected forever. They are explicitly out of scope for _this_ release.
- Writing something as **Won't have** is a decision, not a deferral. Document why. _"Won't have: SAML SSO – identity provider contract not yet signed. Targeted for Q4."_
- Stakeholders feel heard when their items appear here with a rationale rather than vanishing from the backlog.

**Practical notes:** MoSCoW fails when everything becomes a Must. If the Must list consumes 100% of capacity, there is no buffer for surprises and no room for the Shoulds and Coulds that give a release its texture. Run MoSCoW with the whole team. The people building the items need veto power on estimates. Revisit at midpoint: as reality asserts itself, some Musts turn out to be Shoulds, and acknowledging that early beats discovering it during the final week.
