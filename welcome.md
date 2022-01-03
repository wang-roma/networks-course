---
marp: true
theme: default
paginate: true
style: |
    section {
        justify-content: flex-start;
        --orange: #ed7d31;
        --left: #66c2a5;
        --right: #fc8d62;
        --source: #8da0cb;
        --target: #e78ac3;
    }
    img[alt~="center"] {
        display: block;
        margin: 0 auto;
    }
    header {
        top: 0px;
        margin-top: 0 auto;
    }
    div.twocols {
        margin-top: 0px;
        column-count: 2;
    }
    div.twocols p:first-child,
    div.twocols h1:first-child,
    div.twocols h2:first-child,
    div.twocols ul:first-child,
    div.twocols ul li:first-child,
    div.twocols ul li p:first-child {
        margin-top: 0 !important;
    }
    div.twocols p.break {
        break-before: column;
        margin-top: 0;
    }
---


# Network Data Science


### Instructor: Ben Pedigo

_Johns Hopkins University_
_[NeuroData lab](https://neurodata.io/)_
[_@bdpedigo (Github)_](https://github.com/bdpedigo)
[_bpedigo@jhu.edu_](mailto:bpedigo@jhu.edu)

![bg right:50% w:600](./slide_images/hemibrain-layout.png)

---
# Goals

<div class="twocols">

- Introduction to the field of network science
- Overview of techniques that are used so that students are well equipped to explore the field further
- Code/analysis product to add to portfolio

<p class="break"></p>

- Familiarity with `Python`
- Familiarity with `git`/`GitHub`
- Practice communicating technical content via oral and online (`jupyter-notebook`/`jupyter-book`) media

</div>

---
# Course logistics

- Course meets MTWThF, 1-2:20pm ET, on Zoom
- Last 20-30 minutes of each day will hopefully be for project work time
- I will be available ~2:20-2:45pm ET (or when everyone leaves) - think of this as extra office hours
- Syllabus: [https://bdpedigo.github.io/networks-course/syllabus.html](https://bdpedigo.github.io/networks-course/syllabus.html) (please review)
- Calendar: [https://bdpedigo.github.io/networks-course/calendar.html](https://bdpedigo.github.io/networks-course/calendar.html)

---
# Grading
(straight from the syllabus)

> To pass, a student must: 
> - Attend and engage with every lecture (please let the instructor know if you need to miss a lecture for some reason)
> - Submit the pre-project mini-assignment by TODO
> - Submit a merge-able final project by 12pm (noon) on Jan 20th (Thursday)
> - Present their final project on the last day of class, Jan 21st (Friday)

---
# Mini-assignment
- Need to make a pull request to this class's repository on GitHub: []()
- Due Jan 5th at 11:59pm

--- 
# Mini-assignment steps
- Make sure you have `git` installed: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
- From the command line on your machine, navigate to a folder where you would like to keep your work for the course
- Go to the page for this repo: https://github.com/bdpedigo/networks-course
- Find the green `Code` button: 
  ![w:900px](./slide_images/git-page.png)

--- 
# Mini-assignment steps (cont.)
- Hit the green `Code` button and copy the `HTTPS` link: 
  ![h:300px](./slide_images/git-clone.png)
- From the command line, do `git clone <link that you just copied>`
- You should now see a directory called `networks-course`

---
# Mini-assignment steps (cont.)
- Make a new file in the directory `networks-course/docs`, call it `<your-last-name>.md`:
  ![h:400](./slide_images/nav-example-name-markdown.png)

---
# Mini-assignment steps (cont.)
- In that file, write `# <your last name> - final project placeholder`:
  ![h:200](./slide_images/name-example-markdown.png)
- From the command line, make sure you are in the `networks-course` directory. You probably need to move there with a command like `cd networks-course`. 
- 

---
# Final projects



--- 


--- 
# Feedback