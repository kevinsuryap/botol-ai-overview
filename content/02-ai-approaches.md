# Lesson 2: Understanding AI Approaches

## 1. Overview

Artificial Intelligence (AI) systems use different approaches to solve problems, make decisions, recognise patterns, and generate content. The approach used depends on the task, the available information, and the intended outcome.

Historically and technically, AI research is often divided into three main paradigms: **Symbolic AI**, **Connectionist AI**, and **Behavior-based AI**. Understanding these approaches helps learners recognise how different AI applications work and why certain methods are more suitable for particular tasks.

A simple way to remember the difference:

> **Symbolic AI is like a rulebook. Connectionist AI is like a student learning from examples. Behavior-based AI is like a reflex.**

This lesson introduces these three fundamental approaches to AI and explains how they are used in different applications.

### Learning Outcomes

By the end of this lesson, learners should be able to:

- Define the term AI approach.
- Identify three common AI approaches (Symbolic, Connectionist, Behavior-based).
- Explain the main differences between these approaches.
- Match AI approaches to suitable real-world applications.
- Identify the strengths and limitations of each approach.
- Understand the relationship between machine learning, deep learning, and generative AI.

### Prerequisites

Learners should have a basic understanding of what Artificial Intelligence is and how it is used in everyday life.

---

## 2. Terminology

Before exploring the approaches, here are key terms used throughout this lesson:

| Term | Meaning |
|---|---|
| **AI approach** | A method used to design a system that performs intelligent tasks. |
| **Symbol** | A representation of a concept, object, or rule (e.g., the word "fever" or the number "5"). |
| **Rule** | An explicit instruction such as "IF X THEN Y." |
| **Neural network** | A computing system made of connected nodes that process information and learn patterns from data. |
| **Weight** | The strength of a connection between nodes in a neural network; adjusted during learning. |
| **Training data** | Examples used to teach a Connectionist system to recognise patterns. |
| **Machine learning** | A branch of AI that allows systems to learn patterns from data and make predictions or decisions. |
| **Deep learning** | A specialised type of machine learning that uses neural networks with multiple layers. |
| **Generative AI** | AI that creates new content, such as text, images, audio, and videos. |
| **Agent** | A system (often a robot or software) that perceives its environment and acts on it. |
| **Environment** | The surroundings an agent interacts with (e.g., a room, a road, a webpage). |
| **Behavior** | An action an agent takes in response to information from its environment. |
| **Reactive** | Responding to input, often without long-term planning. |
| **Black box** | A system whose internal decision-making process can be difficult for humans to inspect or explain. |
| **Hybrid system** | A system that combines two or more AI approaches. |

---

## 3. What Are AI Approaches?

AI approaches are methods used to design systems that perform tasks associated with intelligence, such as solving problems, recognising patterns, making predictions, or generating content.

Different approaches use different methods to achieve their goals. For example, a **Symbolic** system follows logical rules written by developers, while a **Connectionist** system uses artificial neural networks to learn patterns from data. A **Behavior-based** system, meanwhile, focuses on how a robot or agent interacts with its environment in real time.

It is important to understand that not every computer program that follows rules is automatically an AI system. Simple automation can perform fixed instructions without using AI. Symbolic AI generally involves representing knowledge and applying logical rules to reach conclusions or solve problems.

There is no single approach that is best for every situation. The most suitable approach depends on the problem, the available resources, and the expected results.

---

## 4. Common AI Approaches

### A. Symbolic AI (Rule-Based)

Symbolic AI relies on explicit symbols and logical rules. It assumes that intelligence can be simulated by manipulating symbols according to predefined rules. Developers establish the logic before the system is used, and the system follows those rules to reach conclusions.

```text
   Rules + Facts  →  [ Logical Engine ]  →  Conclusion
   (symptoms)        (applies conditions)   (suggested solution)
```

**Example:** A computer troubleshooting expert system that uses several IF-THEN rules to recommend possible solutions.

For example:

- IF the computer has no internet connection AND the network cable is disconnected, THEN recommend reconnecting the cable.
- IF the computer has no internet connection AND the router is not responding, THEN recommend checking the router.
- IF the computer has an internet connection BUT a website cannot load, THEN recommend checking the website or browser settings.

This system uses stored knowledge and logical conditions to suggest possible solutions. It is an example of a rule-based expert system.

**Advantages:**

- Highly transparent and explainable because the rules can be inspected.
- Easy to understand and predict.
- Suitable for tasks with clear, logical conditions and specialised knowledge.

**Limitations:**

- Cannot easily handle situations that are not covered by its rules.
- Requires extensive manual effort to write and update the rules.
- Struggles with noisy data or tasks like image recognition that are difficult to describe using strict logic.

**Important note:** A basic password checker or delivery-fee calculator is an example of rule-based automation, but it is not necessarily AI. A system becomes a stronger example of Symbolic AI when it represents knowledge and applies logical reasoning to solve problems.

