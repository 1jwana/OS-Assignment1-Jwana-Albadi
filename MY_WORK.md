# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Jwana Albadi |
| **Student ID** | 445052167 |
| **University Email** | 445052167@std.psau.edu.sa |
| **GitHub Username** | 1jwana |
| **Repository Link** | https://github.com/1jwana/OS-Assignment1-Jwana-Albadi ||
 
---

## 🎥 Video Link

**Video Link**: [(https://drive.google.com/file/d/1r9aXYG_fZzoFENdPPRbRq2bgBPkcBOZP/view?usp=sharing)]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 6, 2026, 6:58 PM]

**What I did**: Set up my GitHub repository and implemented Feature 1 (Process Priority).

**Details**:
- Set up my assignment repository and opened the Java project in VS Code.
- Verified my student ID in `SchedulerSimulation.java`.
- Added a `priority` field to the `Process` class.
- Updated the constructor to accept a priority value.
- Added the `getPriority()` method to retrieve the process priority.
- Generated random priority values between 1 and 10.
- Updated the output to display each process's priority.
- Tested the feature and committed the changes to GitHub.

**Challenges**: I encountered a GitHub permission error when trying to push my changes.

**Solution**: I checked my GitHub authentication, corrected the account credentials, and successfully pushed my changes to the repository.

**Time spent**: Approximately 3 hours and 35 minutes (including breaks).

---

### Entry 2 - [October 6, 2026, 11:01 PM]

**What I did**: Implemented Feature 2 (Context Switch Counter).

**Details**:
- Added a static integer variable named `contextSwitchCount`.
- Updated the scheduler loop to increment the counter before starting each process thread.
- Added an output statement to display the total number of context switches.
- Ran the simulation to verify that the counter worked correctly.
- Confirmed that the output displayed `Total context switches: 22`.
- Committed and pushed Feature 2 to GitHub separately.

**Challenges**: I needed to determine the correct location in the scheduler loop to count each process execution.

**Solution**: I reviewed the scheduler loop and placed the increment immediately before `currentThread.start()`.

**Time spent**: Approximately 50 minutes (excluding breaks).
---

### Entry 3 - [October 7, 2026, 11:15 AM]

**What I did**: Implemented Feature 3 (Waiting Time and Turnaround Time).

**Details**:
- Added `creationTime` and `totalWaitingTime` variables to the `Process` class.
- Used `System.currentTimeMillis()` to record when each process was created.
- Calculated turnaround time using the difference between process creation and completion times.
- Calculated waiting time by subtracting the CPU burst time from the turnaround time.
- Updated the final summary to display each process's name, burst time, waiting time, and turnaround time.
- Ran the simulation and verified that the summary appeared after all processes completed.
- Committed and pushed Feature 3 to GitHub.

**Challenges**: I needed to understand how to calculate waiting time and turnaround time without adding unnecessary variables.

**Solution**: I used the creation and completion timestamps to calculate turnaround time, then subtracted the CPU burst time to estimate waiting time.

**Time spent**: Approximately 2 hours and 30 minutes (excluding breaks).

---

### Entry 4 - October 9, 2026, 7:35 PM

**What I did**: Worked on the reflection and technical questions in MY_WORK.md.

**Details**:
- Answered the four reflection questions about multithreading.
- Completed the four technical questions about threads, processes, and Round-Robin scheduling.
- Used the program output to explain the ready queue behavior.
- Reviewed the thread lifecycle and real-world applications of Round-Robin scheduling.

**Challenges**: Understanding the thread lifecycle and finding a suitable example from the program output.

**Solution**: Reviewed the code and checked the output to understand the concepts better.

**Time spent**: Approximately 2 hour (excluding breaks)

---

### Entry 5 - October 9, 2026, 11:50 PM

**What I did**: Recorded the video demonstration for the assignment.

**Details**:
- Presented the three features I implemented.
- Showed the Java code and explained the modifications.
- Ran the simulation in VS Code and demonstrated the output.
- Explained how `Thread.start()` and `Thread.join()` work.
- Showed the GitHub repository and commit history.

**Challenges**: Explaining the code clearly within the required video duration.

**Solution**: Prepared the code sections in advance to make the presentation more organized.

**Time spent**: Approximately 10 minutes.

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: Approximately 7 hours and 45 minutes (excluding breaks)

**Most challenging part**: Calculating the waiting time and turnaround time for each process

**Most interesting learning**: Understanding how Round-Robin scheduling works and how threads share CPU time

**What I would do differently next time**: I would read the code more carefully before making changes and test each feature step by step

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[I learned how multithreading works in Java and how threads are used in our program. I understood that `Runnable` is used to define the task that a thread will execute. We used `Thread.start()` to start a thread and `Thread.join()` to wait for it to finish. I also learned that `Thread.sleep()` is used in our simulation to represent CPU execution time. At first, I was confused about how the threads were executed in order. After running the program and checking the output, I understood how the scheduler controls their execution]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part for me was Feature 3, which was calculating waiting time and turnaround time. At first, I was not sure which variables I needed to add to the code. I also had to understand the difference between waiting time and turnaround time. I used `System.currentTimeMillis()` to record the time and calculate the turnaround time. Then I calculated waiting time by subtracting the burst time from the turnaround time. After running the program and seeing the process summary, I understood the calculations better]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I started by reading the code again to understand how the scheduler works. I also reviewed the assignment instructions to make sure I understood what Feature 3 required. I worked on the changes step by step instead of changing everything at once. I used `System.currentTimeMillis()` to calculate the turnaround time and then used it to calculate waiting time. After making the changes, I ran the program and checked the process summary to see if the results made sense. Testing the code helped me understand the calculations and feel more confident about my solution]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading can be useful in many applications that need to handle different tasks. For example, in a game, one thread can handle the player's actions while another handles background tasks. This can help the game stay responsive while different things are happening. Another example is a music player that plays music while the user searches for another song. I learned from this assignment that threads can be used to manage these tasks without making the whole application stop. I think multithreading is important because it helps applications run more smoothly]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A process is a running program, while a thread is a smaller part of a process that executes tasks. Processes usually have separate memory, but threads in the same process can share memory. Threads are also faster and easier to create than separate processes. In our assignment, the `Process` class represents a simulated process, and we use `new Thread(process)` to run it using a Java thread. We used threads because they made it easier to simulate CPU scheduling inside one Java program]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, each process gets a time quantum of 4000ms. If the process does not finish, it goes back to the ready queue. For example, P1 has a burst time of 8918ms, so it needs three turns to finish. P1 is added back to the ready queue two times before completing. This makes scheduling fair because other processes also get a chance to use the CPU.]

