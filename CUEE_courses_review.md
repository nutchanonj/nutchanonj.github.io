---
layout: page
title: CUEE Courses Review
permalink: /CUEE_course_review/
nav_order: 8
---

# CUEE (formerly EECU) Courses Review by Nutchanon J

{: .note } 
This is still under construction! :construction:

This review does not emphasize on how the professors teach each subject. The review summarize why we should learn on this topic, and how can it be applied to subsequent courses.

Also, this review will be very centered on electronics and control systems, since I pursue in my study on these two fields.

The recommended textbooks will be written with **boldface**.

## Year 2 Semester 1

### ELECT ENG MATH I

You will learn about all techniques involved in solving differential equations, solving difference equations, learning about Fourier series and Fourier transform, Laplace transform, Z-transform. Lastly, you will learn to solve partial differential equations (PDEs.)

Firstly, you will solve them (linear differential equations, linear difference equations) the hard way (characteristic equations and some very magical techniques), and then, bam, you discover that Laplace transform and Z-transform really help you in solving those more easily.

Fourier series and Fourier transform will be appeared on many communication courses, because they are the method by which the waves are decomposed. Fourier series is applied on periodic waves and Fourier transform is applied on aperiodic waves. Both and related together and I persuade you to find that connection.

Laplace transform will be appeared on every subject in control systems. The word “transfer function” is heavily relied on Laplace transform. You will find this word first time in CIR THEORY I/LAB, when you learn about frequency response of a circuit.

Z-transform will be found in discrete-time system analysis. The digital control system and digital signal processing courses are heavily relied on Z-transform. However, you will not study those courses until 4th year of EE.

Partial differential equations will not be found in many EE courses (in my opinion.) It’s appeared on electromagnetics and quantum mechanics. If you want to pursue those courses in the future, I recommend that you should learn PDEs thoroughly.

I recommend that you learn the course from **Ajarn Supatana’s lecture notes**, and also her scrap papers during her teaching, since her techniques on solving this math are really wonderful. Some techniques are not even presented on modern textbooks anymore.

The class skips these topics: Series solutions of linear equation (you will miss some special functions like Bessel’s or Legendre’s,) Systems of linear and nonlinear equation (but you will see those in LIN CON SYS I anyway, but you will miss something like phase portraits.) Numerical methods (of which, in the past, is separated to another advanced course, but now that course is abolished. Maybe because now, it is computer who took the jobs!?)

For those who want to rely on textbook, I recommend **Differential Equations with Boundary Value Problems by Dennis G. Zill**. If you have time and dedication, I think you should read that book entirely. For Z-Transform, you will need others textbooks. I recommend **Discrete-Time Signal Processing by Oppenheim** or **Digital Control System Analysis and Design by Charles L. Phillips**.

For an exam, I do not recommend that you rely on textbooks, since the exam will be much harder than problems in textbooks. Instead, rely on Ajarn Supatana’s lecture notes and her former exams.

### PROB STAT ELEC ENG

You will learn all the basic in statistics required in EE. The course is very easy in my opinion.

For the main textbook accompanied with the teaching, please refer to prof. However, these are my recommendation for those who are really into it.

**Introduction to Probability by Joe Blitzstein and Jessica Hwang**: This is my FAVORITE book so far! I recommend that if you really want to understand and to have a very strong foundation on statistics, this book is a must. The book covers all of topics before midterm. For the topics after that, you need another textbook, that is:

**Mathematical Statistics with Applications by Dennis Wackerly**: This book is better than other textbooks because of its very strong mathematical handling. I recommend that if you really want to understand statistics to its mathematical core, this book is also a must. The book covers all of topics after midterm, and additionally covers many interesting topics, such as linear modeling, ANOVA, categorical data, nonparametric statistics, and Bayesian inference. I myself finished this book after the course because the topics provided are so interesting.

**Introductory Statistics by Neil A. Weiss**: For those who have time, I found this book to be practical, not heavily theoretical, so that you can see more easily how statistics can be applied to real world problems. I think it is suitable for someone who do not want to learn stats by seeing many, many math theorems.

### CIR THEORY I/LAB

This is essential for every EE student, period.

The textbook used by prof for many years is **Engineering Circuit Analysis by William H. Hayt**. However, I found some error(s) in that book that I do personally not recommend it. The book that I recommend is Fundamentals of **Electric Circuits by Charles K. Alexander, Matthew N.O. Sadiku**.

The book covers all the topics that you require to learn in this course. The prof will skip Chapter 6, 7, and 8 because those first- and second-order circuits can be solved more easily by Laplace transform, not direct ODE. Furthermore, I very recommend that you understand Bode plot to comprehend frequency response of a circuit more easily. (Also, it may help you on the exam!) Laplace and Fourier transform will be skipped in this course (because you will learn them in ELECT ENG MATH I.) The two-port networks will be taught in CIR THEORY II/LAB. The op-amp will be taught in ETRON CIRCUIT/LAB (2nd semester of 3rd year.)

P.S. This course has lab exams. I recommend that you go and practice when there is an allocated time provided by prof before the lab exam. (Even though this is not the obligation, it will help you.)

### ENG MECHANICS I

The only subject from Mechanical Engineering. Both **Engineering Mechanics by R. Hibbeler** or by **J.L. Meriam & L.G. Kraige** will do your favor. Do homework by yourself since one of the problems will be appear on the exam. End of the review.

