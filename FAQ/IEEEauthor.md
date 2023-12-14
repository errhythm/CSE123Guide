---
title: "Multiple Author format in IEEE"
authors:
  - name: Ehsanur Rahman Rhythm
    email: ehsanur.rahman.rhythm@g.bracu.ac.bd
    link: https://errhythm.me
    avatar: https://errhythm.me/assets/img/rhythm.png
order: -3
icon: ":lower_left_ballpoint_pen:"
---

According to IEEEtran, if your total number of author is more than 3, it is recommended to follow the given format. Follow the given LaTex snippet.

Write after the `\title` command, paste the following code and replace your names and emails. 

```latex
\author{\IEEEauthorblockN{AuthorX, AuthorY, AuthorZ, StudentTutorA, ResearchAssistantB and CourseInstructor}
\IEEEauthorblockA{Department of Computer Science and Engineering (CSE) \\School of Data and Sciences (SDS)\\ 
 Brac University\\KHA 224, Progati Sarani, Merul Badda, Dhaka - 1212, Bangladesh}  
 \IEEEauthorblockA{\{author.x, author.y, author.z, student.tutor.a, research.assistant.b\}@g.bracu.ac.bd, courseinstructor@gmail.com}}
```

* Use linebreak `\\` if necessary.

After the given code, there would be `\maketitle` and then `\begin{abstract}`. 

The output will be like the following:

![ ](https://i.vgy.me/x3Bv8S.png)
