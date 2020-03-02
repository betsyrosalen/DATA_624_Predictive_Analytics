# DATA 624 Predictive Analytics

# Syllabus 
**School of Professional Studies**  
**DATA 624: Predictive Analytics**  

**Instructor Name:** Jeffrey Nieman  
**Instructor Email Address:** Jeff.nieman@sps.cuny.edu  
**Degree Program:** M.S. in Data Science  
**Credits:** 3 graduate credits  
**Prerequisites:** DATA 621 collegial  
**Type of Course:** Required course  

## Course Summary:

This course teaches students to use advanced machine learning techniques that are focused on predictive outcomes. Topics will include time series analysis and forecasting, recommender systems, and advanced regression techniques. In addition, students will learn how to evaluate the predictions that result from these techniques, how to assess model quality, and how to improve models over time.

## Course Learning Outcomes:

At the end of this course, students will be able to:

Apply advanced regression techniques such as constrained linear (PLS, NIPALS, Ridge, LARS), nonlinear (MARS, SVM, KNN), Trees (RF, Boosted).

Utilize various forecasting techniques to produce reliable and robust forecast models.

Develop recommendation systems using knowledge-based and content-based approaches.

Evaluate the quality of models produced and make recommendations for improvement to models.

## Program Learning Outcomes/Competencies addressed by the course:

- Business Understanding. Students will learn how predictive modeling and forecasting techniques can add value to existing business analytics.
- Data Understanding. Students will learn how to explore data to find patterns that allow for forward-looking forecasts and recommendations.
- Model Implementation. Students will learn to implement models for the various predictive modeling techniques covered in the course, with a focus on recommendations, estimation, and forecasting techniques.

## How is this course relevant for analytics professionals?

Predictive modeling and forecasting are mainstays of the analytics profession. Predictive modeling spans numerous fields and approaches. Indeed, within this course the student will be introduced to a multitude of techniques, some of which fall under the moniker "statistical modeling" while others are referred to "machine learning." For this course it's less important the lineage of a particular technique, but rather the classes of problems to be solved.  

Each class of problems introduce multiple techniques. It is likely that the student has encountered many of these approaches in the past. This is both unavoidable and also fortuitous as the bulk of the course can thus focus on applying these techniques to the problem classes as opposed to learning the theory of the techniques.

## Assignments and Grading:

Each section comprises an introduction, a reading assignment, and book exercises. In addition, the bulk of the grading is focused on two course-specific projects along with paper submissions detailing methodology and results, including data visualizations.
 
### Book Exercises 30%

Completion of exercises must include working R code along with a brief discussion of the approach and results.  All homework sets will be due on Sundays at 11:59 PM.   Late homework will be accepted with penalties until the following meetup when the homework will be discussed.

### Slack Authoring and Participation 10%

We will create a slack to help the class participate and discuss.  This is the primary method to reach out to your classmates and me for help.  We will periodically have related topical discussions there as well.  You will be graded on how well you participate both in raising issues and responding to each others’ questions/discussions.

### Project 1 15%

The first student project will be a solo time series and forecasting problem. A professionally written report will be required.  Details in Announcements.

### Project 2 30%

The second student project will be a group predictive modeling problem. A professionally written report will be required.  Part of your grade will be determined by your peers on your contribution to the submission. Details in Announcements.

### Lecture 15%

You and your group will be required to prepare and give a lecture for the entire class.  We will be meeting in GoToMeetings and you will present from your workstation.  There will be 7 presentations and each will last approximately 20 minutes including Q&A.  The 7 topics will be Time Series Decomposition, Exponential Smoothing, ARIMA, Linear Regression and its Cousins, Non-linear Regression, Trees & Rules-based Models and Recommender Systems.  Details and Group Assignments on Blackboard.
 
 
## Required Texts and Materials:

Reading assignments span two primary texts. These are

