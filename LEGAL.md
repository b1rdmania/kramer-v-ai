# Legal & regulatory spine

*Pressure-tested against current E&W family law and UK GDPR (2026-05-27). The point worth noticing: almost every legal constraint pushes the design the same way the philosophy does — toward a simpler, human-gated build that preserves both frames. The law isn't fighting the architecture; it's converging on it.*

---

## The North Star is legally reachable

The fee-pump comes from one thing: the **adversarial two-lawyer model billed by the hour**. Nothing in the law says you can't fix that.

- **Proposing a settlement band is unreserved.** Under the Legal Services Act 2007 only rights of audience, conduct of litigation, reserved instruments, probate, notarial acts and oaths are reserved. Advice and negotiation are not. An AI proposing a band is **not illegal**.
- **The court is the fairness backstop, not the solicitor.** Every settlement binds via a court-approved consent order (s.25 MCA fairness duty). The judge scrutinises it.

### Three routes to the no-lawyer destination

1. **Neutral-process (mediation-shaped)** — AI is a neutral, gives information not advice, serves both; each party optionally takes independent advice before signing. Legal *today*.
2. **Unreserved-advice** — the band given to both parties with no solicitor in the core loop; consent order is the backstop. Risk is professional-negligence liability / PI insurance, not legality.
3. **Own the regulation (the structural North Star)** — SRA-authorised entity (or Arizona ABS); AI supervised in-house; billed fixed-fee / subscription, which kills the hourly pump by construction. It requires an authorised solicitor as principal.

### The reconciliation

The solicitor *panel* was never the enemy — the hourly adversarial retainer is. You can keep solicitors in the loop (for trust, PI cover, GDPR Art 22, SRA standing) **and** kill the fee-pump by flipping their engagement to **fixed-fee unbundled sign-off**: two solicitors, one per side (no conflict), each doing a flat-fee gate review, with the neutral AI process in the middle. Both parties served, settlement reached, court-approved.

---

## Five build decisions

1. **Emotional intake is Art 9 special-category data.** Treat as health-adjacent from day one — explicit consent (standalone) or Art 6(1)(b) + Art 9(2)(f) (inside a regulated firm), DPIA, segregation, encryption. Load-bearing, not polish.
2. **The sign-off gate is the UK GDPR Art 22 mechanism, not just SRA insurance.** A settlement range + offer letter has "legal or similarly significant effects." Meaningful human review with *recorded override reasons* is what keeps it not-solely-automated. The audit artefact does double duty: SRA durability + Art 22 compliance.
3. **Safeguarding is the first gate.** FPR PD3A / MIAM / Resolution norms: on an abuse or coercion signal the system escalates and refuses to propose a number. Quick-exit / cover-your-tracks UX.
4. **No coercive nudging — bands are scenarios.** Settlement binds only via a consent order (s.33A / s.25), set aside for duress, undue influence, or non-disclosure (*Sharland*, *Gohil*). Present ranges as "outcomes in comparable circumstances," stress uncertainty, force a timestamped full-disclosure confirmation, run a "do you feel pressured?" check before finalising (trips → block send, escalate).
5. **The regulatory home is unbundled legal services.** Solicitor gives limited-scope review under a clear limited retainer; AI does drafting-assistance and education. SRA has piloted and endorsed unbundling for access to justice. Stay clear of LSA 2007 reserved activities: no filing, no service, no statements of truth, no holding out as a solicitor.

---

## Single-party vs two-party (resolved)

The conflict-of-interest rule kills "one solicitor advising both" — **not** "settle both sides." **Two solicitors, one per side**, resolves the conflict while keeping the richer two-party demo (each advises their own client; data segregated per Module 1). That is the design.

- **Two-solicitor / two-party** — the target demo and the platform shape. Legal today.
- **Single-party** — the *fallback* if the build runs short on the day, not the ceiling.

---

## Questions we'll be asked on the day — and the answer

- **"Isn't an AI giving legal advice illegal?"** — No. Advice/negotiation are unreserved (LSA 2007). The gate is about durability and insurability, not legality.
- **"Isn't this a solely-automated decision under GDPR?"** — No — meaningful human gate with recorded reasons. That's what Art 22 requires.
- **"What if there's domestic abuse?"** — First gate is a safeguarding screen; on a signal the system stops negotiating and escalates. We don't mediate coercion.
- **"Can the settlement be challenged later?"** — Binds only via a court-approved consent order; the design (non-coercive framing, disclosure confirmation, pressure check, audit trail) is built to survive a *Sharland*-style challenge.
- **"Who's the client / isn't there a conflict?"** — Two solicitors, one per side. Clean under SRA conflict rules.
- **"Is this even allowed?"** — Yes: the unbundled-services model the SRA already endorsed, with an AI intake layer and an audit chain on top.
