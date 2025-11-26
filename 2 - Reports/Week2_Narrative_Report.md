# Narrative Report — Week 2

**Date Covered:** November 10 – November 14, 2025  
**Course:** Object-Oriented Programming (OOP)  
**Project Title:** DataMedic: A Python Library for Data Cleaning


# Development Updates
This week, our team looked into starting the coding part right. The goal? Getting the diagnosis data loaded smoothly - no fiddling with file paths by hand each time. Because we’re aiming for something easy to use, we needed a way for people to just pick or drop a file instead of changing code bits themselves.

## 1. Exploring Initialization Functions
Rynzo led the search, while Jave dug into options. Their focus shifted across ways to manage picking files - like testing shortcuts or adjusting inputs
* Using built-in Python dialogs
* Looking into tools you can use to check files inside a folder
* Checking if Jupyter Notebook supports upload widgets
* Checking if the feature spots file locations on its own
Still, every method brought its own issues. A few used strange tools we’d never seen before, while some needed extra steps just to start. Quite a few guides acted like we already knew stuff we didn’t. Because it was our first go at managing files, all of it seemed confusing and heavy.

## 2. The Main Issue: Constant Path Changes
One major issue we ran into? The setup uses fixed file locations right now - so it can't adapt easily
* Each time we aim to check fresh data,
* Each time you shift the file into a new folder
* Each time someone else in the team executes the script
We’d need to open the script by hand, then update the location. That method takes too much time - plus it won’t work well once the system goes live, particularly when different people start using the tool.
Due to this restriction, we looked into a feature able to:
* Finds the file location on its own
* Let users pick a file
* Bring in data while keeping the code exactly as it is
We found a few options - though each means picking up tools we haven't used before.

#  3. Decision to Move the Task to Next Week
Looking back at what we tried, it seemed clear - more time was needed to explore how files are managed. Rather than rushing something half-baked, we chose to shift this work into next week’s plan so we could:
Check out the top way to pick files
Keep the end result straightforward yet easy to use
Few mistakes could mess up the core system
Makes sure everyone knows how to work it
This’ll make it easier to create a stronger setup down the road - using simpler parts that actually work well together.
# Screenshots

# Challenges Encountered
During this week, Rynzo and Jave tried to figure out how to start the code by searching for solutions. Rynzo thought about how to avoid constantly changing the file path to load the data we need for diagnosis. They looked for a function that would allow us to easily insert or select the file without editing anything in the code. Everyone found it challenging since it was our first time working with these functions, and everything felt new. Since we need to do more research to create a better and more efficient function, we decided to move this task to next week objectives.
