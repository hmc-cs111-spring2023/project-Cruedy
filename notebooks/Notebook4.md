# Design notebook entry

## Last week's critique

_Since I wrote a lot of my parser last week, I wanted to check in with my critique group to see if I was writing my parser correctly. I just felt unsure about the way I wrote my parser because it written in such a way where it just searched for a specific string and spit out another string as an output. My critiquer recommended that I use the regex group function to parse the code so that it's less hard coded. I think I'm going to take that advice for parsing the individual elements like shapes and effects._
_After looking into my code, I decided to just parse it without regular expressions because I'm not grouping elements by "(", and I already have the input code split up by line._

## Description

_I was able to translate every element attribute into extendscipt code and create default values for each attribute. Since I decided to use the names of colors for my DSL, I have to figure out how to translate them to the rgb values. The example I'm using is the color red, which is simply just (1, 0, 0), but I need to make sure it works for more complex values. To do this I imported colors from the matplotlib library. The to_rgba() function gave me the rgba values, and I just removed the last element from the outputted list. I also had to some manipulation to the list to make it the correct format.

## Questions

**What is the most pressing issue for your project? What design decision do
you need to make, what implementation issue are you trying to solve, or how
are you evaluating your design and implementation?**

**What questions do you have for your critique partners? How can they best help
you?**

**How much time did you spend on the project this week? If you're working in a
team, how did you share the work?**

**Compared to what you wrote in your contract about what you want to get out of this
project, how did this week go?**
