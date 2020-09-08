Criteria A Planning
======================


Indentifying the client
--------------------------
Client is Yu, student from UWC ISAK Japan. He is leader of the gym club. Gym club goes to the Kazakoshi gym with a school bus 2-3 times a week. There is too much membes to take everyone to the gym on one day. Every week, he needs to contact all the students and ask them which day would they like to go, then he needs to decide who goes when, and contact all the students again to tell them which day they are going. Then he needs to manually check atttendance and organize it. Becuase he is the only one who has record of attendances, he needs to manually notify students who didn't come the day they should, and let them know how many times they missed the gym club unexcused, because he needs to kick them out when they miss the club 3 times.
Because all that takes him a lot of time he wants a system which will automate as much of his work as possible. He wants system that will enable each user to log in indvididualy. If gym club **member** logs in, they should be able to:
1. Pick at the begining of the week, which days they would like to go
1. Show day which days they were asigned to go
1. Show them warning if they missed the day they should go
1. Show them how many times they can miss the club unexcused before they are kicked out
1. Show them monthly and yearly statistics (how many times they went to the gym)

IF gym club **leader** logs in, they should be able to:
1. See which day every student wants to go
1. Assign each student to a specific day
1. Take attendance for every student
1. Show attendace statistics for every student

Choosing and justifing a solution
------------------------------
My solution will be an online dynamic website built using HTML5 and bootstrap, Python, Flask and SQLLite. Justification for each of the decisions:
* **Online dynamic** - It will be accesible to each user online with their phone/computer. This is important because having ofline localy bassed aplication would reqire each student to have access to one shared machine, which would be really inconvinient. Website needs to be dyinamc, because I want each user to see individualized content when they log in. This is imporant, because gym club members can't have overview of each members attendance. This is also necessery for security reasons, as only club leader should be able to take the attendance and decide if absence was excused or unexcused.
* **HTML5 and bootstrap** - I will be using HTML and bootstrap to build the front end of my website. HTML is the most widely spread language for building websited. It can be opened by any internet browser. I will be using bootstrap, because it offers a lot of pre-built website blocks, which can be re-used. This will decreas time I will spend on the front end desing.
* **Python, Flask and SQLLite** TO build the back end of my website I will be using Flask, which is micro web framework for building websites and servers in python. SQLLite will be used for building a data base. I will be using it because it is already preintegrated in flask. **ADD MORE JUSTIFICATIONS; LOOK AT THE DOCUMENTATIONS; COMAPRE WITH OTHER POSSIBLE SOLUTIONS**

