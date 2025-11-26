# Narrative Report — Week 2

**Date Covered:** November 10 – November 14, 2025  
**Course:** Object-Oriented Programming (OOP)  
**Project Title:** DataMedic: A Python Library for Data Cleaning


# Development Updates
This week, our team looked into starting the coding part right. The goal? Getting the diagnosis data loaded smoothly - no fiddling with file paths by hand each time. Because we’re aiming for something easy to use, we needed a way for people to just pick or drop a file instead of changing code bits themselves.

## 1. Exploring Initialization Functions
Rynzo led the search while Jave explored different options. Their work focused on figuring out how the system could let users select files without manually changing the code. They tried several approaches—like using built-in Python dialogs, checking whether Jupyter Notebook supports upload widgets, and exploring tools that can automatically detect files in a folder or identify file locations on their own.

Each method introduced new complications. Some required unfamiliar tools, others demanded additional setup steps, and many online guides assumed we already knew concepts we hadn’t learned yet. Since it was our first attempt at handling file-management functions, the entire process felt overwhelming and confusing.

## 2. The Main Issue: Constant Path Changes
A major problem we discovered was that the current setup uses fixed file paths. This means the code cannot adjust automatically whenever the dataset changes location. Every time we want to test new data, move the file to a different folder, or let another group member run the script on their own device, we are forced to open the code and manually update the file path.

This approach is inefficient and would cause issues once the system is used by multiple people. Because of this limitation, we began searching for a method that could automatically detect file paths, allow users to select a file easily, and load the data without requiring any changes in the actual script. Although we found potential solutions, each one involved tools or functions that were new to us, which means we still need more time to learn how they work.

##3. Decision to Move the Task to Next Week
After reviewing our progress, we realized that we needed more time to understand how file-handling should be implemented properly. Instead of rushing a solution that might break later, we decided to move this task to next week’s objectives. This will give us the opportunity to study the most effective way to allow file selection, keep the process simple and user-friendly, reduce the chances of errors affecting the main system, and ensure that all group members know how to use the function correctly.

By postponing this task, we can create a stronger and more stable setup that will integrate smoothly with the rest of the project once we fully understand the tools involved.
# Screenshots

# Challenges Encountered
During this week, Rynzo and Jave tried to figure out how to start the code by searching for solutions. Rynzo thought about how to avoid constantly changing the file path to load the data we need for diagnosis. They looked for a function that would allow us to easily insert or select the file without editing anything in the code. Everyone found it challenging since it was our first time working with these functions, and everything felt new. Since we need to do more research to create a better and more efficient function, we decided to move this task to next week objectives.
