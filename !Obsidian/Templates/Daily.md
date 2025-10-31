---
tags:
  - note
created: <%     tp.file.creation_date() %>
---
<<[[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').subtract(1, 'd').format('YYYY-MM-DD') %>|yesterday]] || [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').add(1, 'd').format('YYYY-MM-DD') %>|tomorrow]]>>
# {{date:dddd, MMMM Do, YYYY}}
#### todo: 
- [ ] 


















#### progress:


















---
> [!todo]+ today
> ```tasks
> not done
> happens {{date:YYYY-MM-DD}}
> hide recurrence rule
> hide due date
> hide scheduled date
> sort by priority
> ```

> [!danger]+ overdue 
> ```tasks
> not done
> (due before {{date:YYYY-MM-DD}}) OR ((happens before {{date:YYYY-MM-DD}}) AND (priority is above none))
> hide recurrence rule
> sort by due date
> ```

> [!tip]- next two weeks
> ```tasks
> not done
> happens after {{date:YYYY-MM-DD}}
> hide recurrence rule
> hide due date
> hide scheduled date
> group by happens
> ```

> [!example]- undated
> ```tasks
> not done
> no due date
> hide due date
> hide scheduled date
> group by priority
> ```

---









