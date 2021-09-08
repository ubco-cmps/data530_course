![](../images/header.jpg)

![](../images/UBCO_CMPS_header.jpg)

# Unsyllabus

## Important Details

| Name              | Description                                                                                                                                        |
|-------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
| Course            | {{ COURSE_CODE }}                                                                                                                                  |
| Term              | {{ TERM }}                                                                                                                                         |
| Instructor        | {{ INSTRUCTOR }}                                                                                                                                   |
| Lectures          | {{ MEETING_TIMES }}: {{ ROOM }}                                                                                                                    |
| Labs              | {{ LAB_TIMES }}: {{ ROOM }}
| Student Hours     | To get live 1 on 1 help in the course, use {{ ZOOM_LINK.replace('CANVAS_ID',CANVAS_ID) }} at various times (see below for schedule).               |
| Canvas URL        | {{ CANVAS_LINK.replace('CANVAS_ID',CANVAS_ID) }}                                                                                                   |
| Course Discussion | To ask any course-related questions, use private (personal, not useful for anyone else) or public (helpful for other) messages on {{ FORUM_LINK }} |

### What do I need to purchase for this course?

Being very conscious of the high tuition and technology costs, we have made efforts to remove the additional cost of taking this course.
All course content, references, and resources provided in this course are free and open source, and can be considered open educational resources (OER).

## Contact Us

```{include} syllabus_bits/teaching_team.md
```

## Evaluation

```{include} syllabus_bits/grading_practices_detailed.md
```

## Passing requirements

```{include} syllabus_bits/passing_requirement.md
```

## Schedule

```{include} syllabus_bits/course_schedule.md
```

The best way to get personalized help in this course is to attend the labs and student hours we have scheduled for this course.
They are all done on Zoom and this is time the TAs have set aside to help you!
You may also use this time to talk to us about anything else related to data science as well.
We would love to hear about you, what your interests are, and if you need any career advice. 

A few other notes:

- We will be using {{ FORUM_LINK }} for Announcements in this course.
- For **all** course-related questions you can reach out to the teaching team including instructors and TAs via {{ FORUM_LINK }}.
- You are encouraged to post questions publicly whenever possible so others can benefit. For private and personal issues, you can send private messages on {{ FORUM_LINK }}.
- Any student may visit the student hour for any member of the teaching team (TA or instructor)! In other words, you can go to the student hour of ANY TA, not just the one whose lab/tutorial you are registered in. 

<!--
### Why should I take {{ COURSE_CODE }}?

```{include} syllabus_bits/course_teaser.md
```
-->

## Unsyllabus changes

In this section, I will outline any changes that have been made to the unsyllabus as we go through the course.
We will do our best to follow the plan outlined in this unsyllabus, but in case things go south, I will need to make adjustments to the contents and the schedule.

Any major changes to the syllabus (this page) will be documented here, as well as the date the change was made. 

| Change Date | Summary | Rationale |
|-------------|---------|-----------|
| N/A         | N/A     | N/A       |
|             |         |           |

## Link your Canvas account to Gradescope

You should then be guided through a series of steps to create an account, set a password, and link it to our course. 

On the left sidebar in Canvas, click on Gradescope.
<img src="../images/GradescopeAccount.gif">

This is **very** important for you to do as it'll be our primary mechanism for delivering you feedback in this course.

## Teaching Philosophy