### CALCULUS III

This is essence. Do not believe someone who say this course is useless. Electromagnetics requires this course. If you want to learn something like optimization techniques, understanding from this course is a must.

I recommend that you do exercises provided by prof by yourself, just like what you have done in CALCULUS I and CALCULUS II. The exam will be hard as that. Prof’s handouts are enough. But if not, any international calculus textbooks will do you favors. I personally recommend **Calculus: Early Transcendentals by Howard Anton, Irl Bivens, and Stephen Davis**. Read the entire book, trust me, you are going to use all of those topics in many subsequent courses.

## Year 2 Semester 2

### ELECT ENG MATH II

This is my only course that I got a B+, so far. *I sleep too little before the final exam.*

I, personally, find that **Ajarn Jitkomut’s slides on Linear Algebra**, and **Ajarn Suchin’s slides on Complex Analysis** should be enough for you to get through this course. However, if you want to rely on textbooks, my recommendations are these textbooks:

**Linear Algebra and Its Applications by David Lay, Steven Lay and Judi McDonald**: The first five chapters will be all taught before the midterm. Chapter 6 (orthogonality, least square, Gram-Schmitt) and Chapter 7 (Symmetric matrices and Quadratic form) will not be taught. However, I recommend that you read those anyway since they are going to reappear in many subsequent courses (PRINC COMM, LIN CONT SYS II, RANDOM PROC EE, etc.)

I want to emphasize that Linear Algebra is very important in every field of engineering. You should take this course very seriously.

**Complex Variables and Applications by Brown and Churchill**: The holy grail of complex analysis in my opinion. The first seven chapters will be taught after the midterm. I found these topics have no direct application in electrical engineering yet, but it will help explaining many topics that found in control systems (e.g., Nyquist stability criterions.) If you don’t want to blindly accept those topics, learn the materials. The bonuses of this course are

-	You will finally know how to evaluate some improper integrals which can be solved much easier by the residue theorem.
-	You will finally know how to evaluate inverse Laplace transform without finding partial fraction of a function (but you will not do it that way anyway.)

### CIR THEORY II

In my opinion, this course material is not updated at all. The book of which professors are still using is **Network Analysis and Synthesis by Franklin F. Kuo**. Seriously, this book is published in *1966*, the year my father was born. I would not recommend this book to any new EE students since the way this book handles electrical circuits is obviously outdated. Anyway, I do recommend, still, for those who want to understand how circuits are analysed before the time when computers are very rampant. Nowadays, it is more common to use state-space to analyse any linear models (e.g., linear circuits.) In the book mentioned, the author used full matrix representation to analyse the voltages of all nodes, or the currents of all paths to analyse the circuit. Obviously, this is very computationally-heavy! The practices for the problems which are going to be on the exam are also virtually none since this technique is already outdated. However, there are problems from Ajarn Manop which can be done by hands and can be checked by Simscape Electrical. I also had done it almost entirely and they should be in the EE resources’ Google Drive.

Before the midterm, you will learn the topic mentioned above. After the midterm, more modern techniques such as state-space model and two-port networks will be taught. You can go back and use **Fundamentals of Electric Circuits by Charles K. Alexander, Matthew N.O. Sadiku** to follow those topics again. I want to emphasize that this course is very connected to Linear Algebra in ELECT ENG MATH II. I also want to emphasize that this course will make you more appreciate LIN CONT SYS I, since the way of analyzing electrical circuits will be directly applied to general linear models (mechanical, thermal, etc.) in that course.

### ENG EMAG

Follow **Ajarn Supatana’s lecture notes and her former exams** and you will be fine. End of the review. (Sorry, just kidding.)

This course is very important for those who want to study in the field of communication. (Telecommunication, Microwave, Optics, Antennas, etc.)

My book recommendations are:

**Introduction to Electrodynamics by David J. Griffiths**: Honestly, this is the holy grail. You may think that you already understand electromagnetics from your first-year courses; no, you’re not, until you read this book.

First 9 chapters will be taught in the course. If you cannot self-study from this book, please attend the class and use this book as a reference. Ajarn Supatana has so many techniques to approach EM problems, that they will not be found on textbooks. However, the book will strengthen your understanding in electromagnetics in a very significant way. I still recommend that you read this book!

**Field and Wave Electromagnetics by Cheng**: This book is actually a book used by the course’s professors. I do not read the book myself, by my friend Taran recommends this book so often that I decide that it should be on the recommended list. This book is very connected to the future courses in communication (transmission line, waveguide, antenna.) So, I do recommend that if you don’t want the feeling of too much physics-oriented explaining in the previous mentioned book, this book is more EE-oriented and recommended to those who want to pursue further in communication.

**Electromagnetism: Problems with Solutions by Pramanik**: How the authors can compile these many problems in EM is astonishing. I recommend that if you really have time and get bored of former exams, go for this book.

### ELEC MACH I

This is the first course that is, in my opinion, practical-oriented.

**Electric Machinery Fundamentals by Chapman** is the book used by professor, and I recommend you to read all of the book, since every topic is relevant to technology in these days. I also recommend that, for those will find this book not theoretical enough, you go for **Fitzgerald & Kingsley's Electric Machinery by Umans**. I personally had no time to read the latter book, though.

## Year 3 Semester 1
