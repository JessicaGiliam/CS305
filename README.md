# CS305
Software Security SNHU

Prompt
For this course, you will choose one artifact to add to your GitHub repository for your portfolio. Submit either (1) the completed Artemis Financial Vulnerability Assessment Report, or (2) the completed Artemis Financial Practices for Secure Software Report that you created for your client, Artemis Financial, in Projects One and Two. These completed documents demonstrate your ability to complete a vulnerability assessment and code securely.

Once you have submitted one of the artifacts listed above, update the README file in your repository and include your answers to each of the questions below. You could include the questions and write a few sentences in response to each one, or you could write a paragraph or two weaving together all of your answers.

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
The client was Artemis Financial, and they needed development to enhance the security of their product, which featured an application for financial planning.

What did you do particularly well in identifying their software security vulnerabilities?
Many of the issues I identified could have been very easily prevented by using the most current version's of certain software. I did exceedingly well in finding the underlying problems in the CVE codes. I updated the code prior to even running the dependency report to mitigate having multiple additional vulnerabilities get flagged.

Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
Coding securely ensures that private information stays that way. This becomes abundantly important when dealing with sensitive information such as financial and personal demographics of any number of users. The well-being of a company will rely on the user understanding that they can trust the company with such sensitive information. If the user has no faith that their information will stay private, they will not use it.

What about the process of working through the vulnerability assessment did you find challenging or helpful?
I found Github helpful to find the cve codes and see what current versions were best. I found it challenging that as I worked through the dependency report, probably half of the vulnerabilities that were found were due to the lack of maintenance on the code base since it's induction. 

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
First I would make sure that the code is using versions of programs that are current prior to running a dependency check to avoid multiple unnecessary vulnerabilities, and make sure that the false positives are identified and removed prior to concentrating on the relevent vulnerabilities to fix. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
I reran the dependency check and made sure there were no errors in the code. 

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
I found researching CVE codes and issues on Github very helpful and will do that again in the future when needed. My coding practices did not change during this course. 

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
In this particular assignment I was able to shut down the service by creating a bogus query.


Guidelines for Submission
For your submission, include a link to your repository for your instructor in a text submission. Make sure your repository includes either (1) the completed Artemis Financial Vulnerability Assessment Report or (2) the completed Artemis Financial Practices for Secure Software Report you worked on in the projects in this course. You should also include the README file with your written responses. Use the CS Program GitHub Portfolio Tutorial to help you with this submission. This assignment will be graded pass/fail based on completion.

Note: In the previous module, you should have added your instructor as a collaborator and they should have accepted your request. Please email your instructor if you have trouble adding them as a collaborator.
