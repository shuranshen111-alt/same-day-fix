# Representative Website Handoff Sample

This is a fictional sample showing the format of a focused same-day handoff audit.

## Critical Flow

Visitor opens landing page -> understands offer -> chooses package -> sends brief -> receives payment link.

## Priority Issues

| Priority | Surface | Current State | Expected Behavior | Acceptance Check |
| --- | --- | --- | --- | --- |
| P0 | Hero CTA | "Get started" has no clear destination | Opens the brief section and explains what to send | Clicking CTA scrolls to brief; brief lists scope, input, and turnaround |
| P0 | Contact form | Submit button shows no confirmation | Show success state and expected reply time | Valid submission displays confirmation without page refresh |
| P1 | Pricing | Package scope is vague | Show one clear deliverable and revision limit | Buyer can explain exactly what the $20 package includes |
| P1 | Mobile nav | Pricing link is hidden below the fold | Keep brief/pricing actions easy to reach | Actions remain visible and tappable at 360px width |
| P2 | Trust | No sample output is visible | Add representative downloadable delivery files | Sample files open without login |

## LLM-Ready Next Prompt

Implement the P0 items only. Preserve the current visual style. Do not add authentication or a database. Add a visible success state to the existing contact form and make the primary hero CTA scroll to the brief section. Verify both behaviors at desktop and 360px mobile widths.
