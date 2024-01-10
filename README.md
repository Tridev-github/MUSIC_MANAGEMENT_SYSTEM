# MUSIC_MANAGEMENT_SYSTEM
TABLE OF CONTENTS
ABSTRACT.............................................................................................................. 3ACKNOWLEDGMENT......................................................................................... 31. INTRODUCTION................................................................................................41.1 MOTIVATION........................................................................................41.2 AIM..........................................................................................................41.3 OBJECTIVE.................................................................................................... 41.4 REPORT ORGANIZATION...................................................................42. LITERATURE SURVEY.......................................................................... 52.1 SURVEY OF EXISTING WORK.................................................................. 52.2 SUMMARY OF THE SURVEY............................................................. 63. REQUIREMENT ANALYSIS AND DESIGN........................................63.1 INTRODUCTION................................................................................... 63.2 REQUIREMENT ANALYSIS................................................................73.2.1 STAKEHOLDERS................................................................................................ 73.2.2 FUNCTIONAL REQUIREMENTS.......................................................................73.2.3 NON FUNCTIONAL REQUIREMENTS............................................................. 93.2.4 SYSTEM REQUIREMENTS...............................................................................103.2.4.1 H/W REQUIREMENTS............................................................................103.2.4.2 S/W REQUIREMENTS..............................................................................103.2.5 WORK BREAKDOWN STRUCTURE................................................................113.2.6 GANTT CHART..................................................................................................113.2.7 PROJECT TIMELINE........................................................................................124. DESIGN.....................................................................................................124.1 INTRODUCTION................................................................................. 124.2 HIGH LEVEL DESIGN........................................................................ 134.2.1 ARCHITECTURE DESIGN............................................................................... 134.2.2 ARCHITECTURE DIAGRAM............................................................................134.2.3 UI DESIGN........................................................................................................ 144.3 DETAILED DESIGN............................................................................ 194.3.1 ER DIAGRAM.................................................................................................... 194.3.2 UML DIAGRAMS.............................................................................................. 195. IMPLEMENTATION AND TESTING.................................................255.1 IMPLEMENTATION........................................................................... 255.2 TESTING...............................................................................................305.2.1 TYPES OF TESTING......................................................................................... 305.2.2 TEST CASES...................................................................................................... 316. CONCLUSION.........................................................................................347. REFERENCES......................................................................................... 34
ABSTRACT
The project titled “MUSIQUE” of Music library management systemismanagement software for monitoring and controlling the features of music.Musique has to sale various musical items and each itemcomes withnumberofmodels and varieties The main objective of our project IS to make a freewebsitewhich would allow the users to listen to free music and even addtheir owncollection of songs or albums and contribute towards the broadeningofthewebsite, which we were able to provide through this project. The USERhastheprivilege to post/publish and maintain albums of their own, each albumhavingcorresponding songs. In addition to these features, the user can createandmaintain playlists of songs. They even have the ability to add song to favoritesACKNOWLEDGEMENTI would like to express our special thanks of gratitude to our teacher Prof.Ms.PREETHA EVANGELINE who gave us the golden opportunitytodothiswonderful project on Software Engineering, which also helped me indoingalotof Research and I came up with the project to understand the necessityandusefulness of the software engineering concepts. The project “Music ManagementSystem ” has helped me realize the potential and real-life usage of softwareEngineering concepts of Software Engineering and I came to knowabout somanynew things, I am really thankful to them.
1. INTRODUCTION1.1 MOTIVATION
Scientific studies prove that music can improve your motivation. Musiccancause the brain to release dopamine, a chemical which works toregulatemotivation and goal-oriented behaviour. Keeping this in mindandmanyfactors we wanted to provide the user a good experience and an escapefromthe real world . 1.2 AIM
The aim of this project is the development of a sample relational Musicapplication. This application provides users with multiple songoptions,categories and community polls . The application does give adminaccesstofeedback , the uploading of new songs ,removing current songs etc. 1.3 OBJECTIVE
Objective of Music Library Management System. Music Library ManagementSystem is a web based application which has been developed over PHPandMySQL and runs on WAMP, XAMPP or Apache2 server.The mainobjectivewas to divide the site into modules and provide users a satisfying experience.
2. LITERATURE SURVEY2.1 SURVEY OF EXISTING WORK
https://www.researchgate.net/publication/317600998_Literature_Review_Music_Technology_in_Education_ETEC_5203Foundations_of_Educational_Technology
The study and implementation of music technology in music educationcanbeplaced into certain categories, depending on how the technologyisused.Starting with asynchronous delivery of content, one can exploredistancelearning, which is mainly being explored and implemented at the collegiatelevel. https://www.ijarcce.com/upload/2016/april-16/IJARCCE%2063.pdf
We conclude that there is a large scope for the research work. Maximumwork is done on the western instrument and very less work is doneontheIndian instrument. Need to work on the Indian instrument, whichis averyhuge area for research. https://www.conscientiabeam.com/ebooks/ICEFMO-%20214-552-563.pdfThe focuses of research are defined based on two things; adaptivenessandactor(s) orientation. Some research in the music business model pertainedtostatic or dynamic adaptiveness. In actor(s) orientation, this categorizationofliterature review is based on two things; single actor perspective andmultiactor perspective.
2.2 SUMMARY OF THE SURVEY
In the period of chaotic transition from 2000 to 2015, however, publicdebatespaid little attention to questions concerning how musicians wouldactuallymake money in the still-forming digital era, from what sources, andhowmusical careers might be sustained, beyond speculations about thenewopportunities offered by ‘disintermediation’ and newpossibilities suchas‘crowdfunding’.The current existing models provide user the basic featuresbutasks for subscription and premiums for advance ones . The advertisement insuch cases can be annoying for the user , in such case to fill thegapandprovide a free service or minimize the cost we tried to design a user friendlyand musicians-friendly website . 3. REQUIREMENT ANALYSIS ANDDESIGN3.1 INTRODUCTION
MUSIQUE is a platform where people can listen to online music. Peoplecansearch for albums, songs or the album directors. People can searchasongoran album from a sorted list of data on the basis of genre and language. Onceregistered, the user can avail the privilege of publishing an albumof their ownand create and maintain songs on the website. Users can maintain/edit onlythose music files added by them. Users can create playlists and addsongstoit.The website also allows the user to add songs to ‘favorite list’. Thewebsitehas a Content based Song Recommendation Algorithmwhichprovidesapersonalized suggestion of a particular genre of songs which the user likesthemost.
3.2 REQUIREMENT ANALYSIS
3.2.1 STAKEHOLDERS
 Admin:- Common tasks for the admin include viewingthefeedback,replying and deletion of it.A new user with a unique usernameand password can be added as well as current users can be editedordeleted. The admin can add the new song categories ,givethedescription and upload a song’s image,view, edit and delete thecurrentexisting categories,view the current albums, add songs tothecurrentalbums which can be edited or deleted. ● General users:- This category of users do not have the permissiontoaccess the admin section. They will be able to see the statisticsofthecommunity poll.They have the power to vote for their favouritesongswhich would help a particular song climb the leaderboardof therecommended songs. They are able to view the songs arrangedbyranks.They also access the feature for receiving updates about thecurrentaffairs of songs.The general users are also enabled to give feedbackabout the albums and songs they listen to. 3.2.2 FUNCTIONAL REQUIREMENTS
