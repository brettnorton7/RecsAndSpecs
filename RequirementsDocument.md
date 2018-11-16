<h1>1. Questionnaire</h1>

<ul>a. Do you want permits to expire after the sutdent graduates?</ul>
<ul>b. Do you want some permits to serve as prerequisites for some others?</ul>
<ul>c. How will unpermitted students be prevented from accessing the machinery?</ul>
<ul>d. Which systems should our permit system be able to run on?</ul>
<ul>e. Will permits ever expire before the student graduates?</ul>
<ul>f. Can permits be revoked? By whom?</ul>
<ul>g. What are all of the student and faculty groups who will be given permits?</ul>
<ul>h. Will all permits qualify the student for the same things?? i.e. will there be a tier system governing how much access students have;    or an un-tiered, but segmented system where students are only granted access to specific relevant activities?</ul>
<ul>i. Is the software intended for use by employees on site to scan people in (like many gyms) or is the software intended for use by          students themselves?</ul>
<ul>j. By what method do entries and student permissions get added and removed from the system?</ul>
<ul>k. What input does the software take? (for example an external scanner for the student's school (or purpose-made) ID, typing in their ID    number on a keyboard, biometrics, username/password...etcetc)</ul>
<ul>l. What type of machine is the software required to run on? (regular windows/mac desktop, semi-custom all-in-one scanner and display,      android kiosk (as found elsewhere in the school), a single scanner that unlocks a door...etcetc)</ul>
<ul>m. How much of a concern is security? What type of threat model should the software defend against?</ul>
<ul>n. In what ways does the software interact with other computer systems, if at all? (credential checking as a likely example)</ul>
<ul>o. Who will create/take-away permits?</ul>
<ul>p. When will a permit be given to a student?</ul>
<ul>q. When will this system be implemented?</ul>
<ul>r. How long will the system implementation take?</ul>
<ul>s. How will the permit data be stored? The database it is stored in.</ul>
<ul>t. Who will maintain the database?</ul>
<ul>u. Is there other software required in order to properly implement this?</ul>
<ul>v. How much will this cost to implement?</ul>
<ul>w. When will the system be used?</ul>
<ul>x. How many permits can be given out?</ul>


<h1>2. Textual Description of the software</h1>

<ul>Our software will be a Permit to Work system that tracks a user’s permissions for using machinery.</ul>
<ul>A system administrator will be able to oversee and modify these permissions.</ul>
<ul>Authorized users will be able to access permissions to govern the process of giving out physical keys to students to allow them to use machines.</ul>
<ul>Students will be able to get these permissions by watching relevant instructional materials.</ul>


<h1>3. User Stories</h1>

<ul>a. As a system administrator, I can oversee, change, add, and remove permissions so that unauthorized students will not be able to use machines for which they are not qualified.</ul>
<ul>b. As an authorized user, I can see student permissions so that I can give out physical keys only to students who are qualified to use a particular machine.</ul>
<ul>c. As a student, I can acquire permissions to prove to the authorized users that I am qualified to use a particular machine.</ul>

<h1>4. Basic UML File </h1>
<img src="https://raw.githubusercontent.com/OU-CS3203-fall2018/permittowork-back-row/master/Basic%20UML.PNG?token=AcmX5f87XtlbSKDFui5bBm-F_1HCpg7Kks5b94CIwA%3D%3D" alt="Basic UML Diagram">

<h1>5. UML Sequence Diagram</h1>
<img src="https://raw.githubusercontent.com/OU-CS3203-fall2018/permittowork-back-row/master/Basic%20Sequence%20Diagram-1.png?token=AePQv9Kwy5AU1HyPfMmxJ297w6yY5Rxqks5b93JDwA%3D%3D" alt="Sequence diagram">

<h1>6. UI Design Prototype</h1>
<img src="https://raw.githubusercontent.com/OU-CS3203-fall2018/permittowork-back-row/master/Web%201920%20%E2%80%93%201.png?token=AcmX5W1d9sFZJZYprMQy-Ru4Kf9WNk0Aks5b93YcwA%3D%3D" alt="Mock UI 1">
<img src="https://raw.githubusercontent.com/OU-CS3203-fall2018/permittowork-back-row/master/Web%201920%20%E2%80%93%202.png?token=AcmX5YMAnQpl9tPOD1pcfuChNk41aiEVks5b93ZDwA%3D%3D" alt="Mock UI 2">
<img src="https://raw.githubusercontent.com/OU-CS3203-fall2018/permittowork-back-row/master/Web%201920%20%E2%80%93%203.png?token=AcmX5d0__lPPjDlFj2mKndaqcyXy76hMks5b93ZpwA%3D%3D" alt="Mock UI 3">


<h1>7. Nonfunctional Requirements</h1>
<ul>a. The software must interface with card scanners</ul>
<ul>b. The software must delete user permissions on graduation</ul>
<ul>c. The software must be quick enough to allow user permissions to be managed without major interruptions to workflow</ul>
