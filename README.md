# Fullerton_chat-Software-Architecture

This project is part of my graduate course **CPSC 545 - Software Architecture and Design** guided by **Dr.Chang-Hyun Jo**. We are instructed to build a software architecture for a chat application like WhastApp. Our target audience for the application was the students and Faculties of Cal State Fullerton. 

We followed **Attribute Driven Design Methodology (V2.0)** for selecting the exact software architecture patterns and to implement the design. Attribute-driven design is a methodology to create software architectures that takes into account the quality attributes of the software


# Customer Constraints:
Our Professor was our customer, and we are given the following constraints for our software. Our constraints are,
1. Our application should be available 24*7 
2. Our application should endure high performance
3. Our application should include architecture documentation
4. Our application shall help two users to send or receive text, video and voice messages
5. Messages should be secured. 

# Description:
We created a new software architecture for **fullerton_chat (similar to whatsapp) system**, which helps the student and staffs to communicate with each other through instant messaging platform.

# Simple Context Diagram of our Fchat System:
![Context Diagram](https://raw.githubusercontent.com/deepu2010/Fullerton_chat-Software-Architecture/master/Fchat%20context%20diagram.JPG)


# Key activities in our project:
1. Requirements Gathering
2. Quality Assurance Workshop(QAW)
3. Implementing Attribute Driven Desgin version 2.0(ADD v2.0) methodology for designing our architecture
4. Implementing patterns for various components in Fchat
5. Documenting our architecture

# Architecture Design approaches:

We have built a customized sofware architecture with multiple software patterns. 

- The main pattern we used to build our application is **'CLIENT - SERVER PATTERN'**
- We decomposed the **'SERVER ELEMENT'** with **'MULTI-TIER PATTERN'** by analyzing pros. and cons. table from QAW
- We then decomposed the client element with **'MODEL-VIEW-CONTROLLER'** pattern


# Our Overall Architecture:

![Fchat](https://raw.githubusercontent.com/deepu2010/Fullerton_chat-Software-Architecture/master/Server%20Side%20Architecture%20of%20Fchat.JPG)

# Decomposed Server Element
![Server](https://raw.githubusercontent.com/deepu2010/Fullerton_chat-Software-Architecture/master/Server%20element.JPG)

# Decomposed Client Element
![Client](https://raw.githubusercontent.com/deepu2010/Fullerton_chat-Software-Architecture/master/client%20element.JPG)

# Skills Learned:

1. Requirement Documentation
2. Quality Assurance Workshop for deciding the architecture design patterns
3. Attribute Driven Design (ADD 2.0) hands-on implementation
4. Architecting Server element and client element
5. Architecture Documentation



