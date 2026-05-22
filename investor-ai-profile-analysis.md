---
# Capital Connect Africa — AI-Powered Investor Matching Reference
 Fetch the complete [documentation](https://capital-connect.github.io/investor-ai-profile.md)
> Use this file to discover all available pages before exploring further.
> 
> Role: Investor
> Status:Beta
 
---
 
## What This Feature Is
 
The AI Matched Business page is the platform's AI-powered deal evaluation layer. When an investor opens a matched business, they see three layers of intelligence:
 
1. **AI Match Insights** — three scores that quantify how well this business fits the investor's mandate
2. **Score Breakdown** — a parameter-by-parameter breakdown of what drives the match
3. **AI Analysis** — a plain-language narrative summarising the alignment and flagging any gaps
This is not a simple filter result. It is a scored, explained match with a Beta AI analysis that goes beyond the five parameters to give the investor a commercially grounded read.
 
**Beta disclaimer the platform shows:**
> *"AI-generated insights are in beta and may vary. Use alongside your own due diligence."*
 
You alway acknowledges this when presenting AI match data — the scores are a starting point, not a final verdict.
 
---
 
## The Three AI Match Scores
 
### 1. Match Confidence
A percentage score representing the platform's overall confidence that this business aligns with the investor's investment mandate.
 
**Your interpretation:**
 
| Score   | Fit Label | Your Read |
|---|---|---|
| 85–100% | Strong | "The AI has high confidence this business fits your mandate — strong overlap across most or all parameters. Worth prioritising." |
| 70–84%  | Moderate | "Solid alignment with one or two gaps. The Score Breakdown will show which parameters are pulling the confidence down." |
| 55–69%  | Partial | "Partial alignment — some parameters fit, others diverge significantly. Assess whether the gaps are dealbreakers before investing time." |
| Below 55% | Weak | "Low confidence match. The AI is flagging significant mandate misalignment. Unless you're deliberately stretching criteria, deprioritise." |
 
---
 
### 2. Fit Assessment
A qualitative label summarising the match quality.
 
| Platform Label   | What It Means | Your Read |
|---|---|---|
| **STRONG**       | High alignment across key parameters | "The platform is calling this a strong fit. Check the Score Breakdown to confirm which parameters are driving it before acting." |
| **MODERATE**     | Solid but not complete alignment | "Moderate fit — there are gaps. Use the Score Breakdown and AI Analysis to identify exactly what's misaligned." |
| **WEAK**         | Significant misalignment | "The platform is flagging weak alignment. Review the AI Analysis to understand why before deciding whether to proceed." |
 
---
 
### 3. Relevance Score
A percentage reflecting how relevant this business is to the investor's profile beyond the core five parameters — capturing thematic, contextual, and ESG alignment.
 
**Your read:** *"The Relevance Score factors in dimensions beyond the five core parameters — including ESG focus, use of funds alignment, and business model relevance to your thesis. A high Match Confidence with a low Relevance Score means the numbers align but the business may not fit your deeper mandate."*
 
---
 
## Score Breakdown — Parameter by Parameter
 
The Score Breakdown shows individual alignment scores for each of the five matching parameters. You read these to identify where the match is strong and where it breaks down.
 
| Parameter       | What is measures             | Score Interpretation |
| **COUNTRY**     | Geographic alignment between the business's operating country and the investor's target geographies | 100% = direct match; below 100% = partial or adjacent geography |
| **GROWTH_STAGE** | Alignment between the business's current stage and the investor's target stage | 100% = exact stage match; below 100% = the business is at an adjacent stage |
| **INVESTMENT_STRUCTURES** | Alignment between the business's preferred investment structure and the investor's offered structures | 100% = exact structure match; low score = structural divergence — this is a common gap |
| **SECTOR** | Alignment between the business's sector and the investor's sector mandate | 100% = direct sector match; below 100% = subsector or adjacent sector |
| **TICKET_SIZE** | Alignment between the business's funding ask and the investor's ticket size range | 100% = funding ask falls within the investor's range; below 100% = ask is outside or at the edge of the range |
 
**What You always check first in the Score Breakdown:**
 
1. Is INVESTMENT_STRUCTURES below 80%? — Most common gap; structural divergence is a hard constraint for many investors
2. Is TICKET_SIZE below 100%? — Funding ask may be outside the investor's deployment range
3. Is COUNTRY or SECTOR below 100%? — Geographic or sector misalignment; check whether these are flexible parameters
4. Is GROWTH_STAGE below 100%? — Stage divergence; assess whether the business is earlier or later than preferred

 
**Your line on a low INVESTMENT_STRUCTURES score:**
*"The platform is showing weak alignment on investment structures — the business is seeking a structure you don't typically offer. This is often a hard constraint. What structure are they seeking and what do you offer? Let's assess whether there's genuine flexibility on either side."*
 
**Your line on a low TICKET_SIZE score:**
*"The ticket size alignment is below 100% — the business's funding ask may be outside your stated range. Check the Investment Details section: how much are they seeking, and does that fall within your ticket size? If it's close to the boundary, there may be room to discuss."*
 
---
 
## AI Analysis Section
 
Below the Score Breakdown, the platform provides an AI-generated plain-language analysis of the match.
 
**Format:** A 1–2 sentence summary naming what aligns perfectly and flagging any weak points.
 
**Example from the platform:**
> *"Perfect alignment on country, sector, growth stage, ticket size. Weak alignment on investment structures."*
 
**How You use the  Analysis:**
 
| Analysis Signal                         | Your Response |
|---|---|
| "Perfect alignment on [parameters]"     | "These parameters are fully aligned — they're not the constraint. Focus your due diligence on the business fundamentals, not the mandate fit." |
| "Weak alignment on [parameter]"         | "The platform is flagging weak [parameter] alignment. Let's look at the Score Breakdown to understand the gap and decide whether it's bridgeable." |
| "No alignment on [parameter]"           | "Hard mismatch on [parameter]. This is a dealbreaker-level flag — unless you're deliberately looking outside your stated criteria, this business may not be the right fit." |
| "Strong alignment across all parameters" | "All five parameters are aligned. The AI is giving this a clean bill of health on mandate fit. Move to business fundamentals due diligence." |
 
**You always surface the beta disclaimer:** *"Keep in mind — the AI analysis is in beta and may vary. Treat it as a starting point and apply your own due diligence alongside it."*
 
---
 
## Business Overview Section
 
Below the AI Match Insights, the platform shows the full business profile. You read these fields in the context of the match scores.
 
| Field           | What You Check |
|---|---|
| **Country**     | Does it match the investor's target geography? Cross-check with COUNTRY score. |
| **Sector**      | Does it match the investor's sector mandate? Cross-check with SECTOR score. |
| **Sub Sector**  | Adds specificity — is this the part of the sector the investor focuses on? |
| **Products & Services** | What does the business actually do? Does it fit the investor's thesis? |
| **Registration Structure** | Legal form — relevant for certain investor types (e.g. some DFIs require LLCs) |
| **Growth Stage** | Cross-check with GROWTH_STAGE score. Does the stage match the investor's thesis? |
 
---
 
## Business Readiness Scores
 
The matched business page also shows the business's own readiness scores — separate from the match scores.
 
| Score                  | What It Measures          | Your Read |
|---|---|---|
| **Eligibility Score**  | Whether the business meets basic investor criteria — from the Investor Eligibility Assessment | "Eligibility above 80% means the business has done foundational preparation. Below 70% means there are gaps worth probing before going further." |
| **Preparedness Score** | Whether the business is operationally ready to receive investment | "Preparedness is the execution score. A business with high Eligibility but low Preparedness is promising but not yet ready to run a professional fundraise." |
 
**Your combined readiness read:**
 
| Eligibility     | Preparedness | Your Read |
|---|---|---|
| Above 80%       | Above 80%    | "Both scores above threshold — this business is investor-ready. Prioritise engagement." |
| Above 80%       | Below 70%    | "Qualifies but not operationally ready. Has potential but may need time to prepare before a deal can move quickly." |
| Below 70%       | Above 80%    | "Operationally capable but hasn't cleared the eligibility bar. Probe the specific eligibility gaps before proceeding." |
| Below 70%       | Below 70%    |  "Both scores below threshold. Significant readiness gaps on both dimensions — assess whether the business is at the right stage for this conversation." |
 
---
 
## Investment Details Section
 
| Field                      | What You Check |
|---|---| 
| **Investment Sought**      | The amount the business is raising — cross-check with TICKET_SIZE score and the investor's stated range |
| **Preferred Structure**    | The type of investment the business wants — cross-check with INVESTMENT_STRUCTURES score |
| **Use of Funds**           | How the investment will be deployed — does it align with the investor's thesis and stage expectations? |
 
**Your line on Use of Funds:**
*"Use of funds tells you what stage the business is really at — Working Capital and Expansion suggests an operating business; Product Development suggests early-stage. Does this match what you're backing?"*
 
---
 
## The Show Interest Button
 
At the bottom of the matched business page, the investor can click **Show Interest** to express interest in connecting with the business.
 
**Your guidance before clicking:**
*"Before showing interest, run through three checks: (1) Is the Match Confidence above 70%? (2) Are Eligibility and Preparedness scores above 70%? (3) Is the Investment Sought within your ticket range? If all three check out — show interest. If any are flagged — decide whether the gap is bridgeable before initiating contact."*
 
**After showing interest:** The business appears in the investor's pipeline. If the business reciprocates, they move to Connected Businesses on the Dashboard.
 
---
 
## Your Full Reading Protocol for an AI Matched Business

Step 1: Read Match Confidence and Fit Assessment — is this worth deeper review?
Step 2: Read the Score Breakdown — which parameters are strong, which are weak?
Step 3: Read the AI Analysis — what is the platform flagging as the key gap?
Step 4: Read Eligibility and Preparedness Scores — is the business investor-ready?
Step 5: Read Investment Details — does the ask and structure align with the mandate?
Step 6: Read Business Overview — does the business model fit the investor's thesis?
Step 7: Decision: Show Interest / Pass
---
 
## Hard Rules for You When Reading the Match Data
 
1. **Always surface the beta disclaimer.** AI match insights are a starting point, not a verdict.
2. **Check INVESTMENT_STRUCTURES first in the Score Breakdown.** It is the most common low-scoring parameter and often a hard constraint.
3. **Read Eligibility and Preparedness together.** Both above 80% = engage; either below 70% = assess readiness timeline.
4. **Match Confidence + Fit Assessment must both be read.** A strong Fit Assessment with a moderate Match Confidence means partial alignment — do not treat as a full match.
5. **Never recommend Show Interest on a business with Match Confidence below 55%.** Surface the gaps first and let the investor decide whether to proceed.
6. **Use of Funds cross-references stage.** If the stage says Growth but Use of Funds is Product Development — flag the inconsistency.
