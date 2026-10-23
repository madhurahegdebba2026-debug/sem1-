# 3. Test, check, and own the decision

## Easy

* **What makes a short-versus-detailed instruction test fair?**
  * A fair test keeps all external conditions constant—using the same AI model, context, and core objective—while varying only the level of detail in the instructions. This ensures any difference in output quality is strictly due to the instruction clarity.

* **What is a consequential claim?**
  * A consequential claim is an authoritative statement made by an AI regarding high-stakes information (such as dates, deadlines, financial data, or policies) where errors can cause real-world negative impacts, confusion, or penalties.

* **Why should a student check a confident AI answer before using it publicly?**
  * AI models often output incorrect or hallucinated information with complete confidence. Checking the facts prevents spreading misinformation, protects your reputation, and ensures you take personal responsibility for the final decision.

---

## Intermediate

* **A short instruction gives a correct but general fest reminder. A detailed instruction includes the correct time, venue, and volunteer reporting time. Which answer better serves the fest committee? Explain why.**
  * The **detailed instruction** better serves the fest committee.
  * **Reason:** General reminders lack essential operational details, leading to confusion and coordination issues. Including exact times, venues, and reporting times gives clear, actionable data that eliminates ambiguity and ensures smooth event execution.

* **An AI writes a college exam date in a class-group message, but gives no source. What should the student do before forwarding it?**
  * The student must cross-verify the exam date with official academic calendars, course syllabi, or direct announcements from the professor. They should never forward unverified AI-generated dates because exam schedules are critical and AI hallucinations can lead students to miss exams.

---

## Hard

* **Write one short instruction and one detailed instruction for the same real student task. State what must stay the same so the comparison is fair.**
  * **Task:** Drafting an email to request an assignment extension.
  * **Short Instruction:** "Write an email asking a professor for an assignment extension."
  * **Detailed Instruction:** "Write a professional email to Professor Smith asking for a 2-day extension on the upcoming Data Structures assignment due to an unexpected medical emergency, maintaining a polite tone and including placeholders for dates."
  * **What must stay the same:** The core objective (requesting an extension), the target recipient type (professor), and the AI model used, so that only the level of instruction detail is tested.

* **Change only one part of your detailed instruction, such as the audience or limit. Write what you expect to change in the new answer and what you will check after it runs.**
  * **Modified Instruction (Changing Audience to a Peer):** "Write a casual message to a study group peer asking for help catching up on the missed Data Structures lecture due to an unexpected medical emergency, keeping it under 50 words."
  * **Expected Change:** The tone will transition from formal and professional (addressed to a professor) to casual and friendly (addressed to a peer), and the length will be restricted to a short snippet.
  * **What to check after it runs:**
    1. Verify that the tone successfully shifted to casual and friendly.
    2. Check that the output strictly adheres to the under-50-words limit constraint.
    3. Ensure the core context (medical emergency and missed lecture) is still accurately represented.
