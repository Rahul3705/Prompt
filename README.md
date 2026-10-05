# Prompt

I need you to analyze my repository and documentation specifically for the five documents I will be presenting.

## My presentation topics

I am Rahul, and I will be presenting:

1. **R5 — frontend-react-standard.md**
2. **R6 — confluence-sme-entitlements.md**
3. **R7 — confluence-standards-process.md**
4. **R8 — Org-services-flags-authz-template.md**
5. **R9 — confluence-business-banking-vault.md**

My goal is to understand these documents deeply enough that I can confidently explain them to developers/architects and answer technical questions.

---

# STEP 1 — Find and inspect the documents

First, locate the exact R5, R6, R7, R8 and R9 documents in the repository/workspace.

For each document:
- Read the complete document.
- Identify its purpose.
- Identify important terminology.
- Identify technical standards/rules.
- Identify examples.
- Identify dependencies on other documents/components.
- Identify what the project is expected to implement or follow.

Do not give me a generic explanation. Base your analysis on the actual documents.

---

# STEP 2 — Analyze each document

For EACH of R5, R6, R7, R8 and R9, provide:

### 1. Purpose
- What is this document?
- Why does it exist?
- What problem does it solve?

### 2. Key concepts
Explain all important concepts and terminology in simple but technically accurate language.

### 3. Technical requirements
List the actual standards, rules, patterns, tools, configurations or implementation requirements mentioned.

### 4. Project relevance
Explain:

**"How does this document apply to OUR project?"**

Identify relevant:
- frontend
- backend
- services
- APIs
- authorization
- entitlements
- configuration
- processes
- banking/business functionality
- vault/secrets
- architecture

Only mention something if you can support it from the repository/documentation.

### 5. Actual repository mapping

Find the relevant code/configuration/files.

Use this format:

| Document requirement | Repository file/component | Current implementation | Gap |
|---|---|---|---|

If something is not implemented or cannot be found, explicitly say:

**Not found in repository — needs confirmation.**

---

# STEP 3 — Deep analysis of each topic

## R5 — frontend-react-standard.md

Analyze specifically:

- React architecture
- Component standards
- Folder/project structure
- State management
- Hooks
- API/service communication
- Forms
- Error handling
- Reusable components
- Naming conventions
- Styling
- Testing
- Security considerations
- Accessibility if mentioned
- Any mandatory libraries/tools
- Coding standards

Then explain how these standards should be applied when developing our frontend.

Give me a simple example flow:

User Action → React Component → Hook/Service → API → Backend → Response → UI

Use actual repository names where available.

---

## R6 — confluence-sme-entitlements.md

Analyze:

- What SME means in this context
- What an entitlement is
- Why entitlements are required
- Roles vs entitlements
- Authorization model
- User → Role → Entitlement → Permission flow
- How entitlement information is stored/retrieved
- Which services are involved
- API flow
- Security implications
- How frontend and backend use entitlements

Explain the complete authorization flow using the actual project architecture.

Also identify any relationship with R8.

---

## R7 — confluence-standards-process.md

Analyze:

- Development standards
- Engineering process
- Required development practices
- Code review process
- Testing requirements
- Documentation requirements
- CI/CD expectations
- Branching/version-control standards
- Definition of Done, if present
- Governance/approval process
- Quality gates

Explain what a developer must actually do differently because of this document.

---

## R8 — Org-services-flags-authz-template.md

Analyze deeply:

- Organization services
- Feature flags
- Authorization
- Authentication, if applicable
- Configuration
- Permission checks
- Service responsibilities
- Request flow
- Security boundaries
- How feature flags affect behavior
- How authorization decisions are made
- How frontend and backend interact with these services

Create an end-to-end flow where possible:

User → Frontend → Auth → Org Service → Entitlement/AuthZ → Feature Flag → Business Service

Clearly distinguish which parts actually exist in the repository and which are only described in documentation.

---

## R9 — confluence-business-banking-vault.md

Analyze:

- What Business Banking Vault means in this project
- Its business purpose
- Architecture
- Components
- Data flow
- Security
- Secrets/credentials management
- Vault integration
- Configuration
- Service dependencies
- Authentication/authorization
- How applications access Vault
- What developers need to implement/follow

Explain any relationship between Vault, configuration and security.

---

# STEP 4 — Relationships between R5–R9

This is very important.

Explain how these five documents connect to each other.

Create a dependency/relationship map such as:

R5 Frontend Standards
        ↓
R6 Entitlements
        ↓
R8 AuthZ / Feature Flags
        ↓
Business Services
        ↓
R9 Vault / Secure Configuration

And explain where R7 Standards Process applies across all of them.

Correct the flow if the actual documentation/repository shows a different relationship.

---

# STEP 5 — Documentation vs Repository

Create one consolidated table:

| ID | Document | Main purpose | Relevant code | Implemented? | Gap / Question |
|---|---|---|---|---|---|
| R5 | Frontend React Standard | | | | |
| R6 | SME Entitlements | | | | |
| R7 | Standards Process | | | | |
| R8 | Org Services / Flags / AuthZ | | | | |
| R9 | Business Banking Vault | | | | |

Do not assume implementation status.

---

# STEP 6 — Presentation preparation

Create a presentation structure for me.

For each R5–R9, give me:

### Opening
A 30–60 second explanation of what the document is.

### Main points
The 5–8 most important points I should present.

### Technical flow
A clear end-to-end flow.

### Repository evidence
Exact files/classes/configuration that support the explanation.

### Project impact
What developers need to follow or implement.

### Risks / gaps
Anything unclear, missing or potentially problematic.

### Questions for the team
Questions I should ask if something needs clarification.

---

# STEP 7 — Interview-style technical questions

Prepare likely questions the architect/developers may ask me.

For each document, give me at least 5 questions with concise answers.

Example:

**Q: Why do we need entitlements if we already have roles?**

**Answer:** Explain based on our actual documentation/project architecture.

Do not give generic textbook answers when project-specific information is available.

---

# STEP 8 — Final Rahul cheat sheet

At the end, create:

## Rahul's R5–R9 Cheat Sheet

For each topic give:

**R5:** What it is → Why → How → Project usage → Important files

**R6:** What it is → Why → How → Project usage → Important files

**R7:** What it is → Why → How → Project usage → Important files

**R8:** What it is → Why → How → Project usage → Important files

**R9:** What it is → Why → How → Project usage → Important files

Then give me:

### Top 15 things I MUST know before presenting

### Top 15 questions I may be asked

### Top 10 questions I should ask the architect/team

### Important terminology I should know

### Areas where I should NOT make assumptions

---

## Important instructions

- Do not modify any files.
- Do not generate implementation code unless I explicitly ask.
- Analyze the actual repository and documents first.
- Use exact file names, class names and configuration names wherever possible.
- Do not invent architecture.
- Clearly distinguish **documented requirement vs existing implementation vs recommendation**.
- If something cannot be verified, say **"Needs confirmation."**
- Keep explanations technically accurate but easy enough for me to present verbally.
- Assume I am presenting to experienced developers/architects, so do not oversimplify the technical concepts.
- Prioritize R5–R9 above unrelated documents.
