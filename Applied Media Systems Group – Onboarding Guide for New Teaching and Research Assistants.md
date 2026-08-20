# Applied Media Systems Group  
## Onboarding Guide for New Teaching and Research Assistants

**TU Ilmenau – Institute for Media Technology**  
**Starting October 2026**

Welcome to the Applied Media Systems group. This onboarding is intended to introduce new group members to our technical infrastructure, teaching activities, research topics, publications, software, and AI-supported teaching workflow.

The onboarding should be largely **hands-on**: rather than only reading documentation, new members should use our Jupyter notebooks, GitHub repositories, Moodle courses, lecture chatbots, books, and research papers.

---

# 1. Main Onboarding Goals

At the end of the onboarding period, a new group member should be able to:

1. Access and use the main TU Ilmenau and group IT systems.
2. Navigate the Moodle courses relevant to their teaching.
3. Understand the structure and learning objectives of their assigned courses.
4. Use the corresponding lecture chatbot for course preparation.
5. Run and modify our Jupyter/Colab examples.
6. Find and understand the relevant group GitHub repositories.
7. Know the main research topics and publications of the group.
8. Prepare and supervise seminar exercises.
9. Use Moodle quizzes and the Virtual Programming Lab.
10. Design seminar/project tasks with reproducible and quantifiable grading.
11. Know whom to ask and where to look when technical or organizational questions arise.

---

# 2. IT and Infrastructure Setup

## Our Groups TU Ilmenau webpage

