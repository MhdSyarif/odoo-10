# Odoo-10
Note Odoo 10

#Events

15:41 07/11/2016

Add field event
=> Developer Mode Acive
=> Settings => Technical => Database Structure => Model => search event.event => Edit

1. Room
Field Name => x_event_room
Field Label => Room
Field Type => many2one

Object Relation => event.track.location (diambli dari view form)

2. Topex Coordinator
Field Name => x_event_topex
Field Label => Topex Coordinator
Field Type => many2one

Object Type => res.users

3. Project Code
Field Name => x_event_project_code
Field Label => Project Code
Field Type => char

Size => 15

====================
Disabled Fields

invisible = '1'

======================
edit calender

color = "x_event_room"

name = "x_event_room"
name = "x_event_topex"
