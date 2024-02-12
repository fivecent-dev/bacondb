# bacondb

A reimagining of [Piggydb](https://https://piggydb.net/) inspired by [@shraderdm's](https://github.com/shraderdm) interest in the project.

BaconDB aims to organize fragments of information in useful, relevant ways.

Fragments of information (for example, useful facts, tasks, images, and small pieces of code) are labelled with relevant data to help categorize the fragments and exist in a global pool of all fragments. This pattern breaks the traditional folder-style organization where one file / fragment can only have one main category. In addition, multiple views of the fragments can be defined using flexible key-value labels (for example, `task-dependency: task-10`), providing different lenses to help make sense of all the data and take relevant actions.


## Examples

### Event planning

Fragments:
  - Website links
  - Summaries of information contained in a website link
  - Full contract PDFs / text
  - Summaries or highlights of contracts
  - Tasks needed to be accomplished (with due dates)
  - People / contacts (both those invited and contacts of venue, catering, and more)
  - Meetings (referencing involved people/contacts, tracking physical location or meeting link)

Views:
  - **_To-do list_**: manage only task fragments - which ones exist, any orders, due dates
  - **_Current day task list_**: view only event + tasks fragments coming up today
  - **_Calendar_**: manage any time-related fragments; assign tasks to be completed on a date or a specific time, view meetings in relation to tasks
  - **_Event agenda_**: manage only fragments representing the event order; attach people to timeframes (caterer to food timeframes; DJ to dance timeframe); plan both public-facing items (when food will be ready, when dance floor opens) and private-facing items (when caterers arrive, when drinks tab must be settled); expose public-facing agenda to a website, expose private agenda to relevant staff
  - **_Invite list_**: manage only "attendee" people fragments to track + update RSVP status, including dietary restrictions
  - **_Seating chart_**: manage only "attendee" fragments relative to seating placement, whether simply assigning groups / individuals to a table or assigning individual seats


### Formal learning
Fragments:
  - Key term
  - Definition of key term (or details around key term)
  - Group of key terms (like vertebrae, or key authors in a timeframe and genre)
  - Diagram with highlighted areas linked to key terms

Views:
  - **_Definition memorization_**: display term only, reveal definition on click/tap; display definition only, reveal term on click/tap
  - **_Association map_**: show similarly labeled topics, allowing for discovery of potential parallels
  - **_Group recall_**: display list of all fragments in a larger group (bones) and specify pulling out relevant group terms (vertebrae, in order); request full fill-in of group list based on group name
  - **_Diagram exploration_**: dive deeper into diagrams by examining topics relevant to highlighted area fragment; fill in diagram with term pool; fill in diagram with no word pool
