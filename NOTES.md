# RIG: GoHighLevel Specialist checkout ($300/month), 2026-10-10

**Brief (Javier):** a simple checkout page. Checkout form on the left, offer stack on the right. Use the
brand of the live opt-in (therealinsurancegroup.com/opt-in), not the blue of the offer slide. The offer
slide was only so I'd understand the stack.

**Preview:** https://javmartz04-ship-it.github.io/rig-specialist-checkout/ (repo of the same name; push to update).

**Direction:** the live opt-in is our Marketing Machine opt-in, so the tokens and fonts were lifted from
`builds/rig-marketing-machine-optin` (paper, ink, yellow highlighter, hard offset shadows, Inter Tight,
Caveat, JetBrains Mono). Black logo via brightness(0), same footer.

**Structure:** top bar (logo + Secure Checkout, no nav) → left: eyebrow, H1 "Get your dedicated /
GoHighLevel Specialist." (highlighter emphasis), sub, form card (1 Your Details, 2 Payment, order total,
"Get My Specialist Now", secure / cancel anytime / no contract) → right: sticky stack card (blue header,
Christopher row with real avatar + 800+ / 1,000+ proof, the 5 service areas condensed, 3 bonuses,
dark price block: typically $1,000/mo struck → $300/month). Price shown once, high to low.

**Not wired:** the payment fields are a visual stand-in. Submit validates, then shows "Preview only".
Before live: drop in the GHL order form (or set `CHECKOUT_URL`). Don't name a payment method until seen.

**Choices to confirm:** the "$[X] value" funnel bonus shows "Included" (no number given). "No contract"
is assumed from "cancel anytime". Christopher is shown as the specialist.
