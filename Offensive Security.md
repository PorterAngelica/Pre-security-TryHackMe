# 🧠 Offensive Security – Introduction (TryHackMe Pre Security)

> _"To outsmart a hacker, you need to think like one."_

## 🔓 What is Offensive Security?

**Offensive Security** involves intentionally breaking into computer systems, exploiting software bugs, and finding loopholes in applications to gain unauthorized access. The goal is to **understand hacker tactics** in order to strengthen defenses.

---

## 💻 Practical Case: Hacking FakeBank

You are tasked with hacking the **FakeBank application** to steal money. You're provided with a user account to simulate being a regular user.

---

## 🕵️ Finding Hidden Functionality

One of the easiest ways to hack an application is by discovering **hidden features** or **secret URLs**. Sometimes, developers expose sensitive actions through URLs that aren't linked anywhere but still work if accessed directly.

---

## 🧰 Tool: `dirb`

### ❓ What is `dirb`?

`dirb` is a **brute-force tool** that scans a target website for hidden pages or directories. It uses a wordlist (a list of common page names) and tests them one by one to see which ones exist.

---

## 🖥️ Opening a Terminal

A **terminal** (also called the command line) allows users to interact with the computer by typing commands. Most hacking tools, including `dirb`, must be run through the terminal.

---

## 🚀 Running `dirb`

To scan the FakeBank site, use the following command:

```bash
dirb http://fakebank.thm
```

> Press **ENTER** to execute.

---

## 📄 Sample Output:

```bash
ubuntu@tryhackme:~/Desktop$ dirb http://fakebank.thm

-----------------
DIRB v2.22    
By The Dark Raver
-----------------

START_TIME: Thu Apr 17 16:29:52 2025
URL_BASE: http://fakebank.thm/
WORDLIST_FILES: /usr/share/dirb/wordlists/common.txt

---- Scanning URL: http://fakebank.thm/ ----
+ http://fakebank.thm/bank-deposit (CODE:200|SIZE:4663)                        
+ http://fakebank.thm/images (CODE:301|SIZE:179)                               
-----------------
END_TIME: Thu Apr 17 16:29:59 2025
DOWNLOADED: 4610 - FOUND: 2
```

---

## 🧠 How to Read the Output

- **URL_BASE**: The target site being scanned.
- **WORDLIST_FILES**: The dictionary of potential URLs used by `dirb`. Default: `/usr/share/dirb/wordlists/common.txt`.
- **FOUND**:
  - `bank-deposit`: A valid page (status code **200**).
  - `images`: A redirect (status code **301**).

📌 Tip: Try visiting the discovered URLs in your browser. They may reveal sensitive functionality.

---

---
