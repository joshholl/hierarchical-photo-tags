Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

# Hierarchical Photo Tags
A hierarchical tag list for photographs predominately designed for FOSS image editors. This is effectively a controlled vocabulary to help organize photos and reason about their contents textually. The tags should be great hashtags for sharing an image on social media or using as alt text on a web page(provided enough care is given to ensure proper handling with screen readers).

At its top level each category will be broken down into the [6W's](https://en.wikipedia.org/wiki/Five_Ws). Obviously we wont categorize the why, thats the story we're trying to tell with the photographs

# Conventions

1. Files will be named in the format `rootlevel_subcategory.txt`
2. All nesting will be denoted with tab characters
3. A Top level tag should be All uppercase and preceded with a tilde and wrapped with square braces. e.g. `[~WHAT]`
4. A child level tag that _should_ not be exported should wrapped in square braces and preceded with a tilde e.g. `[~Animal]
5. Any tag should be all lower case (unless it is a proper noun) and preferably in its singular form
6. Any synonym should be nested 1 level deeper than the primary tag, and enclose in curly braces
7. Prefer to use the most descriptive, longer from term possible, but use the other forms as synonyms 
8. If a term is nested and its parent is exported (not in the form of `[~TERM]`) then the parent term must also apply. For example a panda bear is a bear so you would nest panda bear under bear and not the other way around because every bear is not a panda bear
9. If the a parent term could be used but is excessively generic, omit it.

# Categories
1. Who: A properly named person or pet.
2. What: The descriptive subject of what you're shooting, the style (landscape etc will be in "HOW")
   1. Animals
   2. Plants - in cases where the plant bears something edible, the edible part should go under Food
   3. Structures
   4. Concept: A top level generic holder for a societal construct
   5. Food
   6. Drink
3. When: Either time of day or the type of event
   1. 
4. Where: A properly named location such as a country, city, region, etc. Think of some place you would travel to.
5. How: how you made the shot, the photographic style used etc
    

# How you can help.
I am a white cis gendered male from the United States as such most tags are biased towards the
subjects and places that I have encountered thus far in my life. Pull request and feedback are welcome.