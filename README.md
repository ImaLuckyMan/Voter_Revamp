# Voter Revamp 2020  <aside><img src="https://github.com/ImaLuckyMan/Voter_Revamp/blob/master/Vote2.jpg" style="width:100px; height:100px;"></aside>
My MSSA class project using ASP.NET, C#, Visual Studio, and SQL Server to revamp the way we vote. I can not change the National Election but this can be used for College, High School, and Business elections and necessity is the mother of invention, maybe it will one day influence change at a higher level.

# Concept Description:
Before we begin, I want to say that I am not here to offend anyone in any way… or sway your opinion. This can be a very controversial topic but I feel like I am not the only one that is frustrated by our current process and change needs to begin somewhere. Whether you are Republican, Democrat, Liberal, Independant, or Other, is irrelevant to this proposal as it addresses our current voting process and ways we can change it for the better.

# Index:
<a href="#1">1. Why we need a new system</a></br>
<a href="#2">2. My Proposal</a></br>
<a href="#3">3. Improvements Made to the Current System</a></br>
<a href="#4">4. How it would be Implemented</a></br>
<a href="#5">5. Recap</a></br>
<a href="#6">6. Cryptography and Encryption Methods</a></br>
<a href="#7">7. Installation </a></br>
<a href="#8">8. Usage </a></br>
<a href="#9">9. Prototype </a></br>

<h1 id="1">Why we need a new system</h1>
Our election process in the United States has been deemed corrupt, unsecure, and outdated. 
Voters are still using archaic methods, going to polling locations and filling out ballots with pen and paper or using punch cards in order to help ensure fair and secure results. States have been accused of cheating and recounts have been requested. Outside countries have been accused of messing with our voting process. I do not believe our forefathers would agree with the way we currently perform our election or the way that we choose those whom lead our country.</br>

I don’t believe we should vote for our president by how much money you have, their popularity, how well they articulate themselves, their sex, or the color of their skin. We should not vote for the candidate we hear the most about, just because they were the ones that could afford the commercials and a touring campaign.</br>

<h1 id="2">My Proposal</h1>
I propose we go back to the day where we voted for the candidate that had the most in common with the ideals most common to ourselves. I would like to create a new secure electronic voting process that would verify voter credentials so that voters could not cheat and use dead people or children’s identity in order to cast votes for their preferred candidate. A universal system that anyone needing to vote, no matter where they were located on earth, including military members serving overseas are securely verified.</br>

Most importantly, I would change the way we vote for our candidates by running a national poll prior to our election where all citizens could vote on the biggest issues affecting our country. Whether it is abortion, international trade agreements, border wall, immigration, National Debt, Medicare, etc. The top say 15 items will then make it to the candidate’s ballot. Each Presidential candidate will cast an official vote for their stand on each relevant issue. </br>

Then come the election, a blind, randomized list will be displayed that accurately shows each candidates selections without listing their names.  Just how Candidate 1 voted, How Candidate 2 voted, how Candidate 3 voted, etc. listing how they stand on Today’s most important issues. The voter can then vote on the candidate that is most in line with their own views without any “he said, she said” or fact checking distractions. </br>

After the votes are tallied and a President elected, there is a Record on File of how the Candide voted holding them responsible for their actions without them saying, Well, I never said that, and as soon as they enter office, they immediately know the things most troubling the nation. </br>

<h1 id="3">How this imporoves the current system </h1>
There are other electronic voting systems, but not one that changes the way we look at each candidate. This voting method removes prejudism from the voting process in that you do not know the name of the candidate that made which choices on global problems, the system knows, but this prevents voters from voting for a particular candidate on anything other than where they stand on the issues.</br>

<h1 id="4">Requirements to be implemented</h1>
First and formost we would have to work on voter trust in the system. Voters do not necessarily trust the current system due to curruption, and this idea does not allow a voter to see the name of a candidate, which makes it even more difficult. Impressing upon the security and record keeping of the system will help to combat this issue. This system would require a database of authorized voters with locations; a future installment may connect to the national voting database registrar, but in the mean time I will be creating a SQL database for proof of concept. Rule sets will be implemented to ensure they are legal registered voters authorized to cast and submit a vote. Security and authentication precautions and encryption have been considered and will initially just be a username and password located on a remote server. This will include polling databases that list up to date relevant issues from registered citizens that will also be created in SQL and stored in a remote location on the cloud for universal access. Backup systems will be implemented to ensure availability and prevent tampering. Input and Output engines, as well as the ability to accurately count and report submissions. Webpages will be created using ASP.NET Core MVC and hosted page editors that will connect to my SQL Server Databases and framework.</br>

<h1 id="6">Cryptography: This may be updated as I recently learned that Microsoft came out with VoterGuard this year.</h1>
Standard cryptographic techniques are used to improve security. The industry-standard public key cryptography (PKC) is used in electronic voting terminals for achieving authentication and confidentiality. Public key cryptography relies on cryptographic key pairs.</br>

A key pair for System X KX consists of private key KX and public key KX+. The private key is only known to X; whereas the public key must be made available to the other systems communicating with X. When X encrypts (signs) message m using its private key KX (m) and sends it, the receiver validates that X is the source of the encrypted message when it successfully decrypts KX (m) using the public key to retrieve the original message KX +(KX(m)) = m. When a message is encrypted using the public key KX +(m), the confidentiality is achieved as only the holder of the private key can decrypt it KX (KX +(m)) = m. Using 2048-bit RSA encryption keys provides security level sufficient for this system at the current state of the art. We also use digital signatures for authentication and to protect data integrity. A signed message is a message along with its encrypted digest m + KX (H(m)). </br>

Homomorphic Cryptography
I would probably use Paillier cryptosystem for its useful homomorphic properties in preserving the privacy of votes. Although, there are other homomorphic cryptosystems such as ElGamal and Goldwasser-Micali , Paillier is better suited for e-voting and has mature solutions for distributed key generation, threshold decryption, and zero-knowledge proofs, as detailed below. Particularly, this system allows finding the sum of encrypted votes by multiplying them. The votes and the tally remain encrypted, thus preserving the privacy of the voters: KV+(m1 + m2) = KV+(m1)  KV+(m2). </br>

For flexibility, I support the limited vote election. I allow each voter to select up to O options from C candidates. The vote of each voter Vi is encoded as a voting vector (mi,1, mi,2, …, mi,C) where mi,l = 0 or 1 for l = 1, ?, …, C and mi,l = 1 iff the voter chooses the candidate l. The voting vector is encrypted to the vector (ci,1, ci,2, …, ci,C) and the homomorphic property allows finding the encrypted tally of option l by Vi=1ci,l; where V is the number of voters. </br>

<h1 id="7">Installation</h1>
No installation is required. Site will be published via WWW. You will only require an updated web browser. </br>

<h1 id="8">Usage</h1>
Authorized registered Voters will be able to access websites allowing them to list issues affecting the Nation. The site and associated databases will order and reply with the top 15 issues for a candidate to respond with their stand on those issues. Then when a voter goes to vote they will be presented with each candidates views on each of the issues and can vote for the delegate based solely on where they stand on the isseues without knowing which candidate voted which way to prevent voter prejudism due to race, ethenticity, success, sex, religion, etiquette, political gain, charisma and social economics, etc. </br>

<h1 id="9"><a href="https://github.com/ImaLuckyMan/Voter_Revamp/tree/master/Prototype">Prototype File </a></br></h1>

# Contributions: None
# License: Located in Wiki

# Database diagram - Drafts Uploaded
# Wire-frames - Drafts Uploaded
