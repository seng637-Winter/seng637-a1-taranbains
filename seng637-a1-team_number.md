>   **SENG 637 - Dependability and Reliability of Software Systems**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group No 18	|   |
| ------------- | ------------- |
| Student 1  | Taran Bains           |   
| Student 2  | Balkarn Gill          |   
| Student 3  | Satchy Karalasingham  |   
| Student 4  | Hannah D'Souza        |   
| Student 5  | Chioma Ukaegbu        |   


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

# Introduction

This assignment focuses on two different software methodologies: Exploratory and Manual Testing. Exploratory testing focuses on designing test cases as a tester is actively testing the application. They are learning the software as they are writing test cases, and adapting the test cases based on what they find. Manual testing refers to manually executing a set of already thought-out/designed test cases, without using automation tools, ie. a person still needs to execute the test cases. 


# High-level Description of the Exploratory Testing Plan

The team initially set out to understand the application's behaviour by following the instructions under the "Familiarization with the ATM System". This will also allow the team to discover any critical defects or issues that would cause the entire application to crash. After following the set instructions, the team can explore specific features and functionalities of the application and taking notes on the output versus what they expect the output to be. Most common functions/paths are tested extensively to ensure the applictaion works as expected in most cases, while also testing a few more less common paths. The focus is on testing the features used the most by the user.  
 
The following two types of testing should be conducted:    
**Integration Testing:** individual software functions are combined and tested as a group.  
**System Testing:** the entire complete, integrated application will be tested.  

The scope of testing is presented in the table below:  

Table 1: Scope of Testing    

| Module	| Description | Test Logistics |
| ------------- | ------------- | ------------ |
| Turn ATM On/Off  | Operator can turn the ATM application on and off.  | Taran Bains & Balkarn Gill  |
| Inserting Card  | User can insert a valid or invalid card and pin number, with appropriate responses.  | Taran Bains & Balkarn Gill  |
| Withdrawal  | User can withdraw money from an account of their choosing.  | Taran Bains & Balkarn Gill  |
| Deposit  | User can deposit money in an account of their choosing.  | Satchy Karalasingham, Hannah D'Souza & Chioma Ukaegbu   |
| Money Transfer  | User can transfer money between accounts.  | Satchy Karalasingham, Hannah D'Souza & Chioma Ukaegbu  |
| Balance Inquiry   | User can get an accurate balance of an account of their choosing.  | Satchy Karalasingham, Hannah D'Souza & Chioma Ukaegbu  |


# Comparison of Exploratory and Manual Functional Testing

Exploratory testing offers adaptability and can uncover subtle, complex bugs through tester intuition and real-time investigation. It's especially useful in early development stages but may lack thorough coverage and test repeatability. For exmaple, a tester may not be able to accurately reproduce a bug that caused the system to crash that they found through a very convoluted route. Conversely, manual functional testing provides systematic coverage and repeatability, ensuring each application aspect functions as expected. While it excels in verification against established requirements, it may miss issues outside predefined test cases and can be resource-heavy due to test maintenance.

Effectiveness-wise, exploratory testing is superior for identifying new issues especially with a tester experineced in the application, whereas manual testing reliably checks for conformity to known expectations. Exploratory testing is quick to adapt and offers immediate feedback, but manual testing is time-efficient over multiple test cycles.

In practice, a balanced approach that utilizes both methods can maximize the benefits, with exploratory testing for ongoing learning and discovery, and manual testing for consistent validation and regression testing. The integration of both approaches caters to comprehensive quality assurance needs within a project's lifecycle.


# Notes and Discussion of the Peer Reviews of Defect Reports

The observation of diverse testing strategies among team members proved to be an insightful aspect of the project. This variety in approach led to different groups discovering unique bugs, highlighting the importance of collaborative work and peer review in producing detailed and accurate defect reports. The advantage of teamwork in such projects cannot be overstated. Sole reliance on a single individual for testing increases the likelihood of missing defects, a risk that became evident during the exploratory testing phase. In many instances, bugs unnoticed by the person conducting the test were identified by their observing partner.

Additionally, the project underscored the need for a uniform system for logging issues. When team members use varying formats and methods for reporting, it can complicate the process for everyone involved. Miscommunications in such a scenario can result in certain issues not being properly recorded and, as a consequence, not resolved. It’s imperative for the team to agree upon and follow a consistent method of communication and reporting. Such a unified approach is essential not just for maintaining clarity but also for improving the overall efficiency and effectiveness of the bug detection and resolution process.


# How the Pair Testing was Managed and Teamwork/Effort was Divided 

The team's testing process began with a split into two subgroups, each engaging in 'pair testing' to gain a detailed understanding of the application. This phase involved hands-on exploration, where one team member conducted tests while another observed and recorded any bugs, providing a dual perspective that proved effective in uncovering a wider range of defects. After this phase, the teams collectively reviewed and agreed upon the bugs to be reported, ensuring a unified and thorough approach to defect documentation in Jira.

In the next phase, the team conducted manual scripted testing, following the predefined test cases from Appendix C. This approach allowed for a structured and comprehensive examination of the application, with each team member actively participating either as a tester or an observer. The identified defects were then carefully logged into Jira. In the final phase of regression testing on version 1.1, the team reassessed these bugs to determine which had been resolved and which still required attention, categorizing them accordingly in Jira. This methodical approach not only streamlined the defect tracking process but also enhanced the team's collaborative effort in refining the application.


# Difficulties Encountered, Challenges Overcome, and Lessons Learned

There was a challenge in figuring out what exactly the application was supposed to do. Sometimes you would test a functionality during exploratory testing and get a result that seemed suspicious, but you were not 100% sure that it was an actual error. That would require a little more discussion amongst the team to figure out if other team members thought it was a bug or the system was supposed to do that. The manual scripted testing made it a little easier with having a description of what the expected outcome was supposed to be following the given steps. 
The instructions for the assignment were a bit confusing due to the length, otherwise the lab was interesting and useful once we made sense of the instructions.

