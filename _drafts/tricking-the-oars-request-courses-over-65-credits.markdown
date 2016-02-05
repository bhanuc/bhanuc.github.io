---
layout: post
title: 'Tricking the OARS : Request courses over 65 credits'
---

NOTE: The post can be understood and relevant to only recent students of IIT-Kanpur who have had the pleasure to use OARS.
I have been tricked by OARS multiple times over the years. Unexpected downtime, semi-planned downtime, well-planned downtime are now an essential feature of OARS IITK. 
OARS is an Hotch-Potch implementation of Java and Oracle DB which solves the most important academic issue regarding course allocation to students. An interesting thing to note is the ease which the platform offers us over manual registrations. Earlier the registration and time-table/exam clashes were all handled and calculated manually by the administration.

Being Pre-historic in nature, OARS is a poorly implemented insecure platform which even has few open security loopholes which makes the system vulnerable to get gamed. Disclosing and forte security loopholes is not exactly my forte nor the post is about it, but I would like to disclose a loophole in OARS which allows you to request over 65 credits in a semester during the add-drop period. Note: the loophole is still open during the time of posting.

So to over-request courses during the pre-registration, you need to have few accepted courses.So choose a course which you think you can get even after getting de-registered.No. of such courses must be equal to the credits of courses you want to request when overloading. (Beware of professors who might have set the requests to auto-accept, also try to choose a time when the probability of the professor sitting and handling course-requests is minimal) So using the drop option, drop the course. Notice a request will be send to the professor and your request to deregister the course will be shown waiting and as per the discretion of the professor. Now using the add-course, add the request of the course which you want. Request of the course to be added will be shown pending.
 Now here comes the trick. Just cancel your request to drop a course. Voila, now you have the course re-added to your template and accepted and the new course will still be in waiting. 
But at the time of final submission, you would be able to only add course of only upto 65 credits.
I hope this loophole might help some students to get courses of their choices as the current system has a huge factor of getting lucky, leaving the students at a disadvantage.