# {{date:YYYY-MM-DD}}

*Weekly Review: [[<% tp.date.now('yyyy') %>-W<% tp.date.now('ww') %>]]*

---
## Three Goals for Today (most important)
- [ ] 
- [ ]  
- [ ] 

## Mood Barometer
_(1 for worst, 3 for best)_
Professional::
Personal::
Athletics::

## Wins of the Day

## Notable Events

---

## Notes




## Prepared Meetings for Today

```dataview
LIST FROM "pages" WHERE Date=date({{date:YYYY-MM-DD}})
```

### The Day is not over until
- [ ] 1
- [ ] 2
- [ ] 3

## Tasks
### Due today
```tasks
not done
due on {{date:YYYY-MM-DD}}
```

### Scheduled for Today
```tasks
not done
scheduled on {{date:YYYY-MM-DD}}
```

### Selected for this Week
```tasks
not done
priority is high
```

### Overdue
```tasks
not done
happens before {{date:YYYY-MM-DD}}
```

### Due in the next two weeks
```tasks
not done
due after {{date:YYYY-MM-DD}}
due before {{date+14d:YYYY-MM-DD}}
```


### Completed today
```tasks
done on {{date:YYYY-MM-DD}}
```

### Files created Today
```dataview
LIST FROM "pages" where file.ctime >= date(today)
```