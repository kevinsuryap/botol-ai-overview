# Lesson 2: Understanding AI Approaches

## 1. Overview
Artificial Intelligence (AI) systems use different approaches to solve problems, make decisions, recognise patterns, and generate content. The approach used depends on the task, the available information, and the intended outcome.

Historically and technically, AI research is often divided into three main paradigms: **Symbolic AI**, **Connectionist AI**, and **Behavior-based AI**. Understanding these approaches helps learners recognise how different AI applications work and why certain methods are more suitable for particular tasks.

A simple way to remember the difference:
> **Symbolic AI is like a rulebook. Connectionist AI is like a student learning from examples. Behavior-based AI is like a reflex.**

This lesson introduces these three fundamental approaches to AI.

**Learning Outcomes**
By the end of this lesson, learners should be able to:
*   Define the term AI approach.
*   Identify three common AI approaches (Symbolic, Connectionist, Behavior-based).
*   Explain the main differences between these approaches.
*   Match AI approaches to suitable real-world applications.
*   Identify the strengths and limitations of each approach.

**Prerequisites**
Learners should have a basic understanding of what Artificial Intelligence is and how it is used in everyday life.

## 2. Terminology
Before exploring the approaches, here are key terms used throughout this lesson:

| Term | Meaning |
| :--- | :--- |
| **AI approach** | A method used to design a system that performs intelligent tasks. |
| **Symbol** | A representation of a concept, object, or rule (e.g., the word "fever" or the number "5"). |
| **Rule** | An explicit instruction such as "IF X THEN Y." |
| **Neural network** | A computing system inspired by the brain, made of connected nodes that process information. |
| **Weight** | The strength of a connection between nodes in a neural network; adjusted during learning. |
| **Training data** | Examples used to teach a Connectionist system to recognise patterns. |
| **Agent** | A system (often a robot or software) that perceives its environment and acts on it. |
| **Environment** | The surroundings an agent interacts with (e.g., a room, a road, a webpage). |
| **Behavior** | A simple, reactive action an agent takes in response to sensory input. |
| **Reactive** | Responding immediately to input, without long-term planning. |
| **Black box** | A system whose internal reasoning is difficult for humans to inspect or explain. |
| **Hybrid system** | A system that combines two or more AI approaches. |

## 3. What Are AI Approaches?
AI approaches are methods used to design systems that perform tasks associated with intelligence, such as solving problems, recognising patterns, making predictions, or generating content.

Different approaches use different methods to achieve their goals. For example, a **Symbolic** system follows logical rules written by developers, while a **Connectionist** system uses artificial neural networks to learn patterns from data. A **Behavior-based** system, meanwhile, focuses on how a robot or agent interacts with its environment in real-time.

There is no single approach that is best for every situation. The most suitable approach depends on the problem, the available resources, and the expected results.

## 4. Common AI Approaches

### A. Symbolic AI (Rule-Based)
Symbolic AI relies on explicit symbols and logical rules. It assumes that intelligence can be simulated by manipulating symbols according to predefined rules. Developers establish the logic before the system is used, and the system follows those rules to reach conclusions.

```
   Rules + Facts  →  [ Logical Engine ]  →  Conclusion
   (IF fever AND cough)                     (Suspect flu)
```

**Example:** A medical diagnosis expert system that uses "IF-THEN" rules (e.g., IF the patient has a fever AND a cough, THEN suspect the flu).

**Advantages:**
*   Highly transparent and explainable (you can see exactly why a decision was made).
*   Easy to understand and predict.
*   Suitable for tasks with clear, logical conditions.

**Limitations:**
*   Cannot easily handle situations that are not covered by its rules.
*   Requires extensive manual effort to write and update the rules.
*   Struggles with noisy data or tasks like image recognition that are hard to describe with strict logic.

### B. Connectionist AI (Neural Networks)
Connectionist AI is inspired by the structure of the human brain. Instead of following explicit rules, it uses artificial neural networks to process information. These systems learn from data by adjusting the strength of connections (weights) between simulated neurons. This approach encompasses Machine Learning and Deep Learning.

```
   Training Data  →  [ Neural Network ]  →  Prediction
   (labelled emails)   (adjusts weights)     (spam / not spam)
```

**Example:** An email service that learns to identify spam by analysing thousands of examples of spam and legitimate emails, rather than being programmed with a list of "bad words."

**Advantages:**
*   Excellent at recognising complex patterns (e.g., faces, speech, handwriting).
*   Can generalize from examples to new, unseen data.
*   Improves as it is exposed to more data.

**Limitations:**
*   Often acts as a "black box" — the system may say "this is a cat" but cannot clearly tell you which pixels mattered.
*   Depends heavily on the quality and quantity of training data.
*   Can be computationally expensive to train.

### C. Behavior-based AI
Behavior-based AI (often associated with robotics) focuses on the interaction between an agent and its environment. Instead of complex internal models or rigid rules, intelligence is seen as the result of simple behaviors that are selected based on sensory input. These systems are often reactive and adapt to changes in real-time.

```
   Sensors  →  [ Select Behavior ]  →  Action
   (bumper)     (if pressed → back up)   (reverse)
```

**Example:** A robot vacuum cleaner that uses simple behaviors (e.g., "if obstacle detected, turn left," "if bumper pressed, back up") to navigate a room without needing a map.

