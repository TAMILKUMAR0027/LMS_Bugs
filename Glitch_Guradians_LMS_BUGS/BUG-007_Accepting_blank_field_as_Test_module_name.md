---
name: "🐞 Bug Report"
about: Report a defect or unexpected behavior in the application
title: "[BUG] Accepting blank field as Test module name"
labels: ["bug"]
assignees: [Mylambigai]
---
# 🐞 Bug Report (BUG-007)

## Summary
Accepting blank field as Test module name

---

## Environment
| Field | Value |
|-------|-------|
| Environment | QA |
| Browser | Chrome |
| Browser Version | |
| OS | Windows 12 |
| Build / Version | v1.1 |
| Module | Course Management (Add course structure) |

---

## Severity
- [ ] Critical (System/Application crash)
- [ ] High (Major functionality broken)
- [x] Medium (Feature partially affected)
- [ ] Low (Minor UI/Cosmetic issue)

---

## Priority
- [ ] P0 - Immediate
- [x] P1 - High
- [ ] P2 - Medium
- [ ] P3 - Low

---

## Preconditions
User on the Course management page

---

## Steps to Reproduce
1.User logs in to the application.
2.Navigate to the Course Management page.
3.Select the required course to add a course structure.
4.Click the Add Module icon.
5.Leave the Module Title field empty.
6.Click the Add Module button.

---

## Expected Result
The Error Message should be shown as "Title is required for module"

---

## Actual Result
It accept the empty space as valid name and create new module

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
| Reported By | Mylambigai G |
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
