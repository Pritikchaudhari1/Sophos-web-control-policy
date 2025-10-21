# Sophos Web Control Policy

This project demonstrates how to block specific websites using **Sophos Central Web Control**.

## Objective
Block access to `olx.com` and `olx.in` using Sophos Central.

## Steps Performed

### 1. Create a Web Control Policy
- Logged in to **Sophos Central Admin Console**.
- Navigated to: `Endpoint Protection → Policies → Web Control`.
- Clicked on **Add Policy** to create a new policy.

### 2. Configure Website Blocking Rules
- In the **Website Management** section:
  - Added the following websites to the block list:
    - `olx.com`
    - `olx.in`
- Set the **Action** to **Block**.
- Added relevant **tags** (for example: *OLX Block*, *Restricted Sites*).

### 3. Apply the Policy to Endpoints
- Assigned the policy to the desired endpoint devices or user groups.
- Ensured the policy was **enabled** and **synchronized** with Sophos Central.

### 4. Verification
- Tested by visiting `olx.com` and `olx.in` on the endpoint system.
- Verified that both sites were successfully blocked.

## Folder Details
- `webblock_screenshot/` — Contains screenshots of the web control configuration and block test results.

## Conclusion
This demonstrates successful implementation of a website blocking rule using **Sophos Central Web Control Policy**.

---

Would you like me to make this README.md version look more **professional (with formatting, emojis, or badges)** like a GitHub project page?

