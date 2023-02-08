# Free project 1

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

    The user is someone who has some familiarity with programming languages and 
    would want a way to schedule their week quickly.

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

    The need met by this idea is to quickly make schedules using text. This
    could help lots of people by being able to quickly visualize schedules
    and make changes to them. This person's experience right now is probably
    making weekly schedules through google calendar or some other equivalent.
    If this language could help them, that could mean generating weekly
    schedules or course calendars could be automated and done quickly.

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

    I think a DSL is appropriate because calendars sometimes feel too cluttered?
    This might be a me problem, but when making an event on google calendar I
    have 8 options for how it repeats, the option to add notes, google meet links,
    a visibility option, location options, guest permissions, and I don't need all
    of that I just need it to repeat weekly and have a start/end time and name.
    It would be nice if there were a text-based DSL that could quickly generate
    calendars by taking in some input, which could then be automated by Python or
    some other external language. 

### Why you?

_What excites you about this idea? How did you come up with it?_

    I had the idea to make some alternative scheduling/calendar solution over break
    and toyed with the google calendar API in a frontend for a bit.
    It felt like Google calendar was both too broad in it's capabilities, but was still
    so frustrating at times. For instance, if I wanted to add an event to my calendar
    but didn't want to attend, google would mark it as having attended/spent time there.
    I have the dining hall hours on my google calendar and it says I spend over 50% of my
    time in meetings.
    Basically I like the idea of being able to input in some brief text, and having a full
    schedule be output.

### Domain

_Describe the project's domain in five words._

    Weekly schedule creation via text.

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

    The user would interact with the language via a command line or via a text file, with a
    string of functions called in order to generate the schedule. A preview of the schedule
    could then be seen while editing, similar to ContextFree.
    The reason this is the right way to interact with the problem domain is because it is
    both faster than editing a normal calendar/schedule, and also easier to type it out.

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

    When a program runs it outputs a generated schedule as a pdf or an image or
    a csv file. Errors that occur could be type mismatching/incorrect syntax.
    In these cases a small error message could be shown when using a commandline
    or from the program being used to see previews. 

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

    It should be easy to create events with a start day, start time and end time,
    name, and when it repeats using text input. It should be very difficult to 
    add more complexity, and impossible to do much of the functionality that
    typical calendar apps allow for.

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

    There are probably many DSLs in this domain. For instance:
    https://www.canva.com/create/weekly-schedules/
    https://www.coursicle.com/college-schedule-maker/
    https://schedulebuilder.org/

    They address the need very well as they allow for the user to create a schedule
    and to see a preview as they're editing it. I particularly like how there's an
    option for MW/TTR/MWF for events on Coursicle, how Canva has different templates,
    and how schedulebuilder has the option to export to many different options.
    That said, I also don't think they meet the need for being text based/being
    able to make a schedule by using text input, which I think is where they could
    improve on.


## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

    I think it could be skewed towards the systems aspect. Having the ability to add
    different events with parameters to a schedule does not seem very language design
    heavy. That said, there could be opportunities in the project to make language
    design decisions, such as how to define variables/repeating events. Maybe 70/30.

### Scope

_How big an idea is this? How ambitious is this project?_

    I think it's doable? It shouldn't be too big of an idea and could probably be done
    in a similar way to contextFree or even using contextFree. 

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

    It could be a good idea as I would be interested in a project like this, and
    it would involve designing a language and implementing semantics. That being said,
    I don't think it would be as complex as other DSL's, meaning most of the time
    spent on this project may be in systems aspect.
