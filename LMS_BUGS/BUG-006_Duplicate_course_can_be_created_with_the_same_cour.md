---
name: "🐞 Bug Report"
about: Report a defect or unexpected behavior in the application
title: "[BUG] Duplicate course can be created with the same course details"
labels: ["bug"]
assignees: [Shobana]
---
# 🐞 Bug Report (BUG-006)

## Summary
Duplicate course can be created with the same course details

---

## Environment
| Field | Value |
|-------|-------|
| Environment | QA |
| Browser | Chrome |
| Browser Version | |
| OS | Windows 11 |
| Build / Version | v1.0 |
| Module | Course Management (Add course) |

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
User is logged in as Admin and Course Management page is accessible.

---

## Steps to Reproduce
1. User should login.
2. Navigate to the Course Management page.
3. Click Add Course and enter valid course details.
4. Attempt to create another course using the same data.
5. Click the Save Layout button.

---

## Expected Result
The application should display a validation message such as "Course already exists."

---

## Actual Result
The application allows another course with the same details to be created without any validation message.

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
Screenshot attached below

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
| Reported By | Shobana V |
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
