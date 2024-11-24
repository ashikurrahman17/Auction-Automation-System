<p align="center">
  <img src="hstu_logo_.png" alt="hstu_logo_.png" width="250" height="300">
</p>
<h1 align="center">
  <b>Auction Automation System For CSE Super League</b>
</h1>
<h3 align="center">
  <br>
  <b>Level-3 Semester-I Project Report</b>  
</h3>
<h3 align="center">
  Course Code: CSE 305 
</h3>

<h3 align="center">
  Course Title: Software Engineering
</h3>
<br>
<h3 align="center">
  Submitted by 
</h3>
<h3 align="center">
<b>Ashikur Rahman (ID: 2102028) </b> </h3>
<br>

<h3 align="center">
  Submitted To 
</h3>

<h3 align="center"><b>Pankaj Bhowmik  </b></h3>
<h3 align="center"><b>Lecturer, Department of CSE</b></h3>
<br>
<h3 align="center"> <b>Department of Computer Science and Engineering </b></h3>
<h3 align="center"><b>Hajee Mohammad Danesh Science and Technology University  
Dinajpur-5200</b></h3>
<br><br><br>

---





## Table of Contents
1. [Goal of the Project](#goal-of-the-project)  
2. [Introduction to the Prototype Model of SDLC](#introduction-to-the-prototype-model-of-sdlc)  
3. [Steps in the Prototype Model Applied to Auction Automation System](#steps-in-the-prototype-model-applied-to-auction-automation-system)  
   - [1. Identification of Requirements](#1-identification-of-requirements)  
   - [2. Quick Design and Planning](#2-quick-design-and-planning)  
   - [3. Create a Throwaway Prototype](#3-create-a-throwaway-prototype)  
   - [4. User Evaluation](#4-user-evaluation)  
   - [5. Refinement](#5-refinement)  
   - [6. Iterative Development](#6-iterative-development)  
   - [7. Regular User Testing](#7-regular-user-testing)  
   - [8. Gradual Enhancement](#8-gradual-enhancement)  
   - [9. Documentation](#9-documentation)  
   - [10. Integration of Features](#10-integration-of-features)  
   - [11. Security Considerations](#11-security-considerations)  
   - [12. Deployment](#12-deployment)  
4. [Conclusion](#conclusion)  

---

## Goal of the Project
The goal of this project is to develop an Auction Automation System specifically tailored for the CSE Super League. The system aims to streamline player bidding, team formation, and budget management through efficient and user-friendly software. The Prototype Model of Software Development is well-suited for this project because it allows iterative refinement of features based on user feedback, ensuring the system meets the specific needs of organizers, team managers, and participants.
First I introduced The Prototype Model of SDLC.

![ER](https://github.com/user-attachments/assets/672df64e-5d14-4c5f-a1ac-eb98377c4a2f)


---

## Steps in the Prototype Model Applied to Auction Automation System

### 1. Identification of Requirements
The first phase involves understanding the requirements of the auction automation system and defining its core functionalities.

- **Requirement Gathering:**
  - Meet with stakeholders such as event organizers, team managers, and system administrators to understand the process of player auctions.
  - Identify pain points in the current manual auction process, such as delays, calculation errors, or lack of transparency.

- **Core Functionalities:**
  - Real-time player auction with live bidding.
  - Budget tracking for teams during the auction.
  - Automatic allocation of players to teams after successful bids.
  - Visualization of team composition (players and roles like batsmen, bowlers, all-rounders, etc.).
  - Administrator panel to manage player lists, bidding rules, and auction timelines.
  - User authentication for team managers and auction viewers.

---

### 2. Quick Design and Planning
- **Preliminary Design:**
  - Create a simple user interface (UI) for key components:
    - Auction Screen: Displays live bidding progress and player details.
    - Budget Dashboard: Tracks remaining budget for each team.
    - Team Composition Viewer: Shows allocated players and remaining spots in the team.

- **Plan Development:**
  - Break the project into smaller, manageable modules such as:
    - Player Database Management
    - Bidding Mechanism
    - Budget Calculation Logic
    - User Authentication and Role Management
  - Outline iterative development cycles, each focusing on implementing and testing one or more modules.

---

### 3. Create a Throwaway Prototype
The throwaway prototype demonstrates core functionalities without focusing on details like scalability, performance, or a polished UI.

- **Prototype Features:**
  - Simple UI showing a mock auction process for a limited set of players.
  - Basic bidding mechanism where team managers can place bids manually.
  - Static budget tracking for each team.
  - Manual allocation of players to teams after bidding.

- **Purpose:**
  - Provide a tangible representation of the system.
  - Validate key concepts such as live bidding flow and budget management.

---

### 4. User Evaluation
The prototype is shared with stakeholders for feedback and evaluation.

- **Stakeholders Involved:**
  - Event organizers to validate the bidding rules and overall process.
  - Team managers to test the bidding functionality and budget tracking.
  - Observers to simulate the user experience of auction viewers.

- **Feedback Collection:**
  - Gather feedback on the usability of the bidding screen and budget dashboard.
  - Identify areas where the bidding process feels slow or confusing.
  - Note any missing functionalities or issues raised by stakeholders.

---

### 5. Refinement
Refine the design and functionality of the system based on feedback.

- **Refinements to Focus On:**
  - Improve the UI of the auction screen to make it more intuitive (e.g., highlight current bids, show player stats prominently).
  - Enhance budget tracking with error checking to prevent overspending.
  - Add dynamic updates for team composition during the auction.

---

### 6. Iterative Development
Iterate on the prototype by adding features and refining existing ones in each development cycle.

- **First Iteration:**
  - Implement dynamic player allocation with real-time updates.
  - Introduce auction rules such as maximum team size and minimum player roles.
  - Add administrator controls for pausing or resuming the auction.

- **Second Iteration:**
  - Integrate player statistics to help team managers make informed decisions.
  - Add advanced budget tracking with alerts for low budgets.
  - Introduce mock auctions for testing the system in a simulated environment.

- **Third Iteration:**
  - Enhance the bidding mechanism with automated time limits for each bid.
  - Add support for multiple auctions (e.g., main player auction, wildcard auction).

---

### 7. Regular User Testing
Conduct regular testing sessions to ensure the system meets requirements and is user-friendly.

- **Testing Scenarios:**
  - Simulate a complete auction with all stakeholders.
  - Test edge cases, such as two managers bidding the same amount simultaneously.
  - Validate team composition rules (e.g., maximum of four all-rounders per team).

---

### 8. Gradual Enhancement
Enhance the system by incorporating additional features and improving the overall experience.

- **Additional Features:**
  - Introduce a real-time leaderboard showing team budgets and compositions.
  - Add a player search/filter feature to quickly find players by role, skill level, or base price.
  - Implement detailed auction reports, including bid history and final team rosters.

---

### 9. Documentation
Maintain thorough documentation throughout the development process.

- **What to Document:**
  - Initial requirements and design considerations.
  - Changes made during each iteration, along with reasons for the changes.
  - Instructions for using the system, including a user manual for team managers and administrators.

---

### 10. Integration of Features
Integrate advanced functionalities to make the system more robust and versatile.

- **Device Compatibility:**
  - Ensure compatibility across desktops, tablets, and mobile devices.
  - Provide cross-platform support for auction viewers.

---

### 11. Security Considerations
Implement security measures to protect sensitive information.

- **Key Measures:**
  - Use encryption for sensitive data during transmission.
  - Implement role-based access control to ensure only authorized users can bid or manage players.

---

### 12. Deployment
Deploy the final version of the system for the live auction.

- **Steps:**
  - Test the system in a controlled environment before the live event.
  - Monitor the system during the live auction and address issues immediately.
  - Collect feedback after the event to plan for future improvements.

---

## Conclusion
The Prototype Model allows for continuous refinement, making it ideal for developing the Auction Automation System for the CSE Super League. By involving stakeholders in every phase and iterating on feedback, the system can meet the unique needs of cricket auction events while ensuring ease of use, security, and robustness.
