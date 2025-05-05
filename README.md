# dbms-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [DBMS Assignment 3 Solved](https://www.ankitcodinghub.com/product/dbms-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100156&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DBMS Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
There are 16 Question Sets each containing 10 queries. Sets are numbered as SET A, SET B, …, SET P. The questions within each set are numbered as 0, 1, 2, .., 9. You will have to answer 10 queries, one from each of the 10 sets assigned to you. We have uploaded a document that tells your assignment of roll number to sets. For the assigned sets, you have to answer the same question number. The question number within a set you have to answer is the same as the last digit of your roll number.

Suppose you have been assigned the 10 sets SET A, SET B, SET D, SET F, SETG, SET H, SET K, SET L, SET M, SET P and your roll number ends in 5. Then, you have to answer the question with serial number 5 for each of these 10 sets.

HINT: It might be a good idea to first take a look at the set assignment and then mark your questions in the pdf file corresponding to your roll number.

A database schema and the sets of questions are given below.

You have to write your SQLs in a single text file and submit through Moodle (Name it as Lab4_&lt;Roll_no&gt;.txt). The first few lines of the file should have your roll number and name and also the sets assigned to you. Also, you must write before each SQL, the &lt;set number&gt;.&lt;query number&gt;. For example, suppose your roll no. is 19CS10005 and your name is ABC DEF and you have been assigned the above sets. Your submission file should look like this:

File name: Lab4_19CS10005.txt

18CS10005 ABC DEF

SET A, SET B, SET D, SET F, SET G, SET H, SET K, SET L, SET M, SET P

<pre>A.5
Select ....
B.5
Select...
D.5
Not answered
.....
</pre>
Note: For each question, you have to write a single SQL query which can have any number of sub- queries. You cannot split it into separate queries, views, etc. It is important that you use exactly the same table and column names as given in the question. Otherwise, there will be mismatch during evaluation and you will lose marks. For any query, you may write any assumption that you make. It will be considered only if the assumption is found to be reasonable.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Consider the following database schema

RegUser (RNo int, RName varchar(20), ROccu varchar(10), Age int, HighestQual varchar(5), PRIMARY

KEY(RNo));

Possible values for ROccu are: FACULTY, STUDENT, STAFF Possible values for HighestQual are: BTECH, MTECH, PHD

Faculty (FId int, ResearchArea varchar(4), FDept varchar(3), PRIMARY KEY(FId),

FOREIGN KEY fk_std_0(FId) REFERENCES RegUser(RNo));

Possible values for FDept are: CS, EE, ECE, ME

Possible values for ResearchArea are: AI, ML, DBMS, ALGO

Course (CId int, CName varchar(10), CDuration varchar(10), CDept varchar(3), FId int, PRIMARY KEY(CId),

FOREIGN KEY fk_std_1(FId) REFERENCES Faculty(FId));

Possible values for CDuration are: SHORT, MEDIUM and LONG Possible values for CDept are: CS, EE, ECE, ME

Prerequisite (CId int, PreqCId int,

FOREIGN KEY fk_std2(CId) REFERENCES Course (CId), FOREIGN KEY fk_std3(PreqCId) REFERENCES Course (CId), PRIMARY KEY(CId, PreqCId));

CourseReg (RNo int, CId int, Score int,

PRIMARY KEY(RNo, CId),

FOREIGN KEY fk_std4(RNo) REFERENCES RegUser (RNo), FOREIGN KEY fk_std5(CId) REFERENCES Course (CId));

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
SET A

Srl Query No.

