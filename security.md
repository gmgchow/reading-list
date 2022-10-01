# Security

## Secure Coding: Principles and Practices (by Mark G. Graff, Kenneth R. van Wyk, 2003)
- Status: Done (Oct 2020)
- https://learning.oreilly.com/library/view/secure-coding-principles/0596002424/
- Notes:
	- Lists and describes the 30 principles of security architecture, something that all engineers definitely need to know in order to build secure software
	- Examines how security fits into each stage of the SDLC
	- Personal Rating: **10/10 (must read!)** because every engineer and security engineer needs to know these principles, and this book explains everything in a way that's easy to understand

## Practical Security Automation and Testing (by Tony Hsiang-Chih Hsu, 2019)
- Status: Done (Feb 2020)
- https://learning.oreilly.com/library/view/practical-security-automation/9781789802023/
- Notes:
	- Extremely relevant; it talks about secure pipelines, SAST/DAST, DefectDojo, etc.
	- Introduces many tools for security testing and automation. Even if you don't use the same technology stack, it's still useful to know and interesting to read about (e.g. I did not know that JMeter could be used for security testing! I have only ever used it for load and QA testing)
	- Personal Rating: **10/10 (must read!)** because it is interesting to see how automation testing can be applied to security as well

## Agile Application Security (by Laura Bell, Jim Bird, Rich Smith, Michael Brunton-Spall, 2017)
- Status: Done (Jan 2020)
- https://learning.oreilly.com/library/view/agile-application-security/9781491938836/
- Notes:
	- Very interesting, it talks about how to integrate security into the software development process in a way that enables engineers to move fast securely
	- There is lots of information about automation and testing
	- Personal Rating: **10/10 (must read!)** because it talks about best practices and feels very relevant to organizations today

