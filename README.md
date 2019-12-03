# CSCI-3308-Team-Meeting-Logs


---
## 11/13/2019 - Team Meeting
#### What we've done: 
- Massive updatess to front end. The info page now works properly and can be dynamically populated (hard-coded, right now). There is also login/sign-in/my account buttons on the page that will eventually be linked to each corrosponding page. Re-did with PUG instead of HTML 
- Continued work on SQL databases. Determined that we need 2 databases, one with URL's and userID's, and one with usernames and passwords. These are currently working on being hosted on Heroku 
- Discussions and problem-solving related to hosting our site, implementation of exactly how we're going to get it to work and how the call's are going to pass data back and forth upon being hosted on Heroku
- Project Milestone 5 complete 

#### What we still need to do:
- Host our services on Heroku, figure out how to API call with them and link them to our pages
- Figure out how to properly connect all different moving pieces of this. 
- Figure out how to properly make SQL queries using API calls, and pass the data from the login/signup forms into the two aforementioned databases.  
- Build a "My Account" page that will display the user's previously-queired URL's in a table
- Tie up any loose ends in terms of edge cases, testing, scripting (this will be after once we've connected all our working pieces) 
- Project Milestones 6, 7
---
## 11/13/2019 - Team Meeting
#### What we've done: 
- Continued work on updating SQL databases, populated them with data (decided to go with version 12) 
- Discussed logitics with Heroku (and how exactly we might get all of the peices talking to each other with API calls?) 
- Created a working front-end for the results page. Loading animation, page populates with the correct number of "results" boxes to display results. AJ is working on getting the JSON file and the front-end to talk to each other so we can start to get it working with actual data 

#### What we still need to do: 
- Figure out exactly how we can use Heroku to update our app and to get all of the python script, login/info/start pages talking to the SQL databases and web/application servers. We are likely going to go into office hours this week to meet with an instructor/TA about this. 

---
## 11/13/2019 - Team Meeting
#### What we've done: 
- Continued scoping and planning on the specifics of our app - narrowing the gap bettween unknowns and knowns. This includes planning for Heroku, planning for a loading page  (or rather, a loading animation to play while the script is running) 
    -- This will basically just be a loading gif that spins on the results page until the Python finshes running, API gets called, and javascript/jquery is 
- Dicussion of how Heroku will get all of these components to talk to each other 
- Use NodeJH to Call bash script to run python. Using Heroku. 
- Version 12 of PostGres for database setup? Seems like the best 
- Using Heroku with Node JS to make an API call: 


**Front end site takes in input -> calls API with URL calls -> loading page -> JavaScript** 

### What we still need to do:
**Jake**
 * Create loading animation/page for back-end
 * Populate back-end with data from dummy json file (based on real input) 
 * Fix front-end to handle multiple URL calls
 
**Fengyuan** 
 * Create a local database for data 
 * Make some filler/dummy data (user's data) 

**Andrew**
 * Help with PieChart for Javascript 
 * Continue working on Python script 
 
**Yuxi** 
 * Work with Fengyuan's database to populate login page 
 
**AJ**
 * Figuring out Heroku, database management (calling that from the database) 
 
**Other stuff** 
 * Possible integration with Python instead of NodeJS. 

--- 

## 10/30/2019 - Team Meeting

#### What we've done: 
- Basic HTML parser (parses div/header tags, etc.) (Andrew)
- Basic front-end website page (allows for URL text-entry) (Jake)
- Scope of the SQL Database (used for storing login info, previous websites searched, and (maybe) documents of downloaded files)

#### What we still need to do:
- **IMPORTANT UPDATE -** We've decided that, because of the way that parsing metadata about images/text/css can be tricky on public-facing sites, we are going to take in multiple websites and compare similarities, almost like a plagirism checker!

- Continue to work on script
- Create a front-end page for the basic design of the website (Jake)
- Set up a basic SQL database to store username/password info 
- Create a login modal on the homepage

#### Other ways to make this more interesting: 
- Include how many times a pages has been searched
- Include how often pages are being searched 

--- 

## 10/18/2019 -  Team Meeting 

#### What we've done: 
- Completed Project Milestone #2 Documentation
- Created a Project board.

#### What we still need to do:
- Figure out the detailed implementation of the features.
- Began First Sprint

--- 

## 10/16/2019 - Team Meeting  

#### What we've done: 
-Declared the 6 features our project wil have and outlined funtional and none functional features

#### What we still need to do:
- Created a project board to outline the dates which we will have certain features completed.
- Overview that our formatting is inline with the requirments.

--- 

## 9/25/2019 - Initial Team Meeting  

#### What we've done: 
- Worked over ideas for project and completed milestone #1 document.

#### What we still need to do:
- Figure out the detailed implementation of the features.