<ol start="0">
<li>0 &nbsp;List all the registered users along with the courses they are enrolled in, and their faculty (RId,
RName, FId, FName, CId, CName)
</li>
<li>1 &nbsp;List all the registered STUDENTS along with the courses they are enrolled in and their
faculty (RId, RName, FId, FName, CId, CName)
</li>
<li>2 &nbsp;List all the registered users with MTECH as their highest qualifications along with the
courses they are enrolled in and their faculty (RId, RName, FId, FName, CId, CName)
</li>
<li>3 &nbsp;List all the registered users with MTECH as their highest qualifications along with the CS
courses they are enrolled in and their faculty (RId, RName, FId, FName, CId, CName)
</li>
</ol>
<ol start="6">
<li>6 &nbsp;List all the registered users who have enrolled in more than one CS courses and their faculty (RId, RName, FId, FName, CId, CName)</li>
<li>7 &nbsp;List all the registered users who have enrolled in CS and EE courses having SHORT or MEDIUM duration and their faculty (RId, RName, FId, FName, CId, CName)</li>
</ol>
</div>
<div class="column">
Remarks

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users who are NOT FACULTY along with the SHORT courses they are enrolled in and their faculty from CS department (RId, RName, FId, FName, CId, CName)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users who do NOT have PHD as their highest qualification along with the courses they are enrolled in having faculty with research area in AI or ALGO (RId, RName, FId, FName, CId, CName)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users with BTECH as their highest qualification along with the courses they are enrolled in and their faculty such that the courses does NOT include any from EE or ME department and the faculty does Not have DBMS as their research area (RId, RName, FId, FName, CId, CName)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users with highest qualification as BTECH or MTECH and who have enrolled in EE or ECE courses of MEDIUM duration and their faculty such that they are NOT from ME department and has AI or ML as their research area (RId, RName, FId, FName, CId, CName)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
SET B

Srl Query No.

<ol start="0">
<li>0 &nbsp;List top 3 registered users from each department who have scored the highest in CS courses
(RId, RName, CId, CName, Score)
</li>
<li>1 &nbsp;List top 3 registered users from each department who have scored the highest in EE courses
(RId, RName, CId, CName, Score)
</li>
<li>2 &nbsp;List top 5 registered users having BTECH as their highest qualifications from CS department
who have scored the highest in CS courses (RId, RName, CId, CName, Score)
</li>
</ol>
4 List top 2 registered users from CS or ECE department who have scored the highest in CS courses of LONG duration (RId, RName, CId, CName, Score)

7 List top 2 registered users from EE or ECE department who have scored the highest in both EE and ECE courses of MEDIUM or LONG duration (RId, RName, CId, CName, Score)

</div>
<div class="column">
Remarks

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List top 4 registered users having MTECH as their highest qualification from each department who have scored the highest in CS and EE courses courses (RId, RName, CId, CName, Score)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List top 3 registered users who have BTECH or MTECH as their highest qualification from EE department who have scored the highest in both EE and ECE courses of SHORT or MEDIUM duration (RId, RName, CId, CName, Score)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List top 3 registered users who does NOT have PHD as their highest qualification from ME department who have scored the highest in CS, EE or ECE courses (RId, RName, CId, CName, Score)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List top 3 registered users who have MTECH as their highest qualification from NOT ME department who have scored the highest in both EE and ECE or CS courses (RId, RName, CId, CName, Score)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List top 4 registered users with BTECH as their highest qualification from each department who have scored the highest in both EE and ECE courses of MEDIUM duration (RId, RName, CId, CName, Score)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Srl Query

No.

<ol start="0">
<li>0 &nbsp;List all registered users (RNo, RName, CId, CName) who have enrolled in courses each of which has more than one prerequisite (consider only single level of pre-requisite).</li>
<li>1 &nbsp;List all registered users (RNo, RName, CId, CName) who have enrolled in courses each of which has exactly one prerequisite (consider only single level of pre-requisite).</li>
<li>2 &nbsp;List all registered users (RNo, RName, CId, CName) who have enrolled in courses each of which has no prerequisite (consider only single level of pre-requisite).</li>
<li>3 &nbsp;List all registered users (RNo, RName, CId, CName) who have enrolled in at least one course which has more than one prerequisite (consider only single level of pre-requisite).</li>
<li>4 &nbsp;List all registered users (RNo, RName, CId, CName) who have enrolled in at least one course which has exactly one prerequisite (consider only single level of pre-requisite).</li>
<li>5 &nbsp;List all registered users (RNo, RName, CId, CName) who have enrolled in at least one
course which has no prerequisite (consider only single level of pre-requisite).
</li>
<li>6 &nbsp;List all registered users (RNo, RName, CId, CName) who have NOT enrolled in any course
which has more than one prerequisite (consider only single level of pre-requisite).
</li>
<li>7 &nbsp;List all registered users (RNo, RName, CId, CName) who have NOT enrolled in any course
which has exactly one prerequisite (consider only single level of pre-requisite).
</li>
<li>8 &nbsp;List all registered users (RNo, RName, CId, CName) who have NOT enrolled in any course
which has no prerequisite (consider only single level of pre-requisite).
</li>
<li>9 &nbsp;List all registered users (RNo, RName, CId, CName) who have NOT enrolled in any course
which has exactly two prerequisites (consider only single level of pre-requisite).
</li>
</ol>
</div>
<div class="column">
Remarks