## The Web Application Hacker's Handbook 2nd Edition (by Marcus Pinto, Dafydd Stuttard, 2011)
- Status: Done (Nov 2019)
- https://learning.oreilly.com/library/view/the-web-application/9781118026472/
- Notes:
	- Goes into VERY detailed explanations about all the vulnerabilities that can be present in web applications
	- Includes detailed "hack steps" to show how one can test for these vulnerabilities, and also has links to Portswigger's online labs!
	- Very long but contains some slightly out-of-date information (Silverlight, Flash, etc. which aren't really used anymore) so some parts can be skipped
	- Personal Rating: **10/10 (must read!)** because it does a really good job explaining everything as though the reader is a complete beginner. I liked how it explains the vulnerabilities, how to detect them when testing, and how to prevent them.

## Threat Modeling (by Adam Shostack, 2014)
- Status: Done (Oct 2019)
- https://learning.oreilly.com/library/view/threat-modeling-designing/9781118810057/
- Notes:
	- Very helpful for learning how to do security design reviews
	- Covers STRIDE framework in detail (in addition to other frameworks) and lists things to pay attention to when threat modeling
	- Personal Rating: **10/10 (must read!)** because it teaches what to look out for and how to think when doing security design reviews. I would highly recommend it for beginners in security because thinking like a hacker can be difficult if you don't know what to look out for and are just starting out, but this book gives a good base.

## Tribe of Hackers Red Team: Tribal Knowledge from the Best in Offensive Cybersecurity (by Marcus J. Carey, Jennifer Jin, 2019)
- Status: Done (Sept 2022)
- https://www.amazon.com/Tribe-Hackers-Red-Team-Cybersecurity/dp/1119643325
- Notes:
	- This book is a compilation of 47 veteran Red Teamers' tips on working in the industry. Each person answers the same set of interview questions ("What are some tips on writing a good report?", "What nontechnical skills do you look for?", etc.)
	- I personally found it a bit long because across the 47 interviews, many of the same ideas were repeated over and over again so I think 47 chapters is a bit much.
	- Personal Rating: **9/10 (extremely helpful!)** because it provides interesting insight on the industry from veterans. This book will be especially helpful to people like me who don't have a lot of experience in the industry.

## Microservices Security in Action (by Wajjakkara Kankanamge Anthony Nuwan Dias, Prabath Siriwardena, 2020)
- Status: Done (Oct 2020)
- https://learning.oreilly.com/library/view/microservices-security-in/9781617295959/
- Notes:
	- Covers standard micoservice security practices (JWT, mTLS, managing certificates, etc.) in detail
	- Rather than only focusing on security, this book also walks through how to make a microservice using Springboot framework so it can be helpful to microservice developers as well as security engineers and SRE
	- Personal Rating: **9/10 (extremely helpful!)** because topics are covered to a great level of detail and I think this book would be especially helpful to developers who are just starting out in building microservices since it also includes best practices and code samples. Personally I found those parts a bit distracting since I am not using that particular framework and programming language but I enjoyed the security-related parts of the book

## SSCP Systems Security Certified Practitioner All-in-One Exam Guide, Third Edition, 3rd Edition (by Darril Gibson, 2018)
- Status: Done (Mar 2020)
- https://learning.oreilly.com/library/view/sscp-systems-security/9781260128710/
- Notes:
	- It's a very good study guide for SSCP, I found it more interesting and thorough than the Coursera SSCP course
	- Personal Rating: **9/10 (extremely helpful!)** because it covers the material without being too boring or dry. The practice questions were also very helpful in preparing for the exam.

## Secure Programming with Static Analysis (by Jacob West, Brian Chess, 2007)
- Status: Done (Jan 2020)
- https://learning.oreilly.com/library/view/secure-programming-with/9780321424778/
- Notes:
	- Some of it was outdated or not relevant because it focused on vulnerabilities in Javascript and C+ (in more modern languages we don't need to worry so much about garbage collection, memory allocation, etc.)
	- Lots of info about what to test for during security testing (input validation, etc.), probably too much info I will go back and re-read this for the info to sink in
	- Personal Rating: **9/10 (extremely helpful!)** because it covers a wide range of topics- security testing, defensive programming, common vulnerabilities and mistakes. It's a good all-around guide.

## Threat Modeling(by Izar Tarandach, Matthew J. Coles, 2020)
- Status: Done (Nov 2020)
- https://learning.oreilly.com/library/view/threat-modeling/9781492056546/
- Notes:
	- Explains threat modeling at a high level, from creating models to analysis
	- Explains the different approaches that are commonly used (STRIDE, PASTA, etc.)
	- Personal Rating: **8/10 (very good!)** because it explains the whole process from beginning to end, for beginners of threat modeling. However, I wish it had more examples or even exercises to work through to help deepen understanding.

## Web Security for Developers (by Malcolm McDonald, 2020)
- Status: Done (Feb 2021)
- https://learning.oreilly.com/library/view/web-security-for/9781098122683/
- Notes:
	- It covers the major security issues to be careful of when developing web applications
	- Personal Rating: **7/10 (good to read)** because this book can be used like a checklist and is easy to understand so it will certainly be useful to web developers. I personally found the content to be a bit too shallow for security engineers but it is a good book to recommend to web developers that you are working with to help increase security awareness.

## Mastering Kali Linux for Advanced Penetration Testing - Third Edition (by Vijay Kumar Velu, Robert Beggs, 2019)
- Status: Done (Dec 2020)
- https://learning.oreilly.com/library/view/mastering-kali-linux/9781789340563/
- Notes:
	- The topics in the book progresses in the same order of penetration testing (information gathering > exploitation > post-exploitation), making it easy to organize your thoughts
	- It covers a wide variety of tools that can be used, including Metasploit, Social Engineering Toolkit, Netcat, Wireshark, etc.
	- Personal Rating: **7/10 (good to read)** because it introduces so many tools that each one is only covered briefly. Perhaps it will be more useful to read this book while doing hands-on labs (i.e. Hack the Box) at the same time to gain a deeper understanding

## The Tangled Web (by Michal Zalewski, 2011)
- Status: Done (Sept 2020)
- https://learning.oreilly.com/library/view/the-tangled-web/9781593273880/
- Notes:
	- Talks about vulnerabilities in web applications and browsers, and also goes into detail about the history of web browsers, web development, etc.
	- Similar to 'The Web Application Hacker's Handbook' above, but is a little more wordy and includes more details around history
	- The 'Engineer Cheatsheet' at the end of each section is useful and acts as a nice summary
	- Personal Rating: **7/10 (good to read)** because personally, I would recommend 'The Web Application Hacker's Handbook' over this time. They cover similar topics but that one is easier to read due to being more concise

## Hacking the Hacker (by Roger A. Grimes, 2017)
- Status: Done (Oct 2019)
- https://learning.oreilly.com/library/view/hacking-the-hacker/9781119396215/
- Notes:
	- Introduces common security problems (e.g. crytography, insecure OS, the rising of IoT hacks, etc.) and includes interviews from specialists working in these areas
	- Doesn't go much into technical details because it focuses on the motivations and psychology behind hacking
	- Personal Rating: **7/10 (good to read)** because it was interesting learning about the backgrounds of some famous security specialists and the psychology of hacking

## Cybersecurity Attacks - Red Team Strategies (by Johann Rehberger, 2020)
- Status: Done (Aug 2022)
- https://learning.oreilly.com/library/view/cybersecurity-attacks/9781838828868/
- Notes:
	- The first few chapters covers best practices and processes for building and operating a Red Team, and then it moves onto introducing tools for specific types of penetration testing (Active Directory, setting up a Honey Pot, etc.)
	- Personal Rating: **6/10 (can skip)** because it was way too specific in introducing tooling (e.g. assuming the use of AD, assuming the OS of targets is Windows, etc.). I was hoping for a more general, less vendor-specific guide for how to build a Red Team and operate day-to-day but this book wasn't it.

## Penetration Testing (by Georgia Weidman, 2014)
- Status: Done (Oct 2019)
- https://learning.oreilly.com/library/view/penetration-testing/9781457185342/
- Notes:
	- Mostly focuses on hacking with Kali Linux, Metasploit, network attacks
	- Personal Rating: **6/10 (can skip)** because it was just mediocre. Perhaps it would have been more useful if I followed along hands-on in order for the material to sink in better.

## The Hacker Playbook 3 (by Peter Kim, 2018)
- Status: Done (Oct 2019)
- https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing-ebook/dp/B07CSPFYZ2
- Notes:
	- Recommends many tools for red-teaming
	- Has very detailed labs showing how to use the tools so you can set up your PC and follow the tutorials step by step
	- Personal Rating: **6/10 (can skip)** because it introduces way too many tools in too shallow of a depth

## Security Engineering (by Ross Anderson, 2008)
- Status: Dropped (Oct 2019)
- https://learning.oreilly.com/library/view/security-engineering-a/9780470068526/
- Notes:
	- Basically covers topics mentioned in CompTIA Security+ and other books but in much greater detail with examples from history and industry news, etc.
	- Personal Rating: **4/10 (bad.)** because it goes very off-topic...instead of explaining in detail about security topics, it tries to link historical and news events to security concepts. Maybe this book would be great for people already skilled in security who also happened to be interested in news/history, but I would not recommend it for people trying to learn just security itself.
