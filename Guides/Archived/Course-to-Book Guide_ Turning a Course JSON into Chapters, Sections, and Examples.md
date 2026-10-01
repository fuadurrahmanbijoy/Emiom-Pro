# Course-to-Book Guide: Turning a Course JSON into Chapters, Sections, and Examples

*A procedure for processing a course JSON (course details, learning objectives, topics, past questions) into the plan for a book. Works alongside the Visual, Intellectual, and Beginner guides. Every decision below comes from your answers.*

---

## 1. The Central Rule: The Back Story Never Shows

The objectives, topics, and past questions are the **muse**, not the contents. They shape the book from behind the scenes and never appear in it.

**The book must never contain:**

- Objective numbers or labels ("CLO 2", "Learning objective 4")
- Topic lists copied from the course outline
- Mentions of past papers, exam years, marks, or "frequently asked" questions
- Any question copied word for word

**What the reader sees** is a coherent book that happens to cover everything they need. The scaffolding lives in separate working documents (section 9), which are never printed.

---

## 2. The Two Promises the Book Makes

1. **Complete coverage.** Every topic in the JSON is covered somewhere, with the idea built completely and soundly.
2. **Answerability.** A student who reads the book carefully can answer any past question, and any fresh question of the same kind.

Everything else is a means to these two promises.

---

## 3. The Process, Step by Step

### Step 1: Take inventory

Read the JSON and list, without judging:

- Every objective, with its topics beneath it.
- Every question, with whatever fields exist (year, marks, type, linked topic).
- Fields that are missing. Never invent data; note gaps and proceed.

### Step 2: Flatten the topics

Make one flat list of every topic, noting its parent objective. Mark **duplicates and overlaps**: the same topic appearing under different objectives, or topics that are halves of one idea.

### Step 3: Profile the questions

For each question, record:

- **Type:** definition, calculation, short explanation, essay, case analysis, or another kind found in the data.
- **Topic or topics tested.**
- **Skill needed** (recall, apply a formula, interpret, compare, evaluate).
- **Frequency** of the topic and the skill across the years.

Group near-identical questions from different years into **question families**.

### Step 4: Map questions to topics

- Each question points to at least one topic.
- **A question that fits no topic** is covered **fully** in the most natural section of the book, and the list of topics is extended to include it. Note it in the working documents.
- **A topic with no questions** is still covered fully. Coverage follows topics, not questions.

### Step 5: Break topics into concepts

A topic often holds several concepts. List each one as a single teachable idea, and note what each concept needs from earlier ones. This gives a **dependency map**: which idea must come before which.

### Step 6: Decide what the beginner needs first

Look for ideas the first topic quietly assumes. Where an absolute beginner would be lost, add **foundation chapters or bridging sections** at the start or before the concept that needs them. These are encouraged, and they do not come from the JSON.

### Step 7: Build the chapters

- Objectives are **inspiration, not structure.** One objective does not become one chapter.
- **Merge small objectives and split large ones** by size and dependency.
- **Regroup freely by teaching logic**, then check afterward that every objective is covered.
- Order chapters by **dependency**, so nothing appears before its time, even where this differs from the JSON order.
- Target about 8,000-12,000 words per chapter, per the Intellectual Guide.
- Give each chapter a **working title in ordinary book language**, never objective language.

### Step 8: Build the sections

- Sections follow the **best teaching order**, not the topic list.
- **Merge related topics** into one section by theme; absorb small topics into larger ones.
- Add bridging sections where a beginner needs a step the JSON skips.
- Aim for 3-6 sections per chapter.
- **Every topic must appear** in some section, built completely and soundly.

### Step 9: Handle overlaps

When a topic appears under more than one objective:

1. **Teach it fully once**, in the best place.
2. **Revisit it briefly from a new point of view** wherever it returns, taking the chance to show the idea from another side, with a short recall note in the side column.

### Step 10: Plan the examples and practice

See sections 5 and 6.

### Step 11: Check coverage silently

See section 7.

---

## 4. Content Weight: Frequency Does Not Decide It

The **size and emphasis** of any content in the book is decided by two things only: the **importance of the idea** within the subject, and how **difficult it is for a beginner**, as laid out in the Intellectual and Beginner guides.

