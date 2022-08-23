# Cross-site Scripting

  ![Screenshot (869)](https://user-images.githubusercontent.com/63872951/186127677-8a39d5a9-bd61-4f15-9e6a-eb80e189fbd3.png)

- Cross-Site Scripting is a security vulnerability that's typically found in web applications which can be used to execute a malicious script on the ***target's machine***.

- There are multiple types of attack when talking about XSS, here are some:

    - Keylogging
    - Stealing Cookies
    - Phishing
   
- **Keylogging** - A keylogger is used by setting up an event listener on the target's keyboard, which will track their keystrokes and save them on the attacker's server. 

- **Stealing Cookies** - When an attacker steals a target's cookies, they can use that information to log in as the user without needing **advanced authentication** or even just find information stored in the cookies that could lead to devastating effects on the target's online saved accounts. This is why so many websites use `SSL` or some other form of protection against these attacks.

- **Phishing** - An interesting type of exploitation, an attacker can clone the website you're logging into and steal your credentials without you ever knowing. Another form of phishing is an attacker can insert code directly onto the webpage to change forms or input fields to steal the target's information.

# Common Types of XSS

## 1. DOM-Based XSS: 

- This is when an attack payload is executed by manipulating the [DOM]() (Document Object Model) in the target's browser. This type uses the `client-side code` instead of server-side code.

## 2. Reflected XSS: 

- This is when a malicious script bounces off another website onto the target's web application or website. Normally, these are passed ***in the URL*** as a query, and it's easy as making the target click a link. This type originates from the `target's request`.

## 3. Stored XSS: 

- This is when a malicious script is ***directly*** injected into the webpage or web application. This type originates from the `website's database`.

#

# Next Steps

- To learn more about XSS exploitation, detection and how to prevent it, go to **[Next Steps](https://github.com/ShubhamJagtap2000/JavaScript-Basics/tree/main/14%20Next%20Steps)**
