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

The objective of this lab was to develop a better understanding of basic software testing principles that are applicable in the real world. This process began by getting familiarized with the ATM system being tested first, followed by exploratory and manual scripted tests done in pairs. Next, the results were compared and compiled to facilitate a regression test on an updated version of the system. Finally, the new version was put through one last round of manual scripted testing.

Before this lab, we knew little about exploratory and manual functional testing. However, the hands-on experience in this lab has helped us learn more about these techniques and their application in the real world.

# High-level description of the exploratory testing plan

In our exploratory plan, we wanted to focus on functions that involve user interaction and are crucial for basic functionality because they have the highest impact. For a basic ATM system like this, we found it best to test a few functions extensively. This included card inputs, deposits, withdrawals, and balance inquiries. From these functionalities, we opted for a risk-based approach where critical functionalities like deposits, and withdrawals were prioritized first. We planned on starting by testing the most common paths. Then, we aimed to complete test cases for exceptional paths like invalid inputs, exceeding transaction limits, and other error conditions. 

# Comparison of exploratory and manual functional testing

Two initial test strategies were implemented during this lab: exploratory testing followed by manual testing. The exploratory tests proved to be a more extensive and time-consuming endeavor. It was not simple to keep track of which tests had been completed and documented in the bug report and which had not. Furthermore, it was easy to get caught up in one test that failed by searching through every iteration around it for other failures. From this perspective, it was relatively inefficient and disorganized. 

The manual functional testing was much quicker to implement, but significantly less effective. Only two bugs were discovered with the provided test suite that were not documented during exploratory testing. In contrast, many bugs found in exploratory testing were not reiterated through the second round of tests. The manual functional testing was consistent and repeatable. Both pair groups generated identical bug reports in this section. However, it was constraining and less adaptable to the faults discovered in the unique software program being tested. 

Overall, neither testing strategy was flawless. The combination of both, along with regression testing after changes were made, provided a comprehensive bug search of the software. 

# Notes and discussion of the peer reviews of defect reports

The exploratory testing process that both pairs performed ended up being very similar. We all found the same bugs but reported some slightly differently. For example, one pair found a bug with the log showing a successful balance inquiry; however, the balance inquiry actually gave an error on the screen. The other pair found the same error with the balance inquiry but did not report the log error as its own separate bug. We discussed those minor differences as a group when we peer-reviewed each other's defect reports. 

# How the pair testing was managed and team work/effort was divided 

Our team was divided into two pairs and performed pair testing for the exploratory and manual scripted testing. For pair testing, one team member worked on the keyboard and performed tests to find bugs while the other team member recorded the found bugs. Both pairs switched roles halfway through each section of testing. Each pair performed their own exploratory testing and performed all 40 manual scripted tests, comparing it to their own found bugs from the exploratory section. For regression testing, the 4 team members equally divided all of the bugs that we discovered and the manual scripted tests and tested individually.

# Difficulties encountered, challenges overcome, and lessons learned

Although the testing and bug detection process was very straightforward, there were times when it was difficult to determine whether something was a bug or simply a poor feature of the program. For example, when a user entered an incorrect pin, then the correct pin on a second attempt, they would have to enter the pin a third time to be able to login. We were unable to determine at first whether this was meant to act as an extra security feature, or a bug. Ultimately, we came to the conclusion that it was not intended as a user entering the correct pin once should be enough for them to gain access. Something that proved to be a challenge was ensuring we tested every possible outcome in the program during the exploratory phase, so that we did not miss any hidden errors. Although the program was relatively small, covering every possible outcome required a significant amount of effort, going back, and reporting to document. From this challenge, a lesson we learned was the importance of making sure that all possible routes through the program are covered during testing, as it can be easier to glance over or miss certain specific paths that could lead to fatal errors for users.


# Comments/feedback on the lab and lab document itself

Overall, the content of this lab was very informative in demonstrating the importance of extensive software testing, making sure that all program outcomes work as expected to provide the best experience to the user. It was helpful in teaching effective testing methods, such as manual, exploratory and regression through practice, and familiarizing ourselves with issue tracking software like Jira. In the future however, we believe that it would these labs would be simpler to understand if the handouts were laid out in a more efficient manner, such as an actual pdf document that more distinctly separates the lab into a few clear sections (lab summary and deliverables, then instructions, etc) in an organized manner. This was not a massive inconvenience however by any means, and the lab itself was still very helpful and efficient to complete.

