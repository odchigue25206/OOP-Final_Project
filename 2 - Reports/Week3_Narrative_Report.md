# Narrative Report — Week 2

**Date Covered:** November 17 – November 21, 2025  
**Course:** Object-Oriented Programming (OOP)  
**Project Title:** DataMedic: A Python Library for Data Cleaning

# Development Updates

## 1. Implementing the DataGetter Class
In Week 2, it became clear that fixed file paths caused problems; therefore, the focus shifted in Week 3 toward creating a more flexible method for accessing data files. Rather than relying on outdated approaches,
We created the DataGetter class with Python’s pathlib module this setup uses a single main directory but allows inputting any filename during execution.
This setup fetches file data automatically eliminating repeated adjustments to complex directory paths. Unlike the previous version, it reduces frustration while promoting clearer, better-organized file handling.

## 2. Testing the Read Function
We ran checks on the read_file() function with various text plus CSV examples to see if it worked right.
These trials looked at whether the tool opens files from the main folder,
spots when a file isn't there,gives clear warnings, or shows data correctly.
Findings showed the DataGetter class manages correct files well while catching issues for missing ones, making our software more dependable.

## 3. Error Handling Improvements
This week, we spent time improving how errors are handled inside the DataGetter class.
Instead of generic alerts, now it shows clear warnings like “File not found” or “Unexpected error,”
which helps when checking for mistakes in paths or naming. Because of these tweaks, spotting problems got simpler, plus troubleshooting became faster for everyone involved.

# Screenshoot
![WEEK 3](https://github.com/user-attachments/assets/e74ac4ca-9736-4104-962e-b22f8ce65f7c)
![3c17b047-7241-4245-8a34-e1e39cd0dae5 (1)](https://github.com/user-attachments/assets/03c5c6bf-d7b7-4081-a220-b6009bdbc791)



# Challenges Encountered
Some issues included having to set the base path by hand; also,
the program would crash if someone typed an incorrect filename. Folder layouts varied between team members while certain file types weren't well supported either.
Even so, Week 3 showed progress compared to Week 2 our class is now working properly and structured better for handling files methodically.