</div>
</div>
<div class="layoutArea">
<div class="column">
SET C

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
SET D

Srl Query Remarks

No.

0 List all courses along with their departments that are offered by faculty members not belonging to the same department. (CId, CName, CDept,FId, FName, FDept)

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all SHORT duration courses offered by faculty members having PHD as the highest qualification of the CS department whose research area is DBMS (Cid, CName, CDuration, FId, FName, FDept, ResearchArea, HighestQual)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all LONG duration courses offered by faculty members having MTECH as the highest qualification of the EE department whose research area is ALGO (Cid, CName, CDuration, FId, FName, FDept, ResearchArea, HighestQual)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all MEDIUM duration courses offered by faculty members having PHD as the highest qualification of the ME department whose research area is NOT ML (Cid, CName, CDuration, FId, FName, FDept, ResearchArea, HighestQual)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all MEDIUM duration courses offered by faculty members having PHD as the highest qualification of the EE department whose research area is ML (Cid, CName, CDuration, FId, FName, FDept, ResearchArea, HighestQual)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all MEDIUM duration courses offered by faculty members having MTECH as the highest qualification of the ME department whose research area is ALGO (Cid, CName, CDuration, FId, FName, FDept, ResearchArea, HighestQual)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all courses which are NOT of SHORT duration offered by faculty members having PHD as the highest qualification of the EE department whose research area is AI (Cid, CName, CDuration, FId, FName, FDept, ResearchArea, HighestQual)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all courses which are NOT of LONG duration offered by faculty members NOT having PHD as the highest qualification of the ECE department whose research area is DBMS (Cid, CName, CDuration, FId, FName, FDept, ResearchArea, HighestQual)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all courses which are of LONG duration offered by faculty members NOT having PHD as the highest qualification of the ECE department whose research area is NOT DBMS (Cid, CName, CDuration, FId, FName, FDept, ResearchArea, HighestQual)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all courses which are of LONG duration offered by faculty members NOT having BTECH as the highest qualification of the EE department whose research area is DBMS (Cid, CName, CDuration, FId, FName, FDept, ResearchArea, HighestQual)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Srl Query No.

<ol start="0">
<li>0 &nbsp;List all</li>
<li>1 &nbsp;List all</li>
<li>2 &nbsp;List all</li>
<li>3 &nbsp;List all (RNo ,</li>
<li>4 &nbsp;List all (RNo ,</li>
<li>5 &nbsp;List all (RNo ,</li>
<li>6 &nbsp;List all (RNo ,</li>
</ol>
</div>
<div class="column">
Remarks

</div>
</div>
<div class="layoutArea">
<div class="column">
SET E

</div>
</div>
<div class="layoutArea">
<div class="column">
the students who have registered for more than 1 course. (RNo , RName ) the students who have registered for at least 3 courses. (RNo , RName ) the students who have registered for exactly 1 course. (RNo , RName )

the students having age greater than 20 and have registered for exactly 1 course. RName )

the students having age greater than 20 and have registered for at most 4 courses. RName )

the students having age equal to 20 who have registered for exactly 2 courses. RName )

the students having age equal to 20 who have registered for at least 2 courses. RName )

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="7">
<li>7 &nbsp;List all the students whose name starts with an ‘A’ and have registered for at least 2 courses. (RNo , RName )</li>
<li>8 &nbsp;List all the students whose name starts with a ‘D’ and have registered for exactly 3 courses (RNo , RName )</li>
<li>9 &nbsp;List all the students whose names start with an ‘S’ and have registered for at least 2 courses. (RNo , RName )</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
Srl Query

