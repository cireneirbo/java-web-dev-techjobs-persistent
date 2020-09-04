# Java Graded Assignment #4 Rubric (TechJobs, Persistent Edition)

This assignment tests the students' understandings of SQL database management and the mechanics of object relational 
mapping. Students will demonstrate their knowledge of these topics by making updates again to the TechJobs application.
They will be asked to create the database connection, finish what has been started to persist several model classes, 
create a one-to-many and a many-to-many relationship between objects, and answer a few simple SQL questions.

Grading should be done via demonstrations again. Ask your students to give you a guided walkthrough of their sourcecode,
as well as their running application.

## Score your students' work based on the following criteria:

### Performance and Code Check:

1. Ask the student to start their application and navigate to the *Add Job* view.

1. Ask them to create a new employer from the form and show you the resulting object in the employer table.

1. Ask them to create at least two new skills from the form and show you the objects in the skill table.

1. Ask the student to create a new Job from the form, selecting at least two skills. 

   a. Once created, have the student show you their job table and verify that there is an ``employer_id`` column in it. 
      You may note that some students also have a ``employer`` column in job still. This is ok. We asked them to provide the
      ``DROP TABLE`` command in their ``queries.sql`` file but left it optional if they chose to execute the command.
     
   b. Have the student confirm that a mapped table is present for ``job_skills`` and that at least two rows are now in it
      for the job just created.
      
1. At no point should there be an a table related to the ``AbstractEntity`` class. Ask the student to show you all of their
   tables in their ``techjobs`` schema to make sure there is no such table.

1. The students were asked to answer a few SQL questions and input their responses into a file in the root of the 
   project's directory called ``queries.sql``. Check their responses with the ``queries.sql`` found in this solution repo.
   It is ok if the query responses do not match exactly but the syntax is appropriate. 
   

## Feedback and Grades:
    
Give your student a score of 1 if they meet each the requirement above. If they are missing one of the tables, or 
their SQL responses are not sufficient, give some advice on how to correct this. Ask them if they feel there is
something blocking their success. Plan to have them demonstrate their assignment with you again when they have made 
the corrections.
