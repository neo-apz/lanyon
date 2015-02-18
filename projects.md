---
layout: page
title: Projects
---

## Workflow Management System (Fall 2012)

For the “Software Engineering II” class project, we had to build a simple workflow management system in which a user can design his own workflow with multiple steps and assign each step’s task to another user. After the designing phase, the user can start the workflow and the system will automatically follows the defined steps till the whole workflow finishes. We used Ruby On Rails framework, RSpec (TDD) and Cucumber (BDD) to build the whole system as a simple web application. Our written system got the highest mark.

## Blog service management application (Winter 2012)

A simple web application written mainly in PHP for managing multiple blogs. After signing up, each user can create his own blog(s). He can write posts and comment on his or other blogs’ posts. In this project my focus was on three-layer OOP (Model-View-Controller) and I used the [CodeIgniter](http://codeigniter.com/) framework.

## Designing a Knowledge Management System (Winter 2012)

In this project our goal was to build a knowledge management system for University to help the professors track their students' researches; however it can be used for general purpose projects. The registered users identified by three kinds of roles, Consumer, Collaborator or Manger where each has it’s own permissions and capabilities. The consumer can only view the uploaded documents but the collaborator (student) can edit or create new documents while the manager is the person who monitors and defines the tasks. The whole system was designed in UML which contains Use Case Diagram with it’s specifications, Activity and Sequence Diagrams, ERD, FHD and CRUD Matrix of the system.  The project was marked as the best project of the “Software Engineering 1” class.

## Simulator for OS Scheduling Algorithms (Winter 2012)

A simple OS simulator written in Java which gets an XML file consisting a process list and the details of each process such as CPU usage time or different I/O usage times and the details of the system such as available memory and the algorithms to use for scheduling. The goal was to simulate how these process will be scheduled by a real OS and calculating waiting and usage times. It supports the following scheduling algorithms: First Come First Served, Lottery, MLFQ, Priority, Round-Robin, Shortest Process Next, Shortest Remaining Time First, HRRN. The program keeps a queue for different resources and schedules each queue with its algorithm. The project was marked as one of the best projects of the “Operating Systems” class.

## SAHA: iPhone Application for Phone Bills Management (Winter 2012)

SAHA (ساها : سامانه الکترونیکی همراه اول) is an iPhone application designed for the largest Telecommunication Company in Iran, Hamrah-e-Avval (همراه اول). In this version my goal was to make the payment process of phone bills easier. In addition, the users can view their call history and the cost of each call and other detailed costs in their bills. The payment can be done via bank gateways. This application was nominated for the Best Mobile Application at the First Iran Mobile Innovation Awards held by Sharif University of Technology at Tehran in February 2012.

## Pure P2P File Sharing Application (Fall 2011)

In this application each peer can add other peers to its peer list and then asks its peer list for a file name. Each peer then replies whether he has the file or not. If the file is available the asking peer will receive the file from others. For writing this application, I first wrote a general purpose P2P Framework in Java then I wrote a file sharing application on top of it which uses an UDP flooding feature for finding peers. It was the class project of “Computer Networks” class and was chosen as the best project and I personally really like this project.

## Designing a CPU for MIPS Architecture (Fall 2011)

This was the project of our Computer Architecture class. In this project we designed a CPU in Verilog that understands MIPS Instruction Set Architecture. We first wrote different parts of it like Register File, ALU, Control Unit and etc. then combined them with the data-path to create this CPU. It really helped us to understand how a computer really works and I really enjoyed it.

## MiniOS (Fall 2010)

For this project we had to write a small OS that performs 3 or 4 small tasks and is bootable. It’s a small text based OS that can perform these jobs: Changing the color of the written text, clearing the screen, restarting itself and Outputting a help and about text. It’s written in 80x86 Assembly Language.

## Online Judge System with Code Similarity (Fall 2010)

This project is written in Java and it consists of two parts, Client and Server applications. The goal was to create a system for online exams of C Programming course, so that the students can see the questions and submit their answers over the network and they will be graded by the system according to a model answer given by the teacher. It’s just for students to self-check their answers and the real grading will be done by the instructor himself later after the exam. It uses the code similarity algorithms used in Plagiarism Detecting Applications to calculate how much the submitted code is similar to the one that the instructor submitted. The Judge system uses two other ways of grading: Output checking and assembly code checking. The project was marked as the best project of the “Advanced Programming” class.

## Steganography (Winter 2010)

It’s a text based menu-driven application written in C and it can hide a text file in a Bitmap image and extract it back from the image. After researching and reading some papers and articles, our group planned to implement a method called “Adaptive Data Hiding in Edge Areas of Images With Spatial LSB Domain Systems”. Our program can hide up to 15 bits in each pixel of the image. I personally really enjoyed writing this project and I learned a lot during working on it. This was the project of my second programming course at the University and was marked as the best project both by the instructor and the students.