### B. Connectionist AI (Neural Networks)

Connectionist AI is inspired by the structure of the human brain. Instead of relying only on explicit rules, it uses artificial neural networks to process information.

These systems learn from data by adjusting the strength of connections (weights) between simulated neurons.

Connectionist AI is closely related to **Machine Learning (ML)** and **Deep Learning (DL)**.

- **Machine Learning:** A branch of AI in which systems learn patterns from training data and use those patterns to make predictions or decisions.
- **Deep Learning:** A specialised type of machine learning that uses neural networks with multiple layers to recognise more complex patterns.

In simple terms, deep learning is part of machine learning, and machine learning is part of AI.

```text
          Artificial Intelligence (AI)
                     |
              Machine Learning
                     |
                Deep Learning
                     |
          Multi-layer Neural Networks
```

**Example:** An email service that learns to identify spam by analysing thousands of examples of spam and legitimate emails, rather than relying only on a manually written list of unwanted words.

Another example is an image recognition system that uses a deep learning model trained on many animal photographs to recognise whether an image contains a cat, dog, or other animal.

**Advantages:**

- Excellent at recognising complex patterns, such as faces, speech, and handwriting.
- Can generalise from examples to new, previously unseen data.
- Can improve its performance through training and suitable data.

**Limitations:**

- Often acts as a "black box" because it may be difficult to explain exactly how it reached a particular result.
- Depends heavily on the quality and quantity of training data.
- Can be computationally expensive to train.

**Connection to Generative AI:**

Generative AI is another important development associated with modern AI systems. It refers to AI that produces new content, such as text, images, audio, and videos.

Many modern generative AI applications use deep learning models. For example, an AI image generator can create an illustration based on a written description.

However, generative AI is not a separate category alongside Symbolic, Connectionist, and Behavior-based AI. It describes the type of task a system performs, and its underlying technology may involve Connectionist methods.

### C. Behavior-based AI

Behavior-based AI (often associated with robotics) focuses on the interaction between an agent and its environment.

Instead of relying entirely on complex internal models or rigid instructions, intelligence is viewed as the result of simple behaviors that respond to sensory input. These systems are often reactive and adapt to changes in real time.

```text
   Sensors  →  [ Select Behavior ]  →  Action
   (obstacle)   (detects obstruction)   (change direction)
```

**Example:** A robot vacuum cleaner that uses simple behaviors to navigate a room.

For example:

- IF an obstacle is detected, THEN change direction.
- IF the battery is low, THEN return to the charging station.
- IF dirt is detected, THEN clean the affected area.

These behaviors allow the robot to respond to changes in its surroundings.

**Advantages:**

- Can respond quickly to changes in the environment.
- Useful in dynamic environments where conditions may change.
- Can perform practical tasks without requiring a complete map of the surroundings.

**Limitations:**

- Difficult to design for tasks requiring complex planning or long-term strategy.
- Can be hard to predict how multiple simple behaviors will interact.
- May have limited memory or understanding of past events.

### Important Distinction: Hybrid AI Systems

These approaches are related, not completely separate categories. Modern AI applications often combine different methods to achieve better results.

For example, a self-driving car might use:

- **Connectionist AI** to recognise roads, vehicles, and pedestrians.
- **Symbolic AI** to represent traffic rules and apply logical conditions.
- **Behavior-based AI** to respond to immediate changes in its surroundings.

Combining different approaches can help systems perform tasks that would be difficult for one approach to handle alone.

---

## 5. Comparing AI Approaches

| Approach | How It Works | Example Application | Main Limitation |
|---|---|---|---|
| **Symbolic AI** | Uses predefined knowledge, logical rules, and symbols | Expert systems and troubleshooting assistants | Limited flexibility when situations are not covered by existing rules |
| **Connectionist AI** | Learns patterns from data using neural networks | Image recognition, speech recognition, and spam detection | Can be difficult to explain and requires suitable training data |
| **Behavior-based AI** | Uses behaviors that respond to information from the environment | Robot vacuum cleaners and robotic navigation | Limited complex reasoning and long-term planning |

The main difference is how each approach handles a task. Symbolic systems rely on explicit knowledge and logical rules, Connectionist systems rely on learned patterns from data, and Behavior-based systems rely on interaction with the environment.

Machine learning and deep learning are closely associated with Connectionist AI, while generative AI uses techniques that may include deep learning to create new content.

---

## 6. How to Choose an AI Approach

Choosing an AI approach begins with understanding the problem that needs to be solved.

Consider the following questions:

- **What is the task?** Does the system need to follow logical conditions (Symbolic), recognise patterns in data (Connectionist), or react to a physical environment (Behavior-based)?
- **What information is available?** Does the system need training data, or is predefined knowledge sufficient?
- **How accurate must the result be?** Some tasks require highly reliable and predictable outputs.
- **What resources are available?** More complex models, such as deep neural networks, may require significant computing power.
- **How important is explainability?** Some applications need clear explanations of how decisions are reached.

