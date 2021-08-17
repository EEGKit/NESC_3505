# Syllabus
## NESC 3505: Neural Data Science
*Cross-Listed as PSYO 3505*

### Fall 2020, version 1.1, 2020-08-31
September 8 – December 8, 2020

### Instructor
[Dr. Aaron Newman](http://aaronjnewman.com) ([Aaron.Newman@dal.ca](mailto:Aaron.Newman@dal.ca))

#### Teaching Assistant
[Danny Godfrey](https://www.thecoast.ca/halifax/maturity-rules/Content?oid=4007362) (use Teams to contact the TA)

---
## Contents:
- [Course Description](#course-description)
- [Background & Rationale](#background-and-rationale)
- [Learning Objectives](#learning-objectives)
- [Format](#course-format)
- [Materials](#course-materials)
- [Assessment & Evaluation](#assessment-and-evaluation)
- [Grading](#grading)
- [Schedule](#schedule)
- [Policies](#policies)

---
## Recognition of Mi’kmaq Territory
Dalhousie University is located in Mi’kma’ki, the ancestral and unceded territory of the Mi’kmaq. We are all Treaty people. The Elders in Residence program provides students with access to First Nations elders for guidance, counsel and support. Visit the [Indigenous Student Centre](https://www.dal.ca/campus_life/communities/indigenous.html) or contact the programs at [elders@dal.ca](mailto:elders@dal.ca).

## Diversity and Inclusion – Culture of Respect
Every person at Dalhousie has a right to be respected and safe. We believe inclusiveness is fundamental to education. We stand for equality. Dalhousie is strengthened in our diversity. We are a respectful and inclusive community. We are committed to being a place where everyone feels welcome and supported, which is why our Strategic Direction prioritizes fostering a culture of diversity and inclusiveness. For more information please see [here](http://www.dal.ca/cultureofrespect.html).

---
# Course Description
An introduction to data management, manipulation, visualization, and analysis for neuroscience. Students will learn scientific programming in Python, and use this to work with example data from areas such as single-cell recording, EEG, and structural and functional MRI. Basic signal processing techniques including filtering will be covered.

## Prerequisites
**PSYO 2000**, **PSYO 2501**, and **NESC 2470**, with a minimum grade of B in PSYO 2501. Grades of B+ or better in all three classes are recommended. **No prior programming experience is required**.

# Background and Rationale
Most areas of neuroscience research and development rely on increasingly large and complex data sets. Discovery and application in neuroscience thus relies on the ability to manage these large data sets, and extract meaning from them. In other words, neuroscience now relies heavily on **data science**, which has been variously defined as “…an umbrella term to describe the entire complex and multistep processes used to extract value from data.” (Wing, 2019) and the ability to “bring structure to large quantities of formless data and make analysis possible” (Davenport & Patil, 2012, p.73).

**In neuroscience, data science is an increasingly necessary skill.** Data from techniques like single-cell recordings, local field potentials, EEG, and fMRI is complex and multidimensional. Being able to understand, manipulate, and visualize the structure of these complex datasets is a necessary skill for performing the research. On top of this, it is increasingly clear that very large data sets - often built collaboratively by many labs - are required to make reliable inferences about neuroscientific processes. Making inferences also depends on computational models - ways of identifying and representing patterns in the data. While some of these will be familiar from statistics class, a wide range of statistical and machine learning models are now widely used in neuroscience.

While data science and statistics are overlapping fields, statistics is generally focused on the specific task of testing hypotheses based on data. Data science more broadly includes the storage, manipulation, visualization, filtering, and preparation of data that is typically required prior to statistical analysis. Data science does also encompass statistics, as well as machine learning; whereas statistics generally involves deriving conclusions from existing data, machine learning involves making predictions from a data set that will generalize to other data. Since statistics is covered in other courses in the neuroscience and psychology curricula, this course focuses instead on the other “front-end” aspects of data science described above. Other areas of data science, including “back-end” data science (engineering, hardware, databases) and software development, will not be covered.

Central to data science is the ability to use scientific programming languages, such as Python, Matlab, and R. This ability includes a strong understanding of the fundamentals of at least one programming language, and the ability to extend one’s knowledge through continuous learning and problem-solving. This course teaches Python, a mature and widely-used language in neuroscience and data science more broadly. However, much of the fundamentals of scientific programming and data science are common to all languages. Thus, having learned Python, you will be better prepared to learn new languages in the future, as necessary.

Another important facet of data science is that it is a **team endeavour**. On the one hand, it is founded on open, shared software developed by widely distributed teams of contributors. On the other hand, the practice of data science typically involves teams of individuals with complementary skillsets, both due to the size and complexity of many projects. In science, these teams often comprise students and faculty members in collaborating labs distributed around the world. This class prepares you for such collaboration by developing and coaching your teamwork skills, as well as teaching you how to use software platforms that support such collaboration.

The skills learned in this class will benefit students working in a wide variety of areas of neuroscience. As well, the class will provide an introductory foundation in data science that can be applied to a wide range of areas of research and application, in academia, industry, and government.

#### References:
Davenport, T. H., & Patil, D. J. (2012). Data scientist. *Harvard Business Review*, 90(5), 70-76

Irizarry, R. A. (2020). The role of academia in data science education. *Harvard Data Science Review*, 2(1). https://doi.org/10.1162/99608f92.dd363929

Wing, J. M. (2019). The data life cycle. *Harvard Data Science Review*. https://doi.org/10.1162/99608f92.e26845b4

# Learning Objectives
## Hard Skills
- Extract meaning from data, but also articulate the limitations of the conclusions you can draw from it
- Write functional and efficient code in Python to perform basic data science tasks
- Use online tools for collaborative software development and project management
- Read and write data files in common formats such as CSV and Excel
- Organize and manipulate data structures
- Work with continuous, discrete, and factorial data
- Visualize data in a variety of graphical formats
- Perform exploratory data analysis using graphical and basic statistical operations
- Perform basic signal processing on data, such as filtering in temporal and spatial dimensions
- Build and run data processing pipelines on various types of neuroscientific data, including single unit recordings, time series, and 2D/3D/4D images
- Understand basic concepts and common tools used in machine learning, including deep neural networks
- Extend your skills using online resources

## Soft Skills
- Demonstrate a professional work ethic
- Be effective and productive in a remote working environment
- Work collaboratively, effectively, and productively in a distributed team
- Manage projects: manage time and human resources effectively to achieve specific objectives on a stated timeline
- Peer-review the work of other team members
- Teach others skills and solutions you discover, and communicate your approach to discovering these
- Articulate your strengths and weaknesses as a data scientist working in a team, and identify ways to improve your abilities
- Demonstrate skills you have developed using a portfolio of work, to potential supervisors/employers
- Use, and communicate the value of, open and reproducible code and data

# Course Format
This course consists of the following components:
- [Freely-accessible online textbook](https://dalpsychneuro.github.io/NESC_3505_textbook/)
- Asynchronous online lectures, lessons, and tutorials
- Optional, synchronous (scheduled/live) check-ins to get guidance from the teaching team

The "home base" for this class will be a [Microsoft Teams](https://dalpsychneuro.github.io/NESC_3505_textbook/2/teams.html) site hosted through Dalhousie University. Registered students will receive an invitation to this site via their Dal.ca email. The Teams site will contain links to all course materials, as well as hosting text messaging and video/audio chat meetings. **The Teams site will be the primary source for course-related announcements, and the official source for assignment due dates.**

## Online Lectures and Tutorials
This course employs a “flipped classroom” model. Lectures and tutorials are available in the [online textbook](https://dalpsychneuro.github.io/NESC_3505_textbook/) and/or as pre-recorded videos, available online for viewing at any time. Many of these lessons involve quizzes and coding activities. **This course requires that you put in significant hours per week outside of class: at the outset, you should budget 18 h/week for a 7-week condensed summer version of the course, or 9 h/week for the regular term version.**

## Check-Ins
**Participation in live check-ins is entirely optional**. We recognize that online delivery presents opportunities and challenges around scheduling. However, check-ins are the primary time when the teaching team are available for consultation. You may post questions on the class Teams site outside of check-in times, but there is no guaranteed response time prior to the next check-in (we will do what we can, but have other demands on our time).

The timing of check-ins will be determined in consultation with registered students. We will aim to be as inclusive as possible in scheduling check-ins.

## Getting Help
One of the course learning objectives is "Extend your skills using online resources", and the course is based on the learning theory of [connectivism](https://dalpsychneuro.github.io/NESC_3505_textbook/1/connectivism.html). You are encouraged and supported in taking a *lifelong learning* approach to solving problems in this course. Many of the evaluations expect you to engage in this; you will not find all the answers in the textbook.

That said, learning can sometimes go a lot faster when you ask questions. We encourage you to ask questions of your peers in the class, and of the teaching team — in that order. Peer teaching is built into the class through collaboration tools, demos, and team projects. This is the way real, functional teams operate — supporting each other to achieve more.

The course Teams site is where you should direct all your questions (after making your own attempts to research and solve your problem). This can include posting questions in the messaging forums, or joining live check-ins to ask questions. Please do not email the teaching team with questions about the class — use the Teams site. Do feel free to email the instructor if you have personal topics that you need to discuss privately, or you can use directmessaging on Teams.

# Course Materials
All necessary materials will be provided online, through the course Teams site. **You must have access to a computer** running a recent version of the Mac, Windows, Chrome, or Linux operating systems. It may be possible to complete this course, including programming assignments, using an iPad, but this has not been verified. It is not a good idea to expect to be able to complete the course using only a mobile device (phone or tablet).

**You must also have access to internet service** of sufficient quality to stream videos and maintain a live connection to remote servers. Provisions will be made if students cannot participate in live audio/video sessions due to internet constraints; please contact the instructor to discuss if this is an issue for you.

Beyond these basic requirements, this course emphasizes (and will teach you about) openly accessible resources including the software that runs the course, open access to the course materials, and the use of external resources that are available for free. No textbook is required. This course will rely on [Open Educational Resources](https://dalpsychneuro.github.io/NESC_3505_textbook/1/oer_this_course.html) — materials that are freely accessible and openly licensed — including online tutorials, videos, and books. A wide variety of educational materials (free and paid) for data science are available, and this course teaches an approach to lifelong learning and exploration by which you will be able to find and critically evaluate the information necessary to perform desired tasks.

# Assessment and Evaluation
Your final grade will be based on a combination of [*formative assessments*](https://dalpsychneuro.github.io/NESC_3505_textbook/1/assessment_evaluation.html) (self and peer evaluations) and [*summative evaluations*](https://dalpsychneuro.github.io/NESC_3505_textbook/1/assessment_evaluation.html) (presentations, assignments, projects). Each component is described below, followed by a table showing the number and point weighting of each.

Due dates for all assessment and evaluation components will be posted on Teams.

## Formative Assessments
Formative assessments are designed to support you in improving your performance in the class, through self-assessment, peer assessment, and instructor feedback. These are designed to require little time to complete. They contribute a smaller proportion of your grade than evaluations (approximately 20%), but collectively can make a significant difference in your grade.

### Online Lessons
Online lessons are to be completed prior to class time. Deadlines are provided online. Each lesson is graded on a pass/fail basis, based on whether you complete the lesson or not. Lessons can be completed later than the posted due date, up to the last day of class, with no penalty. However, not completing lessons by the posted due dates will leave you unprepared for future classes and assignments. No points for lessons will be granted after the last day of class.

### Self-Assessments
You will submit regular written assessments of your own learning progress over the term. Each should be 250-500 words in length. **Late work will be penalized 2% per hour**, with the clock starting the minute after the deadline has elapsed. Self-assessments are only helpful if they're done regularly, and in this class they are timed to synch up with your work in other aspects of the course.

### Demo Peer Assessments
You will provide a constructive review of demos produced by other students in the class. This will be done using a rubric with four components: quality of presentation, quality of work, relevance/usefulness of topic, and creativity. You will also have the option to provide specific, written feedback if you wish. The aim of these assessments is to help your fellow students make better demos (which will in turn benefit you and the rest of the class). Peer assessments are due within 1 week of the demo's being posted (so, 1 week after the demo day that it's submitted for). **Late peer assessments will be penalized 2% per hour**, with the clock starting the minute after the deadline has elapsed. Since your feedback is intended to help improve the quality of demos, it's not useful if it's not timely.

### Portfolio Peer Assessment
You will provide constructive reviews of other students' first-draft portfolios. This has two purposes. One is to get feedback from classmates on your work. The other is for you to get a sense of how other people developed their portfolio, which may provide you with inspiration for your final version. Grading will be according to a rubric with five components: quantity of samples; breadth; quality of work; quality of presentation; and organization. The peer assessments you receive will not affect your portfolio grade, but are meant only as constructive feedback for you.

### Meet 'n Greets
You will earn bonus points by participating in short (5-10 min) online one-on-one meetings with other class members. These are scheduled by students at your mutual convenience, and can take the form of a text-based chat or a video chat. The purpose of these is to allow for the kinds of casual interactions you might normally have with others in a face-to-face class, and allow you to get to know people as potential team members for projects. To protect everyone's safety, all students have the ability to block others anonymously, and may discontinue a meeting at any time without penalty. All students are expected to abide by [Dalhousie University's Code of Student Conduct](https://www.dal.ca/dept/university_secretariat/policies/student-life/code-of-student-conduct.html), and violations will be addressed through the procedures described there. Please report any inappropriate behaviour to the instructor immediately. You will be heard, and you will be respected.

Meet 'n greets should ideally occur early in the course. Three of these are required, and an additional three can be done for bonus points. The required meet 'n greets should be completed by the end of the second week of class (7 week summer course), or by the end of the first month of class (12 week course).


## Summative Evaluations
Summative evaluations comprise the majority of your final grade (approximately 80%). All summative evaluations are graded. Because 20% of your final grade (the formative assessments) are "easy" pass/fail points, you can expect that grading of the summative evaluations will be quite strict.

For all summative evaluations, **late work will be penalized 2% per hour**, with the clock starting the minute after the deadline has elapsed. **Requests for extensions will only be considered prior to the due date**.

### Assignments
These are coding assignments that you will complete, based on neuroscience data. There is an assignment due every week, except weeks when projects are due. Scheduled class time is the only time you will be able to get help on the assignments from the teaching team. There will be 6 assignments over the term. You must submit a minimum of 4 of these, but bonus points will be awarded for submitting 5 or 6.

### Projects
There are 2 [team-based](https://dalpsychneuro.github.io/NESC_3505_textbook/1/teamwork.html) projects to complete. These projects are directly based on the class assignments, but integrate across multiple classes and assignments, as well as requiring you to extend and apply what you have learned, to new contexts.

### Project Peer Assessments
You will be asked to submit structured peer reviews following each of the two team projects. This will be done using a rubric with five components: participation, preparation, communication, collaboration, and academic quality. Your grade will be the average of the ratings assigned to you by your team members. **Late peer assessments will be penalized 2% per hour**, with the clock starting the minute after the deadline has elapsed.

### Demos
Based on workflows in Silicon Valley and the tech industry more generally, the idea of Demos is that you can learn a lot from each other — and often, your classmates (who are in the same "boat" as you in terms of learning) can have more sensitivity and shared experience in the learning process than the teaching team. Demos are short demonstrations that you prepare to teach your fellow students. They can be videos (1-3 min) or written (500-1000 words). The goal is to share some insight or discovery with other students. This could be how you approached and solved some problem in an assignment, a review of a website, or a good YouTube tutorial, an interesting interview with a data scientist or neuroscientist talking about data science; other resources you found helpful for the class, etc..

Grading (by the teaching team) will be based on a rubric with four components: *quality of presentation*, *quality of work*, *relevance/usefulness of topic*, and *creativity*. In addition, demos can be peer-reviewed (see [Formative Assessments](#demo-peer-assessments), above) based on the same criteria. Note that only three demos are required; you may submit up to four more demos for bonus points.

At the end of every week (7-week course) or two weeks (12-week course) there will be a scheduled, synchronous "Demo Day". You are not required to attend Demo Days synchronously, but they are an opportunity to share and showcase work, ask questions, and generally discuss the demos and course material. Demo days also serve as the deadline for submitting each demo.

### Portfolio
One of the outcomes of this class is that you will have a portfolio demonstrating your work, that you could show to a potential employer or graduate supervisor. Building this will mostly happen in the context of your completing the course work (demos, projects, and assignments). Assembling your portfolio simply means selecting what you feel best represents your work, and putting a bit of "packaging" around it. You will submit a first version midway through the course for feedback, and then a final version at the end of term. Grading will be according to a rubric with five components: quantity of samples; breadth; quality of work; quality of presentation; and organization. The detailed rubric is provided on the Teams site, as well as a collection of videos with advice on how to create and format your portfolio online.

# Grading
This course follows the Dalhousie grading scale, but in a different way than you are probably used to. Borrowing the model of role-playing games (RPGs), you accumulate [experience points (XP)](https://dalpsychneuro.github.io/NESC_3505_textbook/1/assessment_evaluation.html#everyone-starts-with-an-f) by completing the assessments and evaluations listed above. Formative assessments are pass/fail, so you get the full XP for completing them. Summative evaluations are graded, so the XP you receive will be in proportion to your grade (e.g., if you get 70% on an assignment, you get 70% of the XP that the assignment is worth). Like RPGs, your XP determine your level in the course, according to the table below. Your level at the end of the course determines your final grade.

| Level | XP     | letter grade |
|-------|--------|--------------|
| 1     | 100    |              |
| 2     | 400    |              |
| 3     | 900    |              |
| 4     | 1,600  |              |
| 5     | 2,500  |              |
| 6     | 3,600  |              |
| 7     | 4,900  |              |
| 8     | 6,400  |              |
| 9     | 8,100  |              |
| 10    | 10,000 |              |
| 11    | 12,100 | D            |
| 12    | 14,400 | C-           |
| 13    | 16,900 | C            |
| 14    | 19,600 | C+           |
| 15    | 22,500 | B-           |
| 16    | 25,600 | B            |
| 17    | 28,900 | B+           |
| 18    | 32,400 | A-           |
| 19    | 36,100 | A            |
| 20    | 40,000 | A+           |

While on the one hand this might sound a bit gimmicky, it's actually a really powerful re-framing of the concepts of assessment and evaluation in a course. This framing also makes assessment more authentic, in the sense that you are receiving credit for achieving specific, meaningful learning outcomes. It also recognizes that throughout the course, you are continuously building knowledge, experience, and skills.

The XP system is also built to be inclusive and adaptive to the need and life circumstances of individual students. While some assessments are not accepted after the due date, and some evaluations have late penalties, we recognize that missed or late assignments sometimes happen for excusable reasons. Rather than making a big deal about your proving to us that your reason is legitimate, we instead provide options for you to make up lost points in other ways. This also allows you to compensate for getting a lower grade on an assessment(s) than desired.

Because there are a variety of bonus points on offer, there are actually more opportunities to earn XP than you need to get an A+ in the course. This means that you can, within reason, pick and choose how to achieve your desired grade. All that said, XP (and your grade) are intended to reflect the degree to which you have met the learning objectives, so you do need to demonstrate competence with regard to all of the objectives.

## How to Earn XP
The table below lists all the "core" and "bonus" opportunities to earn course XP.

| **Summative Evaluations (graded)**    | XP     | Bonus XP | Notes                      |
|---------------------------------------|--------|----------|----------------------------|
| *Assignments*                         |        |          |                            |
| Assignment 1                          | 700    |          |                            |
| Assignments 2-6, 2nd best             | 3000   |          |                            |
| Assignments 2-6, 3rd best             | 3000   |          |                            |
| Assignments 2-6, 4th best             | 3000   |          |                            |
| Assignments 2-6, 5th best             |        | 1000     |                            |
| Assignments 2-6, 6th best             |        | 1000     |                            |
| *Projects*                            |        |          |                            |
| Project 1                             | 6000   |          |                            |
| Project 2                             | 8000   |          |                            |
| *Demos*                               |        |          |                            |
| Demo (best mark)                      | 1500   |          |                            |
| Demo (2nd best mark)                  | 1500   |          |                            |
| Demo 3rd best mark                    | 1500   |          |                            |
| Demo 4th best mark                    |        | 500      |                            |
| Demo 5th best mark                    |        | 500      |                            |
| Demo 6th best mark                    |        | 500      |                            |
| *Portfolio*                           |        |          |                            |
| Portfolio submission 1                | 500    |          |                            |
| Portfolio submission 2                | 3500   |          |                            |
| **Formative Assessments (Pass/Fail)** |        |          |                            |
| *Datacamp lessons*                    | 5000   |          | (DataCamp XP/10; max 5000) |
| *Peer Assessments*                    |        |          |                            |
| Demos: 1st peer assessment            | 100    |          |                            |
| Demos: 2nd peer assessment            | 100    |          |                            |
| Demos: 3rd peer assessment            | 100    |          |                            |
| Demos: 4th peer assessment            |        | 100      |                            |
| Demos: 5th peer assessment            |        | 100      |                            |
| Demos: 6th peer assessment            |        | 100      |                            |
| Project 1 peer assessment             | 500    |          |                            |
| Project 2 peer asessment              | 500    |          |                            |
| Portfolio v1 peer assessment          | 150    |          |                            |
| Complete all Peer Assessments         |        | 400      |                            |
| *Self-Assessments*                    |        |          |                            |
| Self-assessment 1                     | 150    |          |                            |
| Self-assessment 2                     | 150    |          |                            |
| Self-assessment 3                     | 150    |          |                            |
| Self-assessment 4                     | 150    |          |                            |
| Self-assessment 5                     | 150    |          |                            |
| Self-assessment 6                     | 150    |          |                            |
| Self-assessment 7                     | 150    |          |                            |
| Complete all self-assessments         |        | 400      |                            |
| *Meet 'n Greets*                      |        |          |                            |
| Meet 'n Greet 1                       | 100    |          |                            |
| Meet 'n Greet 2                       | 100    |          |                            |
| Meet 'n Greet 3                       | 100    |          |                            |
| Meet 'n Greet 4                       |        | 100      |                            |
| Meet 'n Greet 5                       |        | 100      |                            |
| Meet 'n Greet 6                       |        | 100      |                            |
| *Other Bonus Points*                  |        |          |                            |
| Did not ask for extension bonus       |        | 200      |                            |
| Project 1 team size > 3 people        |        | 200      |                            |
| Project 2 team size > 3 people        |        | 200      |                            |
| Typo reports                          |        | 250      | 50 ea, 5 max               |
| **Totals**                            | 40,000 | 5,750    |                            |

That's a lot of ways to earn points! The table below summarizes how the points add up:

|                                      | XP    | % of A+ Grade |
|--------------------------------------|-------|---------------|
| Graded (summative evaluation) total  | 32200 | 83.0%         |
| Pass/Fail (formative assessment)     | 7800  | 17.0%         |
| Bonus graded total                   | 3500  |  8.8%         |
| Bonus P/F total                      | 2250  |  5.6%         |

# Schedule

[Click here to see the schedule](https://dalpsychneuro.github.io/NESC_3505/schedule.html).

# Policies
This course is governed by the academic rules and regulations set forth in the University Calendar and by Senate.

## Attendance
Attendance of scheduled class meetings is optional. However, due to the flipped classroom model, scheduled class times are the only time when you can get live help with the course material. However, if you have other issues you need to discuss (e.g., personal reasons that make it difficult for you to succeed in the class), you may contact the instructor by email to discuss the matter and/or set up a meeting.

## Academic Freedom
Freedom of speech and of thought are cornerstones of academic institutions such as Dalhousie. Our goal in science is to observe and characterize the world accurately and objectively. However, we must realize that our perceptions of reality are often coloured by our beliefs and assumptions, some of which we may not be aware of. Academic freedom includes not only the freedom to think as you please, but others’ freedom to express their beliefs as well. Please do not hesitate to express your ideas, but do so in a way that is respectful of others. This is the only avenue for the free expression and exchange of ideas.

## Academic Integrity
At Dalhousie University, we are guided in all of our work by the values of academic integrity: honesty, trust, fairness, responsibility and respect (The Center for Academic Integrity, Duke University, 1999). As a student, you are required to demonstrate these values in all of the work you do. The University provides policies and procedures that every member of the university community is required to follow to ensure academic integrity. For more details please see: [https://www.dal.ca/dept/university\_secretariat/academic-integrity.html](https://www.dal.ca/dept/university\_secretariat/academic-integrity.html)  

## Accessibility
The Advising and Access Services Centre is Dalhousie's centre of expertise for student accessibility and accommodation. The advising team works with students who request accommodation as a result of a disability, religious obligation, or any barrier related to any other characteristic protected under Human Rights legislation (Canada and Nova Scotia).
Information: [https://www.dal.ca/campus\_life/academic-support/accessibility.html](https://www.dal.ca/campus\_life/academic-support/accessibility.html)

## Code of Student Conduct
Everyone at Dalhousie is expected to treat others with dignity and respect. The Code of Student Conduct allows Dalhousie to take disciplinary action if students don’t follow this community expectation. When appropriate, violations of the code can be resolved in a reasonable and informal manner—perhaps through a restorative justice process. If an informal resolution can’t be reached, or would be inappropriate, procedures exist for formal dispute resolution. For more information please see [https://www.dal.ca/campus\_life/safety-respect/student-rights-and-responsibilities/student-lifepolicies/code-of-student-conduct.html](https://www.dal.ca/campus\_life/safety-respect/student-rights-and-responsibilities/student-lifepolicies/code-of-student-conduct.html)

## Important Dates in the Academic Year (including add/drop dates)
[https://www.dal.ca/academics/important\_dates.html](https://www.dal.ca/academics/important\_dates.html)

## University Grading Practices
[https://www.dal.ca/dept/university\_secretariat/policies/academic/grading-practices-policy.html](https://www.dal.ca/dept/university\_secretariat/policies/academic/grading-practices-policy.html)

## Missed or Late Academic Requirements due to Student Absence (policy)
[https://www.dal.ca/dept/university_secretariat/policies/academic/missed-or-late-academic-requirements-due-to-student-absence.html](https://www.dal.ca/dept/university_secretariat/policies/academic/missed-or-late-academic-requirements-due-to-student-absence.html)

## Learning and Support Resources

### Advising
General Advising: [https://www.dal.ca/campus\_life/academic-support/advising.html](https://www.dal.ca/campus\_life/academic-support/advising.html)

Science Program Advisors: [https://www.dal.ca/faculty/science/current-students/academic-advising.html](https://www.dal.ca/faculty/science/current-students/academic-advising.html)

Indigenous Student Centre: [https://www.dal.ca/campus\_life/communities/indigenous.html](https://www.dal.ca/campus\_life/communities/indigenous.html)

Black Students Advising Centre: [https://www.dal.ca/campus\_life/communities/black-student-advising.html](https://www.dal.ca/campus\_life/communities/black-student-advising.html)

International Centre: [https://www.dal.ca/campus\_life/international-centre/current-students.html](https://www.dal.ca/campus\_life/international-centre/current-students.html)

### Academic supports
Library: [https://libraries.dal.ca](https://libraries.dal.ca)  

Writing Centre: [https://www.dal.ca/campus\_life/academic-support/writing-and-study-skills.html](https://www.dal.ca/campus\_life/academic-support/writing-and-study-skills.html)

Studying for Success: [https://www.dal.ca/campus\_life/academic-support/study-skills-and-tutoring.html](https://www.dal.ca/campus\_life/academic-support/study-skills-and-tutoring.html)

Copyright Office: [https://libraries.dal.ca/services/copyright-office.html](https://libraries.dal.ca/services/copyright-office.html)  

Fair Dealing Guidelines: [https://libraries.dal.ca/services/copyright-office/fair-dealing.html](https://libraries.dal.ca/services/copyright-office/fair-dealing.html)

### Other supports and services
Student Health & Wellness Centre: [https://www.dal.ca/campus\_life/health-and-wellness/servicessupport/student-health-and-wellness.html](https://www.dal.ca/campus\_life/health-and-wellness/servicessupport/student-health-and-wellness.html)

Student Advocacy: [https://dsu.ca/dsas](https://dsu.ca/dsas)

Ombudsperson: [https://www.dal.ca/campus\_life/safety-respect/student-rights-and-responsibilities/where-to-get-help/ombudsperson.html](https://www.dal.ca/campus\_life/safety-respect/student-rights-and-responsibilities/where-to-get-help/ombudsperson.html)

### Safety
Biosafety: [https://www.dal.ca/dept/safety/programs-services/biosafety.html](https://www.dal.ca/dept/safety/programs-services/biosafety.html)

Chemical Safety: [https://www.dal.ca/dept/safety/programs-services/chemical-safety.html](https://www.dal.ca/dept/safety/programs-services/chemical-safety.html)

Radiation Safety: [https://www.dal.ca/dept/safety/programs-services/radiation-safety.html](https://www.dal.ca/dept/safety/programs-services/radiation-safety.html)

Scent-Free Program: [https://www.dal.ca/dept/safety/programs-services/occupational-safety/scent-free.html](https://www.dal.ca/dept/safety/programs-services/occupational-safety/scent-free.html)
