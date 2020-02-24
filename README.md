# Voter_Revamp
My MSSA class project using ASP.NET, C#, Visual Studio, and SQL Server to revamp the way we vote. I can not change the National Election but this can be used for College, High School, and Business elections and necessity is the mother of invention, maybe it will one day influence change at a higher level.

Concept Description:
Before we begin, I want to say that I am not here to offend anyone in any way… or sway your opinion. This can be a very controversial topic but I feel like I am not the only one that is frustrated by our current process and change needs to begin somewhere. Whether you are Republican, Democrat, is irrelevant to this proposal as it addresses our current voting process and ways we can change it for the better.

Agenda:
Why we need a new system
My proposal
Improvements made to current systems
How it would be implemented
Recap
Questions

Our election process in the United States has been deemed corrupt, unsecure, and outdated. 
Voters are still using archaic methods, going to polling locations and filling out ballots with pen and paper or using punch cards in order to help ensure fair and secure results. 
States have been accused of cheating and recounts have been requested. 
Outside countries have been accused of messing with our voting process. 
I do not believe our forefathers would agree with the way we currently perform our election or the way that we choose those whom lead our country.

I don’t believe we should vote for our president by how much money you have, their popularity, how well they articulate themselves, their sex, or the color of their skin. We should not vote for the candidate we hear the most about, just because they were the ones that could afford the commercials and a touring campaign.

Instead, I propose we go back to the day where we voted for the candidate that had the most in common with the ideals most common to ourselves. I would like to create a new secure electronic voting process that would verify voter credentials so that voters could not cheat and use dead people or children’s identity in order to cast votes for their preferred candidate. A universal system that anyone needing to vote, no matter where they were located on earth, including military members serving overseas are securely verified. 

Most importantly, I would change the way we vote for our candidates by running a national poll prior to our election where all citizens could vote on the biggest issues affecting our country. Whether it is abortion, international trade agreements, border wall, immigration, National Debt, Medicare, etc. The top say 15 items will then make it to the candidate’s ballot. Each Presidential candidate will cast an official vote for their stand on each relevant issue.

Then come the election, a blind, randomized list will be displayed that accurately shows each candidates selections without listing their names.  Just how Candidate 1 voted, How Candidate 2 voted, how Candidate 3 voted, etc. listing how they stand on Today’s most important issues. The voter can then vote on the candidate that is most in line with their own views without any “he said, she said” or fact checking distractions.

After the votes are tallied and a President elected, there is a Record on File of how the Candide voted holding them responsible for their actions without them saying, Well, I never said that, and as soon as they enter office, they immediately know the things most troubling the nation. 

There are other electronic voting systems, but not one that changes the way we look at each candidate.

This would require a database of authorized voters with locations and rule sets to ensure they are registered. Security and authentication precautions, polling databases that list up to date relevant issues, backup systems to ensure availability and prevent tampering, Input and Output engines, as well as the ability to accurately count and report submissions. 

Cryptography
Standard cryptographic techniques are used to improve security. The industry-standard public key cryptography (PKC) is used in electronic voting terminals for achieving authentication and confidentiality. Public key cryptography relies on cryptographic key pairs.

A key pair for System X KX consists of private key KX and public key KX+. The private key is only known to X; whereas the public key must be made available to the other systems communicating with X. When X encrypts (signs) message m using its private key KX (m) and sends it, the receiver validates that X is the source of the encrypted message when it successfully decrypts KX (m) using the public key to retrieve the original message KX +(KX(m)) = m. When a message is encrypted using the public key KX +(m), the confidentiality is achieved as only the holder of the private key can decrypt it KX (KX +(m)) = m. Using 2048-bit RSA encryption keys provides security level sufficient for this system at the current state of the art.
We also use digital signatures for authentication and to protect data integrity. A signed message is a message along with its encrypted digest m + KX (H(m)). 

Homomorphic Cryptography
We use Paillier cryptosystem for its useful homomorphic properties in preserving
the privacy of votes. Although, there are other homomorphic cryptosystems such as
ElGamal and Goldwasser-Micali , Paillier is better suited for e-voting and has mature
solutions for distributed key generation, threshold decryption, and zero-knowledge
proofs, as detailed below. Particularly, this system allows finding the sum of encrypted
votes by multiplying them. The votes and the tally remain encrypted, thus preserving the
privacy of the voters: KV+(m1 + m2) = KV+(m1)  KV+(m2).

For flexibility, we support the limited vote election. We allow each voter to select
up to O options from C candidates. The vote of each voter Vi is encoded as a voting
vector (mi,1, mi,2, …, mi,C) where mi,l = 0 or 1 for l = 1, ?, …, C and mi,l = 1 iff the voter
chooses the candidate l. The voting vector is encrypted to the vector (ci,1, ci,2, …, ci,C) and
the homomorphic property allows finding the encrypted tally of option l by Vi=1ci,l; where
V is the number of voters.


