# Prototype of Voter Revamp 2020  <aside><img src="https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Vote2.jpg" style="width:100px; height:100px;"></aside>
My MSSA class project using ASP.NET, C#, Visual Studio, and SQL Server to revamp the way we vote. I can not change the National Election but this can be used for College, High School, and Business elections and necessity is the mother of invention, maybe it will one day influence change at a higher level.

# Concept Description:
Before we begin, I want to say that I am not here to offend anyone in any way… or sway your opinion. This can be a very controversial topic but I feel like I am not the only one that is frustrated by our current process and change needs to begin somewhere. Whether you are Republican, Democrat, Liberal, Independant, or Other, is irrelevant to this proposal as it addresses our current voting process and ways we can change it for the better.

Electronic voting provides accuracy and efficiency to the electoral processes. World democracies would benefit from a secure e-voting system not only to improve voter participation and trust but also to prevent electoral fraud. However, current e-voting systems are complex and have security weaknesses. In this paper, I describe a secure e-voting system for national and local elections to include college and highschool presidential elections or anyone that requires a secure, fair, voting process free from prejudism and voter fraud. No longer will people be able to choose their candidates by race, sex, money, charisma, or skin color. This system satisfies the important requirements of an e-voting system through state-of-the-art technologies and secure processes. I-Vote is a way to Re-Vamp the voting process in 2020. It will eventually rely on homomorphic cryptography, zero-knowledge proofs, biometrics, smartcards, open-source software, and secure computers for securely and efficiently implementing the system processes over the various stages of the electoral process, without relying on kiosks, volunteers, or geographic polling stations. I outline the main conclusions of the pilot implementations of I-Vote and tested the main technologies and processes used. We also explain how the used technologies and processes achieve the system requirement. In conclusion, I recommend adopting I-Vote ReVamp 2020 for its security, flexibility, economic, and scalability features; but most importantly because it provides a vote based on a candidates political views and not on a candidates, race, color, sex, nationality, charisma, or success.

# Scope: Brief summary description of the domain and top-level user requirements for your product

# Requirements:
A. User Level Requirements
1. Non-Discriminatory: The principle of non-discrimination seeks “to guarantee that human rights are exercised without discrimination of any kind based on race, colour, sex, language, religion, political or other opinion, national or social origin, property, birth or other status such as disability, age, marital and family status, sexual orientation and gender identity, health status, place of residence, economic and social situation”.

2. World-Wide Availability: So that registered authorized voters overseas can accurately and securely submit their vote.

3. Accuracy: The i-vote system does not allow altering or deleting a validated vote and
does not count any ineligible vote in the final tally.

4. Democracy: It allows only eligible voters to vote and allows every voter to vote only
once.

5. Privacy: It does not disclose the votes of the respective voters and does not allow any
voter to prove how he/she voted. This is a fundamental requirement to avoid voter intimidation and vote selling.

6. Verifiability: It allows anyone to verify that all votes were correctly counted. And in
case of electoral disputes, it provides means for rechecking the results.

7. Security: It always satisfies the accuracy, democracy, and privacy requirements and
does not allow inside or outside attackers to undermine these requirements. Additionally, it satisfies reliability, availability, and data integrity requirements.

8. Acceptance: It is accepted by voters and candidates who believe that the system is fair
and they trust its results. This requirement depends on all above requirements.

9. Flexibility: It can carry out various types of elections for parliaments, municipalities,
student boards, plebiscites, referendums, etc. Flexibility provides economic advantage
when the same system is used to conduct multiple electoral processes in a certain country or city. A necessary aspect of the flexibility, which is needed for democracy, is the universality in allowing any eligible voter to vote irrespective of her native language, special needs, or literacy level. One more important aspect is the mobility in allowing the voter to vote in any voting center that is most convenient to her.

10. Cost effectiveness: It uses economic software and hardware components. This requirement is particularly important for large-scale elections.

11. Scalability: It efficiently enables carrying out various sizes of elections. The election
size can be small (up to few hundred voters, e.g., electing the speaker of a parliament),
medium (thousands of voters, e.g., electing the city board), or large (millions of voters,
e.g., general parliamentary elections). When the system is used in various election sizes, it achieves flexibility, provides better return on investment, and facilitates productizing it in mass quantities.

B. System Requirements 

C. Software Requirements


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
