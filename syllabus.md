# EECE2160: Embedded Design Enabling Robotic Syllabus (Fall 2017, Section 8)

## Instructor

[Yifan Sun](https://syifan.github.io) (yifansun@coe.neu.edu)

### Office

R306, 140 the Fenway. You can follow the instruction [here](https://syifan.github.io/contact.html) to find my office.

### Office Hours

* Monday 10 am - 12 am **In Office**
* Thursday 7 pm - 8 pm **Online**

If you are planning to come to the office hour, please come at the beginning of the time slot, since many students usually have the same question.

## Teaching Assitant

**Nasim Shafiee** shafiee.n@husky.neu.edu - Office Hour: Friday 12 - 2 pm

**Luxi Zeng** zeng.l@husky.neu.edu - Office Hour: Tuesday 4 - 6 pm

TA office hours will be held in 009c Hayden Hall.

## Online Discussion

Slack is used for online discussion. Students are encouraged to help eath other on Slack. Instructor and TAs will try their best to answer students questions.

## Class Schedule

* Tuesday 9:15 am - 11:30 am @ 009c Hayden Hall
* Friday  9:15 am - 11:30 am @ 009c Hayden Hall

## Overview

This course presents fundamental concepts of Computer Engineering from a comprehensive, full-stack, software-hardware design perspective. The course explores scripting languages, high-level programming, Unix/Linux operating systems, device drivers, software-hardware interfaces, hardware controllers, and digital circuit design. The course is accompanied by a hands-on lab where students apply theoretical concepts on a full-system ZedBoard platform, featuring a programmable logic module, an ARM processor, and an Ubuntu distribution of the Linux operating system. Students will design custom creative software-hybrid designs interacting with a variety of hardware devices connected to the ZedBoard, including LEDs, push buttons, switches, OLED screens, a Wiimote, and a remote-controlled robotic arm.

## Course Objectives

* Become familiar with the Unix/Linux command-line interface
* Learn new C and C++ programming techniques building upon prerequisite courses
* Understand the principles of digital logic design
* Acquire knowledge of embedded system design
* Get exposed to wireless networking and robotic control
* Develop an appreciation for the software/hardware interface

## Prerequisites

This course assumes a basic understanding of the structure of a C/C++ program, as taught in the General Engineering introductory course GE-1111, titled Problem Solving and Computation.

## Reference

The material presented in this course is a compilation of topics extracted from the following textbooks. The order of topics does not strictly match any of these textbooks in particular.

* Etter and Ingber, “Engineering Problem Solving with C++”, Third Edition, Pearson, 2012, ISBN 978-0-13-249265-2
* P. Deitel and H. Deitel, “C++, How to Program”, 9th Edition, ISBN 978-0133378719
* M. M. Mano and M. D. Ciletti, “Digital Design”, 5th Edition, January 2012, ISBN 978-0132774208

## Grading

| Item          | Scheme 1 | Scheme 2 |
|:-------------:|---------:|---------:|
| Lab           | 30%      | 30%      |
| Quiz          | 20%      | 0%       |
| Final Project | 10%      | 10%      |
| Midterm Exam  | 20%      | 30%      |
| Final Exam    | 20%      | 30%      |

Two grading schemes are provided for students. The final grade of each student will be taken from the higher value.

Quizzes are given at the beginning of the classes. There are no make-up quizzes. Please inform your instructor before the class if you cannot come in for really important reasons.

I will geneally use the Friday class as lab sessions and use the Tuesday class as lection sessions. Each lab will require you to write some code or write a report. The due time of each lab is 23:59 of the next Thursday, unless otherwise noticed. The deadlines are stict. So please do not submit your homework at the last minutes. Since the Labs will be completed in groups(no more than 2 students per group, the group formation cannot change during the semester), group members will receive the same score on the Labs.

Each team (no more than 2 students, can be different from the homework group) will be required to work on a final project at the end of the semester. The topics will be anounced later. Students are encouraged to come up with their own creative ideas.

## Lab Assignment

This class includes a weekly lab session that provides students with hands-on experience on an actual embedded platform: a ZedBoard based on the Zynq system-on-chip (SoC). The platform runs xiLinux, a flavor of the popular Ubuntu Linux distribution. Students will write C/C++ programs on Linux for the ZedBoard, will develop digital designs that are embedded to run on the FPGA of the Zynq SoC, will interface to a wireless Wii remote, will interface to read/write switches/buttons/LEDs on the ZedBoard, and will control a robotic arm with the ZedBoard.

## Course Projects

Students can work individually or in groups of at most two people on a final course project. Groups do not necessarily have to be the same as the lab groups. There will be a set of proposed project topics to choose from, published at least three weeks before the project due dates. The project due dates will be announced in class during the second half of the semester.
The list of proposed projects will be only aimed at giving the student an idea of the expected complexity and topics to choose from. However, students will be encouraged to be creative and propose their own project ideas. Projects will be evaluated based on the quality and quantity of the work, and especially on the student's creativity. One full lab session will be available during the last week of the semester for the students to use the lab equipment should a particular project require it.

## Midterm and Final Exams

A midterm exam will cover the first part of the course material. A comprehensive final exam will focus on the second part of the course, but will also include the material corresponding to the first part. The date of the midterm is available at the end of this document. The date of the final exam will be announced during the second half of the semester.

## Attendance and Punctuality

Attendance to the lectures is highly recommended, while attendance to lab sessions is mandatory, as you will be working in teams. Punctuality for both lectures and lab sessions is indispensable, and constitutes a basic rule of respect toward your class mates and your instructor. If any particular reason forces you to come in late to class, please let me know in advance by email or in person.
If you come to office hours, please show up at the beginning of the corresponding time slot. It is expected that multiple students have similar questions and benefit from the same answers. This will allow us to use everyone's time more efficiently.

## Course Topics

### Unit 1 Linux and the ZedBoard

* Organization of a computing system
* The ZedBoard architecture
* The Linux shell
* The Linux file system
* The vi editor
* The gcc compiler
* File commands

### Unit 2 Arrays, Pointers and Dynamic Memory

* Arrays
    * Searching
    * Mirroring
    * Sorting
* Pointers
* The address-of operator
* Pointer declaration
* The dereference operator
* Arrays vs. pointers
* Pointer arithmetic
* Dynamic memory allocation
* Dynamically allocated arrays
* Function argument passing
* The program memory layout
* Data structures
* Linked lists
* Building a program with gcc
* Working with multiple source files

### Unit 3 Object-Oriented Programming

* Dynamic memory
* Classes
* Constructors and destructors
* Instantiation
* Inheritance
* Virtual functions
* Abstract classes
* Example of non-pure virtual functions
* Multiple inclusion
* Makefiles

### Unit 4 Information Representation

* Base conversion
* Hexadecimal representation
* Binary arithmetic
* Signed numbers
* Signed binary arithmetic
* Overflow
* Sign extension

### Unit 5 Boolean Algebra and Logic Gates

* Postulates and truth tables
* Logic gates
* From Boolean function to gate diagram to truth table
* Theorems
* Simplification examples
* Canonical forms
* From truth tables to Boolean functions
* Problem: the divider-by-3 circuit
* 2-, 3-, and 4-variable Karnaugh maps
* Undefined outputs (don't cares)

### Unit 6 Combinational Logic

* Definition
* The full adder (though K-maps)
* Binary adder
* Binary subtractor
* Binary multiplier
* Magnitude comparator
* Decoder
* Encoder
* Multiplexer
* The k-bit multiplexer
* Demultiplexer

### Unit 7 Sequential Logic

* Combinational vs. sequential logic
* Latches: simple latch, S-R latch, S'-R' latch, S'-R' latch with Enable, D latch
* Clock signals
* Flip-flops: D flip-flop, J-K flip-flop, T flip-flop
* Asynchronous inputs for flip-flops
* Registers
    * 4-bit register
    * Adding a load input
    * Shift register
    * Shift register with parallel load
* Counters
    * Ripple counter
    * Synchronous counter
    * Limited-range counter
    * Counter with direction control
    * Predefined sequence counter

## Schedule (Tentative)

| Day           | Event                                                              |
|:--------------|:-------------------------------------------------------------------|
| Friday 9/8    | **Unit 1** Linux and the ZedBoard                                  |
| Tuesday 9/12  | **Unit 2** Arrays, Pointers and Dynamic Memory                     |
| Friday 9/15   | **Lab 1** Linux and the ZedBoard                                   |
| Tuesday 9/19  | **Unit 2** Arrays, Pointers and Dynamic Memory                     |
| Friday 9/22   | **Lab 2** Dynamically Growing Arrays                               |
| Tuesday 9/26  | **Unit 3** Object-Oriented Programming                             |
| Friday 9/29   | **Lab 3** Linked Lists and the GDB Debugger                        |
| Tuesday 10/3  | **Unit 3** Object-Oriented Programming                             |
| Friday 10/6   | **Lab 4** Memory-Mapped I/O and Object-Oriented Programming        |
| Tuesday 10/10 | **Unit 4** Information Representation                              |
| Friday 10/13  | **Lab 5** Controlling the Wiimote with Object-Oriented Programming |
| Tuesday 10/17 | **Unit 5** Boolean Algebra and Logic Gates                         |
| Friday 10/20  | **Lab 6** Controlling the Robotic Arm by Software                  |
| Tuesday 10/24 | **Unit 5** Boolean Algebra and Logic Gates                         |
| Friday 10/27  | **Lab 7** Introduction to Simulink                                 |
| Tuesday 10/31 | **Unit 6** Combinational Logic                                     |
| Friday 11/10  | **Lab 8** Programming the FPGA Using Simulink                      |
| Tuesday 11/14 | **Unit 7** Sequential Logic                                        |
| Friday 11/17  | **Lab 9** Controlling Push Buttons by Hardware                     |
| Tuesday 11/21 | **Unit 7** Sequential Logic                                        |
| Friday 11/24  | **Lab 10** Controlling Servos by Hardware                          |
| Tuesday 11/28 | Backup Lecture                                                     |
| Friday 12/1   | **Lab 11**                                                         |

## Accommodations for Disabilities

Northeastern University and the Disability Resource Center (DRC) are committed to providing
disability services that enable students who qualify to participate fully in the activities of the university. Students with documented disabilities who may need accommodations, or any student considering obtaining documentation should visit the [DRC website](www.northeastern.edu/drc) or contact their staff at 617.373.2675.

## Statement on Academic Integrity

A commitment to the principles of academic integrity is essential to the mission of Northeastern University. The Academic Integrity Policy can be found in the undergraduate student handbook (pages 38-41), or from the [Office of Student Conduct & Conflict Resolution (OSCCR)](http://www.northeastern.edu/osccr/academic-integrity-policy/). I encourage you to familiarize yourself with it. If a student violates this policy in any way, I reserve the right to impose a sanction of failure on the assignment/assessment or failure in the course. If you have questions about appropriate citations, please ask.”