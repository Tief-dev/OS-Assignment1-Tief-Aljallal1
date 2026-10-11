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
| **Full Name** | Tief Aljallal |
| **Student ID** | 444052215 |
| **University Email** | 444052215@std.psau.edu.sa |
| **GitHub Username** | Tief-dev |
| **Repository Link** | https://github.com/Tief-dev/OS-Assignment1-Tief-Aljallal |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

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

### Entry 1 — October 11, 2026
**What I did:** Set up my GitHub repository.

**Details:** I forked the instructor's starter repository, renamed it to `OS-Assignment1-Tief-Aljallal`, and updated the student ID in `SchedulerSimulation.java`. I committed the change separately.

**Challenges:** I had some confusion about GitHub forks and repository naming.

**Solution:** I created a fresh fork directly from the instructor's starter repository and checked the repository name.

**Time spent:** [25 mins]

---

### Entry 2 — October 11, 2026
**What I did:** Implemented process priorities.

**Details:** I added a `priority` field to the `Process` class, assigned a random value from 1 to 10 in the constructor, and displayed the priority in `addProcessToQueue()` without changing FIFO scheduling.

**Challenges:** I needed to identify where the priority should be stored and displayed.

**Solution:** I placed the field in the `Process` class and used `getPriority()` when printing the queue-entry message.

**Time spent:** [21 mins]

---

### Entry 3 — October 11, 2026
**What I did:** Added context-switch counting.

**Details:** I declared a static `contextSwitchCount` variable in `SchedulerSimulation`, incremented it before `currentThread.start()`, and printed the total after the simulation.

**Challenges:** I needed to determine where the counter should increase.

**Solution:** I located the scheduler loop and placed the increment immediately before each thread starts.

**Time spent:** [20 mins]

---

### Entry 4 — October 11, 2026
**What I did:** Implemented waiting-time tracking.

**Details:** I added `waitingTime` and `lastReadyTime` fields, then created `markReady()`, `stopWaiting()`, and `getWaitingTime()` methods. I connected these methods to queue insertion and process selection. I also created an `allProcesses` list and a final statistics table.

**Challenges:** Understanding how processes were associated with threads and how to accumulate waiting time across multiple scheduling rounds.

**Solution:** I used `processMap` to retrieve the correct `Process` object and accumulated elapsed time using `System.currentTimeMillis()`.

**Time spent:** [50 mins]

---

### Entry 5 — October 11, 2026
**What I did:** Worked on assignment documentation.

**Details:** I reviewed the requirements in `MY_WORK.md`, documented the implementation stages, and prepared to answer the reflection and technical questions.

**Challenges:** Completing the documentation within the remaining time.

**Solution:** I organized the documentation by feature and focused on explaining the code I had implemented.

**Time spent:** [30 mins]

---

## Development Log Summary

**Total time spent on assignment:** Approximately 2 hours and 26 minutes.

**Most challenging part:** Implementing waiting-time tracking. I had to understand how processes were connected to threads and how to calculate waiting time across multiple scheduling rounds.

**Most interesting learning:** Understanding how Round-Robin scheduling works, especially how processes enter the ready queue, execute for a time quantum, and return to the queue if they haven't finished.

**What I would do differently next time:** I would start the assignment earlier, document my progress throughout development, and leave enough time to compile, test, and debug the program before submission.

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