Example from my output:

[ P1 executing quantum [4000ms]
P1 completed quantum 4000ms
Remaining time: 4918ms
P1 yields CPU for context switch
P1 added to ready queue | Burst time: 8918ms | Priority: 9 ]
 



**Explanation of example:**
[P1 used 4000ms of CPU time but still had 4918ms remaining. Since it was not finished, it returned to the ready queue to wait for another turn. This allows the scheduler to run other processes before P1 continues]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 is in the New state when its thread is created using new Thread(process)]

2. **Runnable**: [P1 becomes Runnable when the scheduler calls Thread.start()]

3. **Running**: [P1 starts running when the CPU executes its run() method]

4. **Waiting**: [The main thread waits for P1 to finish using Thread.join(), while P1 uses Thread.sleep() to simulate CPU execution time]

5. **Terminated**: [P1 becomes Terminated when its run() method finishes]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling]

**Description**:
An operating system runs different programs, such as a browser and a music player. Each program needs CPU time to execute its tasks. The scheduler gives each program a time quantum, similar to our simulation

**Why Round-Robin works well here**:
Round-Robin allows each program to use the CPU for a limited time. If a program does not finish, it waits for another turn. This makes CPU scheduling fair and helps programs stay responsive

### Example 2: [Game Server]

**Description**:
A game server needs to handle requests from different players. Each player's request can be treated as a task that needs processing time. The server can use a Round-Robin approach to give tasks turns

**Why Round-Robin works well here**:
Round-Robin helps prevent one player's task from taking all the processing time. Each task gets a turn, and unfinished tasks can wait for the next round. This helps the server handle players fairly

## Summary

**Key concepts I understood through these questions:**
1. The difference between threads and processes.
2. How Round-Robin scheduling uses the ready queue.
3. How `Thread.start()`, `Thread.join()`, and `Thread.sleep()` work.

**Concepts I need to study more:**
1. Thread synchronization.
2. Thread lifecycle states.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
