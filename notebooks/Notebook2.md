# Design notebook entry

## Last week's critique

_From the feedback that I recieved last week, I decided that I would create a language that would output a script file. Script files have the extension .jsx, which means that they are JavaScript Syntax Extension files. After getting that feedback, I decided to look into how extend scripts look. This research made me change my project idea again becuase I realized that the code that I normally wrote straight into the after effects app couldn't run normally in .jsx files. I did some more research on examples of .jsx script files for after effects, and decided to try to output some simple code that actually worked using my DSL. Also, instead of making my language internal with javascript, I decided to make an external dsl with python because I have more experience writing in python._

## Description
_I created an [example script file](https://github.com/hmc-cs111-spring2023/Artifact-Cruedy/blob/main/wiggle.jsx), but the function that I put in the file wasn't able to run in after effects. The function I wrote in the script file was meant for After Effects, so I had to change what the main goal of this language was. I decided that the best basic script file for this project could just be creating a shape file, so I created a script that would create a shape layer that exist for the entirety of the time that the composition exists. Here is my [new example script file](https://github.com/hmc-cs111-spring2023/Artifact-Cruedy/blob/main/shape.jsx), even just writing and testing this file took a while because the version of after effects that I have doesn't work with all the functions that are available in extendscript. [This is what the output of the script is](https://raw.githubusercontent.com/hmc-cs111-spring2023/Artifact-Cruedy/main/Screen%20Shot%202023-04-09%20at%2010.43.32%20PM.png). As you can see, it adds a purple solid layer to the current compostion. I'm going to start out with just making a language that can create scripts that create solids, but then I want to get the scripts to be able to transform any layers._

## Questions

_I spent around 6 hours working on this part of the project, most of that time was spent on testing the script I wrote on an actual composition._

_There are a couple of ideas that I want for the new design of the language. One I'm thinking of at least for creating a shape, is saying the name of the shape and then making all of the attributes of the shape as parameters(words). This would make it a little more limited for colors. 
The other design structure I'm thinking of is more similar to an english sentence structure. Like:
"make circle with ..." where the '...' is the attributes._

_Since I did have to restart a little when I ran into an error while running my original script, I am now slightly behind, but I think the idea I have now might be slightly easier to execute than my idea from earlier._
