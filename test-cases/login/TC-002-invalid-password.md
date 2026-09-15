---
id: TC-002
title: Login attempt with an incorrect password
priority: high
module: login
automated: false
tags: [auth, negative]
---

**Preconditions:** User has an active account.

**Steps:**
1. Navigate to the login page.
2. Enter a valid email with an incorrect password.
3. Click Log in.

**Expected result:** Login is rejected and an invalid credentials error message is shown. The user remains on the login page.
