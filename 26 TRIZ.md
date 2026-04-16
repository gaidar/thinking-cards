# TRIZ

TRIZ ("Theory of Inventive Problem Solving") was developed by Genrich Altshuller from 1946 through analysis of hundreds of thousands of patents. His insight: inventive solutions follow patterns. He cataloged 40 inventive principles, 39 contradiction parameters, and a contradiction matrix. Heavier than most methods. Yet, genuinely powerful when two requirements conflict and conventional tradeoff thinking keeps failing.

**1. Identify the contradiction.** Inventive problems almost always involve a contradiction: improving one thing worsens another.
- _"Deeper security scans make the user experience slower."_
- _"More MSP console features make onboarding harder."_
- Frame it: _"If we improve X, we worsen Y."_

**2. Restate in TRIZ parameters.** Translate your contradiction into two of the 39 standard parameters: speed, reliability, complexity, ease of use, etc.
- _"Deeper scans vs. slower experience"_ becomes _reliability vs. speed_.
- _"More features vs. harder onboarding"_ becomes _functionality vs. ease of operation_.
- This translation connects your specific problem to solved problems across entirely different domains.

**3. Look up the contradiction matrix.** The 39x39 grid suggests which of the 40 inventive principles historically resolved that type of contradiction.
- For _reliability vs. speed_, the matrix might suggest #13 (Inversion), #35 (Parameter changes), #1 (Segmentation).
- The matrix does not hand you the solution. It tells you the type of solution that has worked before.

**4. Apply the suggested principles.** Brainstorm how each principle applies to your specific problem. The principles are general patterns: **Segmentation**, **Taking Out**, **Nested Doll**, **Counterweight**, **Dynamics**, and thirty-five more.
- Principle #1 (Segmentation) applied to security-vs-speed: heavy checks only at trust boundaries, lightweight checks inside the session. A real architectural pattern used in production.

**5. Seek the Ideal Final Result (IFR).** The IFR is the state where the benefit exists without the system that produces it: no extra complexity, no downside. You will not fully reach it. Yet, aiming for it pushes thinking past conventional tradeoffs.
- _"Security is enforced without any user-perceptible slowdown."_

**6. Eliminate, do not compromise.** The defining TRIZ move is refusing the tradeoff. Instead of "where is the optimal balance?", ask "how do we eliminate the contradiction entirely?"
- Most inventive breakthroughs came from contradiction elimination, not better compromise.
- If you end at a compromise, go back to step four and try a different principle.

**Practical notes:** TRIZ has a steep learning curve and bureaucratic-looking vocabulary that puts off teams who would benefit most. A practical way in: start with the 40 inventive principles alone before touching the full matrix. TRIZ shines on engineering and architectural problems; it is weaker on service design or UX. Pairs well with first-principles thinking.
