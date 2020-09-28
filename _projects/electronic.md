---
title: "Electronic Document Mangement System"
collection: Projects
type: "Projects"
permalink: /projects/electronic

---

# Electronic Document Management System

This project is divided into two parts: client and server.

A. Operation Guide for Client of Electronic Document Management Platform in LAN

1. Software introduction
    Application name: Electronic document management platform in LAN
    File name: FileManagement.exe
    Application version: 1.0.0
    Modification date: May 14, 2019
    Software development platform: Microsoft® Visual Studio 2013 Ultimate, Microsoft® SQL ServerTM 2014
    The software runs on the Windows platform.

 2. Operating environment
    (1) Hardware requirements
    ① 1GHz or higher microprocessor
    ②Use 1G or above memory
    ③At least 100MB of free hard disk space
    (2) Software requirements
    ① Windows 7 or above operating system
      ②.NET Framework 4.7.2 or above

3. Instructions for use
    3.1 Installation and initialization
    (1) Install the necessary software
    Install the Windows 7 operating system on the client computer and configure the TCP/IP protocol to ensure that the computer can connect to the Internet. After the configuration is complete, install the .NET Framework 4.7 runtime library.
    (2) Install an electronic document management platform in the local area network

  1.  Double-click the installation file setup.exe on the desktop;

  2.  Select the installation path and click the Next button;

  3.  Choose whether to create a desktop shortcut, and click the Next button;

  4.  Click the confirm installation button to proceed with the installation;

  5.  After the installation is complete, click Finish to exit the installation program.

      3.2 Start the system
      
      1.  Double-click the desktop shortcut "Electronic Document Management Platform in LAN (Client)" to start the management platform system
      
      2.  Start using the management platform according to the user name and password assigned by the administrator
      
      3.  Main functions of the system
          (1) Initialize the system and user login: After the system is initialized, the user needs to log in and can enter the platform for operation after passing the verification;
          (2) Display document and version information: After the user successfully logs in to the platform, he can see the electronic documents that already exist in the platform from the interface of the platform. Users can choose different ways to view electronic documents, including: large icons, small icons, and detailed information. When the user clicks on a certain document, the platform will automatically load out the various versions of the document and display them on the interface for users to view. Similarly, users can choose to view the version information of the document in three ways, including: large icons, small icons, and detailed information;
          (3) Uploading documents: Users can upload documents from their own computer to the platform by selecting the subject of the document to be uploaded and the path of the document to be uploaded on the machine;
          (4) Browse documents: Users can download documents from the platform to their computer for browsing by selecting the documents to be downloaded and the path where the downloaded documents are saved locally. This platform should have the function of automatically opening documents for users to browse after downloading;
          (5) Modify documents: Users can modify the documents in the platform by selecting the documents to be modified and the path where the documents to be modified are saved locally. This platform should have the function of automatically opening documents for users to modify after downloading;
          (6) Delete documents: Users can delete documents in the platform by selecting the documents to be deleted;
          (7) Browse a certain version of the document: Users can browse the specified version of the document, including the latest version and historical version, by selecting the version of the document to be browsed and specifying the path where the document version to be browsed is saved locally. This platform should have the function of automatically opening the document version for users to browse after downloading;
          (8) Delete a certain version of the document: The user can delete the specified version of the document by selecting the version of the document to be deleted.
      
      4.  Precautions for use
          (1) If the user name and password are entered incorrectly for three consecutive times when logging in, the account will be locked
          (2) The first time you log in, you need to set a secret mailbox or mobile phone number
          (3) The data in the personal account and the uploaded documents are stored encrypted, please rest assured to use
          (4) Do not use illegal operations such as SQL injection to damage the database
          (5) Do not use crawlers and other programs to automatically obtain data. The frequency of button clicks is strictly limited
          (6) Please do not try to access data without authorization, the database has been restricted for access control.
      
          
      

B. Operation guide for the server side of the electronic document management platform in the local area network
      
1.  Software introduction Application name: Electronic document management platform in LAN
      File name: FileManagement_Admin.exe Application version: 1.0.0
      Modification date: May 14, 2019
      Software development platform: Microsoft® Visual Studio 2013 Ultimate, Microsoft® SQL ServerTM 2014
      The software runs on the Windows platform.

2.  Operating environment
      (1) Hardware requirements
      ① 1GHz or higher microprocessor
      ②Use 1G or above memory
      ③At least 100MB of free hard disk space
      (2) Software requirements
      ①Windows Server 2012 R2 or above operating system
      ②.NET Framework 4.5 or above
      ③Microsoft® SQL ServerTM 2014 or above database management system

3.  Instructions for use 

    3.1 Installation and initialization
      (1) Install the necessary software Install the Windows Server 2012 R2 operating system on the server and configure the TCP/IP protocol to ensure that the computer can connect to the Internet. After the configuration is complete, install the .NET Framework 4.5 runtime and SQL Server 2014 database, and configure the user name and password. Set the administrator username as sa and password as Admin123456; common user username as userlogin and password as User123456. At the same time, set up roles in the database and assign corresponding permissions to the roles. Then create a folder and configure the ftp site to allow anonymous login for reading and writing. (2) Install an electronic document management platform in the local area network

1. Double-click the installation file setup.exe on the desktop;
2. Select the installation path and click the Next button;
3. Choose whether to create a desktop shortcut, and click the Next button;
4. Click the confirm installation button to proceed with the installation;
20. After the installation is complete, click Finish to exit the installation program.
      3.2 Start the system
1.  Double-click the desktop shortcut "LAN electronic document management platform (server)" to start the management platform server system
    2.  Log in according to the administrator's username and password and start using the management platform
    3.  Main functions of the system
          (1) View and manage user account information, department information, subject information, and authority information;
          (2) View documents and their version information, view and manage system log information;
          (3) Modify the administrator password;
          (4) Back up and restore system data.