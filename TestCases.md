# Test Cases – Message Template Editor

## TC-01 – Variable Insertion

**Precondition:**  
Editor is opened.

**Steps:**  
1. Place cursor inside text area.  
2. Click on variable button {firstname}.  

**Expected Result:**  
Variable is inserted at cursor position.

---

## TC-02 – Handling Unknown Variable

**Precondition:**  
Editor is opened.

**Steps:**  
1. Manually enter {unknown}.  
2. Open Preview.

**Expected Result:**  
Unknown variable is treated as plain text.

---

## TC-03 – IF-THEN-ELSE Execution

**Precondition:**  
Conditional block is added.

**Steps:**  
1. Enter valid value in IF condition.  
2. Open Preview.

**Expected Result:**  
Only THEN branch is executed.

---

## TC-04 – Nested IF-THEN-ELSE Validation

**Precondition:**  
Nested conditional structure created.

**Steps:**  
1. Provide value for outer IF.  
2. Provide value for inner IF.  
3. Open Preview.

**Expected Result:**  
Only correct branch of nested logic is executed.

---

## TC-05 – localStorage Persistence

**Precondition:**  
Template edited.

**Steps:**  
1. Click Save.  
2. Refresh page.

**Expected Result:**  
Template remains saved in localStorage.
