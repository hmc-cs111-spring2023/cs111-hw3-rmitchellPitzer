# Free project 2

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

    This user would basically be anyone that cooks, and the language would be
    a good way to keep track of any recipes and any alterations they may need
    to make to it. Kind of like a cook book!
    They would probably need to also have some familiarity with programming.

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

    The need met is to have a way to store cookbooks and recipes as a DSL/text
    file. I mean Chef language already exists, but I like the idea of having
    a collection of recipes stored in a cookbook as functions and variables. 
    The person probably just looks up on their phone or just cooks as is. If
    I could help them, they can define different dishes/processes to make dishes
    and look them up that way.

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

    It's not at all I can not justify this. I just think it'd be so so cool
    to define a function that could take in milk and a frother and make foam
    and a frother, and then be able to make your own recipe functions and
    save them in a cookbook/text file.
    I think maybe it addresses the need of saving a cookbook, so instead of
    typing it out on google docs or bookmarking or on paper like everyone does,
    you could now save it as recursive functions in a dsl.

### Why you?

_What excites you about this idea? How did you come up with it?_

    I think it is so absurd, and I absolutely love it. I think it's so cool.
    instead of following the directions to "cook the salmon on the stove 
    for 45 minutes", you could run the function cookOnStove(Salmon, 45). 
    It sounds like such a backwards way of saving recipes but it's so cool.

### Domain

_Describe the project's domain in five words._

    Cookbook, recipes, and checking ingredients.

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

    I think the user would interact with the language by editing a text
    file. In this text file the user could define different methods such
    as cookOverPan() or bakeInOven(), which could then be used to write out
    ingredients as functions.
    Once recipes are written out, the text file could then be passed into
    a terminal to run, which could output the user's recipe in a 
    easy to understand way.
    I think this might be the right way to interact with the problem domain
    because it will give clear instructions that the user will define and
    already know.

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

    When a program runs, it will check for type safety/syntax errors in the
    user's recipe book. It will then ask the user for a recipe, which will then
    output the instructions/ingredients required. 
    Some errors that might occur are syntax errors, or the recipes not working.
    This could then be indicated through compile errors.

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

    It should be easy for the user to define different functions/methods
    that can then be used in other recipes. It should be difficult to
    create functions that output food from ingredients you don't have.
    It should be impossible to create functions/recipes that don't have
    type safety.

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

    There is Chef, but I think Chef is more a general purpose programming 
    language that can be encoded in recipes. There is Cook, which is:
    https://github.com/MichaelBarney/cook
    which is very similar to what I'm describing. 
    I think Cook is implemented in an imperative function, whereas the 
    DSL I'm describing could be done in a funcitonal way, which could
    make more sense to the users.

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

    I think the implementer would spend much more time on the language aspect
    as opposed to the systems aspect. This is because there's not many
    keywords to define. If I had to give a percentage, probably 80/20.

### Scope

_How big an idea is this? How ambitious is this project?_

    I think this isn't too big of an idea and isn't too ambitious, but I 
    really like how absurd/dumb it is, and would love to work on something
    like this for this class.

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

    I think it'd be a great idea for a project just because it perfectly fits
    the DSL definition. I don't think it'd be as good of a project because it
    might not be useful to many people. 