**Advantages:**
*   Robust in dynamic, real-world environments.
*   Reacts quickly to changes (real-time response).
*   Can handle unpredictable situations better than rigid symbolic systems.

**Limitations:**
*   Difficult to design for tasks requiring complex planning or long-term strategy.
*   Can be hard to predict how multiple simple behaviors will interact.
*   Often lacks a "memory" of past events in the way other approaches do.

**Important distinction:** These approaches are related, not completely separate categories. Modern AI often uses **hybrid systems**. For example, a self-driving car might use a connectionist approach to "see" the road (vision), a symbolic approach to follow traffic laws, and a behavior-based approach to avoid sudden obstacles.

## 5. Comparing AI Approaches

| Approach | How It Works | Example Application | Main Limitation |
| :--- | :--- | :--- | :--- |
| **Symbolic AI** | Follows predefined logical rules and symbols | Expert systems, tax calculation software | Limited flexibility; struggles with messy data |
| **Connectionist AI** | Learns patterns from data using neural networks | Image recognition, voice assistants | "Black box" nature; requires lots of data |
| **Behavior-based AI** | Simple reactive behaviors interacting with the environment | Robot vacuum, autonomous drone navigation | Limited complex reasoning; hard to scale |

The main difference is how each approach handles a task. Symbolic systems rely on explicit instructions, Connectionist systems rely on learned statistical patterns, and Behavior-based systems rely on real-time environmental interaction.

## 6. How to Choose an AI Approach
Choosing an AI approach begins with understanding the problem that needs to be solved.

Consider the following questions:
*   **What is the task?** Does the system need to follow strict logic (Symbolic), recognise patterns in data (Connectionist), or react to a physical environment (Behavior-based)?
*   **What information is available?** Does the system need training data, or are predefined rules sufficient?
*   **How accurate must the result be?** Some tasks require highly reliable and predictable outputs.
*   **What resources are available?** More complex models (like deep neural networks) may require significant computing power.

For tasks with clear conditions, a **Symbolic** system may be sufficient. **Connectionist** AI is useful when a system needs to identify patterns in large datasets (like images or text). **Behavior-based** AI is appropriate for robotics and systems that must operate in unpredictable physical spaces.

## 7. Practical Scenario: Improving a School Support System
Imagine that a school wants to improve how it answers students' questions.

The school could use several AI approaches for different tasks:

*   **Symbolic AI:** A virtual assistant uses a decision tree to answer questions (e.g., "If the student selects 'Timetable', display the timetable link").
*   **Connectionist AI:** A system analyses the text of a student's enquiry to determine if it is urgent or routine, based on past examples.
*   **Behavior-based AI:** A delivery robot in the school library navigates around students to deliver books, reacting to obstacles in real-time.

Each approach serves a different purpose. In practice, the school might combine these approaches rather than use only one. Staff should review important responses, and sensitive student information should be handled appropriately.

## 8. Learner Activity: Identify the AI Approach
Read each situation and identify the most suitable approach: **Symbolic**, **Connectionist**, or **Behavior-based**.

1.  A tax software program calculates a citizen's tax owed based on strict legal rules and income brackets.
2.  A security camera system learns to recognise faces by analysing thousands of photos.
3.  A robotic vacuum cleaner navigates a room by bumping into a wall and changing direction.
4.  A password validator checks whether a new password meets the required length and character rules.
5.  A spam filter identifies unwanted emails by learning from patterns in previously flagged messages.

For each answer, explain why the selected approach is suitable.

**Extension Activity**
Choose one AI application that you have encountered in everyday life. Identify its main purpose and suggest which AI approach or combination of approaches it might use. Explain your reasoning and identify one possible limitation.

## 9. Answer Key
1.  **Symbolic AI:** The tax rules are fixed and logical; the system follows explicit instructions.
2.  **Connectionist AI:** The system learns complex visual patterns from data (photos) to recognise faces.
3.  **Behavior-based AI:** The robot uses simple reactive behaviors (bump → turn) to interact with its environment.
4.  **Symbolic AI:** The validator follows predefined logical rules (length, character types).
5.  **Connectionist AI:** The filter learns patterns from examples of spam and legitimate emails.

*These answers are suitable based on the descriptions given. Real-world systems may combine multiple approaches.*

## 10. Discussion and Reflection
Discuss the following questions individually or in groups:

1.  Why do AI systems use different approaches instead of relying on one method?
2.  What is the main difference between a Symbolic system and a Connectionist system?
3.  Why is it important that a system (like a tax calculator) is "explainable"?
4.  What are the benefits and limitations of using Connectionist AI (like deep learning) for schoolwork?
5.  Can you think of a situation in which combining two AI approaches would be more useful than using only one?

## 11. Key Takeaways
*   **Symbolic AI** follows predefined logical rules and is good for clear, explainable tasks.
*   **Connectionist AI** uses neural networks to learn patterns from data and is powerful for complex tasks like vision and language.
*   **Behavior-based AI** focuses on real-time interaction with the environment and is common in robotics.
*   AI approaches have different strengths and limitations, and several approaches can be combined in one application.
*   Choosing an appropriate approach requires considering the task, available data, resources, reliability, and potential risks.

## 12. Further Reading
*   IBM — Machine Learning
*   IBM — Deep Learning
*   NIST — Artificial Intelligence
