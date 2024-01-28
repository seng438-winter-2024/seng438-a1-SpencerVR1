>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: 1     |
|-----------------|
| Harris Hasnain               |   
| Houssem Zaggar             |   
| Spencer van Roessel               |   
| Kaylyn Tanton               |   


**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

An introduction of your lab work, and what you 

we knew little about exploratory and manual functional testing before this lab

# High-level description of the exploratory testing plan

In our exploratory plan, we wanted to focus on functions that involve user interaction and are crucial for basic functionality because they have the highest impact. For a basic ATM system like this, we found it best to test a few functions extensively. This included card inputs, deposits, withdrawals, and balance inquiries. From these functionalities, we opted for a risk-based approach where critical functionalities like deposits, and withdrawals were prioritized first. We planned on starting by testing the most common paths. Then, we aimed to complete test cases for exceptional paths like invalid inputs, exceeding transaction limits, and other error conditions. 

# Comparison of exploratory and manual functional testing

During this lab, two initial test strategies were implemented, exploratory testing followed by manual testing. The exploratory tests proved to be a more extensive and time-consuming endeavour. It was not simple to keep track of which tests had been completed and documented in the bug report and which had not. Furthermore, it was easy to get caught up in one test that failed by searching through every iteration around it for other failures. From this perspective, it was relatively inefficient and disorganized. 

The manual functional testing was much quicker to implement, but significantly less effective. Only two bugs were discovered with the provided test suite that were not documented during exploratory testing, while many bugs found in exploratory testing were not reiterated through the second round of tests. The manual functional testing was consistent and repeatable. Both pair groups generated identical bug reports in this section. But it was constraining and less adaptable to the faults discovered in the unique software program being tested. 

Overall, neither testing strategy was flawless. The combination of both, along with regression testing after changes were made, provided a comprehensive bug search of the software. 

# Notes and discussion of the peer reviews of defect reports

The exploratory testing process that both pairs performed ended up being very similar. We all found the same bugs, but reported some slightly differently. For example, one pair found a bug with the log showing a successful balance inquiry; however, the balance inquiry actually gave an error on the screen. The other pair found the same error with the balance inquiry, but did not report the log error as its own separate bug. We discussed those minor differences as a group when we peer reviewed each others defect reports. 

# How the pair testing was managed and team work/effort was divided 

Our team divided into two pairs of two and performed pair testing for the exploratory and manual scripted testing. For pair testing one team member worked on the keyboard and performed tests to find bugs while the other team member would record the found bugs. Both pairs switched roles halfway through each section of testing. Each pair performed their own exploratory testing and performed all 40 manual scripted tests, comparing it to their own found bugs from the exploratory section. For regression testing, the 4 team members equally divided all of our bugs that we discovered and the manual scripted tests and tested individually.

# Difficulties encountered, challenges overcome, and lessons learned

Text…

# Comments/feedback on the lab and lab document itself

Text…
