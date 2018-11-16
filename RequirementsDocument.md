1. Questionnaire

Do you want permits to expire after the sutdent graduates?
Do you want some permits to serve as prerequisites for some others?
How will unpermitted students be prevented from accessing the machinery?
Which systems should our permit system be able to run on?
Will permits ever expire before the student graduates?
Can permits be revoked? By whom?
What are all of the student and faculty groups who will be given permits?
Will all permits qualify the student for the same things?? i.e. will there be a tier system governing how much access students have; or an un-tiered, but segmented system where students are only granted access to specific relevant activities?
Is the software intended for use by employees on site to scan people in (like many gyms) or is the software intended for use by students themselves?
By what method do entries and student permissions get added and removed from the system?
What input does the software take? (for example an external scanner for the student's school (or purpose-made) ID, typing in their ID number on a keyboard, biometrics, username/password...etcetc)
What type of machine is the software required to run on? (regular windows/mac desktop, semi-custom all-in-one scanner and display, android kiosk (as found elsewhere in the school), a single scanner that unlocks a door...etcetc)
How much of a concern is security? What type of threat model should the software defend against?
In what ways does the software interact with other computer systems, if at all? (credential checking as a likely example)
Who will create/take-away permits?
When will a permit be given to a student?
When will this system be implemented?
How long will the system implementation take?
How will the permit data be stored? The database it is stored in.
Who will maintain the database?
Is there other software required in order to properly implement this?
How much will this cost to implement?
When will the system be used?
How many permits can be given out?


2. Textual Description of the software

Our software will be a Permit to Work system that tracks a user’s permissions for using machinery. 
A system administrator will be able to oversee and modify these permissions. 
Authorized users will be able to access permissions to govern the process of giving out physical keys to students to allow them to use machines. 
Students will be able to get these permissions by watching relevant instructional materials. 


3. User Stories

a. As a system administrator, I can oversee, change, add, and remove permissions so that unauthorized students will not be able to use machines for which they are not qualified. 
  b. As an authorized user, I can see student permissions so that I can give out physical keys only to students who are qualified to use a particular machine. 
  c. As a student, I can acquire permissions to prove to the authorized users that I am qualified to use a particular machine. 
  

4. 


5. See UML Sequence Diagram


6. See attached UI Design Prototype


7. Nonfunctional Requirements

  a. The software must interface with card scanners
  b. The software must delete user permissions on graduation
  c. The software must be quick enough to allow user permissions to be managed without major interruptions to workflow
