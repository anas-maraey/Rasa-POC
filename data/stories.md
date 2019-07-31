## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy
  - utter_goodbye

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## epic_zero
* greet
  - utter_greet
* epic_zero
  - utter_epic_zero
* epic_name
  - utter_corresponding_epic

## New Story

* greet
    - utter_greet
* epic_zero
    - utter_epic_zero
* epic_name{"EPICNAME":"Office IT"}
    - slot{"EPICNAME":"Office IT"}
    - utter_corresponding_epic
