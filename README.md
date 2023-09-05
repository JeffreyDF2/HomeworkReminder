# HomeworkReminder
And project that web-scrapes my schools website for upcoming assignments and text or emails users about weekly and daily summaries of what is due.
It uses a database to store user names and contact information, and it stores assignments, the class it is for, the semester it is for, and it's duedate.
This project currently isn't working (due to changes in the login process) though I have plans in the future to update it and make it accessable to students on campus.

This current version of the project is currently only compatible with my computer.
In order to run this program on your own computer you would need to host a SQL sever and run the script in the project. You would then need to change the connection lines in both the texting and web-scraper programs to connect to your own server. 

I needed a way for my python file to execute the web-scraper program, and I was able to do this my publishing it to some folder, finding the executable, then editing the line in my python code to the path to the correct one for your pc. It is line 86 in the python file.

Limitations-
-It can only detect classes in this format: W23 Database Management Systems (CPTR-319-A)
Where it starts with the semester letter and year then the title and section in parenthesis 
-It will not get classes of the same course that have the same name
-Using your number to receive texts will more then likely give you a cut off message
-Cannot account for bad input
-Only works on my computer