**Question frequency and importance never enlarge or shrink a topic.** A topic that appears in every past paper gets the same depth it would get if it never appeared.

Frequency and question profile affect **only two things**: the **examples** and the **end-of-chapter practice**.

---

## 5. Building the Examples: The Adaptation Ladder

Past questions become **fresh worked examples**, never copies. For each concept that past questions test, build a ladder of examples that helps the learner adapt and migrate step by step:

| Rung | What changes | Purpose |
| --- | --- | --- |
| **1. Familiar** | The same skill and structure as the question family, with **new numbers** | Recognise the pattern and learn the method |
| **2. Reshaped** | Numbers **and shape** changed (the unknown sits elsewhere, the order is reversed, an extra step added) | Show the method is not a script |
| **3. New setting** | A **new scenario**, drawn from the running business or a historical case | Transfer the method to unfamiliar ground |
| **4. Advanced** | **Higher complexity**, combining the concept with ones learned earlier | Prepare for harder questions |

**Rules**

- Examples progress from **familiar to unfamiliar**, using what the learner already knows to carry them forward.
- High-frequency question families receive **more rungs and more examples**. This is the only way frequency enters the body of the book.
- Every worked example follows the standard layout (Given, Find, Formula, Steps, Answer, Check).
- No scenario may be recognisable as a particular past question.
- Examples live naturally inside the running business or a verified historical case, not as stand-alone exam questions.

---

## 6. End-of-Chapter Practice

Practice is where the question bank shows most clearly, though never by name.

1. **Question types decide the formats offered.** If the past questions include definitions, calculations, short explanations, essays, and case analyses, the practice includes all of these, in similar proportion to what students will face.
2. **Frequency decides how much practice** a topic receives, so commonly tested skills get more problems.
3. **Difficulty climbs** within each set, following the ladder in section 5.
4. Every practice set works with the closing features from the Intellectual Guide: review questions with short answers at the back, and a "Think it through" problem.
5. No practice question is copied from the bank; each is newly written.
6. Test that the practice covers **every question type** found in the bank.

---

## 7. The Silent Coverage Check

Before writing, and again after drafting, trace every past question through the plan:

1. Which concepts does the question need?
2. Are those concepts taught in the book, with the definition, method, and an example that a beginner can follow?
3. Could a careful reader answer the question using only the book?

If not, fix the book: add the missing idea in the most natural section. Repeat the same test for every topic and every objective to confirm nothing was dropped.

This check is **recorded in the working documents only.**

---

## 8. Final Clean-Out

Before the book is considered finished, scan it for any trace of the back story:

- No objective labels or numbers.
- No exam years, paper names, marks, or frequency remarks.
- No copied questions.
- No section titles that read like syllabus lines.

Generic advice about studying for exams may appear in the opening "How to use this book" note, but nowhere else.

---

## 9. Working Documents (Never Printed)

1. **Inventory:** every objective, topic, and question as found.
2. **Question profile:** types, skills, frequencies, question families.
3. **Concept map:** concepts, prerequisites, and dependency order.
4. **Chapter blueprint:** one entry per chapter, using the template below.
5. **Coverage matrix:** every question, topic, and objective traced to the sections that cover it.
6. **Log of decisions:** added topics, merged topics, unmapped questions, flagged gaps.

**Chapter blueprint entry**

| Field | Contents |
| --- | --- |
| Working title | In ordinary book language |
| Purpose | One sentence on what the reader can do after this chapter |
| Needs from earlier chapters | Prerequisite ideas |
| Sections | Ordered list, each with its concepts |
| Running business step | The decision or event the case file covers here |
| Historical case | A verified candidate, with source |
| Overlap revisits | Earlier ideas revisited from a new angle |
| Example ladder plan | Concepts, rungs, and number of examples |
| Practice plan | Question types and quantities, with difficulty climb |
| Notes | Anything to flag |

---

## 10. Open Choices Still to Confirm

- The format of the working documents (a spreadsheet for the inventory, profile, and coverage matrix is recommended).
- How many rungs of the ladder to build for ordinary concepts, and how many extra for high-frequency ones.
- Whether foundation chapters appear as numbered chapters or as a clearly marked "Before You Begin" part.