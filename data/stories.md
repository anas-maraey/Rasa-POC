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

## EpicF

* epic_name{"EPICNAME":"EpicF"}
    - slot{"EPICNAME":"EpicF"}
    - utter_corresponding_epic
    - utter_Q1

## EpicG

* epic_name{"EPICNAME":"EpicG"}
    - slot{"EPICNAME":"EpicG"}
    - utter_corresponding_epic

## EpicE

* epic_name{"EPICNAME":"EpicE"}
    - slot{"EPICNAME":"EpicE"}
    - utter_corresponding_epic

## EpicR

* epic_name{"EPICNAME":"EpicR"}
    - slot{"EPICNAME":"EpicR"}
    - utter_corresponding_epic

## EpicAR


* epic_name{"EPICNAME":"EpicAR"}
    - slot{"EPICNAME":"EpicAR"}
    - utter_corresponding_epic

## Escalateme

* epic_name{"EPICNAME":"Escalateme"}
    - slot{"EPICNAME":"Escalateme"}
    - utter_corresponding_epic