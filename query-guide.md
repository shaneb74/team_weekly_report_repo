# CCA Report Query Guide

> **This file controls how Claude interprets and responds to questions about CCA weekly reports.**
> Update this file in the repo to change behavior for all users — no skill update needed.

---

## Current Team Roster

| Name | Territory / Focus | Monthly Goal | Status |
|------|-------------------|-------------|--------|
| Jennifer (James) | Broad hospital network, Shoreline/Monroe/downtown | $80,000 | Active |
| Marta | Swedish Edmonds area | $55,000 | Active |
| Jenny | South King County, Auburn/Sumner area | $40,000 | Active |
| Kelsey | Tacoma, St. Clare/MultiCare network | $40,000 | Active |
| Chanda | Olympia/Tacoma, Kaiser/healthcare focus | $30,000 | Active |
| Alysia | Eastside, building foundation | $30,000 | Active |
| Monika | — | — | Intermittent submissions |
| Karine | — | — | Intermittent submissions |
| J. White | — | — | Intermittent submissions |

## Data Sources

### Self-Reported (Focus Documents)
Each advisor submits a weekly Focus Document. These are compiled into the team report. Self-reported numbers reflect what the advisor believes their metrics are.

### QuickBase (QB)
QuickBase is the system of record. When QB data is present in a report, it is the authoritative source for:
- Revenue (closed deals by advisor by month)
- Intakes / new leads (with timestamps)
- Pipeline counts (all stages, not just "active clients")
- Referral source categorization (hospital, SNF, clinic, fire/police, home health, word-of-mouth)

**When self-reported and QB numbers conflict, QB wins.** Always surface the discrepancy to the user.

## Response Instructions

### Default behavior
- Lead with the most recent data available
- Use tables for any comparison involving 3+ advisors or 2+ weeks
- Always include % of goal when showing revenue
- Flag missing submissions — management wants to know who didn't report

### When asked about a specific advisor
- Start with their current week snapshot (revenue, leads, clients, morale)
- Note any QB discrepancies for that advisor
- Include their upcoming OOO if relevant

### When asked about trends
- Pull at least 4 weeks of data when available
- Highlight inflection points (big jumps or drops in leads, revenue, client count)
- Call out consistent QB discrepancy patterns (e.g., "Advisor X has over-reported revenue by 8-11% for three consecutive weeks")

### When asked "who's doing best" or performance rankings
- Rank by QB revenue when available, self-reported otherwise
- Factor in goal attainment % not just raw dollars (someone at 110% of a $30K goal is arguably outperforming someone at 80% of an $80K goal)
- Mention lead generation trajectory as a forward indicator

### Things to always flag
- Any advisor with 0 leads in a week
- Revenue discrepancies > 10% between self-reported and QB
- Missing submissions for 2+ consecutive weeks
- Morale signals that seem concerning (e.g., "fine" with no elaboration after previously positive reports)

## Terminology
- **QB** = QuickBase (the CRM / system of record)
- **Focus Document** = the weekly report each advisor submits
- **Active clients** = clients the advisor is currently working with (self-reported count)
- **Pipeline** = all leads in QB at any stage, usually higher than "active clients"
- **Placement** = a successful move-in (generates revenue)
- **SNF** = Skilled Nursing Facility
- **AL** = Assisted Living
- **SW** = Social Worker (hospital contact / referral source)
- **HCPC** = Healthcare Professional networking group
- **Eldernet** = Senior care networking organization
