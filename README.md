<h1>SQL Murder Mystery</h1>

<h2>Description</h2>
This is a walkthrough of my thought process while doing the SQL Murder Mystery challenge. The challenge aims to teach users the basics of how to navigate and filter for information on an SQL server. Going into this challenge I knew the basics of SQL already.

Link to the challenge: [SQL Murder Mystery](https://mystery.knightlab.com/)

<h2>Table of contents:</h2>

[What you're given](#what-you're-given)

[Walk-through](#walk-through)

<h2>What you're given:</h2>
<b>Description of the murder:</b>

![SQL description](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/0b4af637-b5af-44fc-89cb-2603c4b29ca6)
  - Key info:
    - Crime = murder
    - Date = Jan.15, 2018
    - Place = SQL City

<b>Schema Diagram of Police Department's SQL Database:</b>

![Schema diagram](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/c5898701-c456-4edb-b51f-6002b5f2dd0a)

<h2>Walk-through:</h2>
<b>Key information that I identify will be highlighted in yellow in the image.</b>

1. Using information from the description I retrieved the correct crime scene report:

![crime scene report highlight](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/b27ccbdb-6477-4c94-a672-394534bad332)

2. Looked up the name of the first witness:

![First witness](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/e47f0d10-1a00-4871-83d8-d08877faca57)
![First witness name](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/ecac401a-13db-4d00-bda9-12a74dcf0f3c)

3. Using the name I looked up Morty Shapiro's witness transcript:

![first witness transcript](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/4c32a1c7-02f7-4bb9-b962-0cdc0ab508c3)

4. Looked up the name of the second witness:

![second witness name](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/1b9f4e77-de03-4291-9269-830b6cc3b18a)

5. Using the name I looked up Annabel Miller's witness transcript:

![Second witness transcript](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/e0c5666a-9283-4b74-8ea1-93a1d23726dd)

6. Using witness testimonies I looked up people with membership id starting with 48Z and checked in to the gym on January 9th:

![person_id](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/322e8ad6-6b1b-4e7d-94f6-51c7be8ad08b)

7. Using the membership_id given I look up their names:

![membership id](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/1aae4d84-915e-456b-8f56-786cced6b327)

8. Using their names I looked up their license id:

![license_id](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/13927953-2bd4-4c01-a4b2-324f52ba2ef8)

9. Using the license_id I looked up their plate numbers:

![license_id](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/4d0497e4-5e27-4d1d-9ee9-f8a7306ca610)

<b>The first witness said that the license plate included H42W. The license plate of Jeremy Bowers matches this, so it has to be him!!!</b>

<b>Part 2</b>

1. Using the person_id found in previous queries I look up Jeremy Bowers’s interview transcript:

![murderer testimony](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/864c1faa-c866-4dcd-9cb8-585eb9b5eba5)

2. Using the description in the transcript I look up al the people that might match:

![4 ids](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/2f66239c-a4d6-4159-b932-87d0f12271fc)

3. Using the ids I look up people that match in the person database:

![4 names](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/a1b155be-9751-4f23-a648-f93ed508e4c3)

4. Using the id I find out which one of them has been at the SQL Symphony Concert 3 times in December 2017:

![concert 3 times](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/1512d159-b60c-428b-97fa-fad129d5e6c4)

5. From this query it shows that Miranda Priestly is behind the murder:

![Found hirer](https://github.com/ntieu4328/SQL-Murder-Mystery/assets/156137990/991d8dec-af6a-4877-a770-f13a0771d5f9)

<b>The SQL Murder Mystery has been solved!!!</b>
