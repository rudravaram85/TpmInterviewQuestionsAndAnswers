                                      <h2>Technical Project Manager Interview Questions and Answers</h2>



<h3>Managing **dependencies** and bringing **transparency** to them is essential in Scrum, especially when working with multiple teams or complex products. Here's how to approach this effectively:</h3>

---

### ✅ How to **Manage Dependencies** in Scrum

1. **Identify Dependencies Early**

   * Use **Product Backlog Refinement** to surface dependencies before the Sprint starts.
   * Engage stakeholders, architects, and other teams during planning to identify cross-team or external blockers.

2. **Visualize Dependencies**

   * Use visual tools like:

     * Dependency Boards
     * Program Boards (e.g. SAFe style)
     * Gantt Charts (sparingly, to show sequence)
     * Colored labels/tags in tools like Jira or Azure DevOps
   * Make dependencies visible in your Sprint or Release Planning.

3. **Prioritize to Minimize Dependencies**

   * Break down backlog items to reduce inter-team or external reliance.
   * Reorder work to reduce “wait time” on others.

4. **Cross-Team Coordination**

   * Use **Scrum of Scrums** or **Nexus Daily Scrum** for regular alignment between teams.
   * Appoint a **Dependency Owner** or **Integration Lead** in large projects.

5. **Set Clear Ownership**

   * Assign clear responsibility for resolving each dependency.
   * Encourage teams to negotiate ownership during Sprint Planning or PI Planning.

---

### 🔍 How to Bring **Transparency** to Dependencies

1. **Track Dependencies in Agile Tools**

   * Use linking features in Jira, Trello, Azure DevOps, etc.:

     * “Blocked by,” “Depends on,” or custom tags
     * Visual boards or roadmaps to highlight them

2. **Make Them Part of Daily Standups**

   * Ask daily: *“Are we blocked by any dependency?”* or *“Is another team waiting on us?”*

3. **Show Them in Reviews or Demos**

   * Call out unresolved or resolved dependencies that affected deliverables.
   * Helps stakeholders see system-wide implications.

4. **Document and Share**

   * Maintain a shared **Dependency Log** or **Risk Register**.
   * Keep it lightweight and accessible by all.

5. **Use Metrics**

   * Track delays or issues caused by dependencies.
   * Use this data to push for structural changes if necessary (e.g. team realignment, architecture simplification).

---

### 💡 Pro Tips

* **Shift-left** your dependency management — handle them as early in the lifecycle as possible.
* Foster a **collaborative culture** where teams feel safe raising and discussing blockers.
* Reorganize teams to become more cross-functional if dependencies are persistent and painful.

---

Would you like a sample dependency board layout or a Jira configuration for tracking dependencies?


    <h3> In **Scrum**, *artifacts* are key information items used to ensure transparency and provide critical information that the Scrum Team and stakeholders need to understand the product and the work. There are **three main Scrum artifacts**:</h3>

---

### 1. **Product Backlog**

* **What it is:** A prioritized list of everything that might be needed in the product.
* **Owned by:** Product Owner
* **Contains:** Features, enhancements, bug fixes, technical work, and knowledge acquisition.
* **Evolves:** It's never complete; it's continuously refined as the product and environment evolve.
* **Key attribute:** Ordered by priority and business value.

---

### 2. **Sprint Backlog**

* **What it is:** A set of Product Backlog items selected for the Sprint, plus a plan for delivering them.
* **Owned by:** Developers (the Scrum Team)
* **Includes:** Selected backlog items + a plan (often broken down into tasks) on how to achieve the Sprint Goal.
* **Key attribute:** It’s a real-time picture of the work the team plans to complete in the current Sprint.

---

### 3. **Increment**

* **What it is:** The sum of all the Product Backlog items completed during a Sprint, plus all previous Increments.
* **Must be:** Usable and meet the Scrum Team’s Definition of Done.
* **Delivered:** At the end of each Sprint.
* **Key attribute:** It’s a step toward the product vision and must be in a usable state regardless of whether the Product Owner decides to release it.