- Hyndman & Athanasopoulos. [Forecasting: Principles and Practice](https://www.otexts.org/fpp2/)
- Kuhn & Johnson. [Applied Predictive Modeling](http://appliedpredictivemodeling.com/)

A third book can be used for supplemental reading, which is

- Hastie, Tibshirani, & Friedman. [Elements of Statistical Learning.](http://statweb.stanford.edu/~tibs/ElemStatLearn/)

Some of the reading will overlap across the two books. Where there is overlap, HA is generally more accessible, acting as an introduction, while KJ is a bit more theoretical. The student is encouraged to exercise judgment as to whether to skip the overlapping content.
 
NOTE: Books are referenced by abbreviation for convenience. Hyndman & Athanasopoulos is abbreviated HA, and Kuhn & Johnson is abbreviated KJ.

## Relevant Software, Hardware, or Other Tools:

This course requires using the R language. Students must be familiar with the language and know how to install packages. All homeworks must be written in R and submitted as code that can easily be cut and copied into R Studio to run.  Students must describe in written form their approach and analysis for all problems. The exposition is used to not only determine whether thought processes are sound but also to provide partial credit on problems.

## My Contact Information:

You are encouraged to ask me questions on our class Slack page so other students may benefit from your inquiries.  You may also reach out to me on the “Ask Your Instructor” forum on the course discussion board.  As I work at a busy day job, I generally check the forums in the evenings.

I am available by email (jeff.nieman@sps.cuny.edu). We can also set up an interactive session for screen share. For the most part, you can expect me to respond to questions by email within 24 to 48 hours. If you do not hear back from me within 48 hours of sending an email or have an emergency, you may send a text message or call my mobile phone at 734-649-7537 (text is better).

## Course Outline:

_The course schedules is as follows. Note that the first week is an introductory week and I expect you to use it to get a jump start on the class as well as make relationships with fellow students.  You will greatly benefit by discussing and working together with your classmates.   The projects are a major part of the class and will require early planning and organization._

Week | Topic | Reading | Homework | HW Due
--- | --- | --- | --- | ---
1 | Welcome and Introductions |  |  | 
2 | Time Series | HA ch. 1-2 | HA 2.1-2.3, 2.6 | 2/9/2020
3 | Forecasting | HA ch. 3 | HA 3.1-3.3, 3.8 | 2/16/2020
4 | Decomposition | HA ch. 6 | HA 6.2, 6.3 | 2/23/2020
5 | Data Preprocessing/Overfitting | KJ ch. 3-4 | KJ 3.1, 3.2 | 3/1/2020
6 | Exponential Smoothing | HA ch. 7 | HA 7.1, 7.5-7.9 | 3/8/2020
7-8 | ARIMA | HA ch. 8 | HA 8.1-8.3, 8.5-8.7 | 3/22/2020
9 | Project 1 |  |  | 3/29/2020
10 | Linear Regression | KJ ch. 6 | KJ 6.3 | 4/5/2020
11 | Non-linear Regression | KJ ch. 7 | KJ 7.2, 7.5 | 4/19/2020
12-13 | Trees and Rules | KJ ch. 8 | KJ 8.1-8.3, 8.7 | 4/26/2020
14 | Recommender Systems | Articles | Rules HW | 5/3/2020
15 | Project 2 |  |  | 5/10/2020

### ACCESSIBILITY AND ACCOMMODATIONS

The CUNY School of Professional Studies is firmly committed to making higher education accessible to students with disabilities by removing architectural barriers and providing programs and support services necessary for them to benefit from the instruction and resources of the University. Early planning is essential for many of the resources and accommodations provided. Please see: http://sps.cuny.edu/student_services/disabilityservices.html

### ONLINE ETIQUETTE AND ANTI-HARASSMENT POLICY

The University strictly prohibits the use of University online resources or facilities, including Blackboard, for the purpose of harassment of any individual or for the posting of any material that is scandalous, libelous, offensive or otherwise against the University’s policies.  Please see: http://media.sps.cuny.edu/filestore/8/4/9_d018dae29d76f89/849_3c7d075b32c268e.pdf

### ACADEMIC INTEGRITY

Academic dishonesty is unacceptable and will not be tolerated. Cheating, forgery, plagiarism and collusion in dishonest acts undermine the educational mission of the City University of New York and the students' personal and intellectual growth. Please see:http://media.sps.cuny.edu/filestore/8/3/9_dea303d5822ab91/839_1753cee9c9d90e9.pdf

### STUDENT SUPPORT SERVICES

If you need any additional help, please visit Student Support Services: http://sps.cuny.edu/student_resources/
