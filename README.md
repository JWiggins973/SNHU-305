# SNHU-305 Reflection

### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting company that develops individualized financial plans for its customers. The financial plans include savings, retirement, investments, and insurance. Artemis Financial are seeking a way to modernize its current web based application to better protect client data and finacial information.

### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

After identifying the client’s software vulnerabilities, I believe I did best by refactoring the code to include SHA-256 hashing for file verification. I say this because it successfully secured data transfers without introducing any new vulnerabilities. It is important to code securely because software vulnerabilities can be exploited to steal company or client data, as well as disrupt business operations. Additionally, the cost of fixing a vulnerability after deployment is much higher than addressing security at each step of the software development life cycle (SDLC). Strong software security improves client trust and enhances a company’s reputation, giving it a slight competitive edge in the market.

### Which part of the vulnerability assessment was challenging or helpful to you? 

The part of the vulnerability assesment I found most challenging was that after running the dependency check and it generated the file i cpouldnt open it for some reason, I would get a 404 error. Im still not entirely sure why this was happening but after some research i discovered that i had to move this file to the stataic folder under resources and it opened successfully. This was especially useful because next time I'll know what to do if this error occurs. But overal I see the value in using it because it shows how third party libraries can impact application security.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

To increase the layers of security I implemented the SHA-256 hashing algorithm to ensure data integrity during data trasnfers while implementing exception handling to prevent exposure to sensitive information

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
