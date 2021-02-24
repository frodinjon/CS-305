# CS-305
Software Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial services company that provides financial planning solutions and insurance solutions to their clients. The issue they wanted me to address was secure storage of private data and secure communications to upload and download data.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I think I did the implementation of the keystore.jks very well. The instructions were very unclear in some cases, but I managed to get the keystore working, and then, I was even able to help a classmate integrate and configure the keystore in the SSL of the final project. Coding securely is important because there are thraets everywhere. People steal data constantly. In some instances, other companies even want to steal your data. Secure code can mitigate a lot of threats out there. The overall wellbeing of a company is improved with secure software because it increases trust in the company, it increases a companies reliability, and it decreases the chances of seeing the company on the news with some major data leak, which has become so common these days.

What about the process of working through the vulnerability assessment did you find challenging or helpful?
I found the implementation of the hash algorithm to be a bit challenging. This is because the source code needed to create a class that threw an exception in order for the message digest to work. The examples we had did not show that the same way, so implementing that was a bit of a task. Also, getting the SSL to work was also a bit of an involved task. I did not know that the files were out of place, but learning that enabled me to, in the final project, include my own keystore exactly where it needed to be to process right away. I found all of this helpful, though, because I want to code securely in my own life and I want to learn where the threats are so that I don't unknowingly expose myself or anyone else I'm coding for to attacks.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
I approached the need to increase security by first running the dependency checks. Then I analyzed the source code to make sure that nothing had an error. Then, I implemented the TLS and the encryption. I would do a similar procedure in the real world. I would try to find a more accurate list of false positives on the dependency checks, though, because some of those lists were huge and difficult to read through.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
For functionality, I ensured first that I had no code errors in Eclipse. Once I had the code error-free, I ran the service and opened up the localhost to confirm that the output was correct. I also verified that the site was accessed via https using the self-signed certificate. After refactoring, I checked to see about new vulnerabilities by running another dependency check and cross-checking the results against the previouos one. I also double-checked my code for any errors.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Creating SSL certificates was very useful. I think I will use that going forward to test secure communications while developing websites. I also really liked the dependency check tool. I think that is very helpful to analyze risks that are out there. I will definitely use that going forward.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I would like to showcase the final document and my ability to learn how to search for security threats and apply what I have learned to mitigate them. I think that skill can be built upon to make me more security conscious and more of an asset to a future employer. I would also like to showcase my keystore.jks file and how I refactored the code to use a self-signed certificate because that can be helpful in testing.
