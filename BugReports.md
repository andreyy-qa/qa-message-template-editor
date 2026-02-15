# Bug Reports – Message Template Editor

---

## BUG-01 – Incorrect Execution of Nested IF-THEN-ELSE

**Environment:**  
Local setup (Node.js), Chrome browser

**Precondition:**  
Nested IF-THEN-ELSE structure created.

**Steps to Reproduce:**
1. Create outer IF block.
2. Add nested IF block inside ELSE branch.
3. Provide value for outer IF.
4. Open Preview.

**Expected Result:**  
Only THEN branch of outer IF should execute. Nested ELSE block should not be evaluated.

**Actual Result:**  
Nested condition inside ELSE branch is executed even when outer IF is true.

**Severity:** High  
**Priority:** High

---

## BUG-02 – Re-processing of Variable During Message Generation

**Environment:**  
Local setup (Node.js), Chrome browser

**Steps to Reproduce:**
1. Insert variable {firstname}.
2. Enter value containing template-like text (e.g., {lastname}).
3. Open Preview.

**Expected Result:**  
Variable value should be processed once without re-parsing.

**Actual Result:**  
Variable content is re-processed, leading to incorrect output.

**Severity:** High  
**Priority:** Medium

---

## BUG-03 – Unknown Variable Removed Instead of Treated as Text

**Environment:**  
Local setup (Node.js), Chrome browser

**Steps to Reproduce:**
1. Enter {unknown} manually.
2. Open Preview.

**Expected Result:**  
Unknown variable should be displayed as plain text.

**Actual Result:**  
Unknown variable is removed from generated message.

**Severity:** Medium  
**Priority:** Medium
