---
name: "🐞 Bug Report"
about: Report a defect or unexpected behavior in the application
title: "[BUG] Logged-in user email is displayed incorrectly after successful login"
labels: ["bug"]
assignees: [Muhindhar]
---
# 🐞 Bug Report (BUG-011)

## Summary
Logged-in user email is displayed incorrectly after successful login

---

## Environment
| Field | Value |
|-------|-------|
| Environment | QA |
| Browser | Chrome |
| Browser Version | Latest |
| OS | Windows 11 |
| Build / Version | v1.0 |
| Module | Login (Login) |

---

## Severity
- [ ] Critical (System/Application crash)
- [x] High (Major functionality broken)
- [ ] Medium (Feature partially affected)
- [ ] Low (Minor UI/Cosmetic issue)

---

## Priority
- [ ] P0 - Immediate
- [x] P1 - High
- [ ] P2 - Medium
- [ ] P3 - Low

---

## Preconditions
User account testing1@gmail.com exists and has valid credentials.

---

## Steps to Reproduce
1.Open the LMS application.
2.Navigate to the Login page.
3.Enter email: <testing1@gmail.com>
4.Enter the valid password.
5.Click Login.
6.Observe the email displayed after login.

---

## Expected Result
The application should display the authenticated user's email:<testing1@gmail.com>

---

## Actual Result
The application displays:

<testing@gmail.com>

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
<img width="583" height="631" alt="Image" src="https://github.com/user-attachments/assets/a539bc50-0135-4770-afaa-eedab9dd416e" />

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
| Reported By | Muhindhar S V |
| Assigned To | Dev Team |
| Date Reported | 2026-07-08 00:00:00 |
| Sprint | 1 |
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
