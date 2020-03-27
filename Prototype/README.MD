# Prototype of Voter Revamp 2020  <aside><img src="https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Vote2.jpg" style="width:100px; height:100px;"></aside>
My MSSA class project using ASP.NET, C#, Visual Studio, and SQL Server to revamp the way we vote. I can not change the National Election but this can be used for College, High School, and Business elections and necessity is the mother of invention, maybe it will one day influence change at a higher level.

# Concept Description:
Before we begin, I want to say that I am not here to offend anyone in any way… or sway your opinion. This can be a very controversial topic but I feel like I am not the only one that is frustrated by our current process and change needs to begin somewhere. Whether you are Republican, Democrat, Liberal, Independant, or Other, is irrelevant to this proposal as it addresses our current voting process and ways we can change it for the better.

Electronic voting provides accuracy and efficiency to the electoral processes. World democracies would benefit from a secure e-voting system not only to improve voter participation and trust but also to prevent electoral fraud. However, current e-voting systems are complex and have security weaknesses. In this paper, I describe a secure e-voting system for national and local elections to include college and highschool presidential elections or anyone that requires a secure, fair, voting process free from prejudism and voter fraud. No longer will people be able to choose their candidates by race, sex, money, charisma, or skin color. This system satisfies the important requirements of an e-voting system through state-of-the-art technologies and secure processes. I-Vote is a way to Re-Vamp the voting process in 2020. It will eventually rely on homomorphic cryptography, zero-knowledge proofs, biometrics, smartcards, open-source software, and secure computers for securely and efficiently implementing the system processes over the various stages of the electoral process, without relying on kiosks, volunteers, or geographic polling stations. I outline the main conclusions of the pilot implementations of I-Vote and tested the main technologies and processes used. We also explain how the used technologies and processes achieve the system requirement. In conclusion, I recommend adopting I-Vote ReVamp 2020 for its security, flexibility, economic, and scalability features; but most importantly because it provides a vote based on a candidates political views and not on a candidates, race, color, sex, nationality, charisma, or success.

# Index:
<a href="#I">I. Scope</a></br>
<a href="#II">II. Requirements</a></br>
<a href="#II.A">II.A User Requirements</a></br>
<a href="#II.B">II.B System Requirements</a></br>
<a href="#II.C">II.C Software Requirements</a></br>
<a href="#III">III. Solution Design</a></br>
<a href="#3.a">3.a User Stories</a></br>
<a href="#3.a.1">3.a.1 Legal Registered Voter Stories</a></br>
<a href="#3.a.2">3.a.2 Candidate Stories</a></br>
<a href="#3.b">3.b Use Cases</a></br>
<a href="#4">4. Data Design</a></br>
<a href="#5">5. UI Design</a></br>
<a href="#6">6. Project Plan</a></br>
<a href="#7">7. Project Demo </a></br>
<a href="#8">8. Recent Accomplishments </a></br>
<a href="#9">9. Design Changes </a></br>
<a href="#10">10. Next Steps </a></br>
<a href="#11">11. Test Report </a></br>
<a href="#12">12. Prototype </a></br>

# Project Files:

<a href="https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Wire%20Frame%20Layout%20Drafts.pdf">2. WireFrame Diagrams</a></br>
<a href="https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Flow%20Chart%20Draft.pdf">3. Flow Chart</a></br>
<a href="https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Use%20Case%20Diagram.pdf">4. Use Case</a></br>
<a href="https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Candidate%20Registration.JPG">5. Candidate Registration</a></br>
<a href="https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Voter%20Registration%20Form.JPG">6. Voter Registrations</a></br>
<a href="https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Example%20Ballot.pptx?raw=true">7. Ballot </a></br>
<a href="https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Test%20Case%20Table%201.JPG">8. Test Case </a></br>
<a href="http://www.iwannavote.net">9. Issues Site </a></br>
<a href="http://www.ivote.online">10. Voter Site </a></br>

