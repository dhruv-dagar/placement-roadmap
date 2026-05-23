# 🎯 6-Month Placement Roadmap — IIIT Delhi CSE (2026–27)
**Target:** Tier-1 Product Companies + AI-First Startups | **Start:** Day 1 of Summer Break

---

## PHASE OVERVIEW

### Why This Sequencing Matters
Most students grind LeetCode from Day 1 and burn out by Month 3. This roadmap is sequenced differently:
- **Foundation** builds the *thinking* muscles (DSA patterns, CS fundamentals, core AI tooling)
- **Application** converts that thinking into *demonstrable output* (projects, system design, LLM engineering)
- **Mastery** simulates the *interview battlefield* (mocks, optimization, behavioral polish)

Each phase is 8 weeks. Each phase ends with a checkpoint week.

---

### **PHASE 1 — FOUNDATION** (Weeks 1–8)
**Months:** 1–2 | **Start:** Day after semester ends

**Goal:** Build rock-solid DSA foundations (Arrays → Trees → Graphs), master 2 CS fundamentals (OS + DBMS), onboard to AI dev tooling, and ship Project 1.

**Why first?**
Without pattern recognition in DSA, grinding 300 problems yields nothing. The first 8 weeks are about *understanding structures and patterns*, not speed. OS and DBMS are the two most commonly tested CS fundamentals in IIIT placement interviews and can be prepared in parallel with DSA without heavy cognitive load.

**End-state:** 80 LeetCode problems done (quality > quantity), OS + DBMS notes ready, Cursor/Copilot workflow established, Project 1 in progress.

---

### **PHASE 2 — APPLICATION** (Weeks 9–16)
**Months:** 3–4 | **Semester begins mid-phase**

**Goal:** Advance DSA to Graphs + DP, add CN + OOP, integrate AI into your dev workflow deeply, complete Projects 1 & 2, build system design vocabulary.

**Why second?**
Once patterns are internalized, you shift from *learning* to *applying*. System design requires CS fundamentals to already be in place. Projects built in this phase should demonstrate the skills you've been developing — not just GPT wrappers, but real AI-integrated engineering.

**End-state:** 200 LC problems done, CN + OOP complete, 2 deployable projects, RAG pipeline built, resume v1 drafted.

---

### **PHASE 3 — MASTERY** (Weeks 17–24)
**Months:** 5–6 | **Semester in full swing**

**Goal:** Harden weak DSA areas, do daily mock interviews, complete Project 3, optimize resume and LinkedIn, run cold outreach campaigns for internships.

**Why last?**
Mock interviews are useless if you don't have the vocabulary yet. By Week 17, you'll have enough exposure to simulate real conditions meaningfully. This phase is about *speed, confidence, and signaling* — not new learning.

**End-state:** 300+ LC problems, 20+ mock interviews done, 3 live GitHub projects, internship applications out, placement-ready.

---
---

## WEEK-BY-WEEK BREAKDOWN

> **Time Budget Assumptions:**
> - Summer (Weeks 1–8): 6–7 hrs/day
> - Semester weeks (Weeks 9–24): 3–4 hrs weekdays, 6–7 hrs weekends
> - Total ~600 hours over 6 months

---

### 📌 PHASE 1: FOUNDATION (Weeks 1–8)

---

#### **Week 1**
**Theme:** Orientation + Arrays + Dev Environment Setup

**DSA (2 hrs/day):**
- Topic: Arrays — Two Pointers, Sliding Window, Prefix Sums
- Problems: 12–15 problems
- Resources:
  - LeetCode tags: `array`, `two-pointers`, `sliding-window`
  - Striver's A2Z: Step 3 (Arrays Easy → Medium)
  - CSES: Introductory Problems (all 19)
- Target problems: LC 1, 11, 15, 26, 53, 121, 167, 209, 238, 283, 560, 713

**CS Fundamentals (45 min/day):**
- OS: Process vs Thread, PCB, Process States, Context Switching
- Resource: Galvin Chapter 3–4 (skim), Gate Smashers OS playlist (YT), InterviewBit OS questions

**AI Skills (30 min/day):**
- Set up Cursor IDE, enable Claude/GPT-4 backend
- Learn: Tab completion, inline chat, codebase Q&A
- Exercise: Re-implement a previous assignment using Cursor — observe what it gets right/wrong

**Project Work:**
- Brainstorm Project 1 (see Project Roadmap section). Finalize idea. Set up GitHub repo with proper README skeleton.

**Daily Split (6 hrs summer):**
| Slot | Activity | Duration |
|------|----------|----------|
| Morning | DSA (fresh brain) | 2.5 hrs |
| Midday | CS Fundamentals | 1 hr |
| Afternoon | Project / AI Tools | 1.5 hrs |
| Evening | Review + Anki | 1 hr |

---

#### **Week 2**
**Theme:** Arrays (Advanced) + Sorting Algorithms

**DSA:**
- Topic: Sorting — Merge Sort, Quick Sort, Count Sort; Array Hard problems
- Problems: 12–15 problems
- Resources:
  - Striver's A2Z: Step 3 Medium/Hard
  - CSES: Sorting & Searching (first 8 problems)
  - LC: 56, 75, 84, 88, 169, 189, 229, 252, 253, 347

**CS Fundamentals:**
- OS: CPU Scheduling (FCFS, SJF, Round Robin, Priority), Scheduling Criteria
- Practice: Write out scheduling examples by hand — this is directly asked at Sprinklr, DE Shaw

**AI Skills:**
- Learn GitHub Copilot: install in VS Code, understand diff between Copilot and Cursor
- Practice: Use Copilot to write unit tests for your sorting implementations
- Read: Anthropic's prompt engineering guide (docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)

