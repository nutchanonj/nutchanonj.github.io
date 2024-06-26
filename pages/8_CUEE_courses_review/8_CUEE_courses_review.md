---
layout: page
title: CUEE Courses Review
permalink: /pages/8_CUEE_courses_review/
nav_order: 8
has_toc: true
---

# CUEE (formerly EECU) Courses Review by Nutchanon J :books:
{: .no_toc }

![Chulalongkorn University](chula-1.jpg)
*Chulalongkorn University (Photo by myself)*

This review does not emphasize on how the professors teach each subject. The review summarize why we should learn on this topic, and how can it be applied to subsequent courses. The review also includes the workload of each course so you can decide how many credits you want to register in each semester.

Three metrics are given:
- Quantity of Content: How much the content in the course is.
- Course Workload: How much HWs and projects in the course are. Please note that this **does not include** the time that you have to read or review the content, or prepare for exam.
- Exam Difficulty: How difficult the exams (midterm, final, quizzes) are.

Also, this review will be very centered on electronics and control systems, since I pursue in my study on these two fields. 

{: .warning } 
My review may be out-of-date. To be specific, Year 2 of mine is A.Y.2020, Year 3 of mine is A.Y.2021 and Year 4 of mine is A.Y.2022. (A.Y. = academic year.) Please note that 2020 and 2021 were heavily affected by the COVID-19 pandemic and the review on teaching would not be accurate. Hence, I focus on the content of each course instead.

The recommended textbooks will be written with **boldface**.

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

## Year 2 Semester 1

![Bhumibol Bridge](bhumibol-bridge.jpg)
*Bhumibol Bridge (Photo from Yee Associates)*

### EE201: ELECT ENG MATH I

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: (No HWs and projects) \\
Exam Difficulty: :star: :star: :star: :star: 

You will learn about all techniques involved in solving differential equations, solving difference equations, learning about Fourier series and Fourier transform, Laplace transform, Z-transform. Lastly, you will learn to solve partial differential equations (PDEs.)

Firstly, you will solve them (linear differential equations, linear difference equations) the hard way (characteristic equations and some very magical techniques,) and then, bam, you discover that Laplace transform and Z-transform really help you in solving those more easily.

Fourier series and Fourier transform will be appeared in many communication courses, because they are the methods by which the waves are decomposed. Fourier series is applied on periodic waves and Fourier transform is applied on aperiodic waves. Both are related and I persuade you to find that connection.

Laplace transform will be appeared in every subject related to control system theory. The word “transfer function” is heavily relied on Laplace transform. You will find this word the first time in CIR THEORY I/LAB, when you learn about the frequency response of a circuit.

Z-transform will be found in discrete-time system analysis. The digital control system and digital signal processing courses are heavily relied on Z-transform. However, you will not study those courses until the 4th year of EE.

Partial differential equations will not be found in many EE courses (in my opinion.) It’s appeared on electromagnetics and quantum mechanics. If you want to pursue those courses in the future, I recommend that you should learn PDEs thoroughly.

