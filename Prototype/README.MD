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
Again, this is tied to their credential, so they can go back and change their opinion as time goes on prior to the vote, but their opinion only counts once. That way issues are presented by the people. Prior to election, candidates will go to their site and a database of all the world issues will pull the top most voted on and present those results to each candidate. 
Each candidate will receive the same questions. The candidate will then provide answeres to where he/she stands on each issue. The results of the candidates ballot will be stored in a secure database. Come time to vote, everyone that is a legal, authorized, registered, voter will be able to log in from anywhere in the world to the secure online electronic voting site using their registered credential just as if you were casting an out of state ballot. Each voter will be presented with the candidates answers so that they can make an educated decision as to whom they feel are most inline with their own beliefs. 
**The difference is the answer sheet WILL NOT DISPLAY the candidates name, only the answers. Therefore, you do not know if the candidate most in line with you is male or female, black or white, rich or poor, etc... just where they stand. 

Because it is documented on the ballot, whom ever gets elected cannot deny they ever said Yes or No to a particular topic. After the votes have been submitted, the system will be able to provide reports that voters can use to look up their vote by their voter id number and verify that their vote counted. The system will monitor the ip address and geo location of where a vote was placed to deter curruption and will be able to identify through AI when something isn't quite right similar to how your credit card company or bank identifies purchases that are out of the ordinary.  

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

		* 3.1.1\. Candidate will be able to update their opinion up to the day before the election associated with their voter id

* 4.0\. Vote

	* 4.1\. On the day of election users will be able to login voter page

		* 4.1.1\. The software will verify the user is authorized voter by checking registration for Voter ID

		* 4.1.2\. If authorized, the system will allow voter access and will provide voter with voter form and candidates answers to national issues without candidates name

		* 4.1.3\. The system will track how each user votes connected to their voter ID so that the voter can verify their submission
		
		* 4.1.4\. The system will track users IP address and Geo location for security of the vote to track multiple votes using same ID and different locations

		* 4.1.5\. The system will tally the votes and provide live results to map


* 5.0 \. The Administrator will have access to the database 

	* 5.1\. System will log all changes in order to ensure administration actions are done ethically

* 6.0 \. Security
	* 6.1\. System will eventually use Microsoft Election Guard or implement Secure ID, Fingerprint, Smart Card, and/or Encryption
	
	* 6.1.1\. System will ensure users browsers are up to date with latest patches and meets software requirements
	
	* 6.1.2\. System will automatically close browser once user logs off


## WIRE FRAMES
[(back to top)](#table-of-contents)
![Wire Frame Diagram](https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Prototype/Prototype_Documents/)

The Landing Page would be a login Screen or redirect to register so that they can loging:
![National Issues Page](https://www.iwannavote.net)

When registering, the user can enter their information which will be stored in the authorized voter database:
![Voter Registration](https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Prototype/Prototype_Documents/Voter%20Registration%20Wire%20Diagram.png)

One logged in, the user will see a list of the National Issues listed by other authorized voters and will have the option to provide
their own opinion because everyones opinion counts tied to their voter id.
![National Issues](https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Prototype/Prototype_Documents/National%20Issues%20Wire%20Diagram.png)

When a candidate registers to vote, they will have the option to list thier opinion on each presented issue. They can update their opinion until it is time to vote tied to their voter id.
![Candidate registration](https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Prototype/Prototype_Documents/Candidate%20Registration%20Wire%20Diagram.PNG)

Come election day, each authorized voter will login to the voter website
![Voter Website](https://www.ivote.online)

Each voter will be presented with each candidates answers to the National Issues so they can make an educated decision without listing the candidates name
![Voter Ballot](https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Prototype/Prototype_Documents/Voter%20View%20Candata%20Answers%20Wire%20Diagram.png)

## REQUIREMENTS TABLE
[(back to top)](#table-of-contents)

| Requirement  ID | Requirement Description                                      			| Test Method   | TEST ID      |
| --------------- | ------------------------------------------------------------------------------------| ------------- | ------------ |
| 1.0.0           | User visits National Issues Website				 			| Demonstration | TC005        |
| 1.1.0           | System shows current status of National Issues 					| Inspection    | TC005        |
| 1.1.1           | User decides they wish to add to the current list of issues 			| Inspection    | TC006        |
| 1.1.2           | User is asked by the system to login or register if they are not currently registered | Demonstration | TC006        |
| 2.0.0           | User needs to regiester						             	| Demonstration | TC007        |
| 2.1.0           | User is directed to appropriate registration page 					| Test          | TC007        |
| 2.1.1           | The software asks user if they are a voter or candidate and directs them to the appropriate page to register | Demonstration | TC007        |
| 2.1.2           | System updates the database with registration information 				|Demonstration	| TC007        |

| 3.0.0           | Candidates Opinion 									| Test          | TC008        |
| 3.1.0           | Availability to provide their opinion on the top national issues 			| Test          | TC008        |
| 3.1.1		  | Candidate update their opinion til the day before election  with their voter id	| Test		| TC008	       |

| 4.0.0           | Vote							                        | Demonstration | TC001        |
| 4.1.0           | The software verifies the user is authorized by checking registration for Voter ID  | Inspection    | TC001        |
| 4.1.1           | If authorized, access will provide voter with voter form and candidates answers to national issues without candidates name | Test          | TC001, TC003 |
| 4.1.2           | The system will track each user votes with their voter ID so the voter can verify their submission | Demonstration | TC001, TC003 |
| 4.1.3           | The system will tally the votes and provide live results to map		        | Demonstration | TC001        |

| 5.0.0           | The Administrator will have access to the database 				        | Demonstration | TC003, TC004 |
| 5.1.0           | System will log all changes in order to ensure administration actions are ethical   | Test          | TC003, TC004 |

| 6.0.0           | Security									        | Inspection    | TC009        |
| 6.1.0           | System will eventually use Microsoft Election Guard or implement Secure ID, Fingerprint, Smart Card, and/or Encryption | Demonstration | TC009        |
| 6.1.1           | System will ensure users browsers are up to date with latest patches and meets software requirements | Inspection    | TC009        |
| 6.1.2		| System will automatically close browser once user logs off				| Inspection | TC009|


## TESTS TABLE
(https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Prototype/Prototype_Documents/Test%20Case%20Table%201.JPG)
[(back to top)](#table-of-contents)


## Feature List
[(back to top)](#table-of-contents)

Additional features that would be welcomed would be:

 - Encryption
 - Fingerprint Reader
 - Smart Cards
 - Printed Reports
 - Additional Verification
 
 ## Prototype
 [(back to top)](#table-of-contents)
 
 Details and Demonstration of the prototype can be found here:
 
 [Revamp the Vote Prototype](https://www.ivote.online)
