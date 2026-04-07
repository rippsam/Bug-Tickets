## [StarWars API] Count is 82 People, 83rd Person Exists

---

### Description
On the [Star Wars API](https://swapi.dev) the people endpoint returns a count stating there are 82 people listed but if you go to people/83 there is a 83rd person. The count should state 83 not 82 since the first person starts at 1

---

### Replication Steps
1. Send a GET request to https://swapi.dev/api/people 
2. Verify that the first line of the response is "count": 82
3. Send a GET request to https://swapi.dev/api/people/83
4. Observe there is a 83 person

---

### Expected Behavior
The count on the /people endpoint states 83

---

### Actual Behavior
The count on the /people endpoint states 82

---

### Environment
- **Browser / Device:** Postman/Mac
- **Test Environment:** Production

---

### Customers Affected
All Users

---

### Category
Backend

---

### Attachments
<img width="545" height="589" alt="PeopleEndpoint" src="https://github.com/user-attachments/assets/abd7486a-fb59-4f32-b7fe-73243b27e22c" />
<img width="895" height="823" alt="PeopleEndpoint83Bug" src="https://github.com/user-attachments/assets/2ca783c4-e7b2-425d-8da3-5377eda71af5" />


---

### Severity / Priority
- **Severity:** Low
- **Priority:** 1
