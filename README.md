# CS-305-SNHU-Project2

-- Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

- The client, Artemis Financial, is a financial consulting company where they help customers with creating financial plans. Artemis Financial wanted me to help them with giving security advice for their platform. They want to protect their users from security threats.

-- What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

- I believe, once I found the security vulnerabilities, that I did well with explaining each vulnerability, what it is and solutions to them. It is important to have secure code since hackers can take advantage of the application by taking user data. If the user data is compromised, it is bad for the safety of the customers. Software security adds to a company's wellbeing since no one would want to use an application that has security issues like suceptibility to attacks. Artemis Financial would have no customers if they did not have security for their platform and therefore it would cause the company to fail. 

-- What part of the vulnerability assessment was challenging or helpful to you?

- The most challenging part about the vulnerability assessment was learning how to suppress false positives. I did not have to do it for project 2 but for module 6 I struggled a bit to get some vulnerabilities to not show up anymore. But I think the assessment was super helpful in guiding me into what vulnerabilities that needed to be addressed. 

-- How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

- I first started with using a certificate. I generated a self-signed certificate so that the application would be secure immediately after I deployed it. Then, I used a algorithm cipher called SHA-256 to add message digesting to the application so that I could test if the data was being protected correctly. Lastly I ran a vulnerability test on the application before rendering and then after rendering to check if I had introduced any new vulnerabilities into the application. I woukd use the OWASP dependency check module again to assess vulnerabilities because the dependency gave a clean, easy to read view of what vulnerabilities needed to be mitigated. 

-- How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

- First, I ran the code without an refactoring just to see what vulnerabilities were already there. Then, I implemented the SHA-256 algorithm but didn't make a certificate yet nor change the application.properties file yet and ran the program again to make sure no errors or new vulnerabilities showed up. Lastly, I then changed the application.properties files to include the keystore information for the certificate and ran it once more to check for new vulnerabilities. I checked the vulnerabilities through the OWASP dependency-check file that was provided and made sure the 77 vulnerabilities I found did not increase.

-- What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

- The OWASP dependecy checker was a helpful resource when it came to checking for vulnerabilities. The NVD website was very helpful also with finding out more information on each vulnerability. I can see myself using both of these tools again in the future for sure.

-- Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
