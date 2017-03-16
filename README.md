# book_trading
A FreeCodeCamp challenge creating a Book Trading Club application using Google book API, Node.js, Express.js, Passport.js, JQuery and Embedded Javascript (EJS).

#Working Application
https://agile-plains-41064.herokuapp.com

#Objective:
Build a full stack JavaScript app that is functionally similar to this: http://bookjump.herokuapp.com/ and deploy it to Heroku.

	1.	Note that for each project, you should create a new GitHub repository and a new Heroku project. If you can't remember how to do this, revisit https://freecodecamp.com/challenges/get-set-for-our-dynamic-web-application-projects.
  
	2.	Here are the specific user stories you should implement for this project.
  
	3.	User Story: I can view all books posted by every user.
  
	4.	User Story: I can add a new book.
  
	5.	User Story: I can update my settings to store my full name, city, and state.
  
	6.	User Story: I can propose a trade and wait for the other user to accept the trade.

#Challanges:
I'm still getting familiar with embedded javascript which is a HTML templating language. I was challanged again with AJAX and rendering the page after I send data to be used. My work around was to use the form to send the data straight to the route I was looking for. 
I had trouble thinking about how to load the page to display the data. I decided to use the "window.location.href" and "window.location.reload();". 
I find the right mongodb syntax is still a challange so I will continue to work with mongodb so that I can become more familiar.
I attempted to use socket.io to get more familiar with that library but discovered a bug in the process. I soon realized that socket.io didnt really apply to this application. Unless I wanted to create some kind of realtime addition. 
