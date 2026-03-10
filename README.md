## Platform Navigation Guide

This repository hosts guides on how the platform is used. The documents are ingested into Lara. The platform guides portal is hosted on GitHub Pages.

## Setup

Clone the repository:
```bash
git clone git@github.com:Capital-Connect/documentation.git
```

## Contribution

1. Add the documentation — add an `md` file following this structure:
```md
    > ## Documentation Index
    > Fetch the complete [documentation](https://capital-connect.github.io/index.md)
    > Use this file to discover all available pages before exploring further.

    # Name
    > A brief description of what the page or feature does.

    ---

    ## Requirements (Optional)
    > List all the information or prerequisites a user needs before using this feature.
    - Requirement 1
    - Requirement 2

    ---

    ## Sections (Optional)
    > Use this for pages with multiple distinct sections (e.g. Dashboard, Databases, Analytics pages).
    > List the major sections visible on the page and link to their descriptions below.
    - Section 1
    - Section 2
    - Section 3

    ---

    ## Section Descriptions (Optional)
    > Describe each section in detail. Use this for dashboards, listing pages, analytics views, and database pages.

    ### Section 1 Name
    Description of what this section shows or does.

    | Field/Column | Description |
    |---|---|
    | Field name | What it means |

    ### Section 2 Name
    Description of what this section shows or does.

    ---

    ## Steps (Optional)
    > Use this for features that involve a multi-step process (e.g. forms, assessments, onboarding flows, bookings).
    > Link to the URL of each step where applicable.

    > **Step 1: Step Name**
    > Open [Step Page](https://app.capitalconnect.africa/path)

    1. **Question or field label**
       > Context or guidance for this field.
       > Examples: *example 1, example 2*

    > **Step 2: Step Name**

    1. **Question or field label**
       > Context or guidance for this field.

    ---

    ## Cards / Items (Optional)
    > Use this for pages that display a list of cards, tiers, or selectable items (e.g. Services page, Call for Applications).

    ### Item Name — Price or Tag
    > Tagline or short description.

    **What's included:**
    - Feature 1
    - Feature 2

    > Call to action note. Click **Button Label** to proceed.

    ---

    ## Possible Issues
    - Issue 1 — when it occurs
    - Issue 2 — when it occurs

    ## Possible Remedies
    - Fix for issue 1
    - Fix for issue 2
    - If the issue persists, contact our office

    ---

    ## Next Steps
    On completion, some or all of these could be the next steps:
    1. **Next Feature** — Brief description
    2. **Go to Dashboard** — Return to the main dashboard

    ## Suggestions
    - How to do X
    - How to do Y
    - What is on the Dashboard
```

2. Update the feature in the `index.md` file in the format:
```md
    - [Name](Link): What it does
```

---

## Page Type Reference

Use the table below to decide which optional sections to include for each type of page:

| Page Type | Sections to Include |
|---|---|
| **Form / Assessment** | Requirements, Steps, Possible Issues, Possible Remedies, Next Steps, Suggestions |
| **Dashboard** | Sections, Section Descriptions, Possible Issues, Possible Remedies, Next Steps, Suggestions |
| **Database / List Page** | Sections, Section Descriptions, Possible Issues, Possible Remedies, Next Steps, Suggestions |
| **Analytics Page** | Sections, Section Descriptions, Next Steps, Suggestions |
| **Services / Pricing Page** | Cards/Items, Possible Issues, Possible Remedies, Next Steps, Suggestions |
| **Booking / Scheduling** | Requirements, Steps, Possible Issues, Possible Remedies, Next Steps, Suggestions |
| **Document Upload** | Requirements, Steps, Possible Issues, Possible Remedies, Next Steps, Suggestions |
| **Navigation / Sidebar** | Sections, Section Descriptions, Possible Issues, Possible Remedies |
| **Profile Page** | Sections, Section Descriptions, Possible Issues, Possible Remedies, Next Steps, Suggestions |
| **Invoice / Billing** | Sections, Section Descriptions, Possible Issues, Possible Remedies, Next Steps, Suggestions |