I recommend that you learn the course from **[Ajarn Supatana](https://ee.eng.chula.ac.th/supatana-auethavekiat/)’s lecture notes**, and also her scrap papers during her teaching, since her techniques on solving this math are really wonderful. Some techniques are not even presented on modern textbooks anymore.

The class skips these topics: Series solutions of linear equations (you will miss some special functions like Bessel’s or Legendre’s,) Systems of linear and nonlinear equations ( you will see those in LIN CON SYS I anyway, but you will miss something like phase portraits,) Numerical methods (of which, in the past, is separated to another advanced course, but now that course is abolished. Maybe because now, it is a computer who took the job!?)

For those who want to rely on textbook, I recommend **Differential Equations with Boundary Value Problems by Dennis G. Zill**. If you have time and dedication, I think you should read that book entirely. For Z-Transform, you will need other textbooks. I recommend **Discrete-Time Signal Processing by Oppenheim** or **Digital Control System Analysis and Design by Charles L. Phillips**.

For the exams, I do not recommend that you rely on textbooks, since the exams will be much harder than the problems in textbooks. Instead, rely on [Ajarn Supatana](https://ee.eng.chula.ac.th/supatana-auethavekiat/)’s lecture notes and her collected former exams.

---

### EE203: PROB STAT ELEC ENG

Quantity of Content: :star: :star: \\
Course Workload: :star: :star: \\
Exam Difficulty: :star: :star:

You will learn all of the basics in statistics required in EE. The course is very easy in my opinion.

For the main textbook accompanied with the teaching, please refer to prof. However, these are my recommendation for those who are really into it.

**Introduction to Probability by Joe Blitzstein and Jessica Hwang**: This is my FAVORITE book so far! I recommend that if you really want to understand and to have a very strong foundation on statistics, this book is a must. The book covers all of topics before midterm. For the topics after that, you need another textbook, that is:

**Mathematical Statistics with Applications by Dennis Wackerly**: This book is better than other textbooks because of its very strong mathematical handling. I recommend that if you really want to understand statistics to its mathematical core, this book is also a must. The book covers all of topics after midterm, and additionally covers many interesting topics, such as linear modeling, ANOVA, categorical data, nonparametric statistics, and Bayesian inference. I myself finished this book after the course because the topics provided are so interesting.

**Introductory Statistics by Neil A. Weiss**: For those who have time, I found this book to be more practical, not heavily theoretical, so that you can see more easily how statistics can be applied to the real world problems. I think it is suitable for someone who do not want to learn stats by seeing many, many math theorems.

---

### EE213: CIR THEORY I/LAB

Quantity of Content: :star: :star: :star: \\
Course Workload: :star: :star: \\
Exam Difficulty: :star: :star: :star:

This is essential for every EE student, period.

The textbook used by prof for many years is **Engineering Circuit Analysis by William H. Hayt**. However, I found some error(s) in that book that I do personally not recommend it. The book that I recommend is **Fundamentals of Electric Circuits by Charles K. Alexander, Matthew N.O. Sadiku**.

The book (6th edition) covers all of the topics that you require to learn in this course. The prof will skip Chapter 6, 7, and 8 because those first- and second-order circuits can be solved more easily by Laplace transform, not direct ODE. Furthermore, I strongly recommend that you understand the Bode plot to comprehend the frequency response of a circuit more easily. (Also, it may help you on the exam!) Laplace and Fourier transform will be skipped in this course (because you will learn them in ELECT ENG MATH I.) The two-port networks will be taught in CIR THEORY II/LAB. The op-amp will be taught in ETRON CIRCUIT/LAB (2nd semester of the 3rd year.)

P.S. This course has lab exams. I recommend that you go and practice when there is an allocated time provided by prof before the lab exam. (Even though this is not the obligation, it will help you.)

---

### ME213: ENG MECHANICS I

Quantity of Content: :star: :star: :star: \\
Course Workload: :star: \\
Exam Difficulty: :star: :star: :star:

The only subject from Mechanical Engineering. Both **Engineering Mechanics by R. Hibbeler** or by **J.L. Meriam & L.G. Kraige** will do your favor. Do homework by yourself since one of the problems will be appear on the exam. End of the review. Good luck.

---

### MATH207: CALCULUS III

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: (No HWs and projects) \\
Exam Difficulty: :star: :star: :star: :star: :star:

This is an essence. Do not believe someone who say this course is useless. Electromagnetics requires this course. If you want to learn something like optimization techniques, understanding from this course is a must.

I recommend that you do exercises provided by prof by yourself, just like what you have done in CALCULUS I and CALCULUS II. The exam will be as hard as that. Prof’s handouts are enough. But if not, any international calculus textbooks will do you favors. I personally recommend **Calculus: Early Transcendentals by Howard Anton, Irl Bivens, and Stephen Davis**. Read the entire book, trust me, you are going to use all of those topics in many subsequent courses.

---

## Year 2 Semester 2

![Philadelphia, PA, United States](philadelphia.jpg)
*Philadelphia, PA, United States (Photo by Trev Adams)*

### EE202: ELECT ENG MATH II

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: (No HWs and projects) \\
Exam Difficulty: :star: :star: :star: :star: :star:

This is my only course that I got a B+, so far.

I, personally, find that **[Ajarn Jitkomut](http://jitkomut.eng.chula.ac.th/)’s slides on Linear Algebra**, and **[Ajarn Suchin](https://ee.eng.chula.ac.th/suchin-arunsawatwong/)’s slides on Complex Analysis** should be enough for you to get through this course. However, if you want to rely on textbooks, my recommendations are these textbooks:

**Linear Algebra and Its Applications by David Lay, Steven Lay and Judi McDonald**: The first five chapters in the book (5th edition) will be all taught before the midterm. Chapter 6 (orthogonality, least square, Gram-Schmitt) and Chapter 7 (Symmetric matrices and Quadratic form) will not be taught. However, I recommend that you read those anyway since they are going to reappear in many subsequent courses (PRINC COMM, LIN CONT SYS II, RANDOM PROC EE, etc.)

I want to emphasize that Linear Algebra is very important in every field of engineering. You should take this course very seriously.

**Complex Variables and Applications by Brown and Churchill**: The holy grail of the complex analysis in my opinion. The first seven chapters in the book (9th edition) will be taught after the midterm. I found these topics have no direct application in electrical engineering yet, but it will help explaining many topics that found in control systems (e.g., Nyquist stability criterions.) If you don’t want to blindly accept those topics, learn the materials. The bonuses of this course are

- You will finally know how to evaluate some improper integrals which can be solved much easier by the residue theorem.
- You will finally know how to evaluate inverse Laplace transform without finding partial fraction of a function (but you will not do it that way anyway.)

---

### EE214: CIR THEORY II

Quantity of Content: :star: :star: \\
Course Workload: :star: :star: \\
Exam Difficulty: :star: :star: :star: 

In my opinion, this course material is not updated at all. The book of which professors are still using is **Network Analysis and Synthesis by Franklin F. Kuo**. Seriously, this book is published in *1966*, the year my father was born. I would not recommend this book to any new EE students since the way this book handles electrical circuits is obviously outdated. Anyway, I do recommend, still, for those who want to understand how circuits are analysed before the time when computers are very rampant. Nowadays, it is more common to use state-space to analyse any linear models (e.g., linear circuits.) In the book mentioned, the author used full matrix representation to analyse the voltages of all nodes, or the currents of all paths to analyse the circuit. Obviously, this is very computationally-heavy! The practices for the problems which are going to be on the exam are also virtually none since this technique is already outdated. However, there are problems from [Ajarn Manop](https://ee.eng.chula.ac.th/manop-wongsaisuwan/) which can be done by hands and can be checked by Simscape Electrical. I also had done it almost entirely and they should be in the EE resources’ Google Drive.

Before the midterm, you will learn the topic mentioned above. After the midterm, more modern techniques such as state-space model and two-port networks will be taught. You can go back to use **Fundamentals of Electric Circuits by Charles K. Alexander, Matthew N.O. Sadiku** to follow those topics again. I want to emphasize that this course is very connected to Linear Algebra in ELECT ENG MATH II. I also want to emphasize that this course will make you more appreciate LIN CONT SYS I, since the way of analyzing electrical circuits will be directly applied to general linear models (mechanical, thermal, etc.) in that course.

---

### EE222: ENG EMAG

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: :star: :star: \\
Exam Difficulty: :star: :star: :star: :star: :star: 

Follow **[Ajarn Supatana](https://ee.eng.chula.ac.th/supatana-auethavekiat/)’s lecture notes and her former exams** and you will be fine. End of the review. (Sorry, just kidding.)

This course is very important for those who want to study in the field of communication. (Telecommunication, Microwave, Optics, Antennas, etc.)

My book recommendations are:

**Introduction to Electrodynamics by David J. Griffiths**: Honestly, this is the holy grail. You may think that you already understand electromagnetics from your first-year courses; *no*, you’re not, until you read this book.

First 9 chapters in the book (4th edition) will be taught in the course. If you cannot self-study from this book, please attend the class and use this book as a reference. Ajarn Supatana has so many techniques to approach EM problems, that they will not be found on textbooks. However, the book will strengthen your understanding in electromagnetics in a very significant way. I still recommend that you read this book!

**Field and Wave Electromagnetics by Cheng**: This book is actually a book used by the course’s professors. I do not read the book myself, by my friend [Taran](https://www.facebook.com/nineza.taran) recommends this book so often that I decide it should be on the recommended list. This book is very connected to the future courses in communication (transmission line, waveguide, antenna.) So, I do recommend that if you don’t want the feeling of too much physics-oriented explaining in the previous mentioned book, this book is more EE-oriented and recommended to those who want to pursue further in communication.

**Electromagnetism: Problems with Solutions by Pramanik**: How the authors can compile these many problems in EM is astonishing. I recommend that if you really have time and get bored of former exams, go for this book.

---

### EE253: ELEC MACH I

Quantity of Content: :star: :star: :star: \\
Course Workload: :star: :star: \\
Exam Difficulty: :star: :star: :star: 

This is the first course that is, in my opinion, practical-oriented.

**Electric Machinery Fundamentals by Chapman** is the book used by professor, and I recommend you to read the entire book, since every topic is relevant to electrical machinery in these days. I also recommend that, for those who find this book not theoretical enough, you go for **Fitzgerald & Kingsley's Electric Machinery by Umans**. I personally had no time to read the latter book, though.

---

## Year 3 Semester 1

![Saint Petersburg, Russia](saint-petersburg.jpg)
*Saint Petersburg, Russia (Photo by Serj Sakharovskiy)*

### EE360: ELEC POWER SYS I

Quantity of Content: :star: :star: :star: \\
Course Workload: :star: \\
Exam Difficulty: :star: :star: :star: 

To be honest, this is the course that I did not give my attention that much. (How I can get an A from this course is still astonishing to me!?) 

The prof's slides, materials and former exams should be enough for the course. If you are energetic for this course, please refer to **Power System Analysis and Design by J. Duncan Glover**. I heard that this book can be used further in ELEC POWER SYS II as well.

---

### EE385: SEMICON DEV I

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: (No HWs and projects) \\
Exam Difficulty: :star: :star: :star: 

This is where many EE students find themselve whether they really want to pursue further in electronics or not.

This course is taught entirely by [Ajarn Songpol](https://ee.eng.chula.ac.th/songphol-kanjanachuchai/) in my year, and he's very good at it. You will learn all of the essential topics related to semiconductor. *Essential* is not an exaggerated word: these topics will be useful when you take ETRON CIRCUIT/LAB next semester. 

The textbook that Ajarn Songpol uses for many years is **Solid State Electronic Devices by Ben Streetman**. I find that book good if you want to learn fast. If you want to learn these topics in a more physics-oriented way, I recommend you to read **Semiconductor Physics and Devices by Donald A. Neamen** for more in-depth understanding. (Again, if you have time.)

---

### EE371: PRINC COMM/LAB

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: :star: :star: \\
Exam Difficulty: :star: :star: :star: 

This course give you many basic topics about communication in general. Some say it is useful, and some say it cannot provide any pictorial understanding about communication at all. I am in the former group; I find it useful enough for me who don't want to study further in communication field.

The textbook that I relied on, parallelly with the prof's slides and materials, is **Modern Digital and Analog Communication Systems by B. P. Lathi**. I found it readable for any beginner. [Ajarn Nisachon](https://ee.eng.chula.ac.th/nisachon-tangsangiumvisai/) says that the course relies on **Digital and Analog Communication Systems by Leon Couch**, but I found it very hard to read for the beginners. Some people recommend the book **Communication Systems by Michael Moher and Simon Haykin**, but I haven't read that book yet.

---

### EE387: FUND DIGIT CIRC

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: :star: :star: :star: \\
Exam Difficulty: :star: :star: :star: 

{: .note } 
I want to say this for a long time: You don't have to love SEMICON DEV I and ETRON CIRCUIT/LAB to decide whether you want to pursue further in electronics or not. Field of electronics is huge that you don't have to be good at everything.

{: .warning } 
I heard that for subsequent years, profs would want you to use Xilinx Vivado software suite. You should have your own computer with AT LEAST 200 GB OF FREE SPACE to install that. If not, you need to have some generous friends whom you can rely their computers.

This course is the first course in electronics (along with SEMICON DEV I.) This is the first step in digital design.

All of the basics will be taught in this course. The pair of books which I used simultaneously are:

**Digital Fundamentals by Thomas L. Floyd**: This book is made for beginner that I find it very easy to read. Furthermore, it includes topics in common digital ICs used in discrete electronics (74 series.) It also includes many common electronics knowledges that I personnally find those very helpful. All in all, I recommend that anyone who wants to go further in digital electronics to read this book entirely. Nevertheless, this book does not cover all of the topics in FUND DIGIT CIRC. (It lacks the topic about state machine.) The next book that covers all topics in this subject is

**Fundamentals of Logic Design by Charles H. Roth**: This book is very in-depth. In the book (7th edition,) Unit 1 through Unit 13 will be thought in this course (seriously.) Some topics will be skipped (e.g. Quine-McCluskey method, hazards in digital circuits, etc.) The rest of the topics are also very interesting if you want to work in digital design in the future. Follow this book along with the course will give you the best understanding.

This course uses VHDL for synthesizing digital logics (even though Verilog is more popular.) For VHDL, The book from Charles H. Roth mentioned above have some units dedicated to VHDL, but I found them not enough for me. I personnally find **Free Range VHDL by Bryan Mealy and Fabrizio Tappero** to be very helpful for beginner who wants to start fast. (This book is FREE, you can search it for yourself in Google.) Anyway, this book does not include the topic on testbench (and many advanced topics about VHDL.) For more in-depth topics, you should follow **The Designer’s Guide to VHDL by Peter J. Ashenden**.

For anyone interest in Verilog, I recommend **Quick Start Guide To Verilog by Brock J. LaMeres**.

---

### EE333: LIN CONT SYS I/LAB

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: :star: :star: :star: \\
Exam Difficulty: :star: :star: :star: :star: :star:

The first course in control system theory. Since I'm in the field of electronics, this course is very important (trust me.)

I personally found that [Ajarn Manop](https://ee.eng.chula.ac.th/manop-wongsaisuwan/)'s slide for this course is very easy to read, but not enough for in-depth understanding. You should rely on additional examples and explanation in textbooks to achieve real understanding in this course. (If you want to.) The recommended books are:

**Modern Control Engineering by Katsuhiko Ogata**: This is the book that is recommended by [Ajarn Suchin](https://ee.eng.chula.ac.th/suchin-arunsawatwong/), and I will also recommend this book to you. This book is very easy to read, and my friend [Taran](https://www.facebook.com/nineza.taran) also agree with me. Chapter 1 through Chapter 7 in the book (5th edition) will be taught in this course. (You can safely skip Chapter 4.) Chapter 8, the PID, can be read for further understanding. Chapter 9 and 10 will be covered in LIN CONT SYS II.

For other books, there are **Modern Control Systems by Richard C. Dorf**, but I find it hard to read for beginners, and **Control Systems Engineering by Norman S. Nise**, but I have not read it yet.

{: .note } 
For those who find this course very hard: I personally read all of the topics in this course FOR 3 TIMES to make an A out of it.

---

## Year 3 Semester 2

![Jiufen, Taiwan](jiufen-taiwan.jpg)
*Jiufen, Taiwan (Photo by We Fun Taiwan)*

{: .note } 
This is where the fun begin.

### EE308: PROP ELEC ENG MAT

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: :star: \\
Exam Difficulty: :star: :star: :star: 

I personally hate this course, lol. (Don't mind me.)

You can rely on prof's slides entirely and you should be fine. The textbook used by prof is **Principles of Electronic Materials and Devices by S. O. Kasap**, but I have no time to read that book. Good luck.

---

### EE311: ELEC MEAS/INSTRU

Quantity of Content: :star: :star: :star: \\
Course Workload: :star: \\
Exam Difficulty: :star: :star: 

This course teaches you about the basics on electrical instrumentations and measurements. I personally find this course useful. The course has no companion textbook. Some of the topics are out-of-date in my opinion. Relying on prof's slides only and you should be fine. End of the review.

---

### EE386: ETRON CIRCUIT/LAB

Quantity of Content: :star: :star: :star: :star: :star: \\
Course Workload: :star: :star: :star: :star: \\
Exam Difficulty: :star: :star: :star: :star: :star: 

I personally not recommand you to rely prof's slides to fully understand this course! [They will never be enough!](https://www.youtube.com/watch?v=6jZVsr7q-tE)

Finally, one of the courses that I found the instructors not so very helpful (only [Ajarn Boonchuay](https://ee.eng.chula.ac.th/boonchuay-supmonchai/) and [Ajarn Napong](https://ee.eng.chula.ac.th/napong-panitantum/) are good, the other are :unamused:.) If you want to pursue further in analog design, PLEASE use the textbooks. THIS COURSE IS HARD AS IT SUPPOSED TO BE! I recommend that for someone who go for analog or microelectronics in general, please refer to:

**Microelectronic Circuits - Sedra & Smith**: This book is the best in my opinion. Only warning is that the arrangement of the topics in this book is not the same as in the course, so that you need to learn fast enough if you want to rely on this book along with the course. I recommend this book first because I love how this book arranges its content.

If you want to use this book (7th edition) along with the course, this is my advice:
- Firstly, you should review the basic about semiconductor from Chapter 3.
- Then, you need to learn about device physics (BJT and MOS) from Chapter 5 and 6.
- The BJT amplifier will be taught first, you read it from Chapter 7. I recommend that you should understand how the resistance-reflection rule works.
- Also, you need to learn more about the frequency response of a BJT amplifier. You read that from Chapter 10 for those relevant topics. The prof is generous if you are lucky, so only the frequency response of the common-emitter configuration will be asked in the exam.
- Secondly, the MOS amplifier will be taught. You go back to Chapter 7 again. MOS is easier than BJT since there is no gate (base) current.
- Some of the MOS amp configurations will be new for you (e.g. cascoding, current mirror, etc.) You should read Chapter 8.
- Also, you need to learn more about the frequency response of a MOS amplifier, so you go back to Chapter 10 to read about that. If the prof is generous, again, only the frequency response of the common-source configuration will be asked in the exam.
- For the op amp, you read from Chapter 2. This is the most easy topic that you will learn from this course.
- For the basic of current mirror, differential amp, analog filter and some oscillator, you read those from Chapter 8, 9, 17 and 18. The oscillator circuit is analysed more easily if you know things from feedback in Chapter 11.

Chapter 11 and 13 will be taught further in PRIN ANALOG CIR. Chapter 14 to 16 is very helpful if you want to study DIG IC in the future.

If you want to read the textbook that arrange its content in the same way as of the course, you can refer to **Microelectronics Circuit Analysis and Design by Donald A. Neamen**. I cannot comment on that book since I have not read it yet. (I just skim on it.) Other recommended textbooks are **Fundamentals of Microelectronics by Behzad Razavi** and **Microelectronic Circuit Design by Richard C. Jaeger**, those I haven't read yet, too.

{: .note } 
The terminology used in this course is not the same as in any standard textbook. It is also not mentioned by the prof AT ALL. (Why? :expressionless:) So, I note it here: 
- A(vin) = voltage gain with no load and no source resistance
- A(vn) = voltage gain with no load but with source resistance
- A(vi) = voltage gain with load but no source resistance
- A(v) = voltage gain with load and source resistance

---

### EE432: LIN CONT SYS II (compulsory elective; control system theory)

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: :star: :star: :star: \\
Exam Difficulty: :star: :star: :star: :star: :star: 

I would like to say that this is a course which teaches all the things that you should have learnt in ELECT ENG MATH II and LIN CONT SYS I but have not learnt yet.

For the first half before midterm, [Ajarn David](https://ee.eng.chula.ac.th/david-banjerdpongchai/) will review about all of the mathematical topics relevent to the course. Some topics that you have not learnt yet are:
- QR factorization and Gram-Schmitt algorithm. (Why it was not taught in ELECT ENG MATH II!?)
- left and right eigenvalues/eigenvectors.
- least-square solution and pseudoinverse.
- Jordan canonical form.

Then, for the second half after midterm, (finally) the topics are shifted to control system theory.
- controllability and observability.
- minimalization of control system.
- state-space feedback design.
- state observer and observer-based controller.
- introduction to servomechanism problem.
- optimal state feedback (LQR problem.)

The advanced topics will be taught, but will not be appeared on the exam:
- optimal LQG control design.
- robust control design.
- model predictive control design. (MPC)

For the recommended book, I suggest that for the first half, you should rely on any linear algebra textbook (I have recommended **Linear Algebra and Its Applications by David Lay, Steven Lay and Judi McDonald** in ELECT ENG MATH II and you should be fine if you have read it all.)

For the second half, you can rely on the last 2 Chapters (5th edition) of **Modern Control Engineering by Katsuhiko Ogata**, but it won't be enough. **[Ajarn David](https://ee.eng.chula.ac.th/david-banjerdpongchai/)'s slides** should be enough and I find it *relatively* easy to read by yourself. I found that **A Linear Systems Primer by Panos J. Antsaklis** to be very concised mathematically. (For instance, many practical-oriented books such as Ogata or Dorf do not differentiate between *controllability* and *reachability* anymore, but this book from Antsaklis does explain how both are different.) So, I recommend that book if you have time.

P.S. Most of the sildes from Ajarn David is brought from Stephen Boyd's EE263 materials of Stanford University. [Link](https://ee263.stanford.edu/archive/).

---

### EE444: INTRO EMBED SYS (compulsory elective; electronics)

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: :star: :star: :star: :star: \\
Exam Difficulty: :star: 

This course is a rely-on-yourself course. I'm not kidding.

For the first half, you will learn about C and C++. You will also learn some (very little) computer architecture relevant to embedded system. The AVR assembly language will be taught (a little.)

For the second half, you will learn about Arduino (hands-on.) You will also learn about some embedded system low-level communication (SPI, I2C, CAN, etc.) 

The recommended book for learning C by yourself is **C: How to Program by Harvey Deitel and Paul Deitel**. Actually, you can learn C from any source since it is a relatively easy programming language. 

For the C++, the situation is very different. C++ is easy to learn but very hard to be mastered. ([You can see this meme.](https://www.reddit.com/r/ProgrammerHumor/comments/7eyrbx/how_to_learn_programming_in_21_days/)) For a quick start, I recommend **C++ Programming by D. S. Malik**. Until you find yourself say "Fuck, I could not understand other C++ codes even though I read that book." that I suggest you to read further in:

**C++ Primer by Stanley B. Lippman**: This is recommended by so many Reddit users in the programming field. Very hard to read in my opinion but I got through this book and have no regret afterward. It will take your time and your brain energy. Get prepared for pointers (a LOT of.) Be prepared for headache.

**Programming - Principles and Practice Using C++ by Bjarne Stroustrup**: Written by the creater of C++ himself, this is also recommended by so many (I mean 99% of) Reddit users. The only downside of this book is that it is very big and take much time for beginner. But hey! C++ is supposed to take a lot of time anyway! So why not just read this book to save any further headache?

For Arduino programming, I think learn from your own projects (those will be provided in the class anyway) is the best way. 

Class materials should be enough for the exam. But for anyone further curiousity, I suggest taht you read **Making Embedded Systems by Elecia White**. It is the *overview* in professional world of embedded design.

---

### CP574: AI ENG (free elective; a course from computer engineering)

Quantity of Content: :star: :star: :star: \\
Course Workload: :star: :star: :star: (If you do them by yourself.) \\
Exam Difficulty: (No exams.)

{: .note } 
This is not a course in EE. This is a course from CP which is open for any student EXCEPT from CP itself.

I love this course, the reasons are
- A is guaranteed for those who summit all homeworks on time. (On time = before the final exam.)
- There is no exam in this class.
- How much you learn from this course depends on how much you work on this course. You can struggle through the HWs and get skills, or you copy other's HWs effortlessly and get nothing. (Academic integrity is a thing and I don't recommend you do that.)
- All works can be done by yourself. This course has no group project so congratulation for introverts.

Course materials and class attendances should be enough for you to get through this course. You don't need to get an A in the 1st year computer programming course to be good in this AI ENG course. This course DOES NOT guarantee that you will get a job in ML or data analytics or somethings. Anyway, this course is recommended by me because you will learn the best practice in ML and data analytics from the professors themselves. Many professors are actively finding someone who want to work in ML (as a researcher assistance) from this course members; some of my friend in EE got research works of CP prof from this course. Again, this course provides many opportunities, but it depends on how much you works for.

Course content for each week:
- Week 1: Introduction to AI for Engineers
- Week 2: State-Space Search
- Week 3: Iterative Improvement Algorithm
- Week 4: Machine Learning Pipeline
- Week 6: Linear Regression
- Week 7: Logistic Regression
- Week 8: Naive Bayes Classifier
- Week 9: Decision Tree
- Week 10: Unsupervised Learning
- Week 11: Neural Networks
- Week 12: CNN
- Week 13: Transfer Learning
- Week 14: Sequence Modeling

---

### EE447: ETRON ENG LAB (compulsory lab; electronics)

Quantity of Content: :star: :star: \\
Course Workload: :star: :star: :star: :star: \\
Exam Difficulty: (No exams.)

There are 3 labs. 
- The first one was designing amplifier for ECG signal. In my year, it was done entirely in LTSpice. In A.Y.2022 (on-site teaching,) I heard from my friend that it was done by discrete components on breadboard.
- The second one was designing IR break beam sensors system for pass-through-a-door detection. I did this lab on-site. The discrete components given by the lab were sometimes (30 - 40%) broken so you have to test them one-by-one by yourself (recommended.) This lab took so much time.
- The last one was about IoT. Follow the instructions and you will be fine.

This course is fun (in my opinion.) Prof are not very stricted about neatness of the lab reports.

---

### EE436: CONT INSTRU LAB (compulsory lab; control system theory)

Quantity of Content: :star: :star: \\
Course Workload: :star: :star: :star: :star: :star: \\
Exam Difficulty: (No exams.)

I will not talk about the labs, I will talk about the workload.
- You will be in the group of 3-5 people (depended on how many students in the section.)
- All lab reports have to be done **in a very stricted way**. (Do not make them like a primary-school student.) Note that this has to be done for **all labs**.
- There are 8 labs (8 weeks and you are done.)

This is the sample report from my year ([link](https://mega.nz/file/Sqo0ULgJ#l6xQNdXdEu9vac-iRfbxxAgqInuQ7fctSG9ElQpIDVs).) Note that this is an average work for one lab. Do not underestimate this course: it takes so much time. Choose your partners wisely.

---

## Year 4 Semester 1

![Kyoto, Japan](kyoto-japan.jpg)
*Kyoto, Japan (Photo by Kristin Wilson)*

{: .warning } 
This semester is very heavy. I DO NOT RECOMMEND YOU TO TAKE 22 CREDITS MAX OR MORE THAN THAT! I assume that you still want to have life outside studying. I also assume that you don't want a life like medical students who need more than 60 hours per week of studying. This semester has a pre-project course. This semester has many courses which are supposed to be for Master students, and those courses are much more heavy than you have imagined when you are in the 2nd or 3rd year. So, please do not underestimate this semester. You will hate yourself if you are studying too much.

### EE401: RANDOM PROC EE (compulsory elective; control system theory)

Quantity of Content: :star: :star: :star: :star: :star: \\
Course Workload: :star: :star: :star: :star: :star: (JSS), :star: :star: (CPW) \\
Exam Difficulty: :star: :star: :star: :star: :star: (JSS), :star: :star: :star: :star: (CPW)

This is the course which teaches all the things that you should have learnt in ELECT ENG MATH II, PROB STAT ELEC ENG and PRINC COMM but have not learnt yet.

For the first half before midterm, [Ajarn Jitkomut](http://jitkomut.eng.chula.ac.th/) will teach you all of the basics

Topics that are taught in this course (that should be in the PROB STAT ELEC ENG) are:
- Markov chains
- characteristic functions of distributions
- many special characteristics of Gaussian
- random vectors
- principal component analysis
- etc.

Topics that are taught in this course (that should be in the ELECT ENG MATH II) are:
- symmetric matrix
- orthogonality and orthonormality
- unitary matrix
- properties of definite matrices

For the second half of this course, [Ajarn Charnchai](https://ee.eng.chula.ac.th/charnchai-pluempitiwiriyawej/) will teach (finally) about the topics in random processes. The book used by both professors is **Probability, Statistics, and Random Processes For Electrical Engineering by Alberto Leon-Garcia**. To be honest, I find *so many errors* in that book that it caused some annoyance for me, but whatever. Ajarn Charnchai will teach on Chapter 9 and 10 in that book (3rd edition.)

To me, I find the classes in random processes to have so many approach to be taught. Ajarn Jitkomut will approach this course in a data-analytics-oriented way since her researches are related to that field. For Ajarn Charnchai, the approach is communication-oriented. Many really essential topics (in my speculation) in random processes are skipped such as queueing theory (it is taught in the another course, that is TRAF ENG COMM NET by [Ajarn Chaodit](https://ee.eng.chula.ac.th/chaodit-aswakul/)) In my opinion, the field of random (stochastic) processes is freaking huge! The other book recommendation from me are **Essentials of Stochastic Processes by Rick Durrett** and **Introduction to Stochastic Processes with R by Robert P. Dobrow**.

---

### EE427: MMEDIA COMPR TECH (elective; communication)

Quantity of Content: :star: :star: :star: :star: :star: \\
Course Workload: :star: :star: :star: \\
Exam Difficulty: :star: :star: :star: :star:

Why I'm in this course is still mesmerizing myself lol.

This course is recommended for those who want to learn the data compression techniques in a very concised way. I don't know how [Ajarn Supavadee](https://ee.eng.chula.ac.th/supavadee-aramvith/) can compress all of the topics in just one semester!? The book used in this course is the holy grail, the one and only, **Handbook of Data Compression by David Salomon**. This book is more than 1300-page long! I found myself could not learn this topic by myself obviously, so I took this course.

Bonus from this course is that you will finally know 
- why ffmpeg can only cut the MPEG video in a lossless way at only some of the certain keyframes.
- why JPEG compression can be done in more than 50% compression ratio without visible changes.
- how f--king complex modern audio compression (MP3) is.

---

### EE433: DIG CONT SYS (compulsory elective; control system theory)

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: :star: :star: \\
Exam Difficulty: :star: :star: :star: 

I strongly recommend that you should take LIN CONT SYS II before this course.

The course materials are mostly overlapped with the LIN CONT SYS II material. Anyway, some topics are new and I recommend that, for those who are interested in digital control system but have already taken the LIN CONT SYS II, you should still take this course.

The topics that are not overlapped with the LIN CONT SYS II are:
- zero-order hold
- continuous-time to discrete-time system estimation
- designing of discrete-time system to meet step response specifications (how it is different from continuous-time system?)
- reduced-order state observer (not appeared in the exam.)
- generalized linear observer (not appeared in the exam.)
- Kalman equation for solving Riccati equation.

For the book, I strongly recommend that you read **Digital Control and State Variable Methods by M. Gopal**. This book is very comprehensive, mathematically concise and practical-oriented. I also strongly recommend **Digital Control System Analysis and Design by Charles L. Phillips**. This book has a topic on reduced-order state observer.

Last comment: Why Jury stability criterion is not covered in this course???

---

### EE489: PRIN ANALOG CIR (compulsory elective; electronics)

Quantity of Content: :star: :star: :star: :star: :star: :star: \\
Course Workload: :star: :star: :star: :star: \\
Exam Difficulty: :star: :star: :star: :star: :star: 

Note: BJT is forgotten.

This course is supposed to be continued from ETRON CIRCUIT/LAB of the last semester. This includes

- More MOS characteristics.
- More topologies of Amplifiers.
- More Differential Ampifiers.
- More Current Mirrors.
- More Frequency responses.
- Noise.
- Feedback.
- Op-Amp internal circuit.
- Frequency compensation techniques (not on the exam.)

To be honest, if you hate ETRON CIRCUIT/LAB, you will hate PRIN ANALOG CIR more. Consider your decision in taking this course thoroughly.

The recommended books are:

**Design of analog CMOS integrated circuits by Behzad Razavi**: The holy grail in analog circuit design. Read this book thoroughly and you should be fine for this course. 

**Analysis and Design of Analog Integrated Circuits by Paul R. Gray**: This book is for my reference. I personnally find that this book is not for beginner, but for someone who needs variety of analog circuit references with very concise mathematical handling. 

**CMOS Circuit Design, Layout, and Simulation by R. Jacob Baker**: This book is recommended by so many people that I decide it should be on the list. It covers so many essential topics in microelectronics that you should know. I find this book to be more practical-oriented than theoretical-oriented, that you can learn from this book by your own interests.

**Microelectronic Circuits - Sedra & Smith**: This book is never be enough for this course. But for me, I found that the explanation of feedback topologies in Razavi book to be very hard to read. I found that Sedra & Smith explain feedback topologies much, much better.

I would like to say that you will not have time in this semester, so read only this first book and you should be fine. Also, I strongly recommend that you read the quick review from [Ajarn Boonchuay](https://ee.eng.chula.ac.th/boonchuay-supmonchai/) since his materials are very helpful in quick analog circuit analysis. He is going to be retired in 2023 so I will put his materials (together with of [Ajarn Napong](https://ee.eng.chula.ac.th/napong-panitantum/)) here: [Link](https://mega.nz/folder/ynQi1DSZ#adxcxV-sO7ii0TwU4iqCeA)

---

### EE505: INTRO OPT TECH (elective; control system theory)

Quantity of Content: :star: :star: :star: :star: \\
Course Workload: :star: :star: :star: :star: :star: :star:\\
Exam Difficulty: :star: :star: :star: :star: :star: 

<img src="meme.jpg" alt="meme" style="width:200px;"/>

This course is hard. I bombed the final exam *entirely*.

The topics in this course are:
- mathematics review.
- solving nonlinear equations (bisection, Newton-Raphson, secant.)
- unconstrained optimization:
    - optimality conditions.
    - line search (bisection, golden section, quadratic and cubic interpolation.)
    - steepest descent method.
    - Newton's method.
    - conjugated direction methods.
    - quasi-Newton methods. 
- constrained optimization:
    - optimality conditions (including KKT.)
    - linear programming
    - active set method for quadratic programming with linear constraints.

You need to love mathematical proving to do this course homework. You also need to love MATLAB.

The recommended books are:

**An Introduction to Optimization by Edwin K. P. Chong**: This book is used by [Ajarn Suchin](https://ee.eng.chula.ac.th/suchin-arunsawatwong/), and I find it relatively easy to read. Use this book along with the prof's materials and you should have the best understanding from this course.

**Linear and Nonlinear Programming by David Luenberger**: This book is used worldwide. I recommended that you also use this book along with the course.

**Algorithms for Optimization by Tim A. Wheeler and Mykel J. Kochenderfer**: If you don't know where to start in coding MATLAB, you can start from this book. Even though this book uses Julia as a programming language, you should have no difficulty in applying those to your own MATLAB works.

To be honest, I find this course to be somehow more heavy in mathematical theory than it should. The final exam also requires real brain power to do numerical things, and proving mathematical problems in 3-hours exam, for me, was exhausting. Since Ajarn Suchin will be retired next year (2023,) Ajarn Jitkomut will take place to teach this course. You can see how the course will be taught in the future (speculation, again) from this [link](http://jitkomut.eng.chula.ac.th/optim.html).

---

### EE545: DIG IC (elective; electronics)

Quantity of Content: :star: :star: :star: :star: :star: \\
Course Workload: :star: :star: :star: :star: :star: :star:\\
Exam Difficulty: :star: :star: 

For those who want to do digital design in the future, I recommend that you take this course. It is not required, though. (You don't have to know how to fabricate IC to do digital design, but it is always helpful.)

This course is all about how to implement what you have learnt in FUND DIGIT CIRCUIT in the real IC. The topics covered are:

- MOS characteristics (including short-channel nonideality.)
- IC fabrication.
- Wiring in IC.
- Delay.
- Static and Dynamic logics.
- Combinational (NAND, NOR) and Sequential (flipflop, latch) logics and layouts.
- Timing constraints.
- Arithmetic circuits and datapath.
- Testing of digital logics.

The recommended book is **CMOS VLSI Design: A Circuits and Systems Perspective by Neil Weste and David Harris**.

---

## Year 4 Semester 2

{: .note }
I decided to take only 2 subjects in that semester because I needed to take (many) Chinese courses at that time before going to Taiwan for my Master's degree. Also, I didn't know how much the senior project workload would be at the time, too. 

### EE546: ANALOG IC (elective; electronics)

Quantity of Content: :star: :star: :star: :star: :star: :star: \\
Course Workload: :star: :star: :star: :star: :star: \\
Exam Difficulty: :star: :star: :star: :star:

Firstly, [Ajarn Napong](https://ee.eng.chula.ac.th/napong-panitantum/) will teach you some essential analog components that are not covered yet in EE489 (PRIN ANALOG CIR). These are:

- Bandgap References (a.k.a. how to generate very-precise reference voltage, that is temperature-independent.)
- Oscillators 
- Phase-Locked Loop
- Switched-Capacitor Circuits

For these four topics above, they rely on the same textbook **Design of analog CMOS integrated circuits by Behzad Razavi** that you should already accustom to if you have learnt the EE489 before. However, for the topic of "Switched-Capacitor Circuits," Ajarn Napong will use the new textbook: **Analog Integrated Circuit Design by Tony Chan Carusone**. This textbook will cover Switched-Capacitor Circuits in the time-domain, Z-transform sense, which could be used further in filter design. The design procedure will be greatly helped by Z-transform, and it will be more make sense if you have learnt EE433 (DIG CONT SYS) before.

Then, the Tony Chan Carusone's textbook will be mainly used. The topics that will be covered further are:

- Data converters
    - Nyquist-Rate ADC
    - Nyquist-Rate DAC
    - Oversampling ADC/DAC (with the famous Delta-Sigma converter.)

These, for me, is the whole new world where analog has changed its feeling. You will use more mathematics than the physics of devices for the first time here. Also, there will be the feeling that finally, you know how the digital world could help analog world to operate in a proper, good way.

Finally, there will be a final project. Ajarn Napong will give you 2 projects (as of my semester) and you only choose one.

These are:

- Designing system-level oversampling ADC/DAC on the Academic Process Design Kit by Institut de Microelectrònica de Barcelona. If you are motivated enough, you can learn it from here: [link](http://www.cnm.es/users/pserra/apdk/).
- Use skywater130 pdk to reduplicate the circuit on some papers on IEEE and compare the result. You can see how to install the toolchain in an easy way in my video on YouTube: [link](https://www.youtube.com/watch?v=l5ollq9Nbl8). Also, The project that I've done with Makkawan Lohitsiri for you to see as an example can be found in [link](https://nutchanonj.github.io/pages/12_analog_ic_design/).

The final project is very comprehensive. I recommend that you should definitely take this course if you want to do an analog circuit design in the future. 

---

### EE519: REINFORCE LRN APP (elective; Data Science Master's Degree at CUEE)

Yes, I take this course because [Ajarn Chaodit](https://ee.eng.chula.ac.th/chaodit-aswakul/).

This course weights only 1 credit and is taught for only 5-weeks-equivalent. (In my semester, it is 3 full-days.) Textbook used in this course is the holy-grail, **Reinforcement Learning: An Introduction by Andrew Barto and Richard S. Sutton**. Ajarn Chaodit will try to teach up to Chapter 7th in that book. Even though his style of teaching is very slow (in my opinion only,) so if you have a good wit, I recommend you to go through that book by yourself prior to class.

Also, if you want to have a good summary, Lilian Weng of OpenAI have made a very good, concise content for you: [Here](https://lilianweng.github.io/posts/2018-02-19-rl-overview/) and [Here](https://lilianweng.github.io/posts/2018-04-08-policy-gradient/).

In my opinion, this course is so damn good. An eye-opener for me. Compare to the optimization techniques, the reinforcement-learning approach seems to use less maths and more common sense to achieve something.

---

Even though I didn't take some courses, there are some book recommendation that worth mentioning here for those who take these courses:
- EE575: STAT INFER MODEL
    - An Introduction to Statistical Learning: With Applications in R by Daniela Witten, Gareth James, Robert Tibshirani, and Trevor Hastie.
    - The Elements of Statistical Learning by Jerome H. Friedman, Robert Tibshirani, and Trevor Hastie
    - Pattern Recognition and Machine Learning by Christopher M. Bishop
    - For other books, pls refer to [Ajarn Jitkomut's website](http://jitkomut.eng.chula.ac.th/ee575.html).
- EE423: DIG SIG PROC
    - Digital Signal Processing by John Proakis and Dimitris Manolakis.
    - (I, also my friend Taran, find the DSP book from Alan V. Oppenheim too hard to read.)

## Some Study Guide

{: .note } 
For answering this, I decide to write it as the Q&A so that it is more engaging.

{: .warning } 
DISCLAIMER: you don't have to do all of these. These are only my suggestion. The expectation from studying are varied. So, you don't have to do all these things.

### Q1: Should I just learn the materials, or just do the exercises and former exams?
{: .no_toc }

A1: TL; DR: Do both.

I would like to say that, ideally, the exams of a course should be the feedback of how much you understand the coursework. But no prof could give you many times of feedback since s/he has no time. Hence, you must feedback yourself how much you have learnt by doing exercises and former exams by yourself. It may be true that you can do those things without fully understanding the concepts of a coursework, but it not worth to do that. Some (many) courses are the pre-requisite for the subsequence courses, that some (or many) misunderstanding from the prior course(s) would be some (big) burden for you in the future. Therefore, you should have time to contemplate about the concepts taught in the courses to understand those to the cores. It supposes to take time.

---

### Q2: Should I rely only on professor’s materials, or should I study further in the associated textbook(s)?
{: .no_toc }

A2: It’s depended on how difficult the exams are, or how much quality of teaching in the course, or ultimately, how much you want to learn.

I would like to say that for 2nd year courses, quality of teaching is still very good. Rely on attending the class and do your HWs/exercises/former exams should be enough; textbooks are used for curiosity. Until 3rd year that some courses are taught in an ill-manner way, that you have to rely on textbook(s) for that course. You can rely on my CUEE courses review to see the recommended textbooks for each course.

---

### Q3: Textbook is very hard to read. What is the recommended way to learn from textbook?
{: .no_toc }

A3: This is my recommendation:
-	Step 1: Study from the course materials first to see the keywords or key concepts of the course.
-	Step 2: Skim through the textbook to see how the content in a textbook associate with the keywords or key concepts of the course. This way, you will have some prior idea or picture of the content, and it will help you with the process of comprehension from the textbook.
-	Step 3: Read it thoroughly.

I would like to say that for each course, you don’t have to read the entire textbook. Read just some parts of it that are not beyond your *frontier of knowledge*. 

I also recommended that some courses really need professors to guide what you must learn from a course (a.k.a., the key concepts.) It’s faster to learn this way.

Also, there will be textbooks that your love and you hate, e.g., some of textbooks are readable for you but some aren’t. I recommend that you read some of its chapters to determine whether you are ok with the book or not. That is why in my CUEE courses review, there are some courses that I recommend 2-3 books so you can choose them for your favor.

---

### Q4: You mentioned the *frontier of knowledge* in the last Q&A. What is it?
{: .no_toc }

A4: There will be time that you read the textbook and not understand it at all. It indicates that this content is beyond your *frontier of knowledge*.

For concrete example, suppose that you want to read about microelectronics from Sedra & Smith. At some point, you need to know some concepts from LIN CON SYS I (root locus, Nyquist’s stability criterions, etc.) to understand how the feedback in circuits works. Surely, there will be a brief review about those topics, but it will assume that you already know those, so the review is very succinct and unfriendly to the novice.

What can you do about this situation? One of the ways is that you have to learn about LIN CON SYS I concept first from professors. What if you are hurry? Then, you need to read LIN CON SYS I by yourself. Maybe from Ogata or Dorf. What if you don’t understand those text by reading yourself? Consult the EE Math II materials what you don’t really understand. This process is recursive as explained. This requires patience and time.

---

### Q5: I am not good at English reading. How can I learn from textbooks which are mostly written in English?
{: .no_toc }

A5: Then you read the textbook. Everyone must start somewhere. If you don’t know the word, use the dictionary, and note the meaning in the book directly. You will thank yourself later when you have to take TOEIC, TOEFL or IELTS before applying for jobs or graduate admissions, or when you have to read a fuckton of research papers in the 4th year. I agree with you that if you are not good at English, reading textbook will take much more time, but it worth it. You will thank yourself later.

---

### Q6: Should I buy the textbook, or print it out from downloaded (pirated) file, or just read it on iPad?
{: .no_toc }

A6: You can use www Dot libgen DOT rs to load the textbooks. (Pirated.) Don’t forget to sort by year so you can get the latest edition of the book. If you are going to read a lot, print it; your eyes are precious. If you can afford the book or you’re very appreciated the writer, then you buy the book.

However, I don’t recommend you buy the book before downloading it and reading its some chapters. This is because you don’t know yet if the book is really for you. Again, there will be textbooks that your love and you hate, e.g., some of textbooks are readable for you but some aren’t. So, I recommend that you read some of its chapters to determine whether you are ok with the book or not before buying it. In addition, the library of Chula Engineering has many great textbooks (not kidding, some are out-of-date editions but still very good resources) that you can lend, so you can be frugal.

Also, there will be time that Chula Book Center dumps the price of their international textbooks to insanely low price. (I had an experience that the price of Cryptography and Network Security by Stalling was sold at 99 baht!?) The promotion usually takes place at the end of each year. So, go check the prices; you may lucky!

---

### Q7: Reading textbook(s) is a very heavy task, should I really read the textbook(s)?
{: .no_toc }

A7: Yes. This is the undergrad, not a school.

---

### Q8: One textbook for a course is enough or not?
{: .no_toc }

A8: Usually not. You can see from my CUEE courses review that I recommend 2-3 books so you can use them parallelly in a course. Surely there will be one main textbook that you read, but the other are also essential as the additional references. This is the way of study; one textbook is usually not enough to understand the course. Fortunately, this is the age of the Internet (and lots of pirated textbooks.)

---

### Q9: Is the academic integrity really matter? Do professors really do the investigation and punishment(s) when there is a misconduct in academic integrity?
{: .no_toc }

A9: There is a chance that you will get caught, and it is never worth it. DO NOT CHEAT, EVEN COPYING HWs! Especially for some professors (e.g., JSS,) the consequence is not worth it at all.

![course-policy-exampl](course-policy-exampl.png)
 
Do you think this HW policy is long and tedious? The answer is not. For the prestigious universities, like UC Berkeley, the 3-page-long document for Academic Misconduct Policy is very common. You can see the example [here](https://fa22.datastructur.es/materials/guides/academic-misconduct/).

{: .warning }
I have warn you. It's not worth it.

---

### Q10: I have finished the 2nd year now and still hesitate about which majors should I choose. (Power, Communication, Electronics, Control System.) Is that normal?
{: .no_toc }

A10: Yes. However, you should finally decide after finishing the 1st semester of 3rd year, in which you will learn all the fundamentals in those four majors. Trust me, at that time you will know what you really want to study.

---

### Q11: Can I choose 3 majors in (Power, Communication, Electronics, Control System?)
{: .no_toc }

A11: Yes. There are people in the past who can do that. Personally, I do not recommend you do that since you will not have time to take the non-compulsory electives in each field enough, that you will know things like a jack of all trades, master of none.

---

### Q12: There are too many electives that I want to learn. Should I take more than 22 credits per semester so I can learn all of those?
{: .no_toc }

A12: You can, but it is not recommended. Even if you really want to do so, taking beyond 23-24 credits will be considered heavily by the registrar. The process will take like 1 to 2 months, and you have to declare explicitly why you really want to take that many credits (mine is a 2-page long document.)

Even if you can get through that tedious process, taking beyond 22 credits will exhaust your time too much that you will hate yourself. Also, your health will be deteriorated.

My recommendation is that you only take the courses which you really want to understand, or that you cannot self-study. You don’t have to know everything!!

---

### Q13: How much GPAX is great?
{: .no_toc }

A13: Would like to say that GPAX above 3.80 is already very great, beyond that is not significant anymore. Takes time for other things (competition, self-study, internship, part-time paid or unpaid work) are better. Also, please note that if you want to study Master at the top U. (internationally) in the future, immediately after graduation, GPAX is important. Some U. declare the average GPAX of the admitted students. For example, U. of Melbourne has the admitted Master students with the average GPAX of about 3.7-3.8 (IIRC.)

---

### Q14: What should I prepare if I want to study Master program in a top international university in the future (after graduation?)
{: .no_toc }

**GPAX** – Above 3.80 and you should be fine. Below this is also fine if you have strong background (internships, research works, activities, competitions, etc.) Note that anything could happen. Good luck.

**English assessments** – TOEFL and IELTS are both fine. Universities in both U.S. and U.K./E.U. are now generally accept both tests. TOEFL 100 is recommended. Also, each part (writing, speaking, listening, reading) should be more than 22, and you are safe. This is from my searching through lots of (more than 50) universities’ admission requirements. The exam result (both TOEFL and IELTS) can be kept for 2 years.

P.S. If you want to talk with computer, take TOEFL. In contrast, If you want to talk with human, take IEFLS. The costs are not different that much.

**GRE** – Some universities require you to take this test. There are three sections: Verbal, Quantitative, and Analytical. Verbal section is like an English test; its vocabs are difficult and not found in everyday life. Quantitative section is like an easy math test that you, the EE student, should be fine. Analytical section is a critical-thinking-kind-of writing test. I personally have not taken the exam yet. This exam requires lots of preparation. The exam result can be kept for 5 years.

The other important things are your activities and internships. I recommend that you also have those in the portfolio.

For others, you can prepare it at the time of application (letter of recommendations, statement of purpose, passport, and your picture; those take not so much time.) I will talk about those later in another post.