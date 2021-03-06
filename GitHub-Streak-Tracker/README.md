### GitHub Streak Tracker and Web Display
***

#### Objective

The goal is to development an incentive for students to be actively engaged in GitHub by creating a reader border showcasing student's current streak and sorting by longest onto a website.  

#### Things to Consider

Build a webscrapper that pulls student' GitHub users current Streak and longest streak, than displays in webpage with URL link to Students at The Tech Academy. The data will be sorted by the longest current streak and a section that will display the longest 10 streaks ever.

#### Requirements
* Webscrapper - grabs profile pic, current streak, longest streak
* Database SQLite3 and Python for programming
* Add to The Tech Academy LMS system in a web page
 * Has a list of students sorted by longest current streak
 * Has a top ten leaderboard of all time
 * Has a link to Videos on GitHub by Michael Allen (As well as templates)
 * Has a link to Philosphy of Markdown syntax
 * Will display students URL link (active), Profile Pick
* Allows students to add their own GitHub profile URL
  * Prevents them from entering extraneous URL script after profile link
  * add filter for current students versus all students versus past students (or based time elements so past students are hogging the leaderboard)
  * Saves to the database
  * Database will compare and remove duplicates
  * Will not allow students to delete
  * Will have an admin section to allow staff to add/remove students
 * Security - SQL Injection deterants in code

#### LMS integration
* Assign project members to add to LMS systme 

