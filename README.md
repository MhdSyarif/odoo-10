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

===========================
16:43 08/11/2016

Menambahkan field Trainer, Traning Place

Add Model

search is_partner

1. Trainer

Field Name => x_is_trainer

Field Label => Trainer

Field Type => boolean

2. Training Place

Field Name => x_training_place

Field label => Training Place

Field Type => boolean


Add form Sales

name ="x_is_trainer"

name ="x_is_training_place"

Event

add model

1. Trainer

Field Name => x_event_trainer

Fild Label => Trainer

Field Type => many2one

object => res.partner

add form

name ="x_event_trainer"