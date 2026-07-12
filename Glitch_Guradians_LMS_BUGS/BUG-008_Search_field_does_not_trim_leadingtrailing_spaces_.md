---
name: "🐞 Bug Report"
about: Report a defect or unexpected behavior in the application
title: "[BUG] Search field does not trim leading/trailing spaces, causing valid course search to fail"
labels: ["bug"]
assignees: [Malavicka]
---
# 🐞 Bug Report (BUG-008)

## Summary
Search field does not trim leading/trailing spaces, causing valid course search to fail

---

## Environment
| Field | Value |
|-------|-------|
| Environment | QA |
| Browser | Chrome |
| Browser Version | |
| OS | Windows 11 |
| Build / Version | v1.0 |
| Module | Course Management (Search) |

---

## Severity
- [ ] Critical (System/Application crash)
- [x] High (Major functionality broken)
- [ ] Medium (Feature partially affected)
- [ ] Low (Minor UI/Cosmetic issue)

---

## Priority
- [ ] P0 - Immediate
- [ ] P1 - High
- [x] P2 - Medium
- [ ] P3 - Low

---

## Preconditions
User should have valid LMS login credentials.

---

## Steps to Reproduce
1.Login and open the Course Management page.
2.Search for an existing course name with leading and trailing spaces.

---

## Expected Result
Matching course should be displayed.

---

## Actual Result
Matching course is not displayed.

---

## Frequency
- [ ] Always
- [ ] Intermittent
- [ ] Rare
- [ ] Unable to Reproduce

---

## Impact


---

## Error Messages / Logs
```text
```

---

## Screenshots / Screen Recording
Screenshot attached

---

## Attachments
- [ ] Playwright HTML Report
- [ ] Cucumber HTML Report
- [ ] Allure Report
- [ ] Execution Logs
- [x] Screenshot(s)
- [ ] Screen Recording

---

## Reporter Details
| Field | Value |
|-------|-------|
| Reported By | Malavicka V |
| Assigned To |  |
| Date Reported | 2026-07-09 00:00:00 |
| Sprint | |
| Related Story / Task | |
| Related Pull Request | |
| Status | New |

---

## Checklist
- [ ] Bug reproduced successfully
- [ ] Expected and actual results verified
- [ ] Supporting evidence attached
- [ ] Environment details provided
- [ ] Steps to reproduce are complete
- [ ] Labels assigned appropriately
