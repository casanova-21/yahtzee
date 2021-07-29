---
title: Played Yahtzee! {{ date | date('dddd, MMMM Do') }}
---
Someone just played a game of Yahtzee: 
Final roll is ${{needs.Roll-dice.outputs.first_die}}${{needs.Roll-dice.outputs.second_die}}${{needs.Roll-dice.outputs.third_die}}${{needs.Roll-dice.outputs.fourth_die}}${{needs.Roll-dice.outputs.fifth_die}}
