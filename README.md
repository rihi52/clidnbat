# clidnbatter (Command Line Interface DNd comBAT TrackER)

A command line tool used to run combat scenarios, designed for 5th edition.

## **_All Features are currently In Progress_**

This is in very early stage development by someone, me, with limited coding experience and limited free time to work on it.

## Features

### Combat Tracker

- Initiative Tracker
- Add and save custom players - _Cannot edit saved players yet_
  - Holds name, AC, and HP for players
- Add up to 50 monsters of the same type
- Add as many different types of monsters as needed, pulled from an integrated sqlite3 db containing basic info on all monsters in the 5E SRD
- Displays Initiative spot, Name, HP, and AC
  - Can track HP of all combatants

### Lookup Tool

- A sqlite database containing the below stats of all monsters in the 5E SRD: - _Available_
  - Name
  - Type
  - CR - _Currently the only lookup option_
  - AC
  - HP
- Monsters can be searched and displayed by any of the above stats
- Custom monsters can be imported to the db via sqlite or using the cli interface of the program itself
