# Induction for new trainers and helpers

## Overview
Research IT delivers most of its training in the form of 1-day courses,
which are open to applications from staff and PG students.
The current [list of courses] is scheduled in advance for the whole year,
but extra courses can be added throughout the year if required.

## Setting the schedule
I aim to schedule the courses mid-week, because it doesn't interfere with anyone
taking a long weekend, and anecodotally it gives better attendance.

The PC cluster booking system for each year is only made live
over the summer --- normally August.
The system for this is now https://resourcebooker.manchester.ac.uk/

I typically book a PC cluster for a number of dates throughout the year,
and then the courses can be allocated based on the availability of the trainers.

[Current schedule]

Course instructors should:
- choose available dates from this [spreadsheet]
- create new events in the [training catalogue]
- find helpers for their course - volunteers in the [spreadsheet]
- create an Outlook calendar event and invite helpers and
  ResearchITNews@manchester.ac.uk

Research IT News is invited to the event for promotional and scheduling purposes.
The Research IT News newsletter promotes training, so this is the easiest way to
communicate the course details.

If there is anyone on the waiting list when the course schedule is set for the year,
I usually clear the waiting list onto the first event before advertising the schedule
to new applicants.

## Teaching format
We teach mostly in the style of Software Carpentry i.e. live-coding / code-along
see [Instructor Training] and [Teaching Tips].

We use G11 in Sackville as a least-worst option. There is a coded lock on the door,
and the door is sometimes locked. Speak to a colleague for the code.
One of the problems is that it's a big room, often with lots of external noise.
As such we have a couple of voice amplifier microphones available for use.
**Trainers should collect a microphone from B38 Sackville the day before the training,
and ensure that the headset and speaker are both charged.**

## Feedback and attendance
Helpers are encouraged to give (constructive) feedback to the trainers.

Feedback should also be solicited from the attendees,
and where possible the trainer should aim to respond to it during the course.

A short feedback questionnaire is to be completed by attendees,
which can also be used to record attendance for the course.
This should be processed by the trainer in the training catalog.

https://goo.gl/forms/jcldhMnnjaigAQFZ2

Marking those who haven't completed the feedback as 'failed to attend' seems to
be the most reliable way to elicit a feedback form response.

## Managing bookings
This is the responsibility of the trainer and is done through the [training catalogue].

Most courses are set for 'unmoderated online booking', but the waiting list is a misnomer.
People can apply to the waiting list if the event is full, but if someone with a
place cancels, the place is not filled automatically from the waiting list.

As such, when you receive an email alert informing of a cancellation, you should
review the waiting list and manually transfer applications to a course event.

An overview of how to use the training catalogue is given in the [guide],
but the waiting list management is detailed below:

Click the participants tab, select *waiting list* as the event,
and status as *pending*, then click on *filter*.
Select the students you want to move to the event,
and change new status to *confirmed*, and click the *override constraints*
button.
Then choose update status and set their event to the one you
want to move them to.

## Checklist for trainers before teaching
- Collect and charge microphone the day before
- Get some sticky notes if you're using them
- Check you have helpers, and that they are aware of this
- Fill empty places from the waiting list when you get cancellations

## Checklist for helpers
- Read the course material and ensure you understand the exercises
- Walk round the room --- learners will often 'grab' you for help if you're close by
- Look out for learners requesting help via sticky notes
- Give feedback to the trainer as required e.g.
	- too fast/ too slow
	- can't read screen
	- can't hear them
	- how long is the break
- Think about what went well and what didn't for post-course feedback

## Software
This should be requested over the summer (starting around July) so that it can be deployed
and tested on the cluster PCs ahead of time.
I recommend checking that it has deployed and works, even though you'll have done
User Acceptance Testing previously.

Sometimes learners will bring their laptop --- I usually try to help with any setup
difficulties, but stress that the course teaches the tool, not the setup, and they should
submit a support ticket if it can't be resolved quicky or during a break.
The software should be available on the training PCs.

## External attendees
Sometimes we have requests to accommodate external applicants.
This is extra work because if the learner brings their laptop and can't access eduroam,
this can be a deal breaker.
A 'conference plus' temporary account can be requested in advance, which gives a log in
for the training PCs. It's extra admin, so we only want to do this if the external applicant
is paying to attend a course. This is currently being investigated as a thing.

## External trainers
Occasionally an external trainer will teach a course which Research IT will organise locally.
Where possible we get the trainer to manage registrations. Previous such courses have been
run by ARCHER and NAG among others.

## Workshops
Software Carpentry workshops are run occasionally. These are two-day training courses which can
be a bit frantic. They need a central teaching room to be booked which is big enough for the number
of applicants, plus a bit of extra space to move around.
On top of a normal course, we need to remember:

- set up a [workshop website](https://github.com/carpentries/workshop-template)
- trailing power sockets, so the learners can power their laptops
- extra helpers for set-up problems, compared with a normal 1-day workshop using training PCs

See also the official [workshop checklist].

[Teaching Tips]: https://software-carpentry.org/blog/2015/03/teaching-tips.html
[Instructor Training]: http://carpentries.github.io/instructor-training/
[guide]: Training-Catalogue_Online-Booking-and-Search-Facility-v4.pdf
[Current schedule]: http://www.staffnet.manchester.ac.uk/staff-learning-and-development/academicandresearch/practical-skills-and-knowledge/it-skills/research-computing/research-courses/
[training catalogue]: http://app.manchester.ac.uk/training/default.aspx
[workshop checklist]: https://docs.carpentries.org/topic_folders/hosts_instructors/hosts_instructors_checklist.html
[spreadsheet]: https://docs.google.com/spreadsheets/d/1t145FFVd1_oQkOGHIz_YjbxO_9cH0YFZHIw4v4P9NAc/edit?usp=sharing