**Project Work:**
- Set up project stack. If building a RAG-based project: set up FastAPI backend, Next.js frontend skeleton

---

#### **Week 3**
**Theme:** Binary Search + Hashing

**DSA:**
- Topic: Binary Search (both on arrays and on answer space), HashMap patterns
- Problems: 15 problems
- Resources:
  - Striver's A2Z: Step 4 (Binary Search — all)
  - CSES: Binary Search problems
  - LC: 33, 34, 35, 74, 153, 162, 278, 349, 438, 454, 560, 567, 875, 1011

**CS Fundamentals:**
- OS: Memory Management — Paging, Segmentation, Virtual Memory, Page Replacement (LRU, FIFO, OPT)
- Hot question at placements: *"Explain page fault and how the OS handles it"*

**AI Skills:**
- Learn: Zero-shot vs few-shot vs chain-of-thought prompting
- Exercise: Write a LeetCode problem solver prompt that reliably gets correct solutions
- Tool: Sign up for OpenAI API, make your first `curl` call to GPT-4o

**Project Work:**
- Build out data layer of Project 1 (schema design, API contracts)

---

#### **Week 4**
**Theme:** Linked Lists + Stack + Queue

**DSA:**
- Topic: Linked Lists (all patterns), Stack (monotonic), Queue (deque)
- Problems: 15 problems
- Resources:
  - Striver's A2Z: Step 6 (Linked Lists) + Step 11 (Stack & Queue)
  - LC: 19, 21, 23, 25, 141, 142, 143, 146, 206, 234, 739, 84, 42, 239, 496

