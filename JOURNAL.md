# JOURNAL

## Week 7 — Issue selection

**Issue link:** https://github.com/ascherj/pathreview/issues/117

**Issue title:** API docs don't include example curl commands

**Tier:** ☑ Tier 1 ☐ Tier 2 ☐ Tier 3

**Problem summary:**

The API documentation currently explains the available endpoints but 
doesn't provide example `curl` commands that developers can copy and 
run. This makes it harder for new contributors to quickly verify that 
the API is working after setting up the project locally. The missing 
examples are located in `docs/API.md` and affect developer onboarding 
rather than application functionality. A successful fix will add clear 
curl examples for the documented endpoints so users can test the API 
more easily.

**"Is this right for me?" checklist reasoning:**

I selected this issue because it is a Tier 1 documentation task with a 
clearly defined scope. It only requires updating the API documentation 
without changing application logic, making it a good first contribution 
to the project. I reviewed the existing documentation and confirmed the 
missing examples before choosing this issue.

**Branch name:** `docs/117-api-curl-examples`

**Setup confirmation:** ☑ App runs locally at `http://localhost:5173`

**Cohort ledger:** ☐ Issue added to cohort ledger (will update after 
adding my information)

## Selection reasoning

### Part 1 — Understanding the Issue

- I can explain the issue: The API documentation lists endpoints but 
does not show example curl commands. The goal is to improve docs/API.md 
by adding runnable examples.
- Affected area: This issue affects the documentation layer. The 
referenced file is docs/API.md.
- Definition of done: Developers should be able to copy the curl 
commands from the documentation and use them to test API endpoints.

### Part 2 — Tier Fit

- Tier: Tier 1
- Reason: This is a small documentation change limited to one file and 
does not require changes to application logic.
- This scope is appropriate for my first open-source contribution.

### Part 3 — Codebase Readiness

- I located the affected file: docs/API.md.
- I reviewed the existing API documentation structure and understand 
where examples should be added.
- I will verify examples against the available endpoints and local API 
setup.

### Part 4 — Scope and Time

- I reviewed issue comments and confirmed other contributors are working 
on similar tasks, but claims are non-exclusive.
- Estimated effort: 2–3 hours, which fits within Weeks 8–9.
- No blockers or dependencies were listed on the issue.

### Verdict

This issue is a good fit because it is a focused Tier 1 documentation 
improvement with clear acceptance criteria.


## Week 8 — Reproduction & solution planning

**Reproduction commit link:**
(To be added after committing)

**Reproduction summary:**

I opened docs/API.md and confirmed that each API endpoint is described 
only with text. There are no example curl commands demonstrating how to 
call the endpoints, making it difficult for new developers to verify the 
API is working locally.

**PLAN.md link:**
(To be added after PLAN.md is committed)

**Walkthrough video (recommended):**
Not recorded for now but will do a final video after all.

**Blockers or open questions:**
Need to verify request bodies for authentication and profile creation 
before writing examples.
