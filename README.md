

For this project, you will build a message generator program. Every time a user runs a program, they should get a new, randomized output. You’re welcome to take the project in a couple of different forms, like an astrology generator, inspirational message, or nonsensical jokes. To make your program truly random, the message that it outputs should be made up of at least three different pieces of data. Take what you know of JavaScript syntax so far to build the program and customize it to your liking.

# Project Objectives:
Build a message generator program using JavaScript
Use Git version control
Use command line
Develop locally on your computer
Prerequisites:
JavaScript
Git and GitHub
Command line


### Come Up with a Topic
Decide on what types of messages you want your program to output.

Think about what kinds of messages you’d like your program to output. Is it a horoscope generator? A fortune teller? An inspiring phrase? Knock-knock jokes? Here’s an example of what the output of a horoscope generator could look like:

Your sign is sun.

You are having good luck. 

You should: "trust no one"
Remember, to make your program truly random the message should really be made up of multiple strings that are output together.

Think about what parts of the string could stay the same each time and what parts could change. In the output above, what do you think are the pieces that change each time?

## Plan your project
Visualize your end result. What is it built with? What can it do? Make sure that it satisfies all of the project objectives.

Make a timeline for yourself and avoid the temptation to build things that aren’t required. Setting firm boundaries and deadlines will keep you on track and prevent scope creep.

The following tasks will help you identify natural break points.

### Store message components
Decide how to store all of the message components for your game.

Think about what kind of data structures would work best to store the information. An array would be a good choice here because you can randomly access an array’s elements. Remember, there will be at least 3 sets of data that make up your final message so you might consider having multiple arrays. You may want to nest these arrays inside of an object to keep them organized.

### Create the message
Add functionality to randomly select the different message components so they can create a cohesive message.

You can use a loop to iterate through the object, with a switch case that can select and format each of the different message components.

### Put the program together
Combine the different parts of your program so the random messages are selected, combined, and then displayed to the user each time they run the program.

You can use a function to handle the overall formatting and display of the randomized message.