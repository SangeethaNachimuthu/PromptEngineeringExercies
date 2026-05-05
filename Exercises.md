![Lexicon Logo](https://lexicongruppen.se/media/wi5hphtd/lexicon-logo.svg)

## Exercises

---

### Exercise 1 — Application Review and Candidate Response

### Scenario

A company is offering a **Fullstack course** and has received over **1000 applications**.

Each application may include:

* name
* background
* experience
* motivation
* technical skills

The company wants to:

* review applications efficiently
* decide if the candidate should be:

    * **Accepted**
    * **Rejected**
* generate a **professional email response**
* include **short feedback**

---

### Example Input

```text
Name: Erik Johansson
Background: Studied economics.
Experience: Basic knowledge of HTML and CSS.
Motivation: Wants to switch to a career in web development.
Skills: HTML, CSS

---

Name: Anna Svensson
Background: Computer science.
Experience: Built several web applications using React and Node.js.
Motivation: Wants to deepen backend skills.
Skills: JavaScript, React, Node.js, MongoDB
```

---

### Task

Write a prompt that:

1. Reviews each application
2. Decides:

    * Accepted or Rejected
3. Generates a **personalized email** for each candidate
4. Includes:

    * clear decision
    * short reasoning
    * professional tone

---

### Your Prompt

Write your full prompt below.

You can structure it as:

```text
SYSTEM:
...
System Prompt:
 - You are a professional application reviewer.
 - Your job is to write clear, polite, and accurate replies.
 - Always be empathetic, concise, and helpful.

Task: Write a response to the candidate about the status of the application.

Context: Review each application from the candidate, and decide whether to accept or reject the application.

Output: Professional email.

Constrains:
 - Under 120 words clear decision.
 - Professional tone.
 - Short reasoning (Feedback).

Instructions:
 - Each application may includes Name, Background, Experience, Motivation and Technical Skills.
 - Review each application.
 - Decide to Accept or Reject the application.

Example Input: 
Name: Erik Johansson 
Background: Studied economics. 
Experience: Basic knowledge of HTML and CSS. 
Motivation: Wants to switch to a career in web development. 
Skills: HTML, CSS

Example Input: 
Name: Anna Svensson 
Background: Computer science. 
Experience: Built several web applications using React and Node.js. 
Motivation: Wants to deepen backend skills. 
Skills: JavaScript, React, Node.js, MongoDB


USER:
...
Subject: Application Status – Erik Johansson

Dear Erik,

Thank you for your application. After careful review, we regret to inform you that we are unable to move forward at this time. While your motivation and foundational skills in HTML and CSS are appreciated, our current positions require more advanced web development experience. We encourage you to continue building your skills and reapply in the future.

Best regards,
[Your Name]
[Company]

Subject: Application Status – Anna Svensson

Dear Anna,

Thank you for your application. We are pleased to inform you that your background in computer science and hands-on experience with React and Node.js make you a strong fit for our team. Your motivation to further develop your backend skills aligns well with our current needs. We look forward to moving to the next stage of the process.

Best regards,
[Your Name]
[Company]

```

> Tip: Think about role, task, structure, and tone when writing your prompt.

---

## Exercise 2 — Meeting Notes to Clear Actions

### Scenario

A team had a meeting, but the notes are messy and unstructured.

The manager wants to quickly understand:

* what was discussed
* what decisions were made
* what the next steps are

---

### Example Input

```text
Project meeting - Monday

- talked about new website
- design not finished
- Johan working on API but waiting for access
- Sara finished UI
- deadline might move?
- issue with content from marketing
```

---

### Task

Write a prompt that:

1. Summarizes the meeting
2. Identifies decisions
3. Creates clear **action items**
4. Structures the output in a clean format

---

### Your Prompt

Write your full prompt below.

You can structure it as:

```text id="xw8p4s"
SYSTEM:
...

USER:
...
```

> Tip: Think about clarity, structure, and output format.

---

## Exercise 3 — Weekly Reports to Manager Overview

### Scenario

A team submits **weekly activity reports**.

Each report includes:

* completed tasks
* blockers
* time spent
* notes (often inconsistent)

The manager wants to:

* get a quick overview
* identify issues
* understand team progress

---

### Example Input

```text
Erik:
Worked on login bug, partially fixed.
Still issues with API.
About 6 hours debugging.
Blocked due to missing access.

---

Anna:
Finished dashboard UI.
Helped team with testing.
No blockers.
Worked ~8h/day.

---

Johan:
Started payment integration.
Not finished yet.
Unclear requirements.
```

---

### Task

Write a prompt that:

1. Summarizes each team member
2. Identifies blockers
3. Highlights risks
4. Creates a structured overview for the manager

---

### Your Prompt

Write your full prompt below.

You can structure it as:

```text
SYSTEM:
...

USER:
...
```

> Tip: Focus on extracting insights and structuring information clearly.

---