<h1 id="I"> I. Scope: Brief summary description of the domain and top-level user requirements for your product </h1>
Our election process in the United States has been deemed corrupt, unsecure, and outdated. Voters are still using archaic methods, going to polling locations and filling out ballots with pen and paper or using punch cards in order to help ensure fair and secure results. States have been accused of cheating and recounts have been requested. Outside countries have been accused of messing with our voting process. I do not believe our forefathers would agree with the way we currently perform our election or the way that we choose those whom lead our country.I don’t believe we should vote for our president by how much money you have, their popularity, how well they articulate themselves, their sex, or the color of their skin. We should not vote for the candidate we hear the most about, just because they were the ones that could afford the commercials and a touring campaign.Instead, I propose we go back to the day where we voted for the candidate that had the most in common with the ideals most common to ourselves. I would like to create a new secure electronic voting process that would verify voter credentials so that voters could not cheat and use dead people or children’s identity in order to cast votes for their preferred candidate. A universal system that anyone needing to vote, no matter where they were located on earth, including military members serving overseas are securely verified. Most importantly, I would change the way we vote for our candidates by running a national poll prior to our election where all citizens could vote on the biggest issues affecting our country. Whether it is abortion, international trade agreements, border wall, immigration, National Debt, Medicare, etc. The top say 15 items will then make it to the candidate’s ballot. Each Presidential candidate will cast an official vote for their stand on each relevant issue. After the votes are tallied and a President elected, there is a Record on File of how the Candide voted holding them responsible for their actions without them saying, Well, I never said that, and as soon as they enter office, they immediately know the things most troubling the nation. There are other electronic voting systems, but not one that changes the way we look at each candidate.

<h1 id="II"> II. Requirements: </h1>
<h2 id="II.A"> II.A User Level Requirements </h2>
<h3> 1. Non-Discriminatory: </h3>
The principle of non-discrimination seeks “to guarantee that human rights are exercised without discrimination of any kind based on race, colour, sex, language, religion, political or other opinion, national or social origin, property, birth or other status such as disability, age, marital and family status, sexual orientation and gender identity, health status, place of residence, economic and social situation”.

<h3> 2. World-Wide Availability:</h3>
So that registered authorized voters overseas can accurately and securely submit their vote.

<h3> 3. Accuracy: </h3>
The i-vote system does not allow altering or deleting a validated vote and
does not count any ineligible vote in the final tally.

<h3> 4. Democracy: </h3>
It allows only eligible voters to vote and allows every voter to vote only
once.

<h3> 5. Privacy: </h3>
It does not disclose the votes of the respective voters and does not allow any
voter to prove how he/she voted. This is a fundamental requirement to avoid voter intimidation and vote selling.

<h3> 6. Verifiability: </h3>
It allows anyone to verify that all votes were correctly counted. And in
case of electoral disputes, it provides means for rechecking the results.

<h3> 7. Security: </h3>
It always satisfies the accuracy, democracy, and privacy requirements and
does not allow inside or outside attackers to undermine these requirements. Additionally, it satisfies reliability, availability, and data integrity requirements.

<h3> 8. Acceptance: </h3>
It is accepted by voters and candidates who believe that the system is fair
and they trust its results. This requirement depends on all above requirements.

<h3> 9. Flexibility: </h3>
It can carry out various types of elections for parliaments, municipalities,
student boards, plebiscites, referendums, etc. Flexibility provides economic advantage
when the same system is used to conduct multiple electoral processes in a certain country or city. A necessary aspect of the flexibility, which is needed for democracy, is the universality in allowing any eligible voter to vote irrespective of her native language, special needs, or literacy level. One more important aspect is the mobility in allowing the voter to vote in any voting center that is most convenient to her.

<h3> 10. Cost effectiveness: </h3>
It uses economic software and hardware components. This requirement is particularly important for large-scale elections.

<h3> 11. Scalability: </h3>
It efficiently enables carrying out various sizes of elections. The election
size can be small (up to few hundred voters, e.g., electing the speaker of a parliament),
medium (thousands of voters, e.g., electing the city board), or large (millions of voters,
e.g., general parliamentary elections). When the system is used in various election sizes, it achieves flexibility, provides better return on investment, and facilitates productizing it in mass quantities.

<h2 id="II.B">II.B. System Requirements</h2>
This would require a database of authorized voters with locations and rule sets to ensure they are registered. Security and authentication precautions, polling databases that list up to date relevant issues, backup systems to ensure availability and prevent tampering, Input and Output engines, as well as the ability to accurately count and report submissions. 