1.Registration
● Description: To enter into this site a user has to register himself first.Requirements of the registration are the first name, middle name, lastname, email id, password, confirm password. 2.User Login
● The system provides the facility to login in to the system.
● The system will check the input of the user and if the valid thenloginisdone. otherwise the user will be asked to re enter the user nameandthepassword. 3.Forgot Password
● The user can send the reset link to the mail id to the reset password. ● By the system will add selected easily change the passwordandupdatethe store in the database. 4.Select the song
● The user can select the preferable type of song. ● The system will add the selected data into the database. 5.Administrator
● Admin is provided with the information of user and songs andadmincan update the system software to meet the requirements
● He can view registered user’s information and update the system, addnew latest songs. 6.User
● The user can view the details of song (like singer, music director, genre,language of that song)
● The user can able to search for various types of songs. ● In this website the user can just view the details but cannot manipulate● This website allow the user to fill out and submit a service form(if anyrequired)
7.Registered Users
● Registered users can download the albums ,He can even Buythelatestalbum ,He can even add new albums into the website. ● He can manage his profile by adding new playlists,songs andchanginghis settings according to his requirements..
3.2.3 NON FUNCTIONAL REQUIREMENTS
1.Performance Requirements
● The system needs to be reliable. ● If unable to process the request then appropriate error message. ● Web pages are to be located within the few seconds. ● The requested songs in this website will be loaded with in fewseconds(with good internet connectivity)
2.Safety Requirements
● The login details of the user need to be maintained properly. ● Users can be authenticated. ● The database is continuously backed up. 3.Security Requirements
● In this website after entering the password and user id the user canaccess his profile and can make necessary changes (if required). ● The details of the user must be safe and secure. ● Sharing the details. 4.Software Quality Attributes
● Usability :-The software will be embedded in a website. It shouldbescalable and designed to be easily adopted by a system. ● Reliability :-The system should have accurate results and fast responsesto user’s changing habits. Security User profile information will beused,so data security is one of the most important concerns of the system. 5.Other Requirements
● Failure handling :-System components may fail independentlyofothers. Therefore, system components must be built so theycanhandlefailure of other components they depend on. ● Openness :-The system should be extensible to guarantee that it isuseful for a reasonable period of time. Security Sensitive informationshould be kept in safe.
3.2.4 SYSTEM REQUIREMENTS
3.2.4.1 H/W REQUIREMENTS
Since the web portal does not have any designated hardware, it doesnot have any direct hardware interfaces. The hardware connectiontothe database server is managed by the underlying operatingsystemonthe web server. 3.2.4.2 S/W REQUIREMENTS
The website components communicate with the database inordertoget the user rating logs for the larger system. Jquery, Javascript PHP,SQL. TheOnline Music Site is developed using PHP, CSS, andJavaScript.The Apache HTTP Server, colloquially called Apache, isafree and open-source cross-platform web server usedfor bettersoftware/user experience using Bootstrap, CSS
3.2.5 WORK BREAKDOWN STRUCTURE
4. DESIGN
4.1 INTRODUCTION
The main purpose of this product is to develop a website which wouldpermitthe clients to tune in to free music and even add their own assortment of tunesor collections. This product is designed to provide users with all thenewreleases, top 6 songs with rankings, news, featured songs, vote their favoritesong and listen to the song. The users can simply view all the albums andclickany one of them to listen to their songs.
4.2 HIGH LEVEL DESIGN
4.2.1 ARCHITECTURE DESIGN
 Community Poll Survey:-User will be able to vote for their favouritesongsand also view the songs according to song ranking.  Admin Login:- Through Admin login we can login user can logintothereaccount and access the privileges such as adding the songs tothealbum,viewing the feedback of the users.  Provide Feedback:-The users can provide feedback through the feedbackoption in the website so that the admin can see the feedbackabout thesongs.The users must be able to read reviews and provide feedbacktothesystem.  Editing Albums:- The registered users will be given privilege of addingorremoving songs from their albums.They can even add their newsongs intothewebsite or they can even remove songs from the website
