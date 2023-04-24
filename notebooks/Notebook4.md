# Design notebook entry

## Last week's critique

_Since I wrote a lot of my parser last week, I wanted to check in with my critique group to see if I was writing my parser correctly. I just felt unsure about the way I wrote my parser because it written in such a way where it just searched for a specific string and spit out another string as an output. My critiquer recommended that I use the regex group function to parse the code so that it's less hard coded. I think I'm going to take that advice for parsing the individual elements like shapes and effects._
_After looking into my code, I decided to just parse it without regular expressions because I'm not grouping elements by "(", and I already have the input code split up by line._

## Description

_I was able to translate every element attribute into extendscipt code and create default values for each attribute. Since I decided to use the names of colors for my DSL, I have to figure out how to translate them to the rgb values. The example I'm using is the color red, which is simply just (1, 0, 0), but I need to make sure it works for more complex values. To do this I imported colors from the matplotlib library. The to_rgba() function gave me the rgba values, and I just removed the last element from the outputted list. I also had to some manipulation to the list to make it the correct format._

_[This jsx file](https://github.com/hmc-cs111-spring2023/Artifact-Cruedy/blob/main/DSL%20Code/shape.jsx) is what I've outputted so far, but I'm still thinking out ways to simplify the parser or use the reqgex library instead of change each line. Since I've tested this outputted file and it does what my example does, I don't think it's necessary to add the last line. I don't think it'll be much more difficult to add the effects parser, so that's what I plan on doing this week._

## Questions

_This section took me about 6 hours because I was testing out a bunch of different ways to parse my language, but decided regex was too difficult for curly braces. I spent about an hour on this write up._

_I don't really want to hard code a ";" to the end of each line, so can you guys think of a way to add those to the file after all the lines are added. Like is there a way to edit javascript file lines after they are already added._
