==create (next) weekly note from template and pull in any scheduled/recurring tasks==
# Reminders Week <% tp.date.weekday("W", 1) %>
![[reminders]]
# Monday <% tp.date.weekday("M/D", 1) %>
- [ ] daily review - process [[scratch]]
- [ ] top [[backlog]] item(s)...
# Tuesday <% tp.date.weekday("M/D", 2) %>
- [ ] daily review - process [[scratch]]
- [ ] top [[backlog]] item(s)...
# Wednesday <% tp.date.weekday("M/D", 3) %>
- [ ] daily review - process [[scratch]]
- [ ] top [[backlog]] item(s)...
# Thursday <% tp.date.weekday("M/D", 4) %>
- [ ] daily review - process [[scratch]]
- [ ] top [[backlog]] item(s)...
# Friday <% tp.date.weekday("M/D", 5) %>
- [ ] daily review - process [[scratch]]
- [ ] weekly review - generate next week's note
- [ ] top [[backlog]] item(s)...
# Saturday <% tp.date.weekday("M/D", 6) %>
- [ ] daily review - process [[scratch]]
- [ ] top [[backlog]] item(s)...
# Sunday <% tp.date.weekday("M/D", 7) %>
- [ ] daily review - process [[scratch]]
- [ ] top [[backlog]] item(s)...

---

Tags: #weekly
Created at: <% tp.file.creation_date() %>
