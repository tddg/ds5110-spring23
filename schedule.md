---
layout: schedule
title: Course Schedule 
description: Being less concrete further out, the course scheduling is tentative and subject to changes.
nav_order: 2
weeks:
  # Each key in this dictionary is a week, and then eaach week has a key in [Mon, Tue, Wed, Thu, Fri].
  # Each day has keys `date` and `content`. The date is shown on the schedule, and `content` is a key into the yml file in \_data/modules.yml. `content` may be an array.
  # Each day can also have a `note` field, which is shown in italics on the calendar.
  # This schedule data is unioned with the deadlines in \_data/config.yml
  '1':
    Mon:
      date: 2023/01/16
      content: 1a
    Wed:
      date: 2023/01/18
      content: 1b
      note: "[Assignment 0](/ds5110-spring23/assignments/a0) out"
  '2':
    Mon:
      date: 2023/01/23
      content: 2a
    Wed:
      date: 2023/01/25
      content: 2b
  '3':
    Mon:
      date: 2023/01/30
      content: 2b
    Wed:
      date: 2023/02/01
      content: 2c
      note: "[Assignment 1](/ds5110-spring23/assignments/a1) out"
  '4':
    Mon:
      date: 2023/02/06
      content: 3a
    Wed:
      date: 2023/02/08
      content: 3b
  '5':
    Mon:
      date: 2023/02/13
      content: 4a
    Wed:
      date: 2023/02/15
      content: 4b
  '6':
    Mon:
      date: 2023/02/20
      content: projectIntro
    Wed:
      date: 2023/02/22
      content: 5b
      note: "[Assignment 2](/ds5110-spring23/assignments/a2) out"
  '7':
    Mon:
      date: 2023/02/27
      content: midtermReview
    Wed:
      date: 2023/03/01
      content: midterm
  '8':
    Mon:
      date: 2023/03/06
      content: springRecess
    Wed:
      date: 2023/03/08
      content: springRecess
  '9':
    Mon:
      date: 2023/03/13
      content: 5c
    Wed:
      date: 2023/03/15
      content: 6a
  '10':
    Mon:
      date: 2023/03/20
      content: 7a
    Wed:
      date: 2023/03/22
      content: 7b
  '11':
    Mon:
      date: 2023/03/27
      content: 7c
    Wed:
      date: 2023/03/29
      content: 8a
  '12':
    Mon:
      date: 2023/04/03
      content: 8b
    Wed:
      date: 2023/04/05
      content: 8c
  '13':
    Mon:
      date: 2023/04/10
      content: 9a
    Wed:
      date: 2023/04/12
      content: 10a
  '14':
    Mon:
      date: 2023/04/17
      content: 10b
    Wed:
      date: 2023/04/19
      content: 11a
  '15':
    Mon:
      date: 2023/04/24
      content: workOnProj
    Wed:
      date: 2023/04/26
      content: presentation
  '16':
    Wed:
      date: 2023/05/03
      content: 
---
