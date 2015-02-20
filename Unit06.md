---
layout: default
title: "CS305: Web Development"
course_description: "A detailed survey of Web-based application development, with particular emphasis on developing web applications using JavaScript, HTML, XML, AJAX, and Java Server Pages (JSP)."
next: ../Unit07
previous: ../Unit05
---
**Unit 6: Web Security and Encryption** <span id="6"></span> 
**Transferring data and personal information over the Internet should be
done in a secure manner.  This unit will introduce you to three
protocols that ensure data security in web applications—HTTPS, TLS, and
SSL—and will explain how these protocols (along with encryption) can
provide a secure means of data transport in web applications. **

**Unit 6 Time Advisory**  
This unit should take you 20 hours to complete.

☐    Subunit 6.1: 5 hours

☐    Subunit 6.2: 5 hours

☐    Subunit 6.3: 5 hours

☐    Subunit 6.4: 5 hours

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, students will be able to:

-   Explain how HTTPS works.
-   Explain how Browser Integration works.
-   Explain how HTTP Authentication works.
-   Demonstrate an understanding of Data Validation principles.

**6.1 Secure Hypertext Transfer Protocol (HTTPS)** <span
id="6.1"></span> 
-   **Web Media: Stanford University: Professor Mitchell and Professor
    Shmatikov’s “SSL/TLS Case Study”**
    Link: Stanford University: Professor Mitchell and Professor
    Shmatikov’s [“SSL/TLS Case
    Study”](http://www.stanford.edu/class/cs259/WWW04/lectures/)
    (PowerPoint or PDF)  
        
     Instructions: Click on the “02-SSL.ppt” file and review the
    presentation in its entirety.  HTTPS is a secure version of HTTP. 
    We implement HTTPS—which relies on two protocols in the TC/IP stack
    (TLS and SSL)—in all websites and Web Servers where information
    exchange must be secure.  
        
     Terms of Use: Please respect the copyright and terms of use
    [displayed on Stanford University’s
    website](http://www.stanford.edu/site/copyright.html).

**6.2 Browser Integration** <span id="6.2"></span> 
**6.2.1 Server Setup** <span id="6.2.1"></span> 
-   **Reading: Microsoft’s “How to Set Up SSL on a Server”**
    Link: Microsoft’s [“How to Set Up SSL on a
    Server”](http://technet.microsoft.com/en-us/library/bb124484%28EXCHG.65%29.aspx)
    (HTML)  
        
     Instructions: Read the article in its entirety.  Please note that
    this article provides an IIS-specific implementation technique.  For
    other Web Servers, refer to appropriate vendor documentation.  
        
     Terms of Use: Please respect the copyright and terms of use
    [displayed on the Microsoft
    website](http://technet.microsoft.com/en-us/library/bb124484%28EXCHG.65%29.aspx).

**6.2.2 Public Key Certificates** <span id="6.2.2"></span> 
-   **Reading: Microsoft’s “Public Key Certificate”**
    Link: Microsoft’s [“Public Key
    Certificate”](http://technet.microsoft.com/en-us/library/cc737812%28WS.10%29.aspx)
    (HTML)  
        
     Instructions: Certificates enable a Web Server to tell a Web
    Browser that it is who it claims to be.  It relies heavily on public
    key cryptography and the secure exchange of certificates.  
        
     Terms of Use: Please respect the copyright and terms of use
    [displayed on the Microsoft
    website](http://technet.microsoft.com/en-us/library/bb124484%28EXCHG.65%29.aspx).

**6.2.3 Acquiring Certificates** <span id="6.2.3"></span> 
-   **Reading: Pentura Labs’ “Creating Your Own Certificate Authority”**
    Link: Pentura Labs’ [“Creating Your Own Certificate
    Authority”](http://penturalabs.wordpress.com/2013/08/19/creating-your-own-certificate-authority/)
    (HTML)  
        
     Instructions: Read this article, which discusses ways you can use
    SSL to authenticate your server.  
        
     Reading this article should take approximately 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.3 HTTP Authentication** <span id="6.3"></span> 
**6.3.1 Usernames and Passwords** <span id="6.3.1"></span> 
-   **Reading: Binghamton University: Professor Steflik’s “Web
    Security”**
    Link: Binghamton University: Professor Steflik’s [“Web
    Security”](http://www.cs.binghamton.edu/~steflik/cs455/)
    (PowerPoint)  
        
     Instructions: Click on the “WebSecurity.ppt” file and review the
    Presentation in its entirety, paying specific attention to slides 2
    and 3.  
        
     Terms of Use: Please respect Binghampton University’s copyright and
    terms of use.

**6.3.2 The Base64 Algorithm** <span id="6.3.2"></span> 
-   **Reading: OWASP’s “Testing for Brute Force: Discovery
    Authentication Methods”**
    Link: OWASP’s [“Testing for Brute Force: Discovery Authentication
    Methods”](http://www.saylor.org/site/wp-content/uploads/2011/06/CS305-6.3.2.pdf)
    (HTML)  
        
     Instructions: Read the article section in its entirety.  
        
     Terms of Use:  <span class="Apple-style-span"
    style="font-family: Arial, 'Helvetica Neue', 'Liberation Sans', FreeSans, sans-serif; font-size: 13px; line-height: 22px; color: rgb(0, 0, 0); ">This
    work is licensed under a </span><span class="Apple-style-span"
    style="font-family: Arial, 'Helvetica Neue', 'Liberation Sans', FreeSans, sans-serif; font-size: 13px; line-height: 22px; color: rgb(0, 0, 0); ">[Creative
    Commons Attribution-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-sa/3.0/), and can be
    viewed in its original from
    [here](https://www.owasp.org/index.php/Testing_for_Brute_Force_(OWASP-AT-004)).
     </span>

**6.3.3 Advantages and Disadvantage of Basic Access Authentication**
<span id="6.3.3"></span> 
-   **Reading: EnterpriseNetworkingPlanet.com: Paul Ruben’s “Watch for
    Authentication Bypass Vulnerabilities”**
    Link: EnterpriseNetworkingPlanet.com: Paul Ruben’s [“Watch for
    Authentication Bypass
    Vulnerabilities”](http://www.enterprisenetworkingplanet.com/netsecur/article.php/3916331/Watch-for-Authentication-Bypass-Vulnerabilities.htm)
    (HTML)  
        
     Instructions: Read the article in its entirety.  
        
     Terms of Use: Please respect Internet.com’s copyright and terms of
    use [as outlined on the
    website](http://www.internet.com/Internetcom/Door/41189#Permissions).

**6.4 Data Validation** <span id="6.4"></span> 
-   **Reading: OWASP’s “Data Validation – OWASP”**
    Link: OWASP’s [“Data Validation –
    OWASP”](http://www.saylor.org/site/wp-content/uploads/2011/06/CS305-6.4.pdf)
    (HTML)  
      
     Instructions: Read the article in its entirety.  
      
     Terms of Use:  <span class="Apple-style-span"
    style="font-family: Arial, 'Helvetica Neue', 'Liberation Sans', FreeSans, sans-serif; font-size: 13px; line-height: 22px; color: rgb(0, 0, 0); ">This
    work is licensed under a </span><span class="Apple-style-span"
    style="font-family: Arial, 'Helvetica Neue', 'Liberation Sans', FreeSans, sans-serif; font-size: 13px; line-height: 22px; color: rgb(0, 0, 0); ">[Creative
    Commons Attribution-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-sa/3.0/), and can be
    viewed in its original form
    [here](https://www.owasp.org/index.php/Data_Validation). </span>