---

### Supporting Concepts (Not official artifacts, but important):

#### ✅ **Definition of Done (DoD)**

* A shared understanding of what it means for work to be complete.
* Ensures transparency and quality.
* Applies to each Increment.

#### 🧭 **Sprint Goal**

* A single objective for the Sprint.
* Guides the Scrum Team during the Sprint.
* Created during Sprint Planning.

---

Great! Here's a **visual-style breakdown** and **example** of how Scrum artifacts are used during a typical Sprint.

---

## 🔄 **Overview of Scrum Artifacts in Action (During a Sprint)**

```
    Product Backlog ─────────┐
                            │
                            ▼
    Sprint Planning ─────► Sprint Backlog
                            │
                            ▼
                      Daily Scrum (progress check)
                            │
                            ▼
                        Development Work
                            │
                            ▼
    Sprint Review ─────► Increment (working product)
```

---

## 🧩 **Step-by-Step Example with Artifacts**

Let’s say a team is building a **To-Do List App**.

---

### 1. 📜 **Product Backlog**

**Owned by:** Product Owner

It's a prioritized list of everything the app needs. For example:

| Priority | Product Backlog Item                     |
| -------- | ---------------------------------------- |
| High     | As a user, I can add a new task          |
| High     | As a user, I can mark a task as complete |
| Medium   | As a user, I can delete a task           |
| Medium   | As a user, I can set due dates           |
| Low      | As a user, I can categorize tasks        |

---

### 2. 📋 **Sprint Backlog**

**Created during Sprint Planning**

The team selects some items from the Product Backlog for a 2-week Sprint. They also define the **Sprint Goal**, e.g.:

🧭 **Sprint Goal:** “Allow users to manage task creation and completion.”

**Sprint Backlog Items**:

* Add task functionality
* Mark task as complete
* Create database schema
* Write unit tests for task model

---

### 3. 🔄 **Development Work**

**Daily Scrums** help the team inspect progress and adapt the plan.

Each day, the team updates the Sprint Backlog as they complete tasks or adjust their approach.

---

### 4. ✅ **Increment**

**At the end of the Sprint**, the team should have a **working app** where:

* Users can add tasks
* Users can mark them complete
* Code meets Definition of Done (tested, documented, integrated)

📦 This is the **Increment** — a usable version of the app that could be released.

---

### 📏 **Definition of Done Example**

* Code reviewed and merged
* Tests written and passing
* UI meets design standards
* Deployed to test environment

---

## Summary Table

| Artifact        | Purpose                                  | Owner         | When It's Used               |
| --------------- | ---------------------------------------- | ------------- | ---------------------------- |
| Product Backlog | Full list of desired work on the product | Product Owner | Always                       |
| Sprint Backlog  | Plan for current Sprint                  | Developers    | During and throughout Sprint |
| Increment       | Working product + value                  | Scrum Team    | Delivered at Sprint end      |

---

<h3>The **three pillars of Scrum** are: </h3>

1. **Transparency**

   * Everyone involved must have a common understanding of the work and the process.
   * Key information (like the product backlog, sprint goals, progress, etc.) must be visible and clear to all stakeholders.
   * Artifacts (such as the Product Backlog, Sprint Backlog, and Increment) must be transparent and well-defined.

2. **Inspection**

   * Scrum users must frequently inspect Scrum artifacts and progress toward the Sprint Goal to detect undesirable variances.
   * Inspections are done during events like Sprint Planning, Daily Scrum, Sprint Review, and Sprint Retrospective.
   * Regular inspection helps identify problems early.

3. **Adaptation**

   * If any aspects deviate outside acceptable limits, the process or materials must be adjusted.
   * This adaptation should be made as soon as possible to minimize further deviation.
   * Sprint Retrospectives, for example, provide opportunities for teams to improve and adapt their processes.

These pillars support **empirical process control** — the foundation of Scrum — which emphasizes making decisions based on what is known.
                                 
