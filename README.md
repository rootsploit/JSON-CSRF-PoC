# JSON CSRF PoC

### What is CSRF?
CSRF is Cross-Site Request Forgery vulnerability which can be used to force an user to conduct unintended actions on a Web Application. Using this flaw an attacker can perform various attacks based on the affected module such as changing Email ID, Password for the User's Account.

### CSRF on JSON Endpoint:
Cross-Site Request Forgery on JSON Endpoint using Fetch API as usual HTML Form does not work in API Request due to padding issue.

### Below are the required conditions in order to perform this attack:
  1. Authentication Method should be cookie based only
  2. No Authentication Token in Header
  3. Same-Origin Policy should not be enforced

Change the URL and Body from the PoC file to perform the CSRF on JSON Endpoint.

More details on: <a href="https://rootsploit.com/2020/08/01/exploiting-csrf-on-json-endpoint-w-o-flash/">https://rootsploit.com</a>

![alt text](https://rootsploit.com/wp-content/uploads/2020/08/JSON_CSRF-PoC.png)
