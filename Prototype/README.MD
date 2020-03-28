# Revamp the Vote

## Table of Contents

- [1. Inspiration](#inspiration)
- [2. Concept](#concept)
- [3. Implementation](#implementation)
- [4. Entity Relationship Diagram (ERD)](#entity-relationship-diagram)
- [5. User Stories](#user-stories)
- [6. Use Cases](#use-cases)
- [7. Use Case Diagram](#use-case-diagram)
- [8. Requirements](#requirements)
- [9. Wire-Frames (DRAFT)](#wire-frames)
- [10. Requirements Table](#requirements-table)
- [11. Tests Table](#tests-table)
- [12. Feature List](#feature-list)
- [13. Prototype](#prototype)

## INSPIRATION
[(back to top)](#table-of-contents)

This is something that I thought of a long time ago. You see I have always been told, when you first meet someone, 
never talk about Religion or Politics. Yet, before every election, I would take the time to research each candidate and 
find out where they stand on important issues such as health care, abortion, national security, trade, etc. Then I would 
have discussions with my friends and family, and there is always someone who wants to debate. 

Why did you vote for that person? I have simply been floored by some of the responses when female friends of mine stated 
that they vote for whom they think looks most presidential. Male and female friends have said they voted for Hiliary Clinton
 and Sarah Palin, because they wanted to be the first to vote in a female President. Now it shouldn't matter whom you decide
to vote for, whether you are Republican, Democrat, Liberal, or Indifferent, I am not here to sway you views one way or another.
I just believe that the voting process in this country has strayed from what it use to be. I picture a time when 
people would travel from far cities and towns on horse drawn carriages to meet in large rooms and vote on whom they felt was the most
qualified to represent them by their proven leadership, charactor, and where they stood on issues affecting the cities, towns, and 
thier peers. I picture candidates presenting their ideas as to what they believed should be done to solve national issues and committees
agreeing or disagreeing and casting their votes. 

Now, when ever I turn on the TV before or after an election, no matter what channel I turn to, there seems to always be a news station
 or political campaign commercial with an add degrading either the current President or one of a candidates opposition. During the 
National debates, candidates are often cutting down other candidates plans rather than explaining their own. I have traveled to over
27 countries and 36 US states and our elections have been seen to many as a joke overseas. With all the slander on TV talking about
a Seated President or outside countries interfearing with the US elections. Our election system is archaiac and outdated. Many locations
still submit there vote over paper ballot becasue they feel that it is more secure. Many locations have to open and volunteers are called on
to support voting polls that cost money to run, not to mention vandalism and fights that have been known to break out at these locations
increasing the need for added security. So how do we fix it? We can't just change the system, it would be unconstitutional. But change needs to begin somewhere. Maybe a school, college, or business can use this program for their
election processes and one day maybe it will inspire change on a larger scale.

## CONCEPT
[(back to top)](#table-of-contents)

What would it take to remove the prejudism and hate out of the electoral process? Establish a voting system where eligible patrons would know
where a politican or candidate stood on the most pressing issues affecting our country right from the candidate and not their constituaries, 
a vote that would not be based on sex, religion, color, success, or chrisma of a candidate, but solely on where they stood on the issues? A voting 
system that could be accessed from anywhere in the world to accomidate for our military and civilian members volunteering overseas. A secure system
that could be trusted and verifyable?  

I propose that we create a secure website that any eligible voter can log into using their voting credential. This is a government issued unique number just as their SSN that is currently being used. 
They can use their voting credential to log into the website and view all the issues currently affecting our country. Then they can include their opinion as to what they feel is a top priority. 
Again, this is tied to their credential, so they can go back and change their opinion as time goes on prior to the vote, but their opinion only counts once. That 
way issues are presented by the people. Prior to election, candidates will go to their site and a database of all the world issues will pull the top most voted on and present those results to each candidate. 
Each candidate will receive the same questions. The candidate will then provide answeres to where he/she stands on each issue. The results of the candidates ballot will be stored in a secure database. Come time to vote, everyone that is a legal, authorized, registered,
voter will be able to log in from anywhere in the world to the secure online electronic voting site using their registered credential just as if you were casting
an out of state ballot. Each voter will be presented with the candidates answers so that they can make an educated decision as to whom they feel are most inline with
their own beliefs. **The difference is the answer sheet WILL NOT DISPLAY the candidates name, only the answers. Therefore, you do not know if the candidate most in line with you is male or female, black or white, rich or poor, etc... just where they stand. Because it is documented on the ballot, whom ever gets elected cannot deny 
they ever said Yes or No to a particular topic. After the votes have been submitted, the system will be able to provide reports that voters can use to look up their vote by their voter id number and verify 
that their vote counted. The system will monitor the ip address and geo location of where a vote was placed to deter curruption and will be able to identify through AI when 
something isn't quite right similar to how your credit card company or bank identifies purchases that are out of the ordinary.  


## IMPLEMENTATION
[(back to top)](#table-of-contents)

To accomplish this task, a few databases would have to be maintained:

 - List of Authorized Voters
 - IP and Geo Location Tracking
 - Voter Ballot for the chosen candidate
 - Candidate Ballot opinion on world issues
 - World Issues database on everything affecting the country
 - Results for archeiving

## ENTITY RELATIONSHIP DIAGRAM
[Preliminary Database](https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Prototype/Prototype_Documents/)

![Voter ERD](https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Prototype/Prototype_Documents/VoterERD.png)

## USER STORIES
[(back to top)](#table-of-contents)

<h2> 1) As a Legal Registered Voter over the age of 18 <h2>
I need/want A secure voting system that frees me from the political backlash and media jargon of candidates lying 
and trying to stab each other in the back in order to win enough votes to possibly be elected for means other than 
the best interests of the people they represent. I require a secure system that is free from outside influence where 
I can place my vote from anywhere and know it will be counted. I need a system that is accurate, counts votes quickly, 
frees up volunteers and funding. I want a system that is modern and encrypted and prevents other voters from choosing 
a candidate by their sex, race, success, charisma, skin color, or any other prejudice, and simply vote for the candidate 
whose political views are most in line with their own. So that voters such as myself can feel safe and secure that my vote 
will be counted and that I will be safe from oppression. So that I do not have to listen to political campaigns backstabbing 
each other in the media. So that the hate will stop between voters for their views on their chosen candidates.

<h2> 2) As a Candidate </h2>
I need/want a system that is secure and accurate, that can be trusted and prevent recount. 
I need a system with near real time results. 
I need a system that voters can access from anywhere including our military members stationed overseas. 
So that accurate results are received in a timely manner and allow for the most votes to be submitted with world-wide secure availability.


## USE CASES
[(back to top)](#table-of-contents)

Given an online electronic voting system and database of current world issues and a registry of legal authorized voters When user Registers to Vote Then the users credentials are stored securely and remotely
Given an online electronic voting system, a database of current world issues, and a registry of legal authorized voters When Registered Candidates log in Then the candidate is sent to their own form that lists the top 15 most relevant issues affecting the country where they can give their opinion.

Given an online electronic voting system, a database of current world issues, and a registry of legal authorized voters When Votes have been submitted Then the votes are tallied securely and results are provided in near real time.

Given an online electronic voting system, a database of current world issues, and a registry of legal authorized voters When Authorized Voters are deployed overseas Then they can still access the system and submit their vote.

Given an online electronic voting system, a database of current world issues, and a registry of legal authorized voters When a voter goes to submit their vote Then are presented with each candidates views on top 15 political issues affecting the country, without knowing which candidate submitted which set of views.

## USE CASE DIAGRAM
[(back to top)](#table-of-contents)

![Use Case Diagram](https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Prototype/Prototype_Documents/UseCaseDiagram.png)

## REQUIREMENTS
[(back to top)](#table-of-contents)

* 1.0\. User visits National Issues Website

	* 1.1\. System shows current status of National Issues

		* 1.1.1\. User decides they wish to add to the current list of issues

		* 1.1.2\. User is asked by the system to login or register if they are not currently registered

		* 1.1.3\. The system checks whether or not the user is authorized to login

		* 1.1.4\. If the user is authorized the system will allow them to submit their opinion connected to their ID

		* 1.1.5\. System will update database of issues with updated information and keep tally
	
		* 1.1.6\. System returns user to status page and allows the user to log out 

* 2.0\. User needs to regiester

	* 2.1\. User is directed to appropriate registration page

		* 2.1.1\. The software asks user if they are a voter or candidate and directs them to the appropriate page to register
		* 2.1.1\. System updates the database with registration information

* 3.0\. Candidates Opinion

	* 3.1\. When a candidate registers they will have availability to provide their opinion on the top national issues in the National Issue Database

		* 2.1.1\. Candidate will be able to update their opinion up to the day before the election associated with their voter id

* 4.0\. Vote

	* 4.1\. On the day of election users will be able to login voter page

		* 4.1.1\. The software will verify the user is authorized voter by checking registration for Voter ID

		* 4.1.2\. If authorized, the system will allow voter access and will provide voter with voter form and candidates answers to national issues without candidates name

		* 4.1.3\. The system will track how each user votes connected to their voter ID so that the voter can verify their submission
		
		* 4.1.4\. The system will track users IP address and Geo location for security of the vote to track multiple votes using same ID and different locations

		* 4.1.5\. The system will tally the votes and provide live results to map


* 6.0 \. The Administrator will have access to the database 

	* 6.1\. System will log all changes in order to ensure administration actions are done ethically

* 7.9 \. Security
	* 7.1\. System will eventually use Microsoft Election Guard or implement Secure ID, Fingerprint, Smart Card, and/or Encryption
	
	* 7.1.1\. System will ensure users browsers are up to date with latest patches and meets software requirements
	
	* 7.1.2\. System will automatically close browser once user logs off


## WIRE FRAMES
[(back to top)](#table-of-contents)
![Wire Frame Diagram](https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Prototype/Prototype_Documents/)

The Landing Page would be a login Screen with the Grab & Go Logo and a tab to be able to sign up:
![National Issues Page](https://www.iwannavote.net)

After selecting the "Sign Up' Tab, the user can enter their information where it can be validated and submitted for account creation:
![Sign Up Screen](https://github.com/cjpleasant88/Grab-Go/blob/master/Assets/Sign%20Up%20Screen.png)

One logged in, the user can create a shopping list in an arbitrary order. This list can be shared with other users such as a family member or spouse:
![Candidate Registration](https://github.com/cjpleasant88/Grab-Go/blob/master/Assets/Shopping%20List.png)

Once the "Let's go shopping" being has been clicked, the app will take the users list of items and reorder them in a way that creates the "fastest path" through the store. A map view can also be shown identifying the location of the items in the store with a bird's eye view of the store:
![Candidate opinion without name](https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Prototype/Prototype_Documents/Voter%20View%20Candata%20Answers%20Wire%20Diagram.png)

## REQUIREMENTS TABLE
[(back to top)](#table-of-contents)

| Requirement  ID | Requirement Description                                      | Test Method   | TEST ID      |
| --------------- | ------------------------------------------------------------ | ------------- | ------------ |
| 1.0.0           | User Shall Input Grocery  Items into personal List by selecting items from a pre-populated list | Demonstration | TC005        |
| 1.1.0           | System Shall show user  categories of items or all items for user to select from | Inspection    | TC005        |
| 1.1.1           | The software shall  maintain the relationship of items and their parent category | Inspection    | TC006        |
| 1.1.2           | The software shall allow  searching an filtering of users typed values with values in the stored list  of grocery items | Demonstration | TC006        |
| 2.0.0           | User Shall view their list  in an ordered manner             | Demonstration | TC007        |
| 2.1.0           | The System shall compare  user list with specific store layout to generate an ordered list | Test          | TC007        |
| 2.1.1           | The software shall  display the users list in the newly ordered format | Demonstration | TC007        |
| 3.0.0           | User shall select a map  view of the were their items are in the store | Test          | TC008        |
| 3.1.0           | The system shall map the  location of users items onto a known store map | Test          | TC008        |
| 4.0.0           | User shall be able to  create an account                     | Demonstration | TC001        |
| 4.1.0           | The system shall store a  users username and password for sign in purposes | Inspection    | TC001        |
| 4.1.1           | The software shall  validate the email is in a valid email format | Test          | TC001, TC003 |
| 4.1.2           | The software shall ensure  that the username is not already in the system database | Demonstration | TC001, TC003 |
| 4.1.3           | The system shall alert  the user if validation fails and gives reason why validation failed | Demonstration | TC001        |
| 4.1.4           | The system will generate  a new Shopping list record and associate the Shopping List ID with the user  account | Inspection    | TC002        |
| 4.2.0           | The system shall link a  user account with a grocery list that the user creates | Inspection    | TC002        |
| 5.0.0           | User shall be able to share  their list with another user    | Demonstration | TC003, TC004 |
| 5.1.0           | The system will ensure that  another user exists             | Test          | TC003, TC004 |
| 5.1.1           | The software will compare  requested username with list of created accounts | Demonstration | TC003        |
| 5.1.2           | The software will notify  original user of the requested user does not exists and halt shopping list  linking | Test          | TC003        |
| 5.2.0           | The system will prompt  requested user upon next login that they have been selected to share list | Demonstration | TC004        |
| 5.3.0           | The system will link list  upon requested users acceptance   | Test          | TC004        |
| 5.3.1           | The software will drop  the requested users shopping list table from the database | Inspection    | TC004        |
| 5.3.2           | The software will add the  Shopping List ID of the original user to the requested users account to  compete the linking process | Inspection    | TC004        |
| 6.0.0           | The Administrator shall  add new grocery items to the Master Grocery List | Inspection    | TC009        |
| 6.1.0           | The system shall display a  form to the administrator for all required information of a grocery item | Demonstration | TC009        |
| 6.1.1           | The Software shall run  script(s) to take form data and create a new record of the item in the Master  Grocery List Table | Inspection    | TC009        |
| 7.0.0           | The Administrator shall be  able to add a new Store and Layout to the System | Inspection    | TC010        |
| 7.1.0           | The System shall display a  form to the administrator for all required information of a Store entity | Demonstration | TC010        |
| 7.1.1           | The software shall run  script(s) to take form data and create a new record of the item in the Store  Table | Inspection    | TC010        |

## TESTS TABLE
[(back to top)](#table-of-contents)

| Test ID | Requirement ID(s)                        | Test Procedure                                               | Current Status | Time Stamp | Version |
| ------- | ---------------------------------------- | ------------------------------------------------------------ | -------------- | ---------- | ------- |
| TC001   | 4.0.0, 4.1.0, 4.1.1, 4.1.2, 4.1.3        | User login w/o having logged in before, taken to signup screen to create  account. Sign out and login with new signup information. | Not Tested     | 3/8/2020   | N/A     |
| TC002   | 4.1.4, 4.2.0                             | Check system database for list id of a new account creation  | Not Tested     | 3/8/2020   | N/A     |
| TC003   | 5.0.0, 5.1.0, 5.1.1, 5.1.2, 4.1.2, 4.1.1 | Add new user, click share list, select user that does not already exist | Not Tested     | 3/8/2020   | N/A     |
| TC004   | 5.0.0, 5.1.1, 5.2.0, 5.3.0, 5.3.1, 5.3.2 | using user from TC003, click share list, select user from TC001, login to  user from TC001 and verify shared list prompt, click approve | Not Tested     | 3/8/2020   | N/A     |
| TC005   | 1.0.0, 1.1.0                             | Add bread, milk, eggs to an existing users list              | Not Tested     | 3/8/2020   | N/A     |
| TC006   | 1.1.1, 1.1.2                             | Have administrator look at SQL data base and verify that report can be  pulled by category, and that the list in the application id the same items | Not Tested     | 3/8/2020   | N/A     |
| TC007   | 2.0.0, 2.1.0, 2.1.1                      | Logged in user can select "Let's go Shopping" and see their  list in an ordered format according to store layout | Not Tested     | 3/8/2020   | N/A     |
| TC008   | 3.0.0, 3.1.0                             | User can select "map View" and see their items on store map,  matching their physical location in the store | Not Tested     | 3/8/2020   | N/A     |
| TC009   | 6.0.0, 6.1.0, 6.1.1                      | Administrator adds a new item to database, adds a non-existing item,  verifies that is shows up in the application | Not Tested     | 3/8/2020   | N/A     |
| TC010   | 7.0.0, 7.1.0, 7.1.1                      | Administrator add a new store and layout to the database, verifies that  store and layout populate in the application | Not Tested     | 3/8/2020   | N/A     |

## Feature List
[(back to top)](#table-of-contents)

Additional features that would be welcomed would be:

 - Ability to scan bar codes of items and add to list
 - Have different Store maps/information to choose from
 - Integration of Available coupons
 - Recipe Integration
 - Home Pantry Inventory
 
 ## Prototype
 [(back to top)](#table-of-contents)
 
 Details and Demonstration of the prototype can be found here:
 
 [Grab & Go Prototype](https://github.com/cjpleasant88/Grab-Go/tree/master/docs)