No.

<ol start="0">
<li>0 &nbsp;List all the courses offered by the CS department that have at least one prerequisite course from the EE department. (CId,CName)</li>
<li>1 &nbsp;List all the courses offered by the CS department that have at least one prerequisite course from the ECE department. (CId,CName)</li>
<li>2 &nbsp;List all the courses offered by the ECE department that have at least one prerequisite course from the EE department. (CId,CName)</li>
<li>3 &nbsp;List all the courses offered by the EE department that have at least one prerequisite course from the CS department. (CId,CName)</li>
<li>4 &nbsp;List all the courses offered by the ECE department that have no prerequisite course from the EE department. (CId,CName)</li>
<li>5 &nbsp;List all the courses offered by the EE department that have at least one prerequisite course of LONG duration. (CId,CName)</li>
<li>6 &nbsp;List all the courses offered by the EE or ECE department that have at least one prerequisite course of MEDIUM duration. (CId,CName,CDept)</li>
<li>7 &nbsp;List all the courses offered by the CS or ECE department that have no prerequisite course of LONG duration. (CId,CName,CDept)</li>
<li>8 &nbsp;List all the courses offered by the CS department that have no prerequisite course of SHORT duration. (CId,CName)</li>
<li>9 &nbsp;List all the courses offered by the EE department that have at least one prerequisite course of MEDIUM duration. (CId,CName)</li>
</ol>
</div>
<div class="column">
Remarks

</div>
</div>
<div class="layoutArea">
<div class="column">
SET F

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
SET G

</div>
</div>
<div class="layoutArea">
<div class="column">
Srl Query No.

</div>
<div class="column">
Remarks

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the faculties, along with course details they teach and the department they belong to, for each research area, who teach more than two courses.

(FId, CId, CName, CDuration, CDept, FDept , ResearchArea)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
For each department, list the faculties and their area of research, who teach at least one long duration course offered by CSE department.

(FDept, FId, ResearchArea)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the faculties , the department they belong to, along with the courses they teach and the department which offers the course, who teach at most three courses and the course duration of all the courses are short.

(FId, FDept, CId/CName,CDept )

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
For each department, list the faculties, courses they teach and their area of research, who teach at most two courses and course duration being either short or long.

(FDept,FId, CId/CName,ResearchArea)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List department wise, the faculties, their research area, courses they teach, Faculties teach more than two courses and course duration is not short.

(FId,ResearchArea, Cid, CName)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
For each department, list the faculties and their area of research, who teach at least two courses offered by either CS or ECE department.

(Fid,FacultyId, ResearchArea)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the faculties, courses they teach and their area of research, who teach at least two courses offered by either CSE or ECE.

(FId, Cid, CName,ResearchArea)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the faculties, courses they teach and their area of research, who teach at least two courses offered by CSE and course duration is long.

(FId, Cid, CName, ResearchArea)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the faculties, corresponding courseid and their area of research, who teach at least two courses offered by either ECE or EE department.

(FId, CId, ResearchArea)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the faculties, course names they teach and their department for each research area who teach at most three courses and course duration is either short or medium.

(FacultyId, CName,FDept,ResearchArea)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
Srl Query No.

</div>
<div class="column">
Remarks

</div>
</div>
<div class="layoutArea">
<div class="column">
SET H

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the courses and corresponding course durations for faculties of CSE department doing research on DBMS who are less than 30 years old and having PHD as highest qualification. ( Cid, CName, CDuration )

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the course id, course names and corresponding course durations by faculties who are less than 30 years old and belong to either CSE or ECE department. (CId, CName, CDuration )

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the registration number, qualification ,research area and names of faculties who are more than 50 years of age and teach courses offered by CSE department.

(RNo, HighestQual, ResearchArea, RName)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
3 List the registration number, qualification , research area,age and names of faculties of age less than 50 , teach only one short course. (RNo, HighestQual, ResearchArea, Age,RName)

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the registration number, qualification, research area and names of faculties who are of age less than 50 and teach a course of long duration.