<h2 id="II.C">II.C. Software Requirements </h2>
Smartphone, terminal, pc, tablet, or any device that can access the world wide web over Secure-HTTP via a Browser running the latest patches and security updates. </br>
<a href="https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/srs.doc?raw=true">1. Software Requirements Specifications Document Link </a></br>

# Solution Design: User Stories and Use Cases
1.  User Stories
As a Legal Registered Voter over the age of 18
I need/want 
A secure voting system that frees me from the political backlash and media jargon of candidates lying and trying to stab each other in the back in order to win enough votes to possibly be elected for means other than the best interests of the people they represent. I require a secure system that is free from outside influence where I can place my vote from anywhere and know it will be counted. I need a system that is accurate, counts votes quickly, frees up volunteers and funding.  I want a system that is modern and encrypted and prevents other voters from choosing a candidate by their sex, race, success, charisma, skin color, or any other prejudice, and simply vote for the candidate whose political views are most in line with their own.
So that voters such as myself can feel safe and secure that my vote will be counted and that I will be safe from oppression. 
So that I do not have to listen to political campaigns backstabbing each other in the media.
So that the hate will stop between voters for their views on their chosen candidates.

As a Candidate
I need/want a system that is secure and accurate, that can be trusted and prevent recount. I need a system with near real time results. I need a system that voters can access from anywhere including our military members stationed overseas.
So that accurate results are received in a timely manner and allow for the most votes to be submitted with world-wide secure availability.

2. Use Cases
Given an online electronic voting system and database of current world issues and a registry of legal authorized voters 
When user Registers to Vote
Then the users credentials are stored securely and remotely

Given an online electronic voting system, a database of current world issues, and a registry of legal authorized voters 
When Registered Candidates log in
Then the candidate is sent to their own form that lists the top 15 most relevant issues affecting the country where they can give their opinion.

Given an online electronic voting system, a database of current world issues, and a registry of legal authorized voters 
When Votes have been submitted
Then the votes are tallied securely and results are provided in near real time.

Given an online electronic voting system, a database of current world issues, and a registry of legal authorized voters 
When Authorized Voters are deployed overseas
Then they can still access the system and submit their vote.

Given an online electronic voting system, a database of current world issues, and a registry of legal authorized voters 
When a voter goes to submit their vote
Then are presented with each candidates views on top 15 political issues affecting the country, without knowing which candidate submitted which set of views.

# Data Design: Database design including the entities, attributes, relationships & data types may be ERD, may be class diagram

# UI Design: Wireframe details

# Project Plan	Product Backlog Items (PBIs) and component design. 
# Indicate which items are Complete, Work-in-Progress (WIP), Not Started, Backlog

# Project Demo:	Screen Shots

# Recent accomplishments: 

# Design changes:

# Next steps:

# Test Report:	Requirements Traceability Matrix (RTM) Every requirement should map to a planned test

Accuracy: I-Vote Revamp uses secure servers and validated voter list. The votes cast cannot be altered or deleted without detection. They are exported from the website to the central register. The site runs over secure encryption and the votes will be transferred in signed packages. Any alteration or deletion during this transfer is detected by the central register. Missing packages are detected as the central register keeps the list of used id's, IP addresses, location, and voting receipts are published. In case some ineligible votes are present in these packages, the central register does not count them because it only counts the votes of the voters listed in the final voter list and pass validity and authenticity checks.

Democracy: Eligible voters’ authentication is securely carried out using voter registration and future additions shall include fingerpring and/or smartcard. Only the real owner of the smartcard ID can cast their vote. This identity check is automated without the need for human involvement. Only the votes of the eligible voters are counted by the central register. Any voter can only vote once
because the database stores the ballot type ID preventing the voter from voting again. Even when this voter ID is somehow reused, the central register only counts one vote for each voter in the final tally. Multiple votes from the same voter are detected by the central register and published.

Privacy: I-Vote uses encrypted ballots that cannot be decrypted by a single party. The homomorphic property of Paillier cryptosystem is used to tally the ballots without decrypting them. Only the final tally is decrypted through a distributed threshold decryption scheme that involves multiple parties. The voting receipt cannot be decoded to retrieve the vote because this receipt is simply an encrypted digest of the encrypted ballot.

