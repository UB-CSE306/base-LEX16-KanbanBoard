# LEX16
This lab exercise is fairly open ended - it asks you to write some code together with your regular CSE306 teammates, demonstrating how you collaborate with the using the Kanban board system used in CSE442 Software Engineering and the department's experiential learning courses.

## Main task
Before you begin this lab, READ all the instructions in this form!

The main goal of this lab exercise is for you and your teammates to develop a proficiency in using the Kanban board as a way to facilitate teamwork, and provide proof of having engaged in teamwork productively using the Kanban board.  You must work collaboratively via the issues on your Kanban board and GitHub, assigning the various tasks to different people on your team, ensuring that everyone on the team has at least two tasks assigned to them (if you need to come up with fairly small tasks to come up with two per team member that's OK - small tasks are actually good!)

You and your teammates have to write a C program that accepts a date (in YYYY-MM-DD format) and prints the week number  and the dates for the days of the week containing that date.  See: https://www.timeanddate.com/date/week-numbers.html and https://en.wikipedia.org/wiki/ISO_8601 for more details.

Make sure you create a suitable makefile.

The executable produced by ```make week``` mut be called ```week```.  The invocation ```week 2020-03-27``` must produce the following output (with Monday as the first day of a week):

```Week Mo Tu We Th Fr Sa Su```  
```# 13 23 24 25 26 27 28 29```

## Preparation
Make sure all members of your team have set up their account on [the system hosting the Kanban boards](https://webdev.cse.buffalo.edu/pmtool), and that all members of your team attend lab in person.  Your course student assistant will demo the system during lab and explain how we expect you to use it in CSE306.  If you have trouble with this consult with a TA during your regular lab time.

## Process
In addition to using the Kanban board and adding issues for the various tasks needed to complete this exercise, suitably assigned to individual team members and moved from one pipeline to the next until complete, make sure you employ good practices: TDD using Criterion, git branching, code coverage with transparent testing, etc.  If there are bugs in your code, document them with Criterion tests as well.

## Finishing up
Make sure you remember to **add/commit/push to your repo on GitHub** - if you don't we can't grade your work!

**NOTE - EXTENDED TIME:** Because this is a teamwork LEX you will have until 11:59 PM on Monday evening to complete your work.