(RNo, HighestQual, ResearchArea, RName)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the CSE faculties (names and ID) of age more than 60 doing research in DBMS, having either PHD or Mtech as qualification and teach at least a course of long duration. (RName,FId)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the CSE faculties and their research area, of age less than 60 , having METCH as qualification and teach only one short duration course offered by CSE department. (ResearchArea, RName,Fid)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the registration number, qualification research area and names of faculties who are of age between 30- 50 and teach courses offered by either CSE or ECE department.

(RNo, HighestQual, ResearchArea, RName)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
<ol start="8">
<li>8 &nbsp;List the course details for faculties who are less than 30 years old and not having PHD degree and belong to ECE department. (CId, CName, CDuration, CDept)</li>
<li>9 &nbsp;List the course details for faculties of EE department who are more than 30 years old and not having PHD degree. (CId,CName , CDuration, CDept)</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
SET I

Srl Query Remarks

No.

0 List all the registered users who are faculties and who teaches either short or long term courses. (RNo, RName, ROccu, CId, CName, CDuration, CDept)

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users who are faculties in EE or CS having qualification as MTECH and who teaches long term courses in ECE. (RNo, RName, ROccu, HighestQual, FDept, CId, CName, CDuration, CDept)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users who are faculties in ECE with research area as DBMS or AI having qualification as PHD and who teach medium term courses. (RNo, RName, ROccu, HighestQual, FDept, ResearchArea, CId, CName, CDuration)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users who are faculties in ME with research areas as ML and age between 40 to 50 years having qualification as PHD and who teach short term courses. (RNo, RName, ROccu, Age, HighestQual, FDept, ResearchArea, CId, CName, CDuration)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users who are faculties in CS with research areas as ALGO having qualification as PHD and who teaches at least 5 short term courses.

(RNo, RName, ROccu, HighestQual, FDept, ResearchArea, CId, CName, CDuration)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users who are faculties in CS with research areas as ML or DBMS having qualification as PHD and who do not teach any short term courses.

(RNo, RName, ROccu, HighestQual, FDept, ResearchArea, CId, CName, CDuration)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users who are faculties in CS with research areas as AI having qualification as PHD and who does not teach any long term courses.

(RNo, RName, ROccu, HighestQual, FDept, ResearchArea, CId, CName, CDuration)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users who are faculties in EE with research areas as ML having qualification as PHD and who teaches more than 3 short term courses.

(RNo, RName, ROccu, HighestQual, FDept, ResearchArea, CId, CName, CDuration)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users who are faculties in ECE with research areas as ML or DBMS having qualification as MTECH and who teach 3 short term courses and at least 3 medium term courses in EE.

(RNo, RName, ROccu, HighestQual, FDept, ResearchArea, CId, CName, CDuration, CDept)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the registered users who are faculties in CS with research areas as DBMS having qualification as MTECH and who teach 2 to 7 short term courses in CS.

(RNo, RName, ROccu, HighestQual, FDept, ResearchArea, CId, CName, CDuration, CDept)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
SET J

</div>
</div>
<div class="layoutArea">
<div class="column">
Srl Query No.

</div>
<div class="column">
Remarks

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List for each student, his/her name, qualification and courses taken in CS or EE with marks greater than 60. The courses are taught by at least one faculty having research areas as ML or AI. (RNo, RName, HighestQual, CId, CName, CDept, Score, FId, ResearchArea)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List for each student, his/her name, qualification and courses taken in at most two departments with marks greater than 60 and less than 95. The courses are taught by at most three faculties having research areas as ALGO or AI.

(RNo, RName, HighestQual, CId, CName, CDept, Score, FId, ResearchArea)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List for each student, his/her name, qualification and courses taken in three departments with marks less than 80. The courses are taught by faculties having research area as ALGO and are from CS or EC.

(RNo, RName, HighestQual, CId, CName, CDept, Score, FId, ResearchArea, FDept)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List for each student, his/her name, qualification and courses taken in three departments with marks less than 80. The courses are taught by faculties having research areas as DBMS and are from CS or ECE.

