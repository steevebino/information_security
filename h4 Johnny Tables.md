##  x) Read and Summarize

- Broken Access Control
  Broken Access Control is currently ranked as the #1 security risk in the OWASP Top 10.
   It occurs when an application fails to properly enforce "sandboxes," allowing users to act outside of their intended permissions.

  -Security Misconfiguration
  Security Misconfiguration is currently ranked as the #5 risk in the OWASP Top 10.
  It occurs when security settings are defined, implemented, or maintained improperly, often leaving "open doors" even if the application code itself is secure.

  -Vulnerable and Outdated Components
  Vulnerable and Outdated Components is currently the #6 risk in the OWASP Top 10.
  It focuses on the dangers of using third-party libraries, frameworks, or operating systems that have known security holes.

  -Injection
  njection is currently the #3 risk in the OWASP Top 10. While it has dropped from its long-held #1 spot, it remains one of the most dangerous
  vulnerabilities because it allows attackers to "trick" your application into executing unintended commands. Injection happens when an application sends untrusted data to an interpreter
   (SQL, Bash, NoSQL, LDAP) as part of a command or query. The interpreter can't tell the difference between the developer's command and the attacker's data, so it executes both.

  ## Goat installing webgoat

  I first updated and then installed "openjdk 17.0.9 2023-10-17"

  <img width="1860" height="824" alt="Screenshot 2026-02-10 215003" src="https://github.com/user-attachments/assets/aa7ca3ee-6ebc-451e-a02b-404b5c1a7844" />


  then made a firewall just in case,
  <img width="1854" height="588" alt="Screenshot 2026-02-10 215425" src="https://github.com/user-attachments/assets/1fc394a9-a2a9-4f0e-a9d5-5c3a5481fba2" />

  enabled it, 
  <img width="811" height="101" alt="Screenshot 2026-02-10 215642" src="https://github.com/user-attachments/assets/a7e9b17f-273b-4277-841f-6d664ac15694" />


##  a)Install WebGoat

<img width="1894" height="667" alt="Screenshot 2026-02-11 001008" src="https://github.com/user-attachments/assets/f611358c-d8c7-4988-ab70-62563b79e620" />

## b)  F12. Solve Webgoat 2023.4: General: Developer tools.

![WhatsApp Image 2026-02-11 at 00 40 27](https://github.com/user-attachments/assets/e55c660f-12a9-4d19-84ea-eb4c13918e91)


## c)  Not outdated. Update all operating system and all applications in your Linux.

![jpeg](https://github.com/user-attachments/assets/d428ed34-d1e8-4ad2-a43e-1c5a92625d85)

## d) SQL Zoo

<img width="1477" height="712" alt="Screenshot 2026-02-11 004826" src="https://github.com/user-attachments/assets/1422a8b5-73e0-482a-9d72-3e3088dc5caf" />

<img width="1424" height="671" alt="Screenshot 2026-02-11 004923" src="https://github.com/user-attachments/assets/1f910f92-4539-4c90-ac40-77d427b43490" />

<img width="1481" height="772" alt="Screenshot 2026-02-11 005022" src="https://github.com/user-attachments/assets/63da8acf-9edd-477d-8d2c-d79dbd627002" />



## e) Portswigger Labs

<img width="1871" height="951" alt="Screenshot 2026-02-11 005918" src="https://github.com/user-attachments/assets/8ce4e6d1-b7e5-46bb-add1-9df24df6e1b1" />

The exploit uses the payload ' OR 1=1-- to manipulate the database query.

' (Single Quote): Breaks out of the category string.

OR 1=1: A "tautology" (always true) that forces the database to return every row.

-- (Double Dash): Comments out the rest of the original code (like AND released = 1), bypassing the "hidden" restriction.

Result: The database ignores the "released" filter and displays all products.





  
