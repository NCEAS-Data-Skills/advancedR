# Meeting Notes Aug. 15, 2024

## Agenda

- what are some things that stood out as important, weird, or otherwise notable from Ch. 2-4?

- review any confusing points or questions from Ch 2- 4

- review yaml and other cool code formatting tidbits from people's code

    - commit message shorthands? 

- discuss potential output products (revisit ones from first meeting, talk about any new ideas)

    - Rachel can show demo of the `glossary` extension
    
- where to put meeting notes - maybe a google doc is better?   

## Notes

### Ch 2 - 4:

- tidyverse obscures some of these background concepts

- the memory component will be important later on for potentially pre-allocating memory to speed up processes

- R's flexibility is this implied coercion under the hood, but can cause some errors; unlike python

- Question: `c(-1, -2, -3)` vs. `-c(1:3)` - maybe transparency 

:::{.concept}
- Question: lookup tables vs. join

    - use a lookup table for display name vs. taxon code when creating plots
    
    - `ggplot` to manually specify colors to go to specific groups
:::

Question: 

    - Casey: what is the definition of "permute" when we talk about "permuting columns"
    
    - Nick: just changing the order of the columns, not duplicating columns
    
- commit messages background: https://www.conventionalcommits.org/en/v1.0.0/?utm_source=pocket_mylist

- a `!` means it is a breaking change 

- types for commit messages: 

    - **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
    
    - **ci**: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
    
    - **docs**: Documentation only changes
    
    - **feat**: A new feature
     
    - **fix**: A bug fix
    
    - **perf**: A code change that improves performance
    
    - **refactor**: A code change that neither fixes a bug nor adds a feature
    
    - **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)

    - **test**: Adding missing tests or correcting existing tests
    
- incomplete type: `dev` type for commit messages


### Products

- create a glossary of key terms from each chapter? potentially use this [extension](https://github.com/andrewpbray/glossary) 

    - we can create distinct classes for different types of notes (e.g. definitions, 
    key concepts, key functions) and then create different "glossaries" for each
    type of note we want to track 
    
    - we can modify the `contributions.md` file with guidelines for how to add to
    the glossary
    
    - we could also spend some time of our group meetings deciding on key concepts and write them in the meeting notes, rather than our own individual notes, to streamline a bit. 
    
- Nick - abbreviated doc with "top 10 things" that will change your code 

    - e.g., the vector coercion order 

### Action Items:

- Next Meeting: Ch. 5 (Control Flow) & Ch. 6 (Functions - aspirational)

- make a products or potential products folder to summarize our "top 10 things" list ? each person could add to their own list as we go. (could be generated by the glossary extension or not)

- make a google doc for meeting notes? OR appoint a scribe for meeting notes and keep a md

- make a template for each chapter with the exercises 

