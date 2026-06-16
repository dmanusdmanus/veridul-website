# Veridul App Screens

## Purpose

Define the user experience for Veridul during communication monitoring and risk detection.

Veridul should remain silent unless meaningful risk is detected.

The objective is to provide useful protection without creating unnecessary interruptions or false alarms.

---

# Screen 1 — Normal Call

Purpose:

Allow normal conversations without interruption.

Behavior:

* No warnings
* No vibration
* No voice alerts
* No visual interference

User Experience:

Veridul monitors communication risk signals in the background.

The user should not notice Veridul during normal conversations.

Goal:

Users should trust that if Veridul remains silent, no meaningful risk has been detected.

---

# Screen 2 — Verify Before Acting

Purpose:

Alert users when unusual patterns are detected but confidence remains moderate.

Trigger Examples:

* Unusual request
* Unknown caller making important claims
* Early signs of manipulation

Behavior:

* Small notification appears
* No aggressive interruption
* Optional vibration

Screen Message:

VERIFY BEFORE ACTING

Additional verification may be appropriate.

Recommendation:

Proceed carefully and verify important requests independently.

---

# Screen 3 — Stop And Verify

Purpose:

Warn users when multiple risk signals are detected.

Trigger Examples:

* Money request
* Urgency
* Impersonation claim
* Verification code request

Behavior:

* Large visual warning
* Strong vibration
* Clear explanation

Screen Message:

STOP AND VERIFY

Potential scam indicators detected.

Examples:

* Money request
* Urgency detected
* Identity cannot be verified

Recommendation:

Verify independently before taking action.

---

# Screen 4 — Immediate Verification Required

Purpose:

Protect users during high-confidence dangerous situations.

Trigger Examples:

* Family impersonation
* Financial fraud attempt
* Verification code theft attempt
* Multiple high-risk indicators

Behavior:

* Full-screen warning
* Repeated vibration
* Optional voice alert

Screen Message:

IMMEDIATE VERIFICATION REQUIRED

Potential fraud in progress.

Do not:

* Send money
* Share passwords
* Share verification codes

Recommendation:

Verify independently before proceeding.

Available Actions:

* End Call
* Continue Call
* Contact Trusted Person

---

# Screen 5 — Call Summary

Purpose:

Provide transparency after the communication ends.

Behavior:

Displayed after the call is completed.

Example:

Call Summary

Trust Assessment:

High Risk

Indicators Detected:

* Money request
* Urgency
* Identity claim

Recommendation:

Verify independently before acting on any requests made during this communication.

---

# Design Principles

* Simple language
* Minimal false alarms
* Human-first communication
* Clear recommendations
* Easy to understand for all age groups

---

# Core Product Rule

Veridul should remain silent most of the time.

Warnings should occur only when meaningful risk is detected.

User trust is the highest priority.