For tasks involving specialised knowledge and logical conditions, a **Symbolic** system may be suitable. **Connectionist** AI is useful when a system needs to identify patterns in large datasets, such as images or text. **Behavior-based** AI is appropriate for robotics and systems that must respond to changes in physical environments.

In some situations, combining multiple approaches may provide a more suitable solution.

---

## 7. Practical Scenario: Improving a School Support System

Imagine that a school wants to improve how it answers students' questions and provides support.

The school could use several AI approaches for different tasks:

- **Symbolic AI:** A virtual troubleshooting assistant uses an expert system to answer common technical questions. It checks several conditions and recommends possible solutions based on stored knowledge.
- **Connectionist AI:** A system analyses the text of a student's enquiry to identify whether it is urgent or routine, based on patterns learned from previously labelled examples.
- **Behavior-based AI:** A delivery robot in the school library navigates around students to deliver books, reacting to obstacles in real time.

Each approach serves a different purpose. In practice, the school might combine these approaches rather than use only one.

However, AI systems used in schools should be evaluated carefully. Their results may not always be accurate, and systems that process student information must protect privacy. Important decisions should involve appropriate human review.

---

## 8. Learner Activity: Identify the AI Approach

Read each situation and identify the most suitable approach: **Symbolic**, **Connectionist**, or **Behavior-based**.

1. A computer troubleshooting expert system checks several reported problems and applies predefined logical rules to recommend a possible solution.
2. An animal-image recognition system uses a deep learning model trained on thousands of photographs to identify different animals.
3. A robotic vacuum cleaner navigates a room by detecting obstacles and changing direction.
4. A medical expert system uses stored medical knowledge and several IF-THEN conditions to suggest possible explanations for a set of symptoms.
5. A spam filter identifies unwanted emails by learning patterns in previously flagged messages.

For each answer, explain why the selected approach is suitable.

### Extension Activity

Choose one AI application that you have encountered in everyday life.

Identify its main purpose and suggest which AI approach or combination of approaches it might use.

Explain your reasoning and identify one possible limitation.

---

## 9. Answer Key

1. **Symbolic AI:** The troubleshooting system uses stored knowledge and predefined logical rules to recommend a solution.
2. **Connectionist AI:** The system uses a deep learning model, which is a specialised type of machine learning, to recognise patterns in animal photographs.
3. **Behavior-based AI:** The robot uses simple reactive behaviors to interact with its environment and avoid obstacles.
4. **Symbolic AI:** The expert system uses stored medical knowledge and logical conditions to suggest possible explanations.
5. **Connectionist AI:** The spam filter learns patterns from examples of spam and legitimate emails.

*These answers are suitable based on the descriptions given. Real-world systems may combine multiple approaches.*

---

## 10. Discussion and Reflection

Discuss the following questions individually or in groups:

1. Why do AI systems use different approaches instead of relying on one method?
2. What is the main difference between a Symbolic system and a Connectionist system?
3. Why is it important that a system, such as a medical expert system, provides explainable recommendations?
4. What are the benefits and limitations of using Connectionist AI, such as deep learning, for schoolwork?
5. How can generative AI help students, and why should its results be checked?
6. Can you think of a situation in which combining two AI approaches would be more useful than using only one?

---

## 11. Key Takeaways

- **Symbolic AI** follows predefined logical rules and uses stored knowledge to solve problems. It is suitable for clear and explainable tasks.
- **Connectionist AI** uses neural networks to learn patterns from data and is useful for complex tasks such as image and speech recognition.
- **Machine Learning** is a branch of AI that allows systems to learn patterns from data.
- **Deep Learning** is a specialised type of machine learning that uses neural networks with multiple layers.
- **Generative AI** creates new content, such as text, images, audio, and videos, and often uses deep learning techniques.
- **Behavior-based AI** focuses on real-time interaction with the environment and is commonly associated with robotics.
- AI approaches have different strengths and limitations, and several approaches can be combined in one application.
- Choosing an appropriate approach requires considering the task, available data, resources, reliability, explainability, and potential risks.

Understanding different AI approaches helps learners recognise how intelligent systems are designed and why different methods are suitable for different situations.

---

## 12. Further Reading

1. **IBM — What Is Machine Learning?**

   https://www.ibm.com/think/topics/machine-learning

   Explains how machine learning systems learn patterns from data and make predictions or decisions.

2. **IBM — What Is Deep Learning?**

   https://www.ibm.com/think/topics/deep-learning

   Introduces deep learning, artificial neural networks, and the relationship between deep learning and machine learning.

3. **NIST — Generative AI Glossary**

   https://csrc.nist.gov/glossary/term/genai

   Provides a definition of generative AI and explains the types of content that generative AI systems can produce.

These resources provide additional information for learners who want to explore machine learning, deep learning, and generative AI in more detail.
