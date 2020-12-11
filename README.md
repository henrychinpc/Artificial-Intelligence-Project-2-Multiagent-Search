# Pacman Project 2 Template (Multiagent Search)

You must read fully and carefully the assignment specification and instructions detailed in this file. You are NOT to modify this file in any way.

* **Course:** [COSC1125/1127 Artificial Intelligence](http://www1.rmit.edu.au/courses/004123) @ Semester 2, 2020
* **Instructor:** Prof. Sebastian Sardina
* **Deadline:** Sunday August 23rd, 2020 @ 11:59pm (end of Week 5)
* **Course Weight:** 5%
* **Assignment type:**: Group of 3 (or 2 in some cases)
* **CLOs covered:** 2, 3, 4 and 5
* **Submission method:** via git tagging (see below for instructions)

The purpose of this project is to get you acquainted with search techniques that account for behavior against an adversarial agent.

 <p align="center"> 
    <img src="logo-p2.png" alt="logo project 2">
 </p>


## Your task

**Your task** is to fully complete [Pacman Project 2 - Multiagent Search](http://ai.berkeley.edu/multiagent.html) from the set of [UC Pacman Projects](http://ai.berkeley.edu/project_overview.html). You **must build and submit your solution** using the sample code we provide you in this repository, which is different from the original UC code base. If you want to provide a report (optional) with your submission (e.g., reflections, acknowledgments, etc.), please do so in file [REPORT.md](REPORT.md).

* This is a group project; before you start you should register your team in the [Project 2 Team Registration Form](https://bit.ly/2ETKiEP). Then, use the same team name as the one you use in the GitHub classroom.

* You should **only work and modify** file `multiAgents.py` in doing your solution. Do not change the other Python files in this distribution or add new files.

* Your code **must run _error-free_ on Python 3.6**. Staff will not debug/fix any code. Using a different version will risk your program not running with the Pacman infrastructure or autograder and may risk losing (all) marks. You can install Python 3.6 from the [official site](https://www.python.org/dev/peps/pep-0494/), or set up a [Conda environment](https://www.freecodecamp.org/news/why-you-need-python-environments-and-how-to-manage-them-with-conda-85f155f4353c/) or an environment with [PIP+virtualenv](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/26/python-virtual-env/). See also [these questions](https://bit.ly/39vTEBH) in the FAQ for more info.

* Your code **must not contain any personal information**, like your student number or your name. That info should go in the [TEAM.md](TEAM.md) file, as per instructions below. If you use an IDE that inserts your name, student number, or username, you should disable that.

* Being a group assignment, you must use your project Github repository and GitHub team to collaborate among the members. The group will have write access to the same repository, and also be members of a GitHub team, where members can, and are expected to, engage in discussions and collaboration. Refer to the marking criteria below. 

#### Marking criteria

Overall we will follow the marking criteria specified in the official project instructions. Observe that while the automarker is a useful indication of your performance, it may not represent the ultimate mark. We reserve the right to run more tests, inspect your code and repo manually, your GitHub team, and arrange for a face-to-face meeting for a discussion and demo of your solution as needed.  

Besides the correctness of your solutions, you must **follow good and professional SE practices**, including good use of git and professional communication during your development such as:

* _Commit early, commit often:_ single or few commits with all the solution or big chunks of it, is not good practice.
* _Use meaningful commit messages:_ as a comment in your code, the message should clearly summarize what the commit is about. Messages like "fix", "work", "commit", "changes" are poor and do not help us understand what was done.
* _Use atomic commits:_ avoid commits doing many things; let alone one commit solving many questions of the project. Each commit should be about one (little but interesting) thing. 
* _Adequate communication in the GitHub team:_ members of the group are expected to communicate, in an adequate and professional way, in the GitHub team created along the repo.

Besides running an automarker, we will also inspect the **commit history** and **GitHub team** to check for high-quality SE practices and meaningful contributions of members. The results of this check can affect the overall mark of the project. For example, few commits with a lot of code changes, or no or poor communication in the corresponding GitHub team may result in deductions, even if the automarker achieves full marks. 

## Submission Instructions

**To submit your assignment** you must complete _all_ the following three steps:

1. Complete the [Project 2 Team Registration Form](https://bit.ly/2ETKiEP).
2. Fully complete the [TEAM.md](TEAM.md) file with the team details of the submission.
3. Check that your solution runs on Python 3.6 and that your source code does not include personal information, like your student number or name. 
4. Tag the commit version you want to be graded with tag `submission` (case sensitive). 
    * The commit and tagging should be dated before the deadline.
    * Note that a _tag_ is a name given to a specific commit in your git history. It is  NOT a branch nor a commit message nor a release. If you create a branch, release, or commit message with the text "`submission`", that will not be counted as tags and no marking will be done. 
    * For more info on tagging, please read the Pacman FAQ post [@110](https://piazza.com/class/kbsmlzxg3k7418?cid=110).
5. Fill the [Project 2 Certification \& Contribution Form](https://bit.ly/3gH7CDy).
    * Non-certified submissions will not be marked and will attract zero marks.
      
**IMPORTANT:** Submissions not compatible with the instructions in this document will attract zero marks and do not warrant a re-submission. Staff will not debug or fix your submission. Please refer to post [@93](https://piazza.com/class/kbsmlzxg3k7418?cid=93) for a video on some of the common mistakes done in Project 0.

## Important information

**Corrections:** From time to time, students or staff find errors (e.g., typos, unclear instructions, etc.) in the assignment specification. In that case, a corrected version of this file will be produced, announced, and distributed for you to commit and push into your repository.  Because of that, you are NOT to modify this file in any way to avoid conflicts.

**Late submissions & extensions:** A penalty of 10% of the maximum mark per day will apply to late assignments up to a maximum of five days, and 100% penalty thereafter. Extensions will only be permitted in _exceptional_ circumstances; refer to [this question](https://bit.ly/32WMVji) in the course FAQs. 

**About this repo:** You must ALWAYS keep your fork **private** and **never share it** with anybody in or outside the course, except your teammates, _even after the course is completed_. You are not allowed to make another repository copy outside the provided GitHub Classroom without the written permission of the teaching staff. Please respect the [authors request](http://ai.berkeley.edu/project_instructions.html): 

> **_Please do not distribute or post solutions to any of the projects._**

**Academic Dishonesty:** This is an advanced course, so we expect full professionalism and ethical conduct.  Plagiarism is a serious issue. Please **don't let us down and risk our trust**. The staff take academic misconduct very seriously. Sophisticated _plagiarism detection_ software (e.g., [Codequiry](https://codequiry.com/), [Turinitin](https://www.turnitin.com/), etc.) will be used to check your code against other submissions in the class as well as resources available on the web for logical redundancy. These systems are really smart, so just do not risk it and keep professional. We trust you all to submit your own work only; please don't let us down. If you do, we will pursue the strongest consequences available to us according to the **University Academic Integrity policy**. For more information on this see file [Academic Integrity](ACADEMIC_INTEGRITY.md).

**We are here to help!:** We are here to help you! But we don't know you need help unless you tell us. We expect reasonable effort from your side, but if you get stuck or have doubts, please seek help. We will run labs to support these projects, so use them! While you have to be careful to not post spoilers in the forum, you can always ask general questions about the techniques that are required to solve the projects. If in doubt whether a questions is appropriate, post a Private post to the instructors.

**Silence Policy:** A silence policy will take effect **48 hours** before this assignment is due. This means that no question about this assignment will be answered, whether it is asked on the newsgroup, by email, or in person.

## AI20 Code of Honour

We expect every RMIT student taking this course to adhere to the **Code of Honour** under which every learner-student should:

* Submit their own original work.
* Do not share answers with others.
* Report suspected violations.
* Not engage in any other activities that will dishonestly improve their results or dishonestly improve or damage the results of others.

Unethical behaviour is extremely serious and consequences are painful for everyone. We expect enrolled students/learners to take full **ownership** of your work and **respect** the work of teachers and other students.


**I hope you enjoy the project and learn from it**, and if you still **have doubts about the project and/or this specification** do not hesitate asking in the [Piazza Course Discussion Forum](http://piazza.com/rmit.edu.au/spring2020/cosc11271125/home) and we will try to address it as quickly as we can!

**GOOD LUCK!**

## Acknowledgements

This is [Pacman Project 2 - Multiagent Search](http://ai.berkeley.edu/multiagent.html) from the set of [UC Pacman Projects](http://ai.berkeley.edu/project_overview.html).  We are very grateful to UC Berkeley CS188 for developing and sharing their system with us for teaching and learning purposes.
