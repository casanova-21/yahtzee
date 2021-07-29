---
name: YAHTZEE!!!
about: Template for actions testing
title: Played Yahtzee! {{ date | date('dddd, MMMM Do h:mm') }}
labels: ''
assignees: ''

---

Someone just played a game of Yahtzee: 
Final roll is **{{env.first_die}}{{env.second_die}}{{env.third_die}}{{env.fourth_die}}{{env.fifth_die}}**
