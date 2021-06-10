# Is it Lit
Is it Lit is a organizational tool to help you ensure all your quests are lit AF.

## Goal
Build the same product with different architectures. Pieces should be interchangeable in true microservice fashion.


## Components
### Meta
We will greate a very simple static page in GitHub Pages to track and link to the various combinations.
Users can request the stack when accessing Is It Lit - 'cause this is a brag.

### Front End
1. React
1. Vue

### API (REST + JSON)
1. Express
1. Go

### Data
0. Translation layer to keep databases in sync
1. AWS SQL Database
1. AWS Graph Database

## Requirements
* AuthN/Z
* User can have characters in their life to make planning quests easier.  (max 100)
* User can manage RELATIONSIPS between 2 or more characters.
* Relationships can be positive or negative.
* Form to add characters.
* Form to view characters.
* Form to edit characters.
* View page to view all characters.
* View page to view all relationships, filterable by positive and negative.
* Build a party form
  * target number
  * interests to include, ranked
  * max/min of positive/negative relationships or total score
  * sensible defaults for party, all counts in form are displayed as a range based on number possible
  * submission of form leads to PArty Suggestino PAge
* party suggestion page
  * editable list of all recommended attendees
  * form to add details about quest, date location etc
  * convert outcome to quest, submission leads to view quest page
* view quest page (quest)
  * TODO list for invites
  * details about party plan
  * edit button
  * delete button
* View page for all Quests, filterable by past and upcoming
* Characters, Relations, Parties and Quests are all permanently deletable.


## Object MOdel
### Character
  * Name
  * Contact Info
  * Interests

### Relationship
  * Members (friends/characters)
  * Score -2 - +2 (bed - good)
  * Name (optional)

### Party
  * Members
  * Name

### Quest
  * Party
  * Time/Date
  * Name
  * Locations
  * Description

# Random Thoughts
* it IS Lit
