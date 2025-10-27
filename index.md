---
layout: default
title: "CS499 Capstone ePortfolio"
---

## Welcome
Welcome to my capstone ePortfolio for Southern New Hampshire University’s Computer Science program. This project completes CS499 and the remaining requirements for my B.S. in Computer Science. My goal was simple, to demonstrate sound engineering practice and explain decisions in plain language while providing evidence of progress from coursework to capstone.


## Table of Contents
- [Self-Assessment](#Self-Assessment)
- [Artifact](#Artifact)
- [Code Review Video](#Code-Review-video)
- [Enhanced Artifact](#Enhanced-Artifact)
- [Enhancement:Software Engineering and Design](#Enhancement:Software-Engineering-and-Design)
- [Enhancement:Algorithms and Data Structures](#Enhancement:Algorithms-and-Data-Structures)
- [Enhancement:Databases](Enhancement:Databases)


## Self-Assessment
  I started the Computer Science program in February 2023, so I have been in the program for about two and a half years. Before this degree, I studied biology at Angelo State University for two years. I originally planned on medical school, but I ultimately decided my interest in science and medicine was rooted in the knowledge and understanding, not so much from practicing medicine. My path into computer science was not a straight line, but that ended up helping me in the long run. Being a biology major taught me how to observe, document, and explain processes clearly and the transition to computer science taught me how to build those processes into working systems.

  During the program I developed three core skills that changed how I work, with the first being self-guided learning and research. Modern development work expects you to solve problems that are not already solved for you. I very quickly had to learn how to analyze documentation that didn’t explicitly tell me how to accomplish a task and then correct my own approach when I discovered a better way to handle it. I successfully improved my structured problem-solving skills and learned how to break a large task into smaller ones, define the requirements, design the logic and then implement that logic in a controlled way instead of constant guessing and patching. Something that I have always struggled with and made it a point to improve is my time management skills. Most courses over the years involved parallel work and it was important that I kept long term deadlines in mind while still delivering working code in short cycles. All three of these skills together made me more reliable and more confident when I work on a project with real expectations.

  I employed strategies for building collaborative environments that enable diverse audiences to support organizational decision-making in the field of computer science by completing a code review of my project before beginning any enhancements. In that review, I walked through the existing functionality of the codebase and explained what the application already did, in plain language that someone outside the project could follow. I then analyzed the code and identified specific areas that needed improvement and outlined the enhancements I planned to make and explained why those changes were important and which course outcomes they would support. Doing this up front created a shared understanding of the system's current state and future direction, which is the foundation of collaboration. Even though the app was completed without assistance from anyone else, the review treated the project as if it were being handed to other developers or stakeholders for feedback and decision-making. This shows that I can prepare technical work in a way that invites review and discussion before changes are made.

  I designed, developed, and delivered professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts by working on course projects that were built around realistic business or client scenarios. In many of these classes, the project was presented as if it came from an organization with specific goals and had I to interpret those requirements, document how the system would meet them, and explain the reasoning behind my design choices in a clear and professional way. This included writing summaries of functionality in non-technical terms for an assumed stakeholder and preparing visual representations such as flowcharts to show how parts of the system would interact. That experience helped me learn how to justify design decisions in a way that focuses on what matters to the reader, not just on how the code works.

  I designed and evaluated computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution while managing the trade-offs involved in design choices by implementing and refining a reinforcement learning agent in a grid-based environment. In a project for CS 370: Current/Emerging Trends in Computer Science, I built a Q-learning system that trained a pirate character to navigate a map and reach a target efficiently. I had to define how the agent represents state, how it chooses actions, and how it updates what it has “learned” after each move. I then evaluated the behavior of the agent over repeated runs and adjusted reward values and training parameters to improve its decision-making. Working through this required me to think in algorithmic terms: convergence, exploration versus exploitation, efficiency of movement, and correctness of the learned policy. It also required me to judge when the solution was “good enough” for the problem and when it needed more tuning.

  I demonstrated an ability to use well-founded and innovative techniques, skills, and tools in computing practices to implement computer solutions that deliver value and accomplish industry-specific goals y treating each major project in the program like a real deliverable with real expectations. In CS 440: Client Server/Development, I developed and used a CRUD Python module to connect a dashboard front end to a live database. That required me to design code that could repeatedly create, read, update, and delete records in a consistent and safe way; while also keeping the logic organized so it could be reused in more than one part of the system. The goal of that project was to support real decision-making for an animal rescue scenario, so accuracy and clarity of the data mattered.

  I developed a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources by  treating data validation and rule enforcement as part of protecting the system. In CS 320 Software Test Automation, I wrote logic that rejected invalid data instead of allowing it into the system. For example, tasks had to include a valid ID and non-empty fields, and appointments could not be created in the past. The checks were written so the application could not be pushed into an inconsistent or unsafe state by bad input. I also added tests around these rules to confirm that the services continued to block invalid or out-of-scope.



## Artifact
  The artifact that I have chosen for all my enhancements is a weight loss tracking app named WeighForward that I designed and tested using Android Studio. It was created as my final project for CS 360: Mobile Architect and Programming  which I completed in December of 2024. This app is the project I’m most proud of from my time at SNHU because it reflects my creativity and the knowledge I gained over the past few years. All of the code is written in Java. That is meaningful for me personally, because Java was the language I struggled with early in the program and it required hours of practice and studying to reach the level I’m at now.
  
  The app itself is centered around a simple but real need: helping a user track progress over time. To make that work, the project needed reliable navigation between screens, input that followed clear rules, and a way to store and show previous entries in a way that made sense to the user. Each entry is saved so the user can come back later and see how their numbers change over time, which turns the app into more than a single-use calculator. I also built the flow so that the information the user enters is checked and handled in a consistent way instead of just being accepted and dumped on the screen. I wanted my approach to reflect planning, not just coding, because the app must respond in a predictable way every time the user interacts with it. Building and refining those parts shows that I can take responsibility for the full behavior of the app, from how the user moves through it to how their information is handled and presented back to them in a consistent way.
  
  This app serves as the core technical artifact for my capstone. All the analysis, planning, and enhancements in this eportfolio are built around improving this project and strengthening how it functions. The codebase gives me a place to show how I approach design decisions, how I handle user data, and how I work toward dependable behavior on a mobile platform. The following sections will reference this application as the foundation for my work.

The original unenhanced code of the artifact can be found [here](https://github.com/Jconner3/Jconner3.github.io/blob/main/WeightLossApp.zip).


## Code Review Video
The link to my code review video can be found [here]


## Enhanced Artifact
The fully updated artifact code can be found [here](https://github.com/Jconner3/Jconner3.github.io/blob/main/WeightLossAppV2.zip).



## Enhancement:Software Engineering and Design
**Click here to view the full narative**|[View Narative](https://github.com/Jconner3/Jconner3.github.io/blob/Software-Engineering-%26-Design/README.md)

The artifact was chosen for this enhancement category because the app had to grow from a basic working idea into something a real person could actually use every day. That meant I had to think about layout, flow, clarity, and error recovery, not just raw functionality. I redesigned screens so that important information is easy to find, made editing and deleting entries feel controlled instead of risky, and adjusted the interaction patterns to feel intentional on a mobile device. I also reworked how the interface and the underlying code support each other, so the behavior the user sees on screen is backed by consistent logic.

I demonstrated an ability to use well-founded and innovative techniques, skills, and tools in computing practices to implement computer solutions that deliver value and accomplish industry-specific goals by rebuilding the data layer of the app so it behaves like part of a real product instead of a basic class project. I standardized how entries are stored and retrieved, created focused query methods that return exactly what the rest of the app needs, and added structure so the app can pull historical data in a clean and predictable way. 

I developed a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources by moving the app to SQLCipher with full at-rest encryption, requiring a passphrase to open the database, and keeping that passphrase out of the code. I also treated each saved record as protected data and controlled how it could be inserted, accessed, and displayed.



## Enhancement:Algorithms and Data Structures
**Click here to view the full narative**|[View Narative](https://github.com/Jconner3/Jconner3.github.io/tree/Algorithms-%26-Data-Structures/README.md)

WeighForward deservers an enhancement in the Algorithms & Data Structures category because the functionally should go beyond just storing numbers for the user to look at. The app processes the user’s history, summarizes it, and turns it into something readable and meaningful. I wrote logic that can group entries by month, generate monthly averages, and build a progress view that reflects real change over time instead of just listing isolated values. I also added filtering to the page that shows all the users logged weights so they can focus on recent history or long-term trends without being overwhelmed. I implemented features that generated useful results efficiently, presents those results in a way that answers, “how am I doing?” for the user.

I designed and evaluated computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution while managing the trade-offs involved in design choices by improving the logic that drives the app’s progress features. I wrote code that groups recorded entries by month, calculates an average for each month, and builds a structured view of progress over time. I also added filtering based on recent activity and a controlled way to sort results so the user can review either their latest changes or their longer-term trend. 

I demonstrated an ability to use well-founded and innovative techniques, skills, and tools in computing practices to implement computer solutions that deliver value and accomplish industry-specific goals by turning raw stored data into something the user can understand and act on. These changes make the information more useful, because the app can now answer practical questions about progress instead of only displaying individual numbers.



## Enhancement:Databases
**Click here to view the full narative**|[View Narative](https://github.com/Jconner3/Jconner3.github.io/blob/Databases/README.md)

A fully functional app treats stored information as something that needs to be both protected and dependable which justified its inclusion for an enhancement in this category. The app isn’t just collecting quick inputs and throwing them away. It’s keeping a record of personal progress that the user expects to be private, accurate, and available later. I upgraded the storage layer to behave more like the storage layer in an official app store product: encrypted data at rest, predictable formats for stored entries, and controlled access paths to read that data back. I also focused on making sure older entries could still be accessed and organized cleanly as the history grows. This reflects the mindset of maintaining trustworthy data over time, which is exactly what the database category is meant to show.

I demonstrated an ability to use well-founded and innovative techniques, skills, and tools in computing practices to implement computer solutions that deliver value and accomplish industry-specific goals by redesigning the interface and interaction flow so the app behaves in a focused, user-centered way. I added features like meaningful progress displays, filter and sort controls, and an improved Home screen that presents the most important information clearly instead of making the user hunt for it

I designed, developed, and delivered professional-quality written and visual communication that is coherent, technically sound, and appropriately adapted to specific audiences and contexts by treating the interface itself as communication. The layout, wording, and screen flow guide the user through actions like reviewing history, updating an entry, or logging new data, and the app gives feedback in a way that can be understood without technical knowledge.

I developed a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources by adding confirmation before deletion and supporting an undo path, which protects the user from accidental data loss and keeps their history under their control.


