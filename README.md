# CS-305
Journal portfolio
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Aretemis Financial is a company that helps customers manage their personal money, including retirement, insurance, investment, and savings accounts. They have engaged Global Rain, our company, to create an application that would enable their clients to access their accounts and submit content. Security is one of Artemis Financials' top concerns, and with good reason—especially when it comes to the application's ability to verify data transfers.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I believe I did well in using the Maven Dependency check to identify security vulnerabilities. By updating the spring-boot-parent version, the number of vulnerabilities found for this specific project was decreased. I also used a hash technique and safe cipher to create a checksum value. Writing secure code is crucial because sensitive information must be safe from hackers and kept secure when it is in jeopardy. Clients and customers put their trust in businesses to protect their data, therefore making sure software is secure will contribute to the security of the business as a whole.

What about the process of working through the vulnerability assessment did you find challenging or helpful?
Determining which dependencies the application used or did not use was the most difficult part of the vulnerability assessment. Knowing this was crucial for determining whether vulnerabilities were regarded as false positives. Reducing this list of potential false positives was greatly aided by updating the spring-boot-parent version to the most recent release.


How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
In order to construct a more secure application, I tackled the need for more security layers by utilizing hashing techniques and encryption. I also used an SSL certificate and keystore to guarantee the security of any data transferred within the program. Using a vulnerability assessment, I also made sure that there were no serious vulnerabilities in the application's dependencies. I'll apply these same methods in the future to manually check the code to make sure there are no vulnerabilities. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
By executing the code and confirming its functionality using a browser check, I was able to ascertain the security and functionality of the software and code. I was able to verify that the program was operating with the correct encryption algorithm and that the webpage opened with an SSL certificate by opening it in a browser. I made adjustments to my refactored code and retested the application to make sure everything was operating as it should, in case I ran into any bugs or unexpected outputs.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
The documentation regarding the Maven dependency checks and the Spring framework proved to be of great assistance. When I encounter questions or circumstances in the future that require me to perform duties of the same nature, I probably will make use of these same resources. 

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I would demonstrate my proficiency in running and interpreting vulnerability assessment results. I feel more at ease reading these reports since I feel like I've spent a lot of time studying how to do so. Since I'm becoming more proficient with hashing algorithms and encryption, I believe I could demonstrate this portion of my work to potential employers. 