For a detailed description of my teaching philosophy and values (including a list of references and citations), you can [read it here](https://firas.moosvi.com/cv/teaching-philosophy/).
Here are the key principles I intend to apply in this class:

1. Student learning is vastly improved through active learning
1. Learning technologies must be leveraged to scale instructor effort across multiple classes.
1. Inter-disciplinarity is the future of education.
1. Effective teaching is inclusive teaching.

### How will this course be taught ?

This course will be taught as a [Blended Learning classroom](https://en.wikipedia.org/wiki/Blended_learning) where some elements of a [flipped classroom](https://www.youtube-nocookie.com/embed/BCIxikOq73Q) will be mixed with a more traditional coding classroom with live demos, clicker questions, and worksheets.
Briefly, this requires students to watch videos and engage with the assigned reading prior to the classroom meeting (knowledge transfer).
During the class meeting, the instructor guides students through clicker questions, worksheet problems, and other activities to help the students make sense of the material (sense-making).
See {numref}`masterymodel1` for a mental model of how learning works {cite}`Ambrose2010`.

```{figure} ../images/masterymodel1.png
---
width: 750px
name: masterymodel1
---
To develop mastery in a concept, students must first acquire the necessary skills, then practice integrating them, and finally know when to apply what they have learned. This figure was adapted from Figure 4.1 of the book "How Learning Works".
The terms "knowledge transfer" and "sense-making" applied in this context is generally attributed to [Dr. Eric Mazur](https://mazur.harvard.edu/files/mazur/files/flip_your_course_online_07.pdf). 
```

### What does this mean in practical terms? 

{numref}`masterymodel2` shows a handy table to help guide you and organize your learning in this course: 

```{figure} ../images/masterymodel2.png
---
height: 500px
name: masterymodel2
---
This table describes how I think each course activity should be classified between knowledge transfer and sense-making.
```

## Academic Integrity

### How do I go through this course with integrity?

I want to be proud of your work in this course, and I want YOU to be proud of yourself as well!
That cannot happen if you make unethical decisions, including (but not limited) to cheating or plagiarism.
According to the scientific literature, the most common reasons students cheat are:

- Fear of failure and life consequences
- Peer pressure, including an inability to say no to help others cheat
- Perceived societal acceptance of cheating (Lance Armstrong, Barry Bonds, Enron, Wall Street & the The Big Short)
- Desire for success without the time/desire to put in the work needed
- Strict deadlines and due-dates
- Requirement from instructors to memorize facts, figures, equations, etc...
- High-stakes exams with no recompense for "having a bad day"
- Peers cheating with no consequences or penalties
- Unclear expectations on what constitutes academic dishonesty
- Inadequate support from instructor and teaching team

Though I sympathize with students and the stresses of your busy lives - in my opinion, there is no good reason to cheat.
I have tried extremely hard to make this course focused on learning rather than grading, and where grading is needed, to have policies that are as student-friendly as possible.
In particular, I hope (and expect) that the following features of the course should eliminate your temptation to cheat or plagiarize:

- {{ GRACE_PERIOD }} grace-period on all due dates and deadlines.
- Long testing window so you can start the tests whenever you're comfortable.
- Weekly learning logs, homework and reading reflections to make you think about your learning ([metacognition](https://cft.vanderbilt.edu/guides-sub-pages/metacognition/)).
- Each test has a "bonus test" available one week later; for each test, we will take the better score of the pair.
- No high-stakes exams (the single largest assessment item is the final exam).
- All course assessments are completely open book, open notes, and open web (except for cheating websites like Chegg, CourseHero, Slader, Bartleby, etc...)
- Plenty of TA and instructor student hours and several outside of normal business hours.
- Class website that outlines exactly what you should do when to help you manage your time.
- Tonnes of supplemental materials including other instructional videos in case you want a different perspective.
- Weekly prompt to accept the integrity pledge to keep you accountable.
- A true willingness from the instructor (me) to help you learn and succeed in this course!

With these features, and several other little things, I sincerely hope that you will consider completing this course with maximum integrity so that you never have to feel guilty, ashamed, or disappointed in yourself and your actions!

A more detailed description of academic integrity, including the University’s policies and procedures, may be found in the [Academic Calendar](https://calendar.ubc.ca/vancouver/index.cfm?tree=3,54,111,0).

### What is considered academic dishonesty in this course?

To make it even easier for you to decide what isn't allowed, below is a list of things that I **definitely** consider to be academic dishonesty:

- Asking others for their work in the course (whether question by question, or all at once)
- Sending others your work in the course
- Doing tests collaboratively (tests **must** be done by yourself and alone)
- Sending others your test questions and/or answers
- Sharing any course material onto Chegg, Course Hero, Slader, or other similar sites
- Searching for solutions to course material on Chegg, Course Hero, Slader, or other similar sites
- Blindly googling the question in hopes of finding someone who had a similar question and then copying their answer
    - Note, googling to find resources to understand specific concepts or general ideas is highly encouraged!
- Having a tutor/friend/nemesis complete and submit your work for you
- Copying and pasting code, equations, text explanations, prose, etc... without attribution
- Manipulating the learning platforms we use to reverse engineer the randomization algorithms, hacking the timer functionality, or other similar technical [malfeasance](https://dictionary.cambridge.org/dictionary/english/malfeasance).

## Course Accommodations

### What if I miss labs, tests, or the exam due to an illness, health, or other personal situations?

Normally, most deadlines in this course have a generous grace period.
If you require an extension beyond the grace period, please contact the instructor on {{ FORUM_LINK }} (ideally before the deadline passes) to discuss your options.

Students who, because of unforeseen events, are absent during the term and are unable to complete tests or other graded work, should normally discuss with their instructors how they can make up for missed work.
If ill health is an issue, students are encouraged to seek attention from a health professional.
Campus Health and Counselling will normally provide documentation only to students who have been seen previously at these offices for treatment or counselling specific to conditions associated with their academic difficulties.

```{tip}
If you miss a course component due to an illness, health, or other personal situation, please reach out to me as soon as you are comfortable, and I'll work with you to get you back on track.
```

### What if I have dependents that rely on me for care and unpredictable emergencies may arise?

Let's talk, send me a private message and we can discuss it.
I do not necessarily need to know all the personal details, just a high-level summary of your situation and what you think an ideal solution would be.

I'm sure we will come to some agreement, generally the earlier you let me know of any special circumstances or accommodation, the more I'll be able to do for you!

### What if I have to miss a deadline because of a wedding, birthday, funeral, religious holiday, or personal event ?

No problem! There's not even any need to tell me, or ask for permission to miss deadlines.
The course is designed to give you maximum flexibility: 

- Every deadline has a {{ GRACE_PERIOD }} grace period that is automatically applied.
- There is no late penalty if you use the grace period
- You can use the grace period an unlimited amount of time in the course (though if it happens every week and for every assignment, I might check in with you and gently encourage you not to leave things to the last minute)

If you miss a deadline by more than the grace period, the general course policy is that you will not be able to get full credit for it, and in many cases, may even get a 0 for it.
In the cases of Tests, it is not possible to get partial credit, or complete it at times other than within the scheduled windows.
In some cases, I reserve the right to grant an extension or make alternate accommodations as needed.

### What should I do if I need accommodations to be successful in this course?

Accommodations are intended to remove barriers experienced by individuals with disabilities.
As a matter of principle, UBC is committed to promoting human rights, equity and diversity, and it also has a legal duty under the BC Human Rights Code to make its goods and services available in a manner that does not discriminate.
[Policy 73](https://universitycounsel.ubc.ca/files/2019/02/policy73.pdf) (Accommodation for Students with Disabilities) sets out principles and processes governing the accommodation of students with disabilities.

All accommodations for this course are handled through the [Disability Resource Centre](https://students.ok.ubc.ca/academic-success/disability-resources/contact-the-disability-resource-centre/) and I encourage you to contact them to book an appointment. 

### Compassion

As I'm sure you're aware, *there is (still) a global pandemic* happening right now and we could all use some extra compassion and humanity.
If you're going through something that is affecting you (course or otherwise), you are always welcome to come and talk to me about it. 
If I am not able to help you myself, then I can probably direct you to the right person or resource.
If you need extra help, or extra time to deal with something you're going through, just ask.
You will *never* owe me an explanation about your physical health, mental health, or those of your family members, friends, etc... I will believe you, and I will trust you.
I will not judge you, nor think any less of you.
I will do everything in my power to work out something that is both reasonable and fair. 
This, I promise!

## Acknowledgements

The syllabus was constructed and adapted from many other templates and examples.
Below is the list of resources I have used to put this syllabus together:

- Physics 117 (Instructor: [Dr. Simon Bates](https://sites.google.com/site/simonpbates/home?authuser=0))
- Psychology 417A-951 (Instructor: [Dr. Catherine Rawn](https://blogs.ubc.ca/catherinerawn/))
- [Dr. Christopher Jones](https://hcommons.org/members/profchrismjones/) and [this tweet](https://twitter.com/ProfChrisMJones/status/1282036533562834944)
- [Dr. Jesse Stommell](https://www.jessestommel.com/designing-for-care/)
- [Header image -  Photo by Pixabay from Pexels](https://www.pexels.com/photo/code-coding-computer-cyberspace-270373/)
- [Course Logo - Photo by Rakicevic Nenad from Pexels](https://www.pexels.com/photo/silhouette-of-person-holding-glass-mason-jar-1274260/)

## References

```{bibliography}
:style: unsrt
```