Verifiability: I-Vote publishes the encrypted ballots, voting receipts, and uses a paper trail. Anyone can download the eligible ballots from the publishing server and verify the announced tally. Any voter can verify that their vote has reached the final tally through searching for her voting receipts among the published receipts by their ID. The paper trail of ballots deposited in the ballot boxes can be used to verify the electronic results. However, some of these ballots are ineligible for several reasons and are not counted by the central register. For example, a ballot is ineligible when it comes from an ineligible voter. These ballots can be discarded in a physical ballot count when the kiosk gives each ballot a random unique number and when the central register exports the list of ineligible ballots. This physical ballot counting can be sped through using man and machine readable ballots. Paper trails also provide the system with redundancy, thereby making it more robust.

Security: The features mentioned above allow the system to securely achieve the accuracy, democracy, and privacy requirements. The use of open source software provides superior secure, reliable, and robust voting software. Software problems and vulnerabilities are detected and solved faster. And the use of secure offline computers for the sensitive system components eliminates all electronic attacks on these components and enhances availability. Moreover, the hardware locks and seals prevent many physical attacks and allow detection of these attacks when committed.

Data exchange among the system components is also secure. Receivers always verify the authenticity and integrity of received data as the exchanged data is digitally signed using hashing and PKC. Furthermore, stored data is secured through replication, digests, and backup as described in the previous sections.

Acceptance: The constituency and candidates are likely to accept the system that achieves the above five requirements. This acceptance is enhanced through providing them with the system’s source code and allowing them to check it for any vulnerabilities.

Another method to enhance acceptance is using the I-voting system in conducting less critical elections or opinion polls before using it in critical, nation-wide elections. Such elections might be directed at selecting most important historical figures or best sites to visit. Another good bulwark against constituency resistance to the new system is providing them with the feel of the old system, namely, paper ballots. Although adding a paper trail endures additional costs, it is essential to gain acceptance at the early stages of the
system adoption and maintain needed verifiability.

Flexibility: A major flexibility feature in S-Vote is a result of using flexible XML descriptions for the ballots. The central register software allows designing any ballot.

The voting kiosks import and use the designed ballot forms that are included in the kiosk voting kit. I-Vote supports multiple election types including single vote, limited vote, and approval vote. As the smartcard holds the voter’s precinct ID, the kiosk offers the voter the correct ballot according to her precinct. However, when the same system is used in multiple electoral processes, the kiosk cannot rely on one precinct ID. The voter precinct overrides described in Section 4 can specify the ballot that the voter should fill irrespective of the voting precinct. When the national e-voting system is used in electoral processes that include noncitizens, special expatriate smartcard IDs should be distributed.

As all data needed in a vote casting is available online. I-Vote allows any authorized voter to vote from anywhere in the world. There is no need to force the voter to appear in a specific voting center that might be far or overcrowded.

I-Vote supports universality through allowing ballots in multiple languages, catering for voters with special needs, and accommodating illiterate people. Illiterates are presented special graphical directions showing candidates’ photos or symbols and supported by audio instructions through headphones.

Cost effectiveness: Licensing costs are reduced by using free software and operating systems. S-Vote uses commodity and cheap technologies. For example, it uses fingerprint readers instead of iris scanners for the cost advantage of the former.

Scalability: S-Vote achieves scalability through using a building block (voting kiosk) that can be deployed in various numbers. The major challenge is to provide enough voting kiosks that allow all voters to cast their votes within the limited election period. We estimate that one voting kiosk can serve from 500 to 1,000 voters in a day. This through put can only be achieved through clear and streamlined kiosk user interface. Depending on the electorate size, the election committee has to provide a suitable number of voting
kiosks distributed over voting centers. Aggregating results of a large election in the central register can be sped up through electronically transferring the ballots exported from the kiosks. There is no need to physically deliver the removable storage containing the ballots package exported from the kiosk because the ballots are encrypted and this package is signed. The large computing load of verifying vote validity and authenticity in large countries is manageable and should be handled through parallel processing.