(RNo, RName, HighestQual, CId, CName, CDept, Score, FId, ResearchArea, FDept)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List for each student, his/her name, qualification and courses taken in three departments with marks less than 70. The courses are taught by faculties having research areas as DBMS and are from EE or ECE.

(RNo, RName, HighestQual, CId, CName, CDept, Score, FId, ResearchArea, FDept)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List for each student, his/her name, qualification and courses taken in 5 departments with marks less than 85 and more than 50. The courses are taught by faculties having research areas as DBMS, age more than 40 and are from EE or ME.

(RNo, RName, HighestQual, CId, CName, CDept, Score, FId, ResearchArea, FDept, Age)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List for each student, his/her name, qualification and courses taken in 5 departments with marks less than 85 and more than 50. The courses are taught by faculties having research areas as DBMS, age more than 35 and are not from EE.

(RNo, RName, HighestQual, CId, CName, CDept, Score, FId, ResearchArea, FDept, Age)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List for each student, his/her name, qualification and courses taken at least 4 departments with marks less than 75 and more than 40. The courses are taught by faculties having research areas not as AI, age more than 38 and are not from ECE.

(RNo, RName, HighestQual, CId, CName, CDept, Score, FId, ResearchArea, FDept, Age)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List for each student, his/her name, qualification and courses taken at least 4 departments with marks less than 75 and more than 40. The courses are taught by faculties having research areas not as DBMS, age more than 38 and are not from CS.

(RNo, RName, HighestQual, CId, CName, CDept, Score, FId, ResearchArea, FDept, Age)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List for each student, his/her name, qualification and courses taken at most 6 departments with marks less than 75 and more than 40. The courses are taught by faculties having research areas as DBMS, age more than 45 and are not from ME.

(RNo, RName, HighestQual, CId, CName, CDept, Score, FId, ResearchArea, FDept, Age)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
Srl Query No.

</div>
<div class="column">
Remarks

</div>
</div>
<div class="layoutArea">
<div class="column">
SET K

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the students enrolled in a course taught by an instructor whose research area is DBMS and has no prerequisite courses taught by an instructor with research area AI (RNo, RName)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the students enrolled in a course taught by an instructor whose research area is DBMS and has only prerequisites courses from the CS dept whose instructors have age &gt; 60 (RNo, RName)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the students enrolled in a course taught by an instructor whose research area is ML and has either atleast one long duration prerequisite course or a medium prerequisite course taught by an instructor belonging to ECE dept (RNo, RName)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the students enrolled in a course taught by an instructor whose research area is ALGO and has either at least one long duration prerequisite course or all ECE prerequisite courses taught by instructors of CS dept (RNo, RName)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the students enrolled in a course taught by an instructor whose research area is ML and has either at least one long duration prerequisite course or a medium prerequisite course taught by an instructor with highest qualification either PHD or MTECH (RNo, RName)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
5 List all the students enrolled in a course taught by a instructor with age&lt;30 whose research area is ML &amp; that instructor teaches only short duration courses (RNo, RName)

<ol start="7">
<li>7 &nbsp;List all the students enrolled in courses taught by faculty of at least 3 departments and those courses all have at least one prerequisite course from CS dept (RNo, RName)</li>
<li>8 &nbsp;List the students enrolled in courses taught by either CS faculty or by faculty with PhD and area ML which have no prerequisites (RNo, RName)</li>
<li>9 &nbsp;List the senior students (age&gt;25) not enrolled in any course (RNo, RName)</li>
</ol>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all the students enrolled in a course taught by an instructor whose research area is ML and that course has only prerequisite courses taught by faculty whose research area is not ML (RNo, RName)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 14">
<div class="layoutArea">
<div class="column">
0 List the courses with &lt;30 registered students which are taught by faculty not belonging to the dept of the course (CId, CName, CDept,FId, FName, FDept)

1 List all the faculty, with MTECH, age &lt;30 who teach only 1 course and it has no prerequisite (FId, FName,Age, HighestQual, CId, CName)

2 List the faculties who teach at most one course offered by CSE or ME which have exactly one prerequisite and course duration is long. (FId, FName)