4.2.2 Architecture diagram
4.2.3 UI DESIGN
HOME PAGE:-
ALBUM
ADMIN LOGIN
FEEDBACK FORM
VOTE SONGS
ADMIN PAGE
ALBUM RECORDS
VOTING RESULTS
4.3 DETAILED DESIGN
4.3.1 ER DIAGRAM
4.3.2 UML DIAGRAM
1. HIGH LEVEL DESIGN
1.1 COMPONENT DIAGRAM
1.2 USE CASE DIAGRAM
1.3 ACTIVITY DIAGRAM
1.4 STATE CHART DIAGRAM
2. LOW LEVEL DESIGN
2.1 ClASS DIAGRAM
2.2 OBJECT DIAGRAM
2.3 SEQUENCE DIAGRAM
5. IMPLEMENTATION AND TESTING5.1 IMPLEMETATION
We used HTML , CSS , Bootstrap for the front-end and for the back-endweused Javascript , SQL and PHP majorly
SCREEN SHOTS OF CODE:- Sample screen shots of code used for this project are
Admin add category.php
Show votestat.php
Vote.php
Add user.php
Admin Add album
Login page.php
About us.php
Album by category.php
5.2 TESTING
5.2.1 TYPES OF TESTING
1. Unit Testing
It focuses on the smallest unit of software design. In this, wetest anindividual unit or group of interrelated units. We have usedSeleniumSoftware for this process. 3 major test-cases were writtenanddocumented. The response of buttons, the navigation throughvariouswebpages and graphics were validated. 2. Integration Testing
The objective is to take unit tested components and buildaprogramstructure that has been dictated by design. Integration testingis testinginwhich a group of components is combined to produce output. Thewholeproject was tested multiple times on a local server which was runusingXampp. All the components were working seamlessly and that thewholesystem was integrated without any errors.
5.2.2 TEST CASES
TEST CASE 1
TEST CASE 2 :
TEST CASE 3 :
6. CONCLUSION● The project aims to create an interactive, maintainable and efficient applicationfor the new or growing musicians who would like to upload their musicfreeofcost along with the added functionality of making playlists/album. ● This website will allow the users to listen to free music and even addtheir owncollection of songs or albums and contribute towards the broadeningofthewebsite, which we were able to provide through this project. ● From this project, we came to a conclusion that by decentralizingthedatainthe database, i.e., adding of albums not only by the admin but alsobytheregistered user, it is easy to obtain a large amount of data fromdifferentsources (registered users).7. REFERENCES
● Music Management System: https://www.slideshare.net/nileshpadwal456/music-management-system
● Online Music Store Management SystemProject Report:https://sites.google.com/site/ignoubcafinalyearprojects/project-report/online-music-store-ma nagement-system-project-report
● Xu, J. The Design and Implementation of Music Player Based on AndroidPlatform, Beijing Posts and Telecommunications University, 2011-5:156～178● Wilson, C., and Brown, M., 2013. Extending Realities: Creativity, ArtistryandTechnology. In Reisman, F., Ed., Creativity: Process, Product, Personality,Environment & Technology. KIE Conference book series. ● Yoeman, I., Robertson, M., Ali-Knight, J., Drummond, S., andMcMahon-Beattie, U., eds.
