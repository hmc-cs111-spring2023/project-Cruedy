# Design notebook entry

## Last week's critique

<p>My feedback partner recommended that I borrow my design from css, so I took that advice at least for creating shapes in my language because I thought that it would be good for describing the attributes of an element. Also, the process of talking to my feedback group about how they hade written their parsers helped me greatly with planning out writing my parser. Some of the questions that my feedback partner posed when he was discussing struggles with his own language regarding outputting javascript files from his parser helped me do some research on that before I started working on my parser.</p>

## Description

<p>I started working on [my parser](https://github.com/hmc-cs111-spring2023/Artifact-Cruedy/blob/main/DSL%20Code/parser.py) this week, so I also made adjustments to my language design to make it so that my parser could get to my desired result better. So far making the parser doesn't seem too hard. I was able to output an extendscript file that selected a composition to work on. Currently I'm able to process code that selected the current composition that is selected in after effects or that pics a specific composition with a given index. </p>

<p>This is the [output I've gotten so far](https://github.com/hmc-cs111-spring2023/Artifact-Cruedy/blob/main/select_comp.png) from my parser, and this is my [goal output](https://github.com/hmc-cs111-spring2023/Artifact-Cruedy/blob/main/goal_output.png). I'm going to make sure that my parser can catch errors, I already added an error catch that tells the user to make sure that their code picks a composition in the first line of code.</p>

<p>I am nervous that the way that I've been writing my parser is incorrect because it seems to simple or that the way I've written my parser is too prone to mistakes. If I find out that I've done it the wrong way, it's going to push back my progress. I'm treating the file that that I write my DSL in as a txt file, and that text file is just read into the parser line by line. When it reads those lines in, it just translates it to extenscript.</p>

## Questions

I feel like I'm making the parser wrong. Since I just have to read in one file and put out a javascript file from it, it seems like I'm pretty much just hard coding what each line.

Am I parsing it wrong if this is the way I'm doing it? It kinda feels similar to the example piconot parser because that one just looked at characters and looked at what to do for each case.

I've spent 6 hours on the code and 1 hour on this notebook.

I'm back on track now because I made a lot of progress on my parser this past week.