4 List the faculty who have courses in which there is at least one student who scored 100 and is below 20 years of age (FId, FName, CId, CName)

5 List the faculty who teach at least 2 courses which have at least two prerequisites courses in the same department as the faculty (FId, FName, FDept)

6 List the faculty who are MTECH and above, and teach at least two medium or longer courses (FId, FName, HighestQual)

7 List the CS faculties and the short courses taught by them such that the course has exactly two prerequisites (FId, FName, CId, CName)

9 List the faculty who are MTECH and above, and teach at least two medium or longer courses from the same department as the faculty (FId, FName, FDept, HighestQual)

</div>
</div>
<div class="layoutArea">
<div class="column">
SET L

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Srl No.

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Query

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Remarks (Output format)

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the ME faculty and their courses taught by them in the descending order of the number of registered students in those courses (CId, CName, FId, FName, NumRegStudent)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
For each department, list the faculties, their area of research and highest qualification, who teach at least two courses offered by either CS or EE department. (Dept, FId, FName, Area, HighestQual)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 15">
<div class="layoutArea">
<div class="column">
Srl Query

No.

<ol start="0">
<li>0 &nbsp;List the faculties and the courses taught by them which have at least one prerequisite (FId, FName, CId, CName)</li>
<li>1 &nbsp;List the CS faculties and the courses taught by them which have exactly one prerequisite (FId, FName, CId, CName)</li>
<li>2 &nbsp;List the CS faculties, having research area as AI or ML, and the courses taught by them which have no prerequisite (FId, FName, CId, CName)</li>
<li>3 &nbsp;List the EE faculties and the courses taught by them which have at least one prerequisite (FId, FName, CId, CName)</li>
<li>4 &nbsp;List the ECE faculties and the SHORT duration courses taught by them which have exactly one prerequisite (FId, FName, CId, CName)</li>
<li>5 &nbsp;List the ME faculties and the LONG duration courses taught by them which have more than one prerequisite (FId, FName, CId, CName)</li>
<li>6 &nbsp;List the CS faculties, having PHD as the highest qualification, and the courses taught by them which have no prerequisite (FId, FName, CId, CName)</li>
<li>7 &nbsp;List the CS faculties, having PHD as the highest qualification, and the courses taught by them which have more than one prerequisite (FId, FName, CId, CName)</li>
<li>8 &nbsp;List the CS faculties, having research area as DBMS, and the MEDIUM duration courses taught by them which have more than one prerequisite (FId, FName, CId, CName)</li>
<li>9 &nbsp;List the CS faculties, having research area NOT as ALGO, and the SHORT duration courses taught by them which have exactly one prerequisite (FId, FName, CId, CName)</li>
</ol>
</div>
<div class="column">
Remarks

</div>
</div>
<div class="layoutArea">
<div class="column">
SET M

</div>
</div>
</div>
<div class="page" title="Page 16">
<div class="layoutArea">
<div class="column">
Srl Query

No.

<ol start="0">
<li>0 &nbsp;List the courses and the highest marks scored for courses having at least 20 registrations and taught by CS faculty. (CId, CName, Score)</li>
<li>1 &nbsp;List the courses and the highest marks scored for LONG duration CS courses taught by ECE faculty. (CId, CName, Score)</li>
<li>2 &nbsp;List the courses and the highest marks scored for CS courses taught by a faculty having research area as ALGO. (CId, CName, Score)</li>
<li>3 &nbsp;List the courses and the highest marks scored for EE courses taught by a faculty having highest qualification as PHD. (CId, CName, Score)</li>
<li>4 &nbsp;List the courses and the highest marks scored for ECE courses taught by a EE faculty having highest qualification NOT as BTECH. (CId, CName, Score)</li>
<li>5 &nbsp;List the courses and the highest marks scored for CS courses taught by a faculty having research area as AI or ML. (CId, CName, Score)</li>
<li>6 &nbsp;List the courses and the highest marks scored for MEDIUM duration courses having at least 30 registrations and taught by a ECE faculty. (CId, CName, Score)</li>
<li>7 &nbsp;List the courses and the highest marks scored for LONG duration courses taught by a ECE faculty having highest qualification as PHD. (CId, CName, Score)</li>
<li>8 &nbsp;List the courses and the highest marks scored for LONG duration courses taught by a faculty not having same dept as the course. (CId, CName, Score)</li>
</ol>
</div>
<div class="column">
Remarks

