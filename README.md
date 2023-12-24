# Schedule Manager

Many institutions have their schedule which the customers are interested in. Swimming pools, libraries, theatres, schools, etc. People want to have them in order to be aware and create their own schedules.

Yes, most institutions have a web site or, at least, social network account. In the best case they provide schedule as a pretty document which you can download and print out. In the worst case it is just a text announcement.

The keyword here is "pretty". There isn't design which everybody likes. Also, if you follow a few schedules you, probably, would like them to be similar. Same font, same colors, same layout, same size, etc

This is why you want to use Schedule Manager!

## Analogies

If you want to add a video clip on your web site you don't usually want to create your own video hosting. Just upload the video on [YouTube](youtube.com) and integrate it.
If you want to add a form/questionnaire just use [Google Forms](https://www.google.com/forms/about/) and integrate it.
If you want to add a map just create whatever you want on [Google Maps](maps.google.com) and integrate it.
If you want to add ad just integrate ad network of your choice.
Why this approach can't be applied to schedules?!

## Features
Schedule Manager serves for both business and customers. This is cloud-based, easy to use service which provides handy way to deal with schedules.

### Common features

Features that can be used buy both Business and Customers

* wide printing capabilities
* calendar

### For business
Business can open an account and use powerful Schedule Wizard to create as much different schedules as they want for any time period. Once a schedule is created you don't have to duplicate it anywere due to wide integration possibilities.

* Schedule Wizard
* visibility (private, public) (?)
* integration (websites, social netrowks, internet messagers)
* veriety integration ways (iframe, js library, json, jpeg file, svg, etc)
* notifications (no schedule events for upcoming period)
* open hours (?)
* style collection and customization

### For customers
A single place where you can find all institutions schedules styled the way your choose. Customers are able to choose among available time period and subscribe on updates. Wide printing capabilities.

* search institutions
* choose uniform layout and style
* view and print combined schedules
* subscription (maitenance, changes, etc)
* add custom notes to any schedule
* export events to popular calendars (Outlook, Google Calendar, Apple iCal, etc)

### Milestones

1. 3rd party calendar API libraries
    * able to get events
    * able to get updates
2. Backend service which exposes API to request schedules
    * variety data formats (json, jpeg, svg, etc)
    * js library to build the schedule on frontend side
    * iframe
    * wide range of customization
3. Web site which provides a handy way to build calendars
    * powerful calendar builder
    * search possibilities

## Competitors

[Orchestra by QuickSchools](https://orchestra.quickschools.com/)

[Trumba](https://www.trumba.com/connect/default.aspx)

## Terminology

* schedule (timetable) - a collection of events
    * period - minimum time range (dayly/weekly/monthly/yearly) which can be repeated over and over again (with some changes) in order to build infinit schedule. If it is set the schedule may be extended automatically (you are alway able to make changes in any period). Otherwise it has to be filled manually in advance.
    * type - defines whether the institution available during working hours or not when there isn't any event on the date (open/close)
* event - a record which belongs to a schedule and describes planned happening
    * duration - duration of the event (time range, day, week, month, year)

### Use cases

A number of real world examples

<details>
<summary>Swimming pool</summary>

The open hours: Tue - Sun, from 5:30 to 21:00. Monday closed.

The institution has many schedules:

#### the pool schedule
```
Sun: 12:00 - 17:45 Private Swim (2 or 3 lanes open)
Mon: 8:00 - 8:45 Deep water HIIT class
    9:00 - 9:45 Low Impact
    10:00 - 10:45 Arthritis Foundation
    16:45 - 19:00 The Entire Pool is Closed for Lessons and Swim Team. Sauna & Hot Tub are open
Tue: 8:15 - 8:45 HIIT Class
    9:00 - 9:45 Cardio & Toning
    10:00 - 10:45 SilverSplash
Wed: 9:00 - 9:45 Low Impact
    10:00 - 10:45 Arthritis Foundation
    16:00 - 17:00 Rec2Connect Swim Team (2 or 3 Lap Lanes Open)
    16:45 - 19:00 The Entire Pool is Closed for Lessons and Swim Team. Sauna & Hot Tub are open
    19:00 - 20:00 Rec2Connect Swim Team (2 or 3 Lap Lanes Open)
Thu: 8:00 - 8:45 Deep water HIIT class
    9:00 - 9:45 Cardio & Toning
    10:00 - 10:45 SilverSplash
    12:00 - 13:00 Rec2Connect Swim Team (1 Lap Lanes Open)
    18:00 - 19:00 Cardio & Toning
```

#### swim teacher Alisa

```
Mon: 8:00 - 9:00 ClassA
    12:00 - 12:00 ClassB
Thu: 8:00 - 9:00 ClassA
    12:00 - 12:00 ClassB
```

#### swim teacher Robert

```
Wed: 8:00 - 9:00 ClassA
    12:00 - 12:00 ClassB
Fri: 9:00 - 10:00 ClassA
    13:00 - 14:00 ClassB
```
</details>

<details>
<summary>School</summary>

Eva's PreK class schedule

```
Mon: 9:00 - 13:00
Thu: 9:00 - 13:00
Wed: 9:00 - 13:00
```

</details>


<details>
<summary>Library</summary>

events schedule
```
01/12/2023: Winter reading Game starts
01/12/2023: ReindeerRoundup starts
01/12/2023 15:30 - 16:30: Kids Cafe
01/12/2023 17:00: Artful Impact
02/12/2023 11:00 - 13:00: Gingerbread Houses
03/12/2023 13:00 - 16:45: Frosty's Fest Drop-in families
24/12/2023: Closed
25/12/2023: Closed
30/12/2023: Whale weeks! During library houses
31/12/2023: Closed
```
</details>