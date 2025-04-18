# 🐞 Bug Report – UserAuth API Suite

## Bug ID: UA-001
**Title:** Login endpoint returns 200 for invalid credentials  
**Severity:** Medium  
**Environment:** Reqres API (https://reqres.in)  
**Steps to Reproduce:**
1. Send POST to `/api/login`
2. Body: `{ "email": "eve.holt@reqres.in", "password": "wrongpass" }`
3. Observe status code

**Expected:** 401 Unauthorized  
**Actual:** 200 OK  
**Notes:** This can mislead users into thinking login was successful

---

## Bug ID: UA-002
**Title:** Missing email field in registration gives unclear error  
**Severity:** Low  
**Steps:**
1. Send POST to `/api/register` with only `password` in body
2. Observe the response

**Expected:** `Missing email` with 400 status  
**Actual:** Generic error message with no detail  