</div>
</div>
<div class="layoutArea">
<div class="column">
SET N

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List the courses and the highest marks scored for MEDIUM duration courses having at least 30 registrations and taught by a faculty not having same dept as the course. (CId, CName, Score)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 17">
<div class="layoutArea">
<div class="column">
Srl Query

No.

<ol start="0">
<li>0 &nbsp;List the ratio of the two highest scores in each course of department CS (Highest score/Second highest score). Display as (CId, Cname, Ratio)</li>
<li>1 &nbsp;List the ratio of the two lowest scores in each course of department ECE (lowest score/Second lowest score). Display as (CId, Cname, Ratio)</li>
<li>2 &nbsp;List the ratio of the highest scores to the lowest score in each course of department EE (Highest score/lowest score). Display as (CId, CName, Ratio)</li>
<li>3 &nbsp;List the ratio of the two lowest scores in each course of LONG duration (lowest score/Second lowest score). Display as (CId, Cname, Ratio)</li>
<li>4 &nbsp;List the ratio of the two highest scores in each course of SHORT duration (Highest score/Second highest score). Display as (CId, Cname, Ratio)</li>
<li>5 &nbsp;List the ratio of the highest scores to the lowest score in each course of MEDIUM duration (Highest score/lowest score). Display as (CId, CName, Ratio)</li>
<li>6 &nbsp;List the ratio of the two highest scores in each course among HighestQual BTECH (Highest score/Second highest score). Display as (CId, Cname, Ratio)</li>
<li>7 &nbsp;List the ratio of the two lowest scores in each course among HighestQual MTECH (lowest score/Second lowest score). Display as (CId, Cname, Ratio)</li>
<li>8 &nbsp;List the ratio of the highest scores to the lowest score in each course among HighestQual PHD (Highest score/lowest score). Display as (CId, CName, Ratio)</li>
<li>9 &nbsp;List the ratio of the two lowest scores in each course (lowest score/Second lowest score). Display as (CId, Cname, Ratio)</li>
</ol>
</div>
<div class="column">
Remarks

</div>
</div>
<div class="layoutArea">
<div class="column">
SET O

</div>
</div>
</div>
<div class="page" title="Page 18">
<div class="layoutArea">
<div class="column">
SET P

</div>
</div>
<div class="layoutArea">
<div class="column">
Srl Query

No.

<ol start="0">
<li>0 &nbsp;Find the number of faculties who offer courses in more than three departments. (RName,FID)</li>
<li>1 &nbsp;List the names and Highest qualification of the faculties whose research area is Algo and they are from ECE dept.(Rname,FID, HighestQual)</li>
<li>2 &nbsp;Find the number of faculties from every dept whose research area is AI.(FDept, Number_value)</li>
<li>3 &nbsp;Find the number of students on the basis of each class of HighestQual. (HighestQual, Number_Value)</li>
</ol>
<ol start="6">
<li>6 &nbsp;Lists the top three student names with the ranks for every course offered along with the course names.(RName,Cname,Rank,Score)</li>
<li>7 &nbsp;List the course name, highest obtained score, mean score and standard deviation score for all courses. (CName, Highest_Score, Mean_Score, SD)</li>
<li>8 &nbsp;Find the Number of faculties from every dept whose research area is DBMS and age is more than 50.(FDept, Number_of_Faculty)</li>
<li>9 &nbsp;Find the number of students, faculties and staffs who have Phd as highest qualification. (Nimber_of_Student, Number_of_Faculty, Number_of_Staff)</li>
</ol>
</div>
<div class="column">
Remarks

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List those number of students who have taken course(s) from CS, ECE and EE depts such that their combined number of courses from CS and ECE depts is less than ECE. (Count value)

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Find the short term course names offered by EE dept which serves as prerequisites for long term courses from CS dept. List the course name pairs.(CName, CDuration, CDept_EE,CName,CDuration, CDept_CS)

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
