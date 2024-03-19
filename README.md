# SpaceInvaders
The following repository contains code samples that contain either of the following "invisible" characters:
- Mongolian Vowel Separator (U+180E)
- Zero Width Space (U+200B)
along with comments on what the code does (spoiler: in most cases it doesn't work)
The results fall into 3 broad categories
1. The code fails to compile
2. The character is treated as an invisible space,
3. The character is treated as part of the identifier

## Treated as a Space
where the character is treated as a space, it is therefore possible to have code that looks like one thing, but compiles and behaves as something else

## Treated as part of the identifier
Where the character is treated as part of the identified, it is therefor possible to create confusion by having multiple identifiers that look identical, but are in fact different.