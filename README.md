# Project 8 - Pentesting Live Targets

Time spent: 5 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: __________________

Description:

<img src="blue-vuln1.gif">

## Green

Vulnerability #1: __________________

Description:

<img src="green-vuln1.gif">

## Red

Vulnerability #1: Username Enumeration

Description: Using the existing usename "jmonroe99" I simply tried logging in with the username and a random password. The Blue and Green website gave me an Invalid Request because the username does not exist in the database. However, the Red website gave me an incorrect password response hinting the fact that the username exists. This vulnerability is caused due to the website given the intruder too much log in information.

<img src="red-vuln1.gif">


## Notes
N/A