**CS Fundamentals:**
- OS: Deadlocks — Conditions, Prevention, Avoidance (Banker's Algorithm), Detection
- DBMS intro: Relational model, Keys (Primary, Foreign, Candidate, Super)

**AI Skills:**
- Build: A simple CLI tool using OpenAI API that explains any LeetCode problem in plain English
- This is your first "AI-integrated" side tool — keep it in a GitHub repo

**Burnout Checkpoint #1:**
- End of Week 4. Rate yourself 1–10 on: Energy, Focus, Consistency.
- If below 6: Take Saturday completely off. No coding.

---

#### **Week 5**
**Theme:** Trees — Binary Trees + BST

**DSA:**
- Topic: Binary Trees (traversals, paths, diameter), BST (insert/delete/search/validate)
- Problems: 15 problems
- Resources:
  - Striver's A2Z: Step 8 (Trees — all)
  - CSES: Tree Algorithms (first 5)
  - LC: 94, 98, 100, 102, 104, 105, 114, 124, 199, 226, 230, 235, 236, 297, 543

**CS Fundamentals:**
- DBMS: SQL — SELECT, JOINs (all types), GROUP BY, HAVING, subqueries, window functions
- Must-practice: Write 10 SQL queries on a sample schema. Use LeetCode DB problems (LC 175, 176, 177, 178, 180, 184, 185)

**AI Skills:**
- Learn: LangChain basics — LLMChain, PromptTemplate, output parsers
- Build: A "SQL query explainer" using LangChain that takes a SQL query and explains it in plain English

**Project Work:**
- Core feature of Project 1 should be working end-to-end by end of this week (even if ugly)

---

#### **Week 6**
**Theme:** Heaps + Greedy

**DSA:**
- Topic: Heaps (min/max, K-th problems), Greedy algorithms (interval scheduling, activity selection)
- Problems: 12 problems
- Resources:
  - Striver's A2Z: Step 9 (Greedy) + Heap section
  - LC: 23, 215, 295, 347, 373, 45, 55, 134, 135, 435, 452, 621, 767

**CS Fundamentals:**
- DBMS: Normalization (1NF–BCNF), Transactions (ACID), Isolation Levels, Concurrency Control
- Hot question: *"Explain dirty read, phantom read, non-repeatable read with examples"*

**AI Skills:**
- Learn: Vector databases conceptually — what embeddings are, what cosine similarity means
- Tool: Explore Pinecone (free tier) or ChromaDB (local)
- Build: Add a semantic search layer to your Project 1

**Project Work:**
- Project 1: Add AI feature (see Project section). Begin writing README with architecture diagram.

---

#### **Week 7**
**Theme:** Recursion + Backtracking

**DSA:**
- Topic: Recursion patterns, Backtracking (subsets, permutations, N-Queens, Sudoku)
- Problems: 12 problems
- Resources:
  - Striver's A2Z: Step 7 (Recursion & Backtracking)
  - LC: 17, 22, 37, 39, 40, 46, 47, 51, 52, 77, 78, 79, 90

**CS Fundamentals:**
- CN: OSI Model, TCP/IP stack, HTTP vs HTTPS, DNS resolution walkthrough
- Most asked CN question at IIIT: *"What happens when you type google.com in your browser?"* — practice a 5-minute answer

**AI Skills:**
- Learn: RAG (Retrieval Augmented Generation) pipeline — chunking, embedding, retrieval, generation
- Build: Simple RAG pipeline using LangChain + ChromaDB on a PDF of your notes
- Reference: LangChain RAG tutorial (python.langchain.com/docs/tutorials/rag)

**Project Work:**
- Project 1: Polish, deploy on Vercel/Railway, record a 2-min demo video

---

#### **Week 8 — PHASE 1 CHECKPOINT**
**Theme:** Revision + Project 1 Finalization + Phase Review

**DSA:**
- Revisit all weak spots from Weeks 1–7
- Do 10 "random" LC Easy/Medium problems timed (25 min each) to test pattern recognition speed
- Target: Should solve 80% of Easy in <15 min, 60% of Medium in <25 min

**CS Fundamentals:**
- OS + DBMS revision: Go through all your notes. Write 1-page summaries of each topic.
- Mock answer 5 CS fundamental questions out loud (record yourself)

**AI Skills:**
- Consolidate: Document your AI tool workflow. What does your Cursor + Copilot + API setup look like?
- Publish a short blog post (on Dev.to or Medium) about something you built with AI this phase

**Deliverables Check:**
- [ ] 80+ LeetCode problems solved
- [ ] OS + DBMS notes complete
- [ ] Project 1 live on GitHub with README + demo link
- [ ] OpenAI API used in at least one project/tool
- [ ] Cursor workflow established

---

### 📌 PHASE 2: APPLICATION (Weeks 9–16)
> Semester begins. Adjust to 3–4 hrs weekdays, 6–7 hrs weekends.

---

#### **Week 9**
**Theme:** Graphs — BFS/DFS Fundamentals

**DSA:**
- Topic: Graph representation, BFS, DFS, connected components, cycle detection
- Problems: 12 problems
- Resources:
  - Striver's A2Z: Step 15 (Graphs) — first half
  - CSES: Graph Algorithms (first 6)
  - LC: 133, 200, 207, 210, 261, 417, 547, 684, 695, 733, 785, 797

**CS Fundamentals:**
- CN: TCP vs UDP, 3-way handshake, flow control, congestion control, TLS/SSL
- OOP: 4 pillars with code examples in Java/C++, method overloading vs overriding

**AI Skills:**
- Learn: System prompt engineering, temperature/top-p effects, token limits
- Read: OpenAI cookbook (github.com/openai/openai-cookbook) — pick 2 relevant recipes

**Project Work:**
- Begin Project 2 planning and architecture (see Project Roadmap)

---

#### **Week 10**
**Theme:** Graphs — Shortest Paths + Topological Sort

**DSA:**
- Topic: Dijkstra, Bellman-Ford, Floyd-Warshall, Topological Sort (BFS Kahn's + DFS)
- Problems: 12 problems
- Resources:
  - Striver's A2Z: Step 15 Graphs continued
  - CSES: Shortest Routes I & II, High Score
  - LC: 743, 787, 847, 1091, 1334, 1368, 207, 210, 269, 329, 444, 1203

**CS Fundamentals:**
- CN: HTTP/2 vs HTTP/3, REST vs GraphQL, WebSockets, CDN, Load Balancers
- OOP: SOLID principles — explain each with a real-world analogy (asked at Atlassian, Microsoft)

**AI Skills:**
- Learn: Function calling / tool use with OpenAI API
- Build: A coding assistant that can both explain code AND run LeetCode test cases (tool use for code execution)

**Project Work:**
- Project 2: Set up repo, implement core data pipeline

---

#### **Week 11**
**Theme:** Graphs — Advanced (MST, Union-Find)

**DSA:**
- Topic: Union-Find/DSU, Kruskal's MST, Prim's MST, Bridges & Articulation Points
- Problems: 10 problems
- Resources:
  - Striver's A2Z: Graphs advanced
  - CSES: Connectivity + MST sections
  - LC: 305, 399, 547, 684, 685, 721, 737, 839, 1202, 1319

**CS Fundamentals:**
- OOP: Design Patterns — Singleton, Factory, Observer, Strategy (know these cold)
- This comes up at Atlassian, Goldman, Sprinklr in OOP design rounds

**AI Skills:**
- Learn: Streaming responses with OpenAI API (stream=True)
- Learn: Structured outputs / JSON mode — critical for production AI apps

**Project Work:**
- Project 2: Core AI feature integrated

**Burnout Checkpoint #2:**
- End of Week 11. You're juggling semester + prep. Check energy levels.
- Recovery protocol: If drained, reduce DSA to 5 problems/day, pause new AI learning for a week.

---

#### **Week 12**
**Theme:** Dynamic Programming — 1D + 2D

**DSA:**
- Topic: DP fundamentals — memoization vs tabulation, 1D DP (climbing stairs, house robber, coin change), 2D DP (grid paths, LCS, Edit Distance)
- Problems: 15 problems (DP is the heaviest topic — allocate more time)
- Resources:
  - Striver's A2Z: Step 14 (DP — all)
  - Neetcode DP playlist (youtube.com/@NeetCode)
  - LC: 70, 118, 198, 213, 300, 322, 338, 343, 416, 494, 62, 63, 64, 72, 97, 115, 1143

**CS Fundamentals:**
- System Design intro: Scalability, CAP theorem, consistency models, caching strategies
- Read: "Designing Data-Intensive Applications" Chapter 1–2 (Kleppmann)

**AI Skills:**
- Learn: LangGraph basics — agents, nodes, edges, state management
- Build: A simple ReAct agent that can answer questions about a GitHub repository

**Project Work:**
- Project 2: Testing, deployment, README polish

---

#### **Week 13**
**Theme:** DP — Advanced Patterns

**DSA:**
- Topic: DP on Trees, DP on Strings (palindromes), Knapsack variants (0/1, unbounded, multiple), Bitmask DP (intro)
- Problems: 12 problems
- Resources:
  - Striver's A2Z: DP advanced
  - CSES: DP section (first 10)
  - LC: 124, 337, 87, 131, 132, 516, 647, 0/1 Knapsack variants, 474, 1049

**CS Fundamentals:**
- System Design: Database scaling — sharding, replication, read replicas
- Design: "Design a URL shortener" — practice this end-to-end (very common at Atlassian)

**AI Skills:**
- Learn: Evaluation of LLM outputs — RAGAS, LLM-as-judge pattern
- This is increasingly tested at AI-first companies: *"How do you know your RAG pipeline is good?"*

**Project Work:**
- Project 2: COMPLETE and deployed. Record demo video.

---

#### **Week 14**
**Theme:** Tries + Segment Trees (intro)

**DSA:**
- Topic: Trie (insert/search/prefix), Segment Tree (range sum, range min, lazy propagation intro)
- Problems: 10 problems
- Resources:
  - Striver's A2Z: Trie section
  - CSES: Range Queries section
  - LC: 208, 211, 212, 336, 421, 472, 648, 745

**CS Fundamentals:**
- OS: File Systems — inodes, directory structure, file descriptors, ext4 vs FAT
- System Design: Design a notification system / rate limiter (asked at DE Shaw, Sprinklr)

**AI Skills:**
- Build: Implement a "semantic code search" tool using embeddings — given a natural language query, find the most relevant function in a codebase
- This is directly demonstrable in interviews as a project

**Project Work:**
- Begin Project 3 planning and architecture

---

#### **Week 15**
**Theme:** Bit Manipulation + Math

**DSA:**
- Topic: Bit tricks (XOR patterns, popcount, power of 2), Number theory (prime sieve, GCD/LCM, modular arithmetic)
- Problems: 10 problems
- Resources:
  - LC: 136, 137, 190, 191, 201, 231, 260, 268, 338, 7, 9, 50, 69, 204

**CS Fundamentals:**
- DBMS: Query optimization — explain plans, indexes (B-tree, Hash), query execution
- Interview question: *"Why is a composite index on (A, B) not useful for queries on column B alone?"*

**AI Skills:**
- Learn: Fine-tuning vs RAG — when to use each (conceptual, not hands-on yet)
- Learn: Prompt injection, jail-breaking concepts — security of AI systems (valued at security-conscious companies like Microsoft)

**Project Work:**
- Project 3: Repo set up, core data model implemented

---

#### **Week 16 — PHASE 2 CHECKPOINT**
**Theme:** Revision + Resume v1 + Mock Interview #1

**DSA:**
- 15 random timed problems across all covered topics
- Focus on identifying your 3 weakest pattern areas

**CS Fundamentals:**
- All 4 subjects revision: OS, DBMS, CN, OOP — create a master cheat sheet (1 page per subject)

**AI Skills:**
- Document your AI project portfolio: what you built, what tools you used, what problems you solved

**Resume v1:**
- Draft your resume (see Resume Strategy section)
- Get feedback from 2 seniors/peers at IIIT

**Mock Interview #1:**
- Platform: Pramp (free) — schedule your first DSA mock interview
- Focus: Arrays/Trees (your strongest area)

**Deliverables Check:**
- [ ] 200+ LeetCode problems solved
- [ ] CN + OOP notes complete
- [ ] Projects 1 & 2 live on GitHub
- [ ] RAG pipeline built and understood
- [ ] Resume v1 drafted
- [ ] 1 mock interview done

---

### 📌 PHASE 3: MASTERY (Weeks 17–24)

---

#### **Week 17**
**Theme:** Consolidation + Hard Problems

**DSA:**
- Topic: Revisit your 3 weakest areas (identified in Week 16 checkpoint)
- Problems: 12 problems — mix of medium and hard
- Start attempting LC Hard problems in your strong areas (Trees, Graphs)

**CS Fundamentals:**
- System Design: Design Instagram / Twitter feed — practice the full interview format (15 min)
- Focus on: HLD (components), LLD (key classes/APIs), tradeoffs discussion

**AI Skills:**
- Build: Project 3 AI core feature (see Project Roadmap)
- Learn: LLM deployment considerations — latency, cost per token, caching strategies

**Mock Interview:**
- Mock #2 on Pramp — Graphs/DP

---

#### **Week 18**
**Theme:** DP — Hard Problems

**DSA:**
- Topic: DP Hard — Matrix Chain Multiplication, DP on Intervals, Stock problems (all 6 variants)
- Problems: 12 problems
- Resources:
  - LC: 123, 188, 309, 312, 664, 730, 1000, 1406

**CS Fundamentals:**
- LLD (Low Level Design): Practice designing classes for:
  - Parking Lot system
  - Library Management System
  - This is asked at almost every Tier-1 IIIT placement
- Resource: Gaurav Sen LLD playlist, "Head First Design Patterns"

**AI Skills:**
- Learn: Multi-agent systems — how to chain agents for complex tasks
- Build: Add an agent-based feature to Project 3

**Mock Interview:**
- Mock #3 — Peer mock with a classmate: focus on communication during problem-solving

---

#### **Week 19**
**Theme:** System Design Deep Dive

**DSA:**
- 10 problems — maintain consistency, don't drop below 10/week

**CS Fundamentals:**
- System Design: Design WhatsApp / Slack (messaging at scale)
- Design: Design a recommendation engine (relevant for AI companies)
- Resource: "System Design Interview" book by Alex Xu (Vol 1, Chapters 1–12)

**AI Skills:**
- Build: Complete Project 3
- Learn: OpenAI Assistants API — threads, file attachments, code interpreter

**Mock Interview:**
- Mock #4 on interviewing.io (paid, but worth 1–2 sessions for real feedback)

**Burnout Checkpoint #3:**
- End of Week 19. You're near the finish line — this is where most students push too hard and plateau.
- Mandatory: One full day off per week from here until placements.

---

#### **Week 20**
**Theme:** Competitive Programming Sharpening

**DSA:**
- Topic: Solve 3 full Codeforces contests (Div 2 — aim for A/B/C consistent solves)
- CSES: Complete all problems you haven't done (target 80/300)
- Focus: Speed + accuracy under contest conditions

**CS Fundamentals:**
- Behavioral prep: STAR format for 10 scenarios (leadership, conflict, failure, learning, collaboration)
- Companies like Google, Microsoft weight behavioral rounds heavily

**AI Skills:**
- Resume and LinkedIn: Frame all AI projects compellingly (see AI Skills Curriculum section)
- Record a 5-minute walkthrough of each project — practice delivering it fluently

**Mock Interview:**
- Mock #5 + #6 — back to back. One DSA, one system design.

---

#### **Week 21**
**Theme:** Company-Specific Preparation

**DSA:**
- Focus: Each target company has a problem pattern. Look up company-tagged LC problems:
  - Google: Graphs, DP, String manipulation
  - Microsoft: Trees, LLD, OOP heavy
  - Atlassian: System Design, OOP, Agile concepts
  - DE Shaw: CP-heavy, Math, Quant-style problems
  - Sprinklr: DSA Medium, OOP Design, React/Node.js
- Do 15 company-tagged problems from your top 3 target companies

**CS Fundamentals:**
- CN: HTTP deep dive — status codes, caching headers, CORS, cookies, sessions, JWT
- OS: Synchronization — Mutex, Semaphore, Monitors, Producer-Consumer, Readers-Writers

**AI Skills:**
- Prepare AI interview answers:
  - *"Tell me about an AI project you built"* — 2-min pitch for each project
  - *"What's the difference between RAG and fine-tuning?"* — crisp 60-second answer
  - *"How would you add AI to our product X?"* — practice with 3 target companies

**Mock Interview:**
- Mock #7 — Full interview simulation: 45 min DSA + 15 min behavioral

---

#### **Week 22**
**Theme:** Weak Topic Elimination

**DSA:**
- Identify your 5 most-missed LC problem types (check your LC submission history)
- Do 3–5 problems on each of those exact types
- Revisit any CSES problem you got wrong — understand the editorial

**CS Fundamentals:**
- Final OS revision: Focus on interview questions, not new material
- Practice: Write out answers to 20 common OS interview questions from memory

**AI Skills:**
- Practice explaining your projects to a non-technical person, then to a technical interviewer — two different pitches

**Mock Interview:**
- Mock #8 + #9 — company-specific simulations

---

#### **Week 23**
**Theme:** Interview Simulation Week

**DSA:**
- ONLY timed problem-solving this week. No tutorials, no new content.
- Format: 2 problems in 45 min, twice a day on weekends
- Goal: Build interview-day pacing and mental stamina

**CS Fundamentals:**
- "Speed round" revision — flip through all cheat sheets 30 min/day

**AI Skills:**
- Final GitHub polish: All repos must have: README with demo GIF, tech stack badges, architecture diagram, setup instructions

**Mock Interview:**
- Mock #10 + #11 + #12 — maximum simulations this week
- After each: Write a debrief (what went well, what to fix)

**Cold Outreach:**
- Send 10 internship referral requests (see Resume & LinkedIn section for scripts)

---

#### **Week 24 — FINAL WEEK**
**Theme:** Peak Readiness + Mental Prep

**DSA:**
- 5 problems only — light, confidence-building, your strongest topics
- NO new problems. Zero new material.

**CS Fundamentals:**
- Rest day for fundamentals on Wednesday and Friday
- Light revision only

**AI Skills:**
- Final portfolio review. Ensure all demo links work.

**Mindset:**
- You've put in ~600 hours. Trust the process.
- Sleep 8 hours, eat well, exercise daily this week.
- Review your wins: # problems solved, projects shipped, mocks cleared

---
---

## DSA STRATEGY

### Topic Priority Ranking (Tier-1 Interview Frequency)

#### 🔴 MUST-DO — Covers ~80% of Questions
*(Do these first, do them well)*

| Rank | Topic | LC Problem Target | Key Patterns |
|------|-------|-------------------|--------------|
| 1 | Arrays + Two Pointers | 25 problems | Sliding window, kadane's, prefix sum |
| 2 | Binary Search | 15 problems | Search on answer, rotated arrays |
| 3 | Trees (BT + BST) | 25 problems | DFS paths, LCA, serialization |
| 4 | Dynamic Programming (1D + 2D) | 35 problems | Memoization, tabulation, LCS/LIS/Knapsack |
| 5 | Graphs (BFS/DFS + Shortest Path) | 25 problems | Topological sort, Dijkstra, Union-Find |
| 6 | HashMap / HashSet | 15 problems | Frequency maps, anagram detection |
| 7 | Stack + Queue (Monotonic) | 15 problems | Next greater element, sliding window max |
| 8 | Linked Lists | 12 problems | Fast/slow pointers, reversal, merge |
| 9 | Backtracking | 10 problems | Subsets, permutations, word search |
| 10 | Heap / Priority Queue | 10 problems | K-th largest, merge K lists, task scheduler |

**Total Must-Do: ~190 problems**

---

#### 🟡 SHOULD-DO — Covers Remaining ~20%
*(Do after Must-Do is solid)*

| Topic | LC Problem Target | Notes |
|-------|-------------------|-------|
| Tries | 6 problems | Asked at Google, Uber |
| Interval Scheduling | 8 problems | Very common at Microsoft |
| Greedy | 10 problems | Usually easy once you see the pattern |
| Bit Manipulation | 8 problems | Common in DE Shaw, Goldman |
| Segment Tree | 4 problems | Know conceptually; rarely coded from scratch |
| Math / Number Theory | 6 problems | GCD, primes, modular arithmetic |
| String Algorithms | 8 problems | KMP/Rabin-Karp — know theory, code easy versions |

**Total Should-Do: ~50 problems**

---

#### ⚪ SKIP-FOR-NOW — Rarely Tested
*(Return only after everything above is done)*
- Network Flow (max flow, min cut) — only at specialized roles
- Suffix Arrays / Suffix Trees — almost never in product company OAs
- Heavy-Light Decomposition — CP-only
- Matrix Exponentiation — niche
- Game Theory (Sprague-Grundy) — niche

---

### Realistic Total Problem Targets
| Phase | New Problems | Cumulative |
|-------|-------------|------------|
| Phase 1 (Wk 1–8) | 90 | 90 |
| Phase 2 (Wk 9–16) | 110 | 200 |
| Phase 3 (Wk 17–24) | 100 | 300 |

**Quality Benchmark by Placement Season:**
- Easy: Solve in <12 min
- Medium: Solve in <25 min
- Hard: Recognize the approach within 5 min, full solution in 40 min

---
---

## PROJECT ROADMAP

### Project Philosophy
Each project must pass the **"So What?" test**: a hiring manager should be able to understand why it's impressive in 60 seconds. AI integration must be *load-bearing*, not decorative.

---

### **Project 1 — CodeLens AI** *(Complete by Week 8)*
**Concept:** An AI-powered GitHub repository analyzer that generates:
- Auto-generated code quality reports (complexity analysis, smell detection)
- Natural language PR summaries
- Semantic code search ("find all functions that handle authentication")
- Automated test case suggestions for uncovered code paths

**Why it's impressive:**
- Directly solves a real engineering pain point
- Demonstrates: GitHub API integration, embeddings + vector search, structured LLM output, streaming UI
- Not a toy — it can be pointed at any real repo

**Tech Stack:**
- Backend: FastAPI (Python) + GitHub REST API + OpenAI API (GPT-4o)
- AI Layer: LangChain + ChromaDB (semantic search) + structured outputs
- Frontend: Next.js + Tailwind (clean, minimal UI)
- Deploy: Railway (backend) + Vercel (frontend)

**Key AI Engineering Decisions to discuss in interview:**
1. Why chunking strategy matters for code files (function-level vs file-level)
2. Why you chose ChromaDB over Pinecone (local dev, no rate limits, cost)
3. How you handle context window limits for large repos

**10-min Interview Walkthrough:**
1. (2 min) Problem statement + demo (live or recorded)
2. (3 min) Architecture diagram walkthrough
3. (3 min) "Here's the hardest technical decision I made"
4. (2 min) What I'd build next + what I learned

**GitHub README must include:** Architecture diagram, tech stack badges, demo GIF, setup instructions, "Limitations & Future Work" section

---

### **Project 2 — StudyBuddy: Adaptive Learning Engine** *(Complete by Week 13)*
**Concept:** An AI-powered study assistant for IIIT Delhi students that:
- Ingests course PDFs and creates a dynamic knowledge graph
- Generates Socratic-style quiz questions adapted to your weak areas
- Tracks learning gaps over time and adjusts difficulty
- Can answer questions about uploaded course material with citations

**Why it's impressive:**
- RAG pipeline at its core, but extends it with personalization
- Demonstrates: multi-document RAG, knowledge graph construction, adaptive algorithms, session persistence
- Target audience is clearly defined (easy to demo to any student audience)

**Tech Stack:**
- Backend: FastAPI + LangChain + LangGraph (for adaptive quiz agent)
- AI Layer: OpenAI Embeddings + ChromaDB + GPT-4o (quiz generation) + LLM-as-judge (answer evaluation)
- Frontend: React + shadcn/ui
- Storage: PostgreSQL (user data, quiz history) + ChromaDB (embeddings)
- Deploy: Render + Vercel

**Key differentiators:**
- LLM-as-judge pattern to evaluate open-ended answers (not just MCQ)
- Spaced repetition algorithm integrated with AI difficulty adjustment
- Knowledge graph visualization (D3.js) — visually stunning in a demo

**10-min Interview Walkthrough:**
1. (2 min) Problem + live demo (upload a PDF, ask a question, take a quiz)
2. (3 min) RAG pipeline architecture: chunking → embedding → retrieval → generation
3. (3 min) Adaptive algorithm: how you combined LLM scoring with spaced repetition
4. (2 min) Evaluation strategy: how you measured if the system was actually good

---

### **Project 3 — DevFlow: AI-Augmented Engineering Metrics Dashboard** *(Complete by Week 22)*
**Concept:** A dashboard for engineering teams that uses AI to:
- Pull GitHub/GitLab data (commits, PRs, reviews, issues)
- Generate natural language sprint summaries
- Detect bottlenecks ("3 PRs have been open > 5 days waiting on Review")
- Answer natural language questions about team velocity ("Why did velocity drop in Week 3?")

**Why it's impressive:**
- Enterprise-relevant (every product company cares about engineering productivity)
- Demonstrates: data pipeline engineering, NL-to-SQL (text-to-query over structured metrics), LLM-powered insights, multi-source data integration
- Directly analogous to internal tools at Google, Atlassian, Microsoft

**Tech Stack:**
- Backend: FastAPI + Celery (background jobs) + PostgreSQL
- Data: GitHub API + optional GitLab API
- AI Layer: OpenAI function calling (NL-to-SQL), GPT-4o (narrative summaries)
- Frontend: Next.js + Recharts (beautiful data visualizations)
- Deploy: Railway + Vercel

**Key technical talking points:**
- NL-to-SQL implementation — why you chose this over pure RAG
- How you handle hallucinations in metric interpretation (confidence scores)
- Async job architecture for fetching large repo histories

---
---

## AI SKILLS CURRICULUM

### What Companies Actually Test

#### Tier-1 Product Companies (Google, Microsoft, Atlassian, DE Shaw)
These companies do NOT (yet) have formal AI interviews for SWE roles. But AI proficiency signals:

| Signal | How It's Evaluated |
|--------|-------------------|
| AI-integrated projects | Project walkthrough in interview |
| AI tooling in workflow | "How do you use AI tools in your daily coding?" |
| LLM API experience | System design questions about AI systems |
| Understanding limitations | "What are the failure modes of RAG?" |

**What NOT to do:** Claim "I built a ChatGPT wrapper" or list "Prompt Engineering" as a skill with no backing. Interviewers will probe.

#### AI-First Startups (Perplexity, Cohere, Sarvam, Krutrim, etc.)
These companies actively test:
- Ability to evaluate LLM outputs quantitatively
- Understanding of embedding models, vector DBs
- Knowledge of RAG evaluation (RAGAS, faithfulness, context precision)
- Awareness of fine-tuning tradeoffs
- Hands-on: "Walk us through how you'd build [X] AI feature"

---

### Tool Learning Sequence

#### Month 1: Foundation Tools
| Tool | What to Learn | Time Investment |
|------|--------------|-----------------|
| Cursor IDE | Tab completion, codebase chat, composer mode | 3 hrs setup + daily use |
| GitHub Copilot | VS Code integration, test generation | 2 hrs + daily use |
| OpenAI API | Chat completions, structured outputs, streaming | 4 hrs |
| Basic prompting | System prompts, few-shot, chain-of-thought | 3 hrs |

#### Month 2: Core AI Engineering
| Tool | What to Learn | Time Investment |
|------|--------------|-----------------|
| LangChain | Chains, prompts, output parsers, retrievers | 8 hrs |
| ChromaDB/Pinecone | Indexing, querying, filtering | 4 hrs |
| RAG pipelines | End-to-end: chunk → embed → retrieve → generate | 6 hrs |
| LangSmith | Tracing and debugging LLM calls | 2 hrs |

#### Month 3: Advanced AI Engineering
| Tool | What to Learn | Time Investment |
|------|--------------|-----------------|
| LangGraph | Stateful agents, multi-agent systems | 6 hrs |
| OpenAI Assistants API | Threads, tools, file handling | 4 hrs |
| RAGAS | RAG evaluation framework | 3 hrs |
| Vercel AI SDK | Streaming UI, useChat hook | 3 hrs |

---

### How to Signal AI Proficiency

**On Resume (do this):**
```
AI/ML Tools: LangChain, OpenAI API, ChromaDB, LangGraph, RAGAS
Built: RAG pipeline serving <X> queries/day with <Y>% relevance score (RAGAS)
Used Cursor + Copilot to reduce development time by ~40% on Project 2
```

**In Interview (say this):**
> "In Project 2, I implemented a RAG pipeline where the key challenge was chunking strategy. For academic PDFs, file-level chunks were too coarse — questions about a specific theorem would retrieve entire chapters. I switched to paragraph-level chunks with 50-token overlaps, which improved RAGAS faithfulness scores from 0.71 to 0.89."

This answer demonstrates: hands-on experience, quantitative thinking, iterative improvement, and awareness of failure modes — exactly what senior engineers look for.

---
---

## RESUME & LINKEDIN STRATEGY

### What a Strong IIIT Delhi CSE Resume Looks Like (2026 Edition)

**Structure (1 page, LaTeX preferred — use Jake's Resume template):**
```
NAME | phone | email | linkedin | github | portfolio (optional)

EDUCATION
IIIT Delhi | B.Tech CSE | CGPA: X.XX | Expected: May 2027

EXPERIENCE (if any — internships, research, TA roles)

PROJECTS (3 projects — this is the most important section)
  Project Name | Tech Stack | GitHub link | Demo link
  - 1 line: what it does
  - 1 line: hardest technical problem you solved
  - 1 line: measurable outcome (users, performance, accuracy metric)

SKILLS
  Languages: C++, Python, JavaScript, SQL
  Frameworks: React, FastAPI, Node.js, LangChain
  AI/ML: OpenAI API, ChromaDB, RAG pipelines, LangGraph, RAGAS
  Tools: Git, Docker, Cursor, Postman, Linux

ACHIEVEMENTS (optional but useful)
  - Competitive programming ratings if strong (Codeforces, LeetCode)
  - Relevant hackathon wins
  - Research publication if any
```

**The golden rule for IIIT resumes:** Hiring from IIIT Delhi is relationship-based — alumni at target companies recognize the college name immediately. Your job is to not mess up the impression with a weak resume.

---

### How to Frame AI Skills Without Overhyping

**❌ Overhyped (don't do this):**
- "Expert in Generative AI and Large Language Models"
- "Built AI applications using cutting-edge technology"
- "Implemented machine learning pipelines"

**✅ Grounded (do this):**
- "Built a RAG pipeline using LangChain + ChromaDB; evaluated with RAGAS (faithfulness: 0.87)"
- "Integrated GPT-4o function calling for NL-to-SQL; reduced query latency by 35% vs naive RAG"
- "Used Cursor IDE and GitHub Copilot throughout development; documented AI-assisted workflow"

The difference: specificity. Hiring managers are now trained to spot AI hype. Numbers and named components signal real experience.

---

### Cold Outreach Scripts for Internship Referrals

**LinkedIn Connection Request (300 chars max):**
```
Hi [Name], I'm a 3rd-year CSE student at IIIT Delhi interested in interning at [Company]. 
I've been building AI-integrated projects (RAG pipelines, LLM agents) and would love 
5 minutes of your time. Happy to share my work. Thank you!
```

**Follow-up message after connection (send within 48 hours of acceptance):**
```
Hi [Name], thank you for connecting!

I'm preparing for summer 2026 internships and [Company] is my top choice because [specific, 
genuine reason — a product, a blog post they wrote, a team they're on].

My recent project: [Project 2 name] — [one-sentence description]. GitHub: [link]. 
Demo: [link].

I'm not asking for a guaranteed referral — just wondering if you'd be open to a 
15-minute chat about what you look for in interns, or if there's a role I should 
apply to that matches my profile.

No pressure at all if you're busy. Thank you!
```

**Who to target at each company:**
- IIIT Delhi alumni first (use LinkedIn "Alumni" filter)
- Recent grads (class of 2023–2025) — most receptive, closest to your situation
- University recruiters on LinkedIn — they see these messages professionally

**Target:** 5 outreach messages per week starting Week 23. Track in a simple Notion table.

---
---

## MOCK INTERVIEW SCHEDULE

### When to Start
**First mock: Week 16** (not before). Starting mocks before you have 150+ problems is demoralizing and unproductive. You need pattern vocabulary first.

### Frequency by Phase
| Phase | Frequency | Focus |
|-------|-----------|-------|
| Phase 2 end (Wk 16) | 1 mock | Arrays/Trees DSA |
| Phase 3 early (Wk 17–19) | 1 per week | Rotating topics |
| Phase 3 mid (Wk 20–22) | 2 per week | Company-specific |
| Phase 3 late (Wk 23–24) | 3 per week | Full simulation |

**Total target: 12–15 mocks before placements**

### Platforms

| Platform | Cost | Best For |
|----------|------|----------|
| **Pramp** | Free | DSA rounds with peers — good volume |
| **Interviewing.io** | $50–100/session | Anonymous interviews with real engineers from top companies — do 2–3 of these |
| **Peer mocks** | Free | Behavioral, system design, LLD — set up a regular mock circle with 2–3 classmates |
| **LeetCode contests** | Free | Weekly + Biweekly — treat every contest as a mock (Sunday, 8pm IST) |
| **Codeforces Div 2** | Free | CP skill sharpening |

### Simulating Real Conditions
1. **No hints policy:** Set a 25-min timer. If stuck, attempt anyway. After timer, check solution.
2. **Think aloud:** Force yourself to verbalize your approach before coding. This is what interviewers evaluate.
3. **Interview-style setup:** Sit at a desk, open a blank editor (no LeetCode hints), 45 min total.
4. **Debrief ritual:** After every mock, write 3 lines: (1) What went well, (2) What failed, (3) What to practice next.

### Types of Rounds to Practice
| Round Type | When to Practice | Notes |
|------------|-----------------|-------|
| DSA (2 problems) | From Week 16 | Most common format |
| System Design | From Week 18 | HLD + LLD combined |
| LLD / OOP Design | From Week 18 | Parking lot, chess, elevator |
| Behavioral (HR) | From Week 20 | STAR format, 10 stories prepared |
| AI project walkthrough | From Week 20 | Your own projects — practice out loud |

---
---

## WEEKLY TRACKER TEMPLATE
*(Copy to Notion, Obsidian, or paper)*

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📅 WEEK ___  |  Dates: _________  |  Phase: ______
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🔢 DSA
  [ ] Problem 1: ___________ (Topic: ___) ⏱ ___min  ✅/❌
  [ ] Problem 2: ___________ (Topic: ___) ⏱ ___min  ✅/❌
  [ ] Problem 3: ___________ (Topic: ___) ⏱ ___min  ✅/❌
  [ ] Problem 4: ___________ (Topic: ___) ⏱ ___min  ✅/❌
  [ ] Problem 5: ___________ (Topic: ___) ⏱ ___min  ✅/❌
  Weekly DSA total: ___ / ___ target problems

📚 CS FUNDAMENTALS
  [ ] Topic: _______________  Resource: _______________
  [ ] Practice question answered: _______________
  [ ] Flashcard/note added: _______________

🏗️ PROJECT WORK
  [ ] Milestone this week: _______________
  [ ] Code committed: Y/N  Commit message: _______________
  [ ] Blocker/challenge: _______________

🤖 AI SKILLS
  [ ] Tool/concept learned: _______________
  [ ] Built/practiced: _______________
  [ ] Resource consumed: _______________

🎤 MOCK / OUTREACH (Phase 3 only)
  [ ] Mock interview #___  Platform: ___  Score: ___/10
  [ ] Debrief written: Y/N
  [ ] Outreach messages sent: ___ / 5 target

📊 WEEKLY STATS
  LeetCode solved this week: ___
  Cumulative LeetCode: ___
  Energy level (1–10): ___
  Consistency (days on track): ___ / 7

🔁 REFLECTION (Sunday, 5 min)
  What went well: _______________
  What to improve: _______________
  Adjustment for next week: _______________
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---
---

## 🗓️ MONTH-BY-MONTH SUMMARY CARD

| Month | Transformation |
|-------|----------------|
| **Month 1** | You go from "knowing CS" to *thinking in patterns* — arrays, binary search, trees click; OS + DBMS notes are built; Cursor becomes a daily tool and Project 1 is live on GitHub. |
| **Month 2** | Graphs and DP no longer intimidate you; CN + OOP are interview-ready; your RAG pipeline works end-to-end and you can explain every architectural decision in Project 2. |
| **Month 3** | You're managing semester + prep without crashing; system design vocabulary is forming; 200 problems solved; resume v1 is drafted and 2 strong projects are deployed. |
| **Month 4** | You've closed your DP + Hard problem gaps; you've done your first real mock interview and survived; Project 3 is nearly done; you can now pitch your AI projects in under 2 minutes. |
| **Month 5** | You're drilling company-specific problems; mock interviews are happening 2x/week and you're getting better each time; your GitHub looks like a serious engineer's profile; cold outreach has begun. |
| **Month 6** | You are placement-ready: 300+ problems solved, 12+ mocks done, 3 deployed AI-integrated projects, a polished resume, and the ability to walk into any Tier-1 interview with grounded confidence — not hope. |

---

*Built for IIIT Delhi CSE | 3rd Year → Placement Season | 2026–2027*
*Roadmap version: May 2026*
