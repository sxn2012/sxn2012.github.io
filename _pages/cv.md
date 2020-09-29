---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Eng. in [Jiangsu Univeristy](https://eng.ujs.edu.cn/), 2015

    Major: Information Security

    Core Modules: Database Security, IOT Security, Cryptography Principles, Networks and Systems Security

    GPA：3.89/5.0, Ranking：2/56

    Supervisor: [Conghua Zhou](https://cs.ujs.edu.cn/info/1348/7371.htm)

* M.S. in [University of Melbourne](https://www.unimelb.edu.au/), 2019

    Major: Computer Science

    Core Modules: Machine Learning, Distributed Systems, Natural Language Processing, Quantum Computing
    
    Research Topic: Statistical Machine Learning

Skills
======
* Familiar with Java (Swing, JUnit), C++ (socket, MFC) and Python (sklearn, tensorflow)
* Familiar with multithreaded programming, as well as Object-Oriented Programming and Functional Programming, have good coding styles
* Familiar with Linux commands, git operations and basic usage of gcc and vim
* Familiar with Data Structure and Algorithms (LinkedList, Stack, Queue, Binary Tree, Divide and Conquer, Dynamic Programming etc), as well as networks (TCP, UDP, HTTP etc)
* Familiar with MySQL Database and basic knowledge of Redis; know about common database optimize strategies
* Familiar with cryptography (symmetric encryption and asymmetric encryption), and common Web attacks and their defence strategies (SQL injection, XSS attack etc)
* Know about machine learning (KNN, SVM etc) and distribution systems (Vector clocks, Leader election algorithm, Mutual exclusion algorithm, 2PC etc)

Projects
======

-   [MVCC Algorithms Implementation](https://github.com/sxn2012/DA2020S1_Project) (2020.04 - 2020.06)

    Task: Simulate a database, and implement the MVCC Algorithm from scratch to ensure data consistency.

    Details:

    1.  Isolation level is Read Committed. Each transaction can only access the committed data of other transactions;
    2.  When the read operation of one transaction conflicts with write operation of another transaction, it will get the previous version of data and another transaction will fail and rollback automatically.

    Results: It can ensure data consistency and prevent dirty read.

    Responsibility: data transmission module and core concurrency control algorithm

-   [Distributed Shared Whiteboard System](https://github.com/Tosnower/DS2019S2_Assignment2) (2019.09 - 2019.11)

    Task: Design a distributed system so that multiple users can draw and chat simultaneously.

    Details:

    1.  Recording and broadcasting the operation of drawing board in the form of Json when a client draws a pixel, so that data consistency in distributed systems can be ensured;
    2.  Using AES to encrypt messages during transmission. When reading records from file, it will use SHA-256 to verify digest of the file.

    Results: It can reach the anticipated results and handle fewer than 50 clients of concurrency volume.

    Responsibility: Drawing board function designing, data encryption and digest verification

-   [Electronic Document Management Platform](https://github.com/sxn2012/ujs_security/tree/master/code/courses-ujs/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1) (2019.02 - 2019.06)

    Task: Design a platform to store and manage electronic documents, with multiversion management functions.

    Details:

    1.  The server saves all versions of different documents, and the transmission of data is implemented by using TCP protocol. FTP protocol is used for transmitting documents;
2.  The messages and documents are encrypted with AES algorithm. When downloading documents, SHA-256 is used to ensure integrity of the documents;
    3.  Meanwhile, RBAC and backup and recovery skills are used to enhance the platform security.

    Skills: WinForm + SQL Server

    Results: This project has implemented a secure multiversion document management platform.
    
    
    

Rewards
======

-   Study Scholarship and Triple-A Student for Academic Year 2017-2018, 2nd Prize (2018.12)
-   Lanqiao Software and Information Technology Competition, 3rd Prize (2018.04)
-   Study Scholarship and Triple-A Student for Academic Year 2016-2017, 1st Prize (2017.12)
-   National English Competition for College Students, 3rd Prize (2017.05)
-   Cyber Security Competition at Jiangsu University, ranked 3rd (2016.12)
-   13th Mathematics Competition, 3rd Prize (2016.08)

Professional Qualifications
======

-   Languages: Chinese (native); English: IELTS (Overall 7.0); CET-6 (Overall 559)
-   IT: Level 3, National Computer Rank Examination