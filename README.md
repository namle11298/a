# RMIT COSC1125/1127 AI20 - Project 1 - Search 

You must read fully and carefully the assignment specification and instructions detailed in this file. You are NOT to modify this file in any way.

* **Course:** [COSC1125/1127 Artificial Intelligence](http://www1.rmit.edu.au/courses/004123) @ Semester 2, 2020
* **Instructor:** Prof. Sebastian Sardina
* **Deadline:** Sunday August 9th, 2020 @ 11:59pm (end of Week 3)
* **Course Weight:** 5%
* **Assignment type:**: Individual
* **CLOs covered:** 2, 3, 4 and 5
* **Submission method:** via git tagging (see below for instructions)

The **aim of this project** is to get you acquainted with AI search techniques and how to derive heuristics in Pacman, as well as to understand the Python-based Pacman infrastructure.

 <p align="center"> 
    <img src="logo-p1.jpg" alt="logo project 1">
 </p>

## Your task

**Your task** is to fully complete [UC Pacman Project 1 - Search](http://ai.berkeley.edu/search.html). You **must build and submit your solution** using the sample code we provide you in this repository, which is different from the original UC code base. If you want to provide a report with your submission (e.g., reflections, acknowledgments, etc.), please do so in file [REPORT.md](REPORT.md).

* You should **only work and modify** files `search.py` and `searchAgents.py` in doing your solution. Do not change the other Python files in this distribution.

* Your code **must run _error-free_ on Python 3.6**. Staff will not debug/fix any code. Using a different version will risk your program not running with the Pacman infrastructure or autograder and may risk losing (all) marks. You can install Python 3.6 from the [official site](https://www.python.org/dev/peps/pep-0494/), or set up a [Conda environment](https://www.freecodecamp.org/news/why-you-need-python-environments-and-how-to-manage-them-with-conda-85f155f4353c/) or an environment with [PIP+virtualenv](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/26/python-virtual-env/). See also [these questions](https://bit.ly/39vTEBH) in the FAQ for more info.

* Your code **must not have carry any personal information**, like your student number or your name. That info should go in the [TEAM.md](TEAM.md) file, as per instructions below. If you use an IDE that inserts your name, student number, or username, you should disable that.

#### Marking criteria

We will follow the marking criteria specified in the official project instructions. Observe that while the automarker is a useful indication of your performance, it may not represent the ultimate mark. We reserve the right to run more tests, inspect your code and repo manually, and arrange for a face-to-face meeting for a discussion and demo of your solution if needed.  You must **follow good SE practices**, including good use of git during your development such as:

* _Commit early, commit often:_ single or few commits with all the solution or big chucks of it, is not good practice.
* _Use meaningful commit messages:_ as a comment in your code, the message should clearly summarize what the commit is about. Messages like "fix", "work", "commit", "changes" are poor and do not help us understand what was done.
* _Use atomic commits:_ avoid commits doing many things; let alone one commit solving many questions of the project. Each commit should be about one (little but interesting) thing. 



## Submission Instructions

This repository serves as a start code for you to carry out your solution for [Project 1 - Search](http://ai.berkeley.edu/search.html) from the set of [UC Pacman Projects](http://ai.berkeley.edu/project_overview.html). 

**To submit your assignment** you must complete the following three steps:

1. Fully complete the [TEAM.md](TEAM.md) file with the team details of the submission (even if it is an individual assignment).
2. Check that your solution runs on Python 3.6 and that your source code does not include personal information, like your student number or name. 
3. Tag the commit version you want to be graded with tag `submission`. 
    * The commit and tagging should be dated before the deadline.
    * Note that a tag is NOT a branch, so do not just create a branch called "submission" as that will not amount to tagging.
4. Fill the [Project 1 Certification Form](https://forms.gle/AHkdFg5gZtYxvciP7).
    * Non-certified submissions will not be marked and will attract zero marks.
      
Submissions not compatible with the instructions in this document will attract zero marks and do not warrant a re-submission. Staff will not debug or fix your submission.

## Important information

**Corrections:** From time to time, students or staff find errors (e.g., typos, unclear instructions, etc.) in the assignment specification. In that case, corrected version of this file will be produced, announced, and distributed for you to commit and push into your repository.  Because of that, you are NOT to modify this file in any way to avoid conflicts.

**Late submissions & extensions:** A penalty of 10% of the maximum mark per day will apply to late assignments up to a maximum of five days, and 100% penalty thereafter. Extensions will only be permitted in _exceptional_ circumstances; refer to [this question](https://bit.ly/32WMVji) in the course FAQs. 

**About this repo:** You must ALWAYS keep your fork **private** and **never share it** with anybody in or outside the course, except your teammates, _even after the course is completed_. You are not allowed to make another repository copy outside the provided GitHub Classroom without the written permission of the teaching staff. Please respect the [authors request](http://ai.berkeley.edu/project_instructions.html): 

> **_Please do not distribute or post solutions to any of the projects._**

**Academic Dishonesty:** This is an advanced course, so we expect full professionalism and ethical conduct.  Plagiarism is a serious issue. Please **don't let us down and risk our trust**. The staff take academic misconduct very seriously. Sophisticated _plagiarism detection_ software (e.g., [Codequiry](https://codequiry.com/), [Turinitin](https://www.turnitin.com/), etc.) will be used to check your code against other submissions in the class as well as resources available on the web for logical redundancy. These systems are really smart, so just do not risk it and keep professional. We trust you all to submit your own work only; please don't let us down. If you do, we will pursue the strongest consequences available to us according to the **University Academic Integrity policy**. For more information on this see file [Academic Integrity](ACADEMIC_INTEGRITY.md).

**We are here to help!:** We are here to help you! But we don't know you need help unless you tell us. We expect reasonable effort from you side, but if you get stuck or have doubts, please seek help. We will ran labs to support these projects, so use them! While you have to be careful to not post spoilers in the forum, you can always ask general questions about the techniques that are required to solve the projects. If in doubt whether a questions is appropriate, post a Private post to the instructors.

**Silence Policy:** A silence policy will take effect **48 hours** before this assignment is due. This means that no question about this assignment will be answered, whether it is asked on the newsgroup, by email, or in person.

## AI20 Code of Honour

We expect every RMIT student taking this course to adhere to it **Code of Honour** under which every learner-student should:

* Submit their own original work.
* Do not share answers with others.
* Report suspected violations.
* Engage in any other activities that will dishonestly improve their results or dishonestly improve or damage the results of others.

Unethical behaviour is extremely serious and consequences are painful for everyone. We expect enrolled students/learners to take full **ownership** of your work and **respect** the work of teachers and other students.


**I hope you enjoy the project and learn from it**, and if you still **have doubts about the project and/or this specification** do not hesitate asking in the [Piazza Course Discussion Forum](http://piazza.com/rmit.edu.au/spring2020/cosc11271125/home) and we will try to address it as quickly as we can!

**GOOD LUCK!**

## Acknowledgements

This is [UC Pacman Project 1 - Search](http://ai.berkeley.edu/search.html) from the set of [UC Pacman Projects](http://ai.berkeley.edu/project_overview.html).  We are very grateful to UC Berkeley CS188 for developing and sharing their system with us for teaching and learning purposes.