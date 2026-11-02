# Thiranex-Forma-Progress
Usabililty statistics and perfomance of forma based on previous builds
# Forma Checkout Usability Study

A moderated usability study of the **Forma** interactive prototype, evaluating how confidently new customers can discover, configure, and purchase furniture. This repository contains the round-one findings, methodology, and design recommendations.

> **Status:** Round one in progress. Three of five planned sessions are complete, so results are directional and may shift once sessions P4 and P5 are finished.

## At a Glance

| Metric | Result |
|---|---|
| Overall task completion | **75%** |
| Average satisfaction | **4.2 / 5** |
| Issues logged | **8** |
| Sessions completed | 3 of 5 |

**Headline finding:** Participants moved confidently into checkout, but struggled to find delivery and configuration information before committing to a purchase. The primary usability gap is not the purchase action itself, but finding delivery timing and finish information earlier in the flow.

> "I assumed shipping would show up later. I didn't see that line at all."

## Study Details

| | |
|---|---|
| **Study dates** | May 12–15, 2026 |
| **Format** | Moderated remote (20–30 minute video calls) |
| **Lead researcher** | Alex Kim |
| **Prototype** | Forma interactive prototype (Figma) |
| **Objective** | Can new customers confidently discover, configure, and purchase a product? |

### Participants

Five people aged 18 to 30 who shop online and match Forma's target audience, anonymized as P1 to P5. Participants shared their screen and thought aloud while completing four neutral task scenarios.

| ID | Profile | Device | Date | Status | Rating |
|---|---|---|---|---|---|
| P1 | Design student | Laptop | May 12 | Complete | 4.2 / 5 |
| P2 | Graduate student | Laptop | May 12 | Complete | 4.6 / 5 |
| P3 | Junior architect | Mobile | May 13 | Complete | 3.8 / 5 |
| P4 | Marketing assistant | Laptop | May 14 | Scheduled | n/a |
| P5 | Postgrad student | Mobile | May 15 | Scheduled | n/a |

### Success Criteria

- 80% or higher completion on each task
- 4.0 or higher average satisfaction
- Every issue has a severity rating and a proposed fix

## Task Scenarios and Results

| # | Task | Scenario | Time limit | Completion | Avg. time | Errors | Outcome |
|---|---|---|---|---|---|---|---|
| 01 | Product discovery | Locate a comfortable reading chair (the Arc chair) from the homepage | 2 min | 100% | 0:42 | 0 | Meets target |
| 02 | Product options | Select a finish and identify the delivery estimate | 2 min | 67% | 1:18 | 2 | Below target |
| 03 | Checkout flow | Continue through checkout to confirmation | 4 min | 83% | 2:46 | 1 | Meets target |
| 04 | Support content | Identify delivery and return policy information | 2 min | 50% | 1:32 | 4 | Priority |

The highest error count appeared when participants actively searched for delivery and returns information.

## What Worked Well

Collection browsing, product imagery, cart review, and the visual simplicity of checkout all supported confident progress.

## Key Findings

### 1. Delivery details are too easy to miss (Critical)
Three participants scanned the product page twice before noticing the delivery estimate beneath the primary action.
**Fix:** Move delivery timing into a visible information row above the Add to cart button.

### 2. Finish swatches need visible labels (Major)
Two participants selected finishes by guessing from color alone and missed that a name appeared elsewhere on the page.
**Fix:** Add persistent labels beneath each swatch and strengthen the active state.

### 3. Cart removal action feels detached (Minor)
One participant expected the remove action to appear beside the quantity control rather than on the opposite side.
**Fix:** Place Remove beside the quantity selector and increase its tap target.

## Prioritized Recommendations

| Priority | Recommendation | Detail | Impact |
|---|---|---|---|
| 1 | Elevate delivery timing | Replace the low-contrast microcopy with a structured delivery row beside finish and pricing information | High |
| 2 | Label every finish option | Show Cognac, Forest, and Natural beneath their swatches at all times, not only after selection | High |
| 3 | Clarify support navigation | Add delivery and returns links to the main footer and surface concise policy content in the cart | Medium |
| 4 | Group cart controls | Keep quantity and remove actions together to match users' existing mental models | Low effort |

The first two recommendations should be implemented before the remaining sessions if the study protocol allows, or validated together in a second round.

## Next Steps

1. Complete sessions P4 and P5.
2. Update the priority screens in the Figma prototype.
3. Run a focused round-two validation with three participants.

## Limitations

- Early directional study with a small sample; three of five sessions are complete, so percentages may shift.
- The Figma prototype does not reproduce every production behavior.
- Participants knew they were completing test tasks.

## Ethics and Quality

- [x] Informed consent recorded
- [x] Participants anonymized
- [x] Same script used in each session
- [x] Metrics logged within 24 hours

Raw notes, recordings, and the moderator script are stored privately in the study workspace and are not included in this repository.

## Repository Contents

```
forma-usability-study/
├── README.md
├── Forma-Usability-Report.pdf
└── [add: test plan, task scenarios, updated screens]
```

## Links

- **Figma prototype:** [add link]
- **Full report:** `Forma-Usability-Report.pdf`

## Author

Lead researcher: Alex Kim · Usability Lab · Round one, May 2026
