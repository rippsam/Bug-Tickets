## [The Case Work] An Admin can delete Account Owner

---

### Description
Admin users can delete the user that is the account owner

---

### Replication Steps
1. Log in with an admin user
2. Navigate to Account Settings>Users
3. Select the delete icon when hovering on the account owner user, or select the delete using the ellipses


---

### Expected Behavior
Permission to delete any of the users besides the account owner. Deleting account owner is denied permission

---

### Actual Behavior
Account owner is deleted the same as any user

---

### Environment
- **Browser / Device:** Chrome/Mac
- **Test Environment:** Production

---

### Customers Affected
All Customers

---

### Category
Security, Backend

---

### Replicated By

- **Name:** Bryce

---

### Severity / Priority
- **Severity:** High 
- **Priority:** 4
