<a href="https://github.com/drshahizan/short-course/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/short-course" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/short-course/network/members"><img src="https://img.shields.io/github/forks/drshahizan/short-course" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/short-course/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/short-course" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/short-course"><img src="https://img.shields.io/github/issues/drshahizan/short-course" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/short-course/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/short-course?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2Fshort-course&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

# Whimsical in ChatGPT: Step-by-Step

## Quick setup (one-time)

1. Open ChatGPT → **Explore GPTs** (left sidebar) → search **“Whimsical Diagrams”** → **Start chat** → (optional) **Keep in sidebar** to pin it for later. ([help.whimsical.com][1])
2. You can also type **@Whimsical Diagrams** in *any* chat and continue your prompt there. ([help.whimsical.com][1])
3. It can generate **flowcharts, mind maps, and sequence diagrams** directly from your prompt. (Concept maps are best formed by asking for a labeled flowchart/mind map with “labeled relationships.”) ([help.whimsical.com][1])
4. Notes & limits: style/colors/layout aren’t fully controllable via prompt; to edit deeply you’ll be prompted to **open in Whimsical** and adjust there. ([help.whimsical.com][1])
5. Access: GPTs are available to all ChatGPT users (Free has tighter message limits). Plus/Team/Enterprise can also create their own GPTs. ([OpenAI Help Center][2])


## A) Create a **Grant Flowchart** (end-to-end lifecycle)

**What this gives you:** a decision-based process from idea → submission → review → award → reporting/outputs.

**Say to Whimsical Diagrams:**

```
Create a grant LIFECYCLE FLOWCHART for a university research grant.

Stages (left to right):
1. Call Announced → 2. Eligibility & Fit Check → 3. Scoping & Literature Gap → 
4. Problem Statement & Objectives → 5. Methodology Design → 6. Work Plan & Milestones → 
7. Budget (show buckets: Personnel, Travel, Equipment/Services, Materials, Fees) → 
8. Compliance (ethics/data) → 9. Drafting & Internal Review → 10. Submission (portal) → 
11. Panel Review → decision: Accept / Revise & Resubmit / Reject → 
12a. Award & Onboarding (kickoff, accounts, procurement) → 
12b. Monitoring (progress reports, milestones, risks) → 
12c. Outputs (publications, students, IP, external grants follow-on) → 13. Close-out (final report).

Add decision diamonds where relevant; label connectors like “meets criteria?” or “budget approved?”.
```

**Iterate:**

* “Add roles swimlanes (PI, Co-I, Department, Research Office, Funder).”
* “Insert quality gates after ‘Methodology Design’ and ‘Budget’.”
* “Attach notes about required attachments at ‘Submission’.”


## B) Create a **Concept Map** (significance → impact → KPIs)

**What this gives you:** labeled relationships between constructs (great for evaluation or theory).

**Say to Whimsical Diagrams:**

```
Create a CONCEPT MAP with labeled relationships for a research grant’s impact logic.

Central concept: “Grant-Funded Research”.
First layer: “Significance to Knowledge”, “Societal Benefit”, “Policy Relevance”, 
“Industry/Economic Value”, “Capacity Building”.
Second layer:
- Under Significance to Knowledge → “Novel Theory”, “Methodological Innovation”.
- Under Societal Benefit → “Health Outcomes”, “Education Access”, “Sustainability”.
- Under Policy Relevance → “Evidence for Decision-Making”.
- Under Industry/Economic Value → “Tech Transfer”, “Workforce Skills”.
- Under Capacity Building → “Master’s/PhD Training”, “Collaboration Networks”.
Label edges with phrases like “enables”, “requires”, “measured by”, “leads to”.
```

**Iterate:**

* “Add KPIs under each node (e.g., 2 WoS papers; 1 PhD enrolled; 1 policy brief).”
* “Color code by stakeholder (funder, university, society)—if not possible here, I’ll edit in Whimsical.” ([help.whimsical.com][1])