I learned how Java threads can be used to simulate multiple processes sharing CPU time. In this assignment, the Process class implements Runnable, allowing each process to be executed through a Java Thread. I learned that Thread.start() begins execution, while Thread.join() makes the main scheduler wait until the current thread finishes. The Thread.sleep() method simulates the time a process spends executing its assigned quantum. I also learned that Round-Robin scheduling uses a FIFO ready queue to give processes turns instead of letting one process use the CPU indefinitely. One interesting detail was that the scheduler creates a new thread whenever an unfinished process is added back to the queue.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The most challenging part was implementing the waiting-time tracking feature. At first, I found it difficult to understand where the waiting timer should start and stop. I also needed to understand the relationship between the Process objects and the Java threads stored in the ready queue. Since a process can return to the queue multiple times, calculating its waiting time only once would not be accurate. I had to use System.currentTimeMillis() and accumulate the waiting periods rather than replace the previous value. Connecting these calculations to the scheduler loop was the part that required the most attention.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I approached the assignment by dividing the required features into smaller steps. I examined the Process class and the scheduling loop to understand where each change belonged. When implementing priorities, I first added the field and getter before modifying the queue message. For context-switch counting, I identified the point where the scheduler starts each thread and added the counter there. For waiting-time tracking, I used the existing processMap to connect the selected thread to its process and called the timing methods at the appropriate points. I also asked for guidance when I was unsure about method placement, which helped me understand the structure of the program.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading is useful in applications that need to handle several activities without making the entire program unresponsive. For example, a web browser can use different threads for loading pages, handling user input, and performing background tasks. Video games can also use threads to separate activities such as input handling, physics calculations, and loading resources. The Round-Robin scheduling concept is useful because it demonstrates how CPU time can be shared fairly between tasks. In my simulation, each process receives a time quantum and returns to the ready queue if it still has work remaining. Understanding these concepts can help me design applications that manage concurrent tasks more efficiently.


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

A process is an independent running program with its own memory space, while threads within the same process share memory and resources. Threads are generally faster to create and communicate between than separate operating-system processes. In SchedulerSimulation.java, the Process class represents a simulated process rather than a real operating-system process. The addProcessToQueue() method uses new Thread(process) to create a Java thread that executes the simulated process. Using threads makes it easier to implement the scheduler and share information through objects such as processMap.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, a process that does not finish within its time quantum returns to the end of the ready queue if other processes are waiting. In my simulation, P8 had a burst time of 5071 ms and the time quantum was 5000 ms. P8 executed for 5000 ms, leaving 71 ms, so it was requeued once before finishing. When it received another turn, it completed its remaining 71 ms. Requeuing helps maintain fairness because other processes get CPU time instead of waiting for one long process to finish.

Example from my output:
```
P8 added to ready queue | Burst time: 5071ms
P8 completed quantum 5000ms | Overall progress: 98%
Remaining time: 71ms
P8 yields CPU for context switch
P8 added to ready queue | Burst time: 5071ms
P8 completed quantum 71ms | Overall progress: 100%
P8 finished execution!
```

**Explanation of example:**
P8 needed slightly more CPU time than one quantum allowed. After its first 5000 ms of simulated execution, it returned to the queue and waited for another turn. It then completed its remaining 71 ms.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1's thread enters the New state when new Thread(process) is executed in addProcessToQueue(), before the thread starts.

2. **Runnable**: When the scheduler calls currentThread.start(), P1 becomes eligible to execute and enters the Runnable state.

3. **Running**:  P1 runs when the JVM schedules its thread and executes the run() method.

4. **Waiting**: P1 enters the timed-waiting state when Thread.sleep(stepTime) pauses its execution; meanwhile, the main scheduler thread waits for P1 to finish by calling currentThread.join().

5. **Terminated**: P1's thread terminates when its run() method returns after completing one quantum, even if the simulated process still has remaining burst time and later runs using a newly created thread.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): CPU Scheduling
**Description**:
An operating system manages multiple runnable tasks that compete for CPU time. Each task needs opportunities to execute while other tasks are also waiting.

**Why Round-Robin works well here**:
 Round-Robin assigns each task a limited time quantum before giving another task a turn. This improves fairness and responsiveness because one CPU-intensive task cannot continuously occupy the processor. The operating system performs a context switch when changing which task is executing.

### Example 2: Background Task Processing

**Description**:
An application server may have several tasks that need processing, such as updating information, handling requests, or performing background calculations.

**Why Round-Robin works well here**:
 A Round-Robin approach can give each runnable task a limited opportunity to make progress before moving to the next one. This prevents a single long-running task from monopolizing a worker. The ready queue represents tasks waiting for execution, and the time quantum determines how long each task can work before yielding.

## Summary

**Key concepts I understood through these questions:**

1. The differences between threads and processes.
2. How Round-Robin scheduling uses a ready queue and time quantum.
3. How Java thread creation, execution, waiting, and termination work.
   
**Concepts I need to study more:**
1.Synchronization and race conditions between threads.
2.How operating systems perform real context switches.

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
