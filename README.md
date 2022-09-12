
# Demcon programming challenge 2022

DEMCON has decided to expand its activities, and to organize
a two musical festival. After being an expert in mechatronic
systems engineering, the move to the entertainment business
seems a rather logical choice.

For the festival 30 acts are hired, such as the DEMCON band
and other popular acts. Unfortunately each band has a very
tight schedule, and is only able to play at a fixed timeslot.
This makes the planning difficult, and the festival organizer
needs to know how many stages to prepare for the event.

You're job is to help the festival organization. You are given
a list of shows, each with a start and end time. Since the
festival goes on non-stop, the start and end times are provided
as an offset since the start of the festival.

For example, the first three shows are given like this:

    show_1 36 39
    show_2 30 33
    show_3 29 36

`show_1` is scheduled from 36 hours after festival start, and will
play for 4 long hours up to (and including) hour 39 after festival
start.

It can be seen that `show_1` and `show_3` overlap, since they both play
at hour 36. Also `show_2` and `show_3` overlap, so they cannot share a
stage.

Your task is to create a planning program which takes the list of
shows and their start and end times, and creates a planning.
Make sure to draw a nice table with the shows filled in at
their corresponding time slots.

Good luck!
