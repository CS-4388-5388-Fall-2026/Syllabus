# Syllabus

CS 4388/CS 5388, Fall 2026  
Computer Graphics  

Instructor: Isayas Berhe Adhanom, Ph.D.<br> 
Office hours: Monday and Wednesday, 1:00 - 2:00 PM, In person (Comal 307 E) 


TA: Mahfujur Rahman<br>
Office Hours: Monday and Wednesday, 4:00 - 5:00 PM, In person (Derrick Hall Mezannine Lobby) and on Zoom

## A Note From Your Instructor

Welcome to Computer Graphics! This is one of my favorite courses to teach, because it lives right at the intersection of mathematics, programming, and visual creativity, it is one of the few classes where you get to watch your code quite literally come to life on the screen. My goal for the semester is to take you from *using* graphics applications to *building* them: not just making something appear on screen, but understanding why the underlying math and algorithms work the way they do.

Computer graphics has been central to my own research in virtual reality, augmented reality and interactive 3D systems, and I am genuinely excited to share both the fundamentals and a feel for how graphics programmers actually think and solve problems. Whether you are headed toward games, visualization, simulation, or graduate research, the skills you build here will carry over. Please come to office hours early and often, I would much rather help you get unstuck than have you struggle alone.

## Overview

Computer graphics is one of the most visible and influential areas of computer science, shaping the visuals we experience in games, film, simulation, scientific visualization, design, education, and medicine. In this course, you will study the fundamental concepts and algorithms behind interactive computer graphics, including geometric transformations, scene representation, polygonal modeling, texture mapping, lighting and shading models, animation, ray casting, and projection, and you will put them into practice by building real, interactive graphics applications. Along the way we will pay close attention to the mathematical and computational techniques used to construct and manipulate 2D and 3D content, and to how these pieces fit together in the real-time rendering pipeline.

Although this is a programming-heavy course, it is designed to be accessible even if you don't have access to a computer with a powerful graphics card. Programming assignments are implemented in TypeScript using a high-level graphics toolkit built on top of WebGL, which runs inside the web browser on a wide range of hardware devices and operating systems.

## Learning Objectives

After completing this course, students should be able to:
- Explain fundamental concepts and algorithms used in computer graphics.
- Solve problems involving 2D and 3D computer graphics systems.
- Implement real-time computer graphics using a scene graph library.
- Develop shader programs for execution on graphics processing units (GPUs).
- Design user interfaces for interactive 3D graphics applications.

## Prerequisites

Formally, you need **CS 3358** and **[MATH 1317 or MATH 2321 or MATH 2417 or MATH 2471 or MATH 2472]**, each completed with a grade of **"C" or better**.

This is a programming-heavy course that assumes knowledge of concepts, algorithms, and data structures taught in previous computer science classes. TypeScript is a strongly-typed, object-oriented language that uses a syntax similar to Java and C#, but does not require explicit memory management like C++.  Prior experience with at least one of these object-oriented programming languages is recommended, but not strictly required. Please contact me if you have any questions about whether the course is a good fit for your interests and background.

## Course Structure and Modality

The course is divided into six **modules**, each of which lasts two weeks.  Generally, I will start each module with a class on graphics concepts, math, and techniques. These classes will generally follow a standard lecture format, but may also involve some in-class activities and discussion.  The lectures on conceptual material will be complemented with live programming sessions with me, which will typically during the second class of the module.  On these days, feel free to bring your laptops to class to follow along in real-time. Note that writing code during class is optional; you can also just watch and take notes. The live programming sessions have been very popular with students in the past, and gives me the opportunity to show you an expert in computer graphics goes about programming and problem solving. This is a great way to learn not only about graphics, but also about debugging, TypeScript syntax, and how to break a programming project into small steps.

During the second week of each module, we will often have a second lecture on more advanced concepts, followed by another live programming class.  However, the exact schedule may vary based on the content we need to cover, and sometimes it makes more sense to swap the order of the lecture and programming classes in a given week.

