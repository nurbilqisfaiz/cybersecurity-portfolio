# TryHackMe - Offensive Security Intro

## 1. Overview

- **Platform:** TryHackMe
- **Room:** Offensive Security Intro
- **Category:** Offensive Security
- **Difficulty:** Beginner
- **Status:** Completed
- **Completion:** All questions answered correctly

## 2. Learning Objectives

The purpose of this room was to understand the basics of offensive security and how hackers identify weaknesses in websites.

I also learned how to use a security tool called DIRB to discover hidden pages on a website and understand why unsecured admin pages can be dangerous.

## 3. Tools and Technologies Used

- TryHackMe AttackBox
- DIRB (Directory Brute Force Tool)
- Terminal
- FakeBank Web Application
- Web Browser

## 4. Practical Activities

### Task 1: Think Like a Hacker

Learned the difference between offensive security and defensive security.

- Offensive security focuses on finding weaknesses before attackers exploit them.
- Defensive security focuses on protecting systems and responding to security threats.

### Task 2: Starting the Lab

Launched the FakeBank virtual application through the TryHackMe environment.

Explored the simulated banking website and identified the account information required for the next activity.

### Task 3: Find Hidden Pages

Used DIRB to scan the FakeBank website and discover hidden directories and pages.

Command used:

```bash
dirb http://fakebank.thm
```

The scan returned two URLs. I examined the discovered pages and identified the hidden admin-related page.

### Task 4: Attack the Admin Page

Accessed the hidden bank-transfer page discovered in the previous task.

I tested the vulnerability in the simulated banking environment by performing a bank transfer and observing the application response.

This demonstrated how an unsecured administrative page could allow unauthorised actions.

## 5. What I Learned

From this practical exercise, I learned:

1. The difference between offensive and defensive security.
2. How to use DIRB to discover hidden website directories.
3. How attackers can find pages that are not directly linked on a website.
4. Why administrative pages should have proper authentication.
5. How an exposed and unsecured administrative function can create security risks.

## 6. Security Recommendations

The FakeBank application could improve its security by:

- Requiring proper login authentication before accessing administrative functions.
- Implementing access control to ensure only authorised users can perform bank transfers.
- Validating user permissions on the server side.
- Monitoring suspicious activities and unauthorised transactions.

## 7. Challenges Faced

I initially needed to understand how directory scanning works and how hidden website pages can be discovered.

After following the instructions and practising with DIRB, I understood how the tool identifies directories and how the discovered pages can reveal potential security weaknesses.

## 8. Personal Reflection

This was my first practical cybersecurity exercise on TryHackMe.

I gained a basic understanding of offensive security and learned how to use DIRB for directory discovery.

The exercise also helped me understand why websites should protect their administrative pages with proper authentication and access control.

I would like to practise more tools and learn how to identify different types of security vulnerabilities in future exercises.

## 9. Completion Status

**Completed successfully.**

All questions in the room were answered correctly.
