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

**(v1 note, superseded by v2 below)** Not wired: the payment fields are a visual stand-in. Submit validates, then shows "Preview only".
Before live: drop in the GHL order form (or set `CHECKOUT_URL`). Don't name a payment method until seen.

**Choices to confirm:** the "$[X] value" funnel bonus shows "Included" (no number given). "No contract"
is assumed from "cancel anytime". Christopher is shown as the specialist.

## v2 (2026-10-10): real checkout + full offer from the deck
Javier sent the newer Specialist sheet ("what they actually can do with it"), the GHL checkout
(realinsurancecrm.com/check-out-page-991997) and then: "this has the full offer, make sure everything on
there" → the Marketing Machine deck (rig-marketing-machine/?v=7).

- **Left:** the fake form is gone. The real GHL order form is framed (product "GHL Expert, $300 per
  month", card fields, Complete Order). No X-Frame-Options; it frames and the card fields load on the
  GitHub Pages origin. Frame height is fixed (840px desktop, 1010px at ≤560px), measured from the form.
- **Right:** the stack is now the deck's final stack: Skool group $147/mo, #1 Playbook $3,000, #2 Real CRM
  $97/mo, #3 Onboarding with David $1,000 (david.jpg from the deck), #4 Automation Snapshots $5,000,
  #5 Dedicated GHL Specialist $1,500/mo as a dark card holding the sheet's 5 deliverables + Christopher.
  Price: bought separately $9,000 + $1,744/mo → $300/month, nothing up front · no contract · cancel anytime
  (deck slide 63 confirms "no contract").
- **Dropped:** the sheet's separate Webinar Automation $3,000 + Speed-to-Lead $2,000 bonuses. The deck
  folds them into Bonus #4 snapshots ($5,000), so listing both would double-count.
- H1 "The full package, / plus your own specialist."

**Open:** the GHL product is named "GHL Expert", not the full package. Worth renaming in GHL so the
order summary matches the page. No scarcity on the page (the deck's "12 seats, closes tonight" is a
live-webinar claim).

## Thank-you page (2026-10-10)
`thank-you/index.html`, same repo, live at /rig-specialist-checkout/thank-you/. Simple post-purchase page:
green "Payment confirmed" strip → "You're in. / Let's build your machine." → 3 steps (check email,
book onboarding with David, join the Skool group) → Christopher handoff line. Button URLs live in
`LINKS` at the bottom of the file and are empty: need David's booking link and the Skool invite link.
Assumed: login details arrive by email; Christopher takes over after onboarding.