## C) Create a **Mind Map** (proposal structure outline)

**What this gives you:** a one-glance outline to draft the proposal faster.

**Say to Whimsical Diagrams:**

```
Create a MIND MAP titled “Winning Research Grant Proposal”.

First ring:
- Background & Rationale
- Objectives & Research Questions
- Literature Review (gaps)
- Methodology (design, data, analysis)
- Work Plan & Milestones
- Budget (Personnel, Travel, Equipment/Services, Materials, Fees)
- Risk & Ethics (mitigation)
- Impact & Dissemination (publications, policy, industry, community)
- Team & Roles
- Sustainability & Follow-on Funding

For each branch, add 3-5 subnodes with examples and prompts to guide writing.
```

**Iterate:**

* “Expand ‘Budget’ with sample justifications and caps by category.”
* “Add ‘Attachments checklist’ branch (CVs, ethics approval, letters).”


### Power tips (inside ChatGPT)

* **Pin** Whimsical Diagrams to your sidebar for quick reuse. ([help.whimsical.com][1])
* In any chat, type **@Whimsical Diagrams** + your prompt to inject a diagram on the spot. ([help.whimsical.com][1])
* If you need fine-tuning (layout/colors), click **Open in Whimsical** when prompted and edit on the canvas. ([help.whimsical.com][1])


### Ready-to-use prompt pack (copy–paste)

**Grant Budget Map (mind map add-on)**

```
Mind map branch “Budget”: expand into
- Personnel: PI/RA rates, justification by tasks
- Travel: conferences (limits), fieldwork
- Equipment/Services: rentals, software, lab services
- Materials & Supplies
- Fees: student fees, publication
Add a sibling branch “Value for Money” → “unit costs”, “leveraged resources”, “co-funding”.
```

**Review Decision Tree (flowchart add-on)**

```
Add a decision subtree after "Panel Review": 
If “Minor Revision” → “Revise & Resubmit (2 weeks)” → back to “Submission”.
If “Major Revision” → “Methodology Rework” & “Budget Rebalance” → internal QC → “Resubmission”.
If “Reject” → “Root Cause Analysis” → “Pipeline for Next Call”.
```

**Impact Evidence Map (concept map add-on)**

```
From “Impact & Dissemination”, create nodes “Academic”, “Policy”, “Industry”, “Community”.
Attach metrics: Academic→ “WoS/Scopus”, “Citations”; Policy→ “Briefs”, “Adoptions”; 
Industry→ “IP/Prototypes”, “MOUs”; Community→ “Outreach”, “Training”.
Label edges with “measured by” / “supported by”.
```


### 🙌🏻 Connect with Me
<p align="left">
    <a href="https://github.com/drshahizan" target="_blank"><img alt="GitHub" src="https://img.shields.io/badge/-@drshahizan-181717?style=flat-square&logo=GitHub&logoColor=white"></a>
    <a href="https://www.linkedin.com/in/drshahizan" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/-drshahizan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/drshahizan/"></a>
    <a href="mailto:shahizan@utm.my" target="_blank"><img alt="Email" src="https://img.shields.io/badge/-shahizan@utm.my-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:shahizan@utm.my.com"></a>
    <a href="https://www.researchgate.net/profile/Mohd-Othman-28" target="_blank"><img alt="ResearchGate" src="https://img.shields.io/badge/-ResearchGate-00CCBB?style=flat-square&logo=ResearchGate&logoColor=white"></a>
    <a href="https://orcid.org/0000-0003-4261-1873" target="_blank"><img alt="ORCID" src="https://img.shields.io/badge/-ORCID-A6CE39?style=flat-square&logo=ORCID&logoColor=white"></a> 
 <a href="https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan" target="_blank"><img alt="A" src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic"></a>
 
![](https://hit.yhype.me/github/profile?user_id=81284918)
</p>