[https://www.tu-ilmenau.de/mt-ams](https://www.tu-ilmenau.de/mt-ams)

## TU Ilmenau Account

Check that the TU Ilmenau login works for the relevant university systems.

Important systems include:

- TU Ilmenau account
- university Wi-Fi / eduroam
- e-mail
- Moodle
- Nextcloud
- other university services required for teaching

The lecture chatbots can also be used without a TU Ilmenau login, which makes them particularly useful for students and external collaborators.

---

## Nextcloud

Become familiar with the group and course folders in Nextcloud.

Typical material may include:

- lecture slides
- exercises
- seminar material
- organizational information
- datasets
- example code
- teaching schedules
- previous student projects

Exercise:

> Locate the material for each course that you will teach and identify the lecture slides, exercises, seminar material, and organizational documents.

---

## Moodle

Become familiar with the Moodle courses for the assigned lectures.

Important functions include:

- lecture material
- announcements
- student groups
- assignment submission
- quizzes
- grades
- seminar organization
- Virtual Programming Lab

### Moodle quizzes

New instructors should try both sides of the system:

1. Complete an existing quiz as if you were a student.
2. Inspect the quiz as an instructor.
3. Create a short experimental quiz.
4. Examine automatic grading and feedback.

---

# 3. Virtual Programming Lab

The Moodle **Virtual Programming Lab (VPL)** can be used for programming exercises with automatic testing.

Suggested onboarding task:

Create a small example programming exercise such as:

- downsampling and upsampling
- digital filtering
- FFT computation
- audio normalization
- convolution
- simple neural-network inference

The exercise should contain:

- task description
- input/output specification
- student template
- automatic test cases
- grading criteria
- feedback for incorrect solutions

This can later serve as a template for actual course exercises.

---

# 4. GitHub and Jupyter Environment

## GitHub

Become familiar with our GitHub repositories and GitHub pages.

Tasks:

- locate the important group repositories
- clone at least one repository
- run an example
- modify an example
- commit the modification to a test repository or branch
- understand Issues and Pull Requests

Where appropriate, we can use **GitHub Codespaces** to provide a reproducible programming environment.

---

## Jupyter Notebooks / Google Colab

Much of our teaching and research material can be explored interactively.

Suggested workflow:

1. Open a notebook.
2. Run all cells.
3. Modify one parameter.
4. Predict what will happen.
5. Run the modified version.
6. Explain the result.

Possible environments:

- local Jupyter
- JupyterLab
- Google Colab
- GitHub Codespaces

A useful long-term goal is that important teaching examples should run with as little installation effort as possible.

---

# 5. Introduction to Our Research

New group members should obtain an overview of the main research directions of the group.

Suggested introductory reading areas include:

### Filter Banks and Multirate Signal Processing

Read selected journal papers on filter banks and related work.

Complement this with material from the **Multirate Signal Processing** book.

Topics to understand include:

- sampling-rate conversion
- polyphase decomposition
- analysis and synthesis filter banks
- aliasing
- perfect reconstruction
- applications to audio and communication systems

---

### ELD Paper

Read the ELD paper and identify:

- research question
- methodological contribution
- experimental setup
- main results
- possible follow-up research questions

Prepare a five-minute explanation for the group.

---

### Deep Learning for Singing Voice Separation

Read the paper by Stelios on deep-learning-based singing voice separation.

Focus on:

- problem formulation
- input representation
- neural-network architecture
- loss function
- dataset
- evaluation
- strengths and limitations

Practical task:

> Identify one experiment from the paper that could be reproduced or extended.

---

### Multichannel Source Separation

Study our material on multichannel source separation.

Topics may include:

- mixing models
- spatial information
- blind source separation
- independent component analysis
- time-frequency processing
- optimization approaches
- low-delay processing

Run at least one corresponding software example if available.

---

### Audio Coding

Use the **Audio Coding** book and accompanying code as an introduction to:

- quantization
- transform coding
- psychoacoustics
- filter banks
- perceptual coding
- modern neural audio coding

---

### Multirate Signal Processing

Use the **Multirate Signal Processing** book and accompanying notebooks.

A new instructor should be able to explain at least:

- downsampling
- upsampling
- aliasing
- imaging
- polyphase structures
- filter banks

---

# 6. Lecture Chatbots

Each course chatbot can serve as an interactive introduction to the course.

A new instructor can begin with:

> I am a new instructor for the seminars for this course. Can you give me an overview of the course, including its learning objectives, main topics, structure, and recommended reading material such as the book chapters and relevant papers?

Then continue with:

> Which parts of the course are most important for someone who will supervise the seminars?

and:

> Give me a suggested reading order for becoming familiar with the course.

---

## Self-Test with the Lecture Chatbot

After studying a topic, use:

> Ask me a test question about this lecture. I will answer it, and then you evaluate my answer, point out mistakes or missing aspects, and give me a better answer if necessary.

The chatbot can then continue adaptively:

> Ask me another question, taking into account the weaknesses you found in my previous answer.

This turns the chatbot into an interactive tutor for instructor onboarding.

---

# 7. Using the Chatbot During Seminars

At the beginning of selected seminar sessions, instructor and students can use the course chatbot together.

For example:

> Ask us a test question about Lecture 4. We will discuss the answer in class and then give you our answer. Evaluate it and explain what is missing.

Possible seminar sequence:

1. Display the chatbot to the class.
2. Ask for a question about the current lecture.
3. Give students 2–3 minutes to discuss.
4. Collect an answer.
5. Submit the answer to the chatbot.
6. Discuss the chatbot's evaluation.
7. Compare it with the instructor's assessment.

This serves several purposes:

- repetition of lecture material
- active learning
- demonstration of appropriate chatbot use
- critical evaluation of AI answers
- preparation for seminar exercises

Students should learn that the chatbot is a **learning tool**, not an unquestionable authority.

---

# 8. Moodle Quiz + Chatbot + Project Workflow

A seminar unit could follow a recurring structure.

### Step 1 – Preparation

Students study the lecture and relevant book chapter.

### Step 2 – Chatbot Self-Test

Students ask the course chatbot questions and test their understanding.

Suggested prompt:

> Ask me three questions about Lecture X, one easy, one medium, and one difficult. Let me answer each question before showing the next one.

### Step 3 – Moodle Quiz

Students complete a short automatically graded quiz.

For example:

- 5–10 questions
- approximately 10 minutes
- conceptual questions
- small calculations
- interpretation of diagrams
- code understanding

### Step 4 – Seminar

Discuss difficult quiz questions and solve more complex examples.

### Step 5 – Programming or Project Challenge

Students apply the concepts to a measurable problem.

Examples:

- implement a signal-processing algorithm
- reproduce a figure from the lecture
- improve an existing algorithm
- compare two approaches
- analyze an audio dataset
- implement part of an audio codec
- design and evaluate a neural network

---

# 9. Quantifiable Seminar Project Challenge

The project task should be designed so that grading is as reproducible as possible.

A possible 100-point scheme is:

| Component | Points |
|---|---:|
| Correct basic implementation | 30 |
| Quantitative performance | 25 |
| Experimental methodology | 15 |
| Explanation of results | 10 |
| Code quality and reproducibility | 10 |
| Presentation / discussion | 10 |
| **Total** | **100** |

Whenever possible, define measurable targets.

For example:

- reconstruction error
- signal-to-noise ratio
- classification accuracy
- bitrate
- runtime
- computational complexity
- perceptual score
- number of passed automatic tests

This reduces ambiguity in grading.

---

# 10. Individual Teaching Onboarding

## Renato

Primary Bachelor-level teaching:

### DSM

Onboarding tasks:

- inspect the complete Moodle course
- obtain an overview from the DSM chatbot
- read the corresponding teaching material
- work through representative exercises
- run relevant Python/Jupyter examples
- complete selected Moodle quizzes
- prepare one seminar session as a rehearsal

Suggested chatbot prompt:

> I will be teaching the seminars for DSM. Give me a structured overview of the knowledge I need to teach the course successfully. Start with the most important concepts and point me to the corresponding lectures and reading material.

### Computer Animation

Onboarding tasks:

- inspect course structure and learning objectives
- identify software/tools used
- work through representative practical exercises
- review previous student assignments
- prepare a sample seminar or lab exercise

### German-language preparation

Since parts of the Bachelor teaching require German, the onboarding should also include the main German technical terminology used in the courses.

A useful exercise is to create a bilingual vocabulary list:

| English | German |
|---|---|
| sampling rate | Abtastrate |
| frequency response | Frequenzgang |
| impulse response | Impulsantwort |
| filter | Filter |
| convolution | Faltung |
| assignment | Aufgabe |
| exercise | Übung |
| grading | Bewertung |

Renato can also ask the chatbot:

> Explain this topic first in English and then give me the German terminology I would need to teach it in a seminar.

---

# 11. Krishnendu

Primary Master-level teaching:

## Audio Coding

The course is fully in English.

Onboarding tasks:

- inspect Moodle
- ask the Audio Coding chatbot for a course overview
- read the relevant chapters of the Audio Coding book
- run the important Python examples
- complete representative exercises
- inspect existing quizzes
- prepare one seminar exercise

Important topics include:

- PCM and quantization
- predictive coding
- transform coding
- psychoacoustics
- filter banks
- perceptual audio coding
- modern/neural audio coding

Suggested chatbot prompt:

> I will be a new seminar instructor for Audio Coding. Give me an overview of the course and identify the concepts that students most often find difficult. For each concept, recommend the relevant book chapter and one exercise I should be able to solve.

---

## Advanced Digital Signal Processing – ADSP

The course is fully in English.

Onboarding tasks:

- obtain course overview from the ADSP chatbot
- identify prerequisites
- study representative lecture topics
- solve exercises independently
- run notebooks
- inspect previous seminar tasks

Suggested prompt:

> I am a new seminar instructor for ADSP. Test whether my background is sufficient for teaching the course. Ask me questions one at a time and adapt the difficulty depending on my answers.

---

# 12. Suggested Four-Week Onboarding Plan

## Week 1 – Infrastructure and Orientation

- TU Ilmenau login
- e-mail
- Nextcloud
- Moodle
- GitHub
- Jupyter / Colab / Codespaces
- course chatbot access
- inspect assigned courses

Deliverable:

> One-page overview of where all important teaching and research resources are located.

---

## Week 2 – Course Preparation

For each assigned course:

- chatbot-generated course overview
- study lecture structure
- read selected book chapters
- solve representative exercises
- run notebooks
- complete Moodle quizzes

Deliverable:

> Give a 10-minute informal explanation of the course structure and identify three topics likely to be difficult for students.

---

## Week 3 – Research Orientation

Read selected papers from the group:

- filter-bank papers
- ELD paper
- singing voice separation paper
- multichannel source separation material

Also explore the Audio Coding and Multirate Signal Processing books.

Deliverable:

> Give a short presentation of one paper: problem, method, results, limitations, and one possible follow-up idea.

---

## Week 4 – Teaching Rehearsal

Prepare a short mock seminar.

The session should contain:

1. chatbot warm-up question
2. explanation of one lecture topic
3. Moodle-style quiz questions
4. practical exercise
5. project challenge
6. explicit grading criteria

Deliverable:

> Conduct a 20–30 minute mock seminar with members of the group acting as students.

---

# 13. Possible Dedicated Onboarding Chatbot

It may be useful to create an **Applied Media Systems Onboarding Chatbot**.

Its knowledge base could contain:

- this onboarding guide
- group organization
- links to Moodle courses
- links to GitHub repositories
- links to Jupyter notebooks
- links to lecture chatbots
- group research overview
- selected publications
- books
- teaching procedures
- seminar procedures
- common TU Ilmenau administrative information

Example questions:

> What should I do during my first week?

> Where can I find the Audio Coding notebooks?

> Which papers should I read to understand the group's work on source separation?

> Which Moodle courses am I teaching?

> How should we use the lecture chatbot during a seminar?

> Give me a test to determine whether I am ready to teach the Audio Coding seminar.

> Suggest a seminar project related to Lecture 5 with an objective grading scheme.

The onboarding chatbot can therefore act as the **entry point**, while the specialized lecture chatbots provide detailed course-specific knowledge.

---

# 14. Suggested Onboarding Chatbot Instruction

A possible basic instruction for the chatbot is:

> You are the onboarding assistant for new teaching and research staff in the Applied Media Systems group at TU Ilmenau.
>
> Help new group members learn the group's research topics, teaching responsibilities, software infrastructure, Moodle courses, GitHub repositories, Jupyter notebooks, books, and publications.
>
> When asked about a course, first provide a structured overview and point to the relevant lecture material, books, papers, notebooks, and Moodle resources.
>
> Encourage active learning. Offer to test the user by asking one question at a time, waiting for the answer, evaluating it, and adapting subsequent questions to the user's level.
>
> For teaching preparation, help instructors create seminar questions, programming exercises, Moodle quizzes, and project challenges with objective and quantifiable grading criteria.
>
> Clearly distinguish between information contained in the provided group material and general knowledge. If group-specific information is unavailable, say so rather than inventing it.

---

# 15. Onboarding Completion Checklist

- [ ] TU Ilmenau account working
- [ ] E-mail configured
- [ ] Nextcloud access working
- [ ] Relevant Moodle courses accessible
- [ ] Instructor permissions checked
- [ ] GitHub repositories located
- [ ] At least one repository cloned
- [ ] Jupyter/Colab examples executed
- [ ] Lecture chatbots tested
- [ ] Assigned course structure understood
- [ ] Representative course exercises solved
- [ ] Moodle quiz completed
- [ ] Example Moodle quiz created
- [ ] VPL example completed
- [ ] At least two group papers read
- [ ] Audio Coding / MRSP book material explored
- [ ] Short research presentation completed
- [ ] Mock seminar completed
- [ ] Seminar chatbot workflow tested
- [ ] Quantifiable project grading scheme prepared

---

# 16. Guiding Principle

The goal of onboarding is not to memorize all existing material. New instructors should learn **how to find information, how to use the group's tools, and how to independently prepare themselves for teaching and research**.

The combination

**Course material → Book/Papers → Jupyter examples → Lecture chatbot → Moodle quiz → Seminar → Project challenge**

can form a common workflow for both instructor onboarding and student learning.