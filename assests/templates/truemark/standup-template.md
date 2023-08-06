---
id:<% tp.file.creation_date('DD-MM-YYYY') %>-standup
created_date: <% tp.file.creation_date('DD/MM/YYYY') %>
type: standup
tags: standup,office,truemark
---

# <% tp.file.creation_date('DD/MM/YYYY') %>
<% await tp.file.move("/content/truemark/standup/" + tp.file.creation_date('YYYY-MM-DD')+ "-standup")%>
### **Today** :<% tp.date.now("Do MMMM") %>
-
-
### **Tomorrow** :
-
-

### **Blockers** :
-
-