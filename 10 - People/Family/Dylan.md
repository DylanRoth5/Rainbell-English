---
name: Dylan
gender: male
birthday: 2003-06-02
email: dylandaltonrh@gmail.com
phone: 5493434808641
tags:
  - family
  - closerfamily
---

## Profile

Name：`=(this.name)`
Age：`$= let date = moment(dv.current().birthday.toString(),"yyyy-MM-DD"); let today = moment().startOf('day'); today.diff(date,"years")` years old
E-mail：`=(this.email)`
Phone：`=(this.phone)`

## Habit Tracker

```dataview
TABLE WITHOUT ID
	link(file.name) as "日期",
	Reading AS "🌄",
	Birds AS "🐥",
	Workout AS "🏃‍♂️",
	E-mail AS "💌",
	Writing AS "📝",
	Mood AS "👾",
	Summary
	FROM "00 - DailyNotes/DailyNote" 
	SORT file.name DESC
	LIMIT 7
```

## Tasks This Week
```tasks
due before in this week
```