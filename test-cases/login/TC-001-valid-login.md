---
id: TC-001
title: Valid login with correct credentials
priority: high
module: login
automated: false
tags: [smoke, auth]
requirements: [REQ-001]
---

**Requirement:** [REQ-001 - User login](../../requirements/REQ-001-user-login.md)

**Preconditions:** User has an active account with a known email and password.

**Steps:**
1. Navigate to the login page.
2. Enter a valid email and password.
3. Click Log in.

**Expected result:** User is redirected to the dashboard and sees their name in the header.