I intend to hold all class sessions **in-person**.  The class will not be live streamed except if situational factors arise, such as personal illness, in which case the class may be held synchronously via Zoom.  On the rare occasion that I am traveling, a session may instead be delivered **asynchronously** using a posted recording. I recognize that in-person attendance is not always possible or practical,  so **I will make an effort to record lectures and post them on Canvas when I can, but recordings are not guaranteed for every class**, and you should plan to attend in person whenever possible. If you do have to miss a class, there is no need to contact me; check Canvas for any posted recording or materials and catch up promptly so you don't fall behind.

## Textbook

There is no *required* textbook for this course. Throughout the semester, online resources, articles, and tutorials on various computer graphics topics will be posted, and students are expected to be familiar with this content in addition to the material covered in class.

For students who would like additional references, the following textbooks are **optional**:

- *Fundamentals of Computer Graphics*, 4th Edition, by Steve Marschner and Peter Shirley,  a comprehensive reference for the graphics concepts covered in the course. This book is **freely available to Texas State students** through the University Libraries' online subscription (the O'Reilly for Higher Education platform), so there is no need to purchase it. You can access it by searching the [TXST University Libraries](https://www.library.txst.edu/) catalog or the library's O'Reilly collection and signing in with your NetID.
- *[3D Math Primer for Graphics and Game Development](https://gamemath.com/)*, by Fletcher Dunn and Ian Parberry, a helpful reference for the vector, matrix, and transformation math we use throughout the course. The full text is **freely available online** at [gamemath.com](https://gamemath.com/).


## Assessments

There will be a total of six programming assignments in this class. Although they are challenging, they are also the most exciting and rewarding aspect of the course (and your chance to impress your friends with some cool 3D graphics). Your goal in these assignments should be to come away with a great practical understanding of how to tackle new computer graphics programming challenges using the modern programming toolkits.

In addition to the programming assignments, your understanding will be assessed by short **quizzes**, a **midterm exam**, and a **final exam** (both exams are described under *Exams* below).

Each assignment will be introduced at the beginning of a two-week module. At the end of the first week, you will complete the **Quiz**. This will review the key mathematical or algorithmic concepts in the assignment. Quizzes will be administered **online** and are **open book**. They will need to be completed before the deadline, and you have flexibility in choosing when to take it. The quizzes' purpose is to get you engaging with the assignment's concepts early. So it is generally a good idea to complete them before starting work on the program. 

At the end of the second week, you will submit the **Program**. If you struggled with the quiz, then seek help from the TA as needed, and make sure that you understand the key concepts first. At a minimum, your goal should be to have a full understanding of the concepts and how you will solve the programming portion by the end of the first week. This way, you will be sure to have at least one full week to implement and debug the program.

Students enrolled in CS 5388 (graduate section) will have additional work to complete for each assessment. This extra work will include tasks designed to meet the higher expectations for graduate students, ensuring a deeper understanding and more advanced application of the course material.

### Exams

There are two exams in this course: a **midterm** and a **final**. Both are held **in class** and are **individually proctored**. Unlike the quizzes, which are short, open-book, and meant to preview each assignment, the exams assess your broader understanding of the graphics concepts, mathematics, and algorithms covered in lecture and the programming assignments. The exams are **closed-book**, though you may bring a single one-page, handwritten note sheet.

The **midterm exam** is held on **Monday, October 12** during our regular class time and covers **Modules 0-3** (2D and 3D graphics, essential graphics math, physical simulation, meshes, textures, and morphing). The **final exam** is held during the university final exam period on **Monday, December 7, 11:00 AM-1:30 PM**, and focuses on **Modules 4-6** (scene hierarchy and animation, lighting and shading, cameras, rays, and projection), while assuming the foundational material from the first half of the course.

If a documented emergency prevents you from taking an exam at the scheduled time, contact me **as soon as possible**, ideally before the exam, to arrange a make-up. A missed exam cannot be replaced by the bonus quiz.

### Class Participation

Certain classes, especially those involving live programming, will include a **participation exercise** that will need to be completed in class. These exercises are very short and meant to provide deeper engagement with the course concepts. Completing the participation exercises will count for 5% of your final grade, and the **lowest two** will be dropped to allow for the occasional missed class.

## Grading

Final course grades will be calculated based upon the following percentages.

- Programing Assignments - 40%
- Midterm Exam - 20%
- Final Exam - 20%
- Quizzes - 15%
- Participation - 5%

The grading in this course is on an absolute scale. This means that the performance of others in the class will not affect your grade. Letter grades will be assigned using the following scale:

- A  ≥ 90.0% 
- B  ≥ 80.0% and < 90.0%
- C  ≥ 70.0% and < 80.0%
- D  ≥ 60.0% and < 70.0%
- F   < 60.0%

## Flexible Late Policy

I want the deadlines in this course to be firm enough to keep you on pace, but flexible enough to absorb the ordinary disruptions of a busy semester, an illness, a family emergency, or a crunch in another class. To that end, every assignment has a fixed due date, but each of you also starts the semester with **7 late points** to spend however you see fit.

Each late point is worth a 24-hour extension on any programming assignment. You are free to allocate them however you want throughout the course. For example, if you are sick, have a family emergency, or even just a big project due in another class, you could put all of your points toward one assignment and hand it in a week late. Alternatively, you could spread them out and submit several assignments a day or two late.

If you have late points remaining, **you do not need to contact me** for an extension on programming assignments. These extensions are applied automatically with no questions asked. When you submit your code using GitHub, the time is logged by the system. If the submission is late, we will apply an extension in the grading system and deduct the corresponding number of late points.

Your current late points will be visible in Canvas and will be updated when your assignments are graded. Note that you are responsible for keeping track of remaining points if you submitted an assignment late, but it has not been graded yet. If you run out of late points and anticipate further difficulties in completing work on time, then you should contact me to discuss your situation.

## Standard Policies

This class follows standard university policies. It's your responsibility to be familiar with:

- [Code of Student conduct](https://studenthandbook.txst.edu/rules-and-policies/code-of-student-conduct.html)
- [Academic honor code](https://studenthandbook.txst.edu/rules-and-policies/academic-honor-code.html)
- [Student handbook](https://studenthandbook.txst.edu/)
- [Grades and Changes of Grades](https://policies.txst.edu/division-policies/global/02-12.html)
- [Sexual misconduct policy ](https://docs.gato.txst.edu/322645/TSUS%20Sexual%20Misconduct%20Policy.pdf)

## Academic Integrity

First, please review the [Academic honor code](https://studenthandbook.txst.edu/rules-and-policies/academic-honor-code.html). The following describes how these policies specifically apply in this course. 

#### Collaboration Policy

All work submitted for this course is required to be your original work, except where specifically noted in the syllabus or the assignment description. In general, you are expected to do your own thinking, your own design, and your own implementation.

You are encouraged to discuss the content of the lectures and the texts with your peers. With respect to programming assignments, you are also permitted to discuss and make posts about programming in general (e.g., a syntax error you are stuck on, missing include file). However, your communication with others must stop before discussing a solution to the assignment. If you have any question about whether discussing something with peers might go beyond what is permitted, then stop and ask me for clarification on the policy.

####  Use of Web Resources

The web will be one of your best learning tools and sources of documentation for working with TypeScript and computer graphics toolkits used in the class, but you are not allowed to use web or other external resources to find solutions to the core computer graphics problems in your assignments.

**What you can do:**

- You are permitted to use course material without citation. This includes the lecture videos, slides, textbook, example code from class, official API documentation, and any other course material the instructor posts on Canvas. 
- You are permitted to use art assets (e.g., 3D models, textures, sound effects, etc.) from the internet in programming assignments. **However, you must cite all third-party assets in a readme file.** This citation must include a brief title or description of the specific assets used along with a link to wherever you found them.

**What you cannot do:**

- You are not allowed to search for solutions to assignments. For example, if your assignment is to develop your own texture mapping routine for a sphere, you can lookup the API documentation to learn the right function to call and the right syntax to use to set the texture coordinate for each vertex in a mesh. What you cannot do is google for “texture map a sphere” and find out how to setup a for loop and use cos() and sin() equations to determine the correct texture coordinates for each vertex of the sphere. This is the difference between using the web as a programming toolkit reference vs. using the web as a reference for the computer graphics algorithms/solutions that are being taught in the course. With the exception of the small snippets of code that are found in the official language or API documentation, you should never copy code like a routine, class, object, etc. from a website and include it in an assignment or project. 
- You are not allowed to ask other people to complete portions of an assignment or project for you. This includes classmates, friends, and use of paid services.
- You are **not allowed to use AI platforms** such as ChatGPT, Gemini, Claude, Perplexity or Microsoft Copilot to solve conceptual problems or generate code on the programming assignments or exams.  While AI technologies can be powerful tools for experienced programmers, using them to complete this graded work will undermine your learning. (The quizzes are low-stakes and graded on completion; you are still expected to attempt them yourself and to think through the concepts, since doing so is what prepares you for the assignments and exams.)
- You are **not allowed to use AI programming plugins or IDEs** such as GitHub Copilot or Cursor. Once again, these tools are intended to help professional developers write code faster, but if you use them in this course, they may trivialize portions of the assignments and prevent you from learning the core concepts that a graphics programmer would be expected to understand.
- You cannot use third-party assets that violate license terms or the rights of the original author. For example, free art assets that are posted in a public forum or asset store are permissible. However, any commercial or copyrighted assets, such as 3D models available for purchase on an online store, must be obtained legitimately. In general, using someone's work without their consent is ethically wrong and will be considered academic dishonesty in this course.

#### Consequences of Academic Dishonesty

Academic dishonesty in this class will result in a 0 on the assignment or exam in question for the first offense, and an automatic F in the class for the second offense. All cases of academic dishonesty are required to be reported to the University Honor Code Council.

Remember, we are here to help you. If you have any questions about whether something counts as academic dishonesty, please ask me for clarification!

## Mental Health Information

Texas State University strives to ensure all students have access to resources that will help them feel safe and supported. Your mental health is part of who you are and if you are unsure where to turn, we are here to help you. If you are encountering challenges, I encourage you to visit the [Counceling Center](https://www.counseling.txst.edu/) website and connect with one of our Mental Health Advocates, who are available to provide mental health resources and services.

## Disability Information

University policy is to provide, on a flexible and individualized basis, reasonable accommodations to students who have documented disability conditions (e.g., physical, learning, psychiatric, vision, hearing, or systemic) that may affect their ability to participate in course activities or to meet course requirements. Students with disabilities are encouraged to contact the [Office of Disability Services](https://www.ods.txst.edu/) to discuss individual needs for accommodations.

If you have already been working with the Office of Disability Services and have a letter from them to help direct your instructors on to set you up for success, then please send that to me at the beginning of the semester. In many cases, you will find that this course is already designed to be accessible for students that would benefit from additional flexibility (e.g., non-timed quizzes, flexible late policy on programming assignments, etc.). However, if additional accommodations are necessary, I will make every reasonable effort to make sure this class is a good experience for you.

## Acknowledgments

*Aspects of this syllabus (including this statement) were adopted from Evan Suma Rosenberg, Nathan Taylor, Daniel Keefe, Blair MacIntyre, Shana Watters, Lana Yarosh, and the American Association of University Professors Joint Statement on Rights and Freedoms of Students. This course was adapted from Evan Suma Rosenberg's CSCI 4611 at the University of Minnesota*
