# Design notebook entry

## Last week's critique

_From the feedback that I recieved last week, I decided that I would create a language that would output a script file. Script files have the extension .jsx, which means that they are JavaScript Syntax Extension files. After getting that feedback, I decided to look into how extend scripts look. This research made me change my project idea again becuase I realized that the code that I normally wrote straight into the after effects app couldn't run normally in .jsx files. I did some more research on examples of .jsx script files for after effects, and decided to try to output some simple code that actually worked using my DSL. Also, instead of making my language internal with javascript, I decided to make an external dsl with python because I have more experience writing in python._

## Description
_I created an [example script file](https://github.com/hmc-cs111-spring2023/Artifact-Cruedy/blob/main/wiggle.jsx), but the function that I put in the file wasn't able to run in after effects. The function I wrote in the script file was meant for After Effects, so I had to change what the main goal of this language was. I decided that the best basic script file for this project could just be creating a shape file, so I created a script that would create a shape layer that exist for the entirety of the time that the composition exists. Here is my [new example script file](https://github.com/hmc-cs111-spring2023/Artifact-Cruedy/blob/main/shape.jsx), even just writing and testing this file took a while because the version of after effects that I have doesn't work with all the functions that are available in extendscript. [This is what the output of the script is](https://raw.githubusercontent.com/hmc-cs111-spring2023/Artifact-Cruedy/main/Screen%20Shot%202023-04-09%20at%2010.43.32%20PM.png). As you can see, it adds a purple solid layer to the current compostion._

**TODO:** Fill in this part with information about your work this week:
important design decisions, changes to previous decisions, open questions,
exciting milestones, preliminary results, etc. Feel free to include images
(e.g., a sketch of the design or a screenshot of a running program), links to
code, and any other resources that you think will help clearly convey your
design process.

## Questions

_I spent around 6 hours working on this part of the project, most of that time was spent on testing the script I wrote on an actual composition._
**What is the most pressing issue for your project? What design decision do
you need to make, what implementation issue are you trying to solve, or how
are you evaluating your design and implementation?**

**What questions do you have for your critique partners? How can they best help
you?**

**How much time did you spend on the project this week? If you're working in a
team, how did you share the work?**

**Compared to what you wrote in your contract about what you want to get out of this
project, how did this week go?**
