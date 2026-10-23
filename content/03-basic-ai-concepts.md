    # Basic AI Concepts

## 1. Overview

Artificial Intelligence (AI) allows computer systems to perform tasks such as recognising patterns, analysing information, making predictions, and generating content.

To understand how AI works, it is important to learn several basic concepts: **data, algorithms, models, training, and predictions**. These concepts help explain how an AI system receives information, processes it, and produces an output.

For example, an email service may use AI to identify spam messages. The system can learn patterns from previously labelled emails and use those patterns to predict whether a new email is likely to be spam.

This section introduces the fundamental concepts behind AI through simple explanations, a worked example, and a learning activity.

### Learning Objectives

By the end of this section, learners should be able to:

1. Define data, algorithms, models, training, and predictions.
2. Explain how these concepts relate to one another in a basic AI system.
3. Describe how an AI model can learn patterns from data.
4. Identify the main stages of a simple AI workflow.
5. Match basic AI terms with their correct definitions.

**Prerequisite knowledge:** Basic computer literacy and the ability to understand simple examples. No programming or mathematical background is required.

---

## 2. Data

### 2.1 What Is Data?

**Data** refers to information that can be collected, stored, and processed by a computer system.

AI systems may use different types of data, including:

- **Text:** Emails, messages, articles, and documents.
- **Images:** Photographs, scanned documents, and pictures.
- **Audio:** Speech, music, and recorded sounds.
- **Numerical data:** Prices, temperatures, measurements, and scores.
- **Video:** Recorded activities, traffic footage, and other moving images.

Data provides information that an AI system can use to perform a task. Depending on the system, the data may be used to identify patterns, make predictions, or generate content.

### 2.2 What Is a Dataset?

A **dataset** is a collection of related data organised for a particular purpose.

For example, an email dataset might contain messages labelled as either spam or not spam.

| Email | Example content | Label |
|---|---|---|
| Email A | "Your account statement is ready." | Not spam |
| Email B | "Congratulations! Claim your prize now!" | Spam |
| Email C | "Our class meeting starts at 10 AM." | Not spam |
| Email D | "You have won a free gift. Click here!" | Spam |

The labels identify the category associated with each example. In this case, they help a model learn patterns that may distinguish spam from ordinary emails.

### 2.3 Why Is Data Important?

The quality and relevance of data can affect the performance of an AI system.

For example:

- Incorrect data can lead to unreliable results.
- Incomplete data may leave out important information.
- Biased data may contribute to unfair predictions.
- Data that does not represent real-world situations may cause a model to perform poorly on new examples.

Therefore, collecting and preparing suitable data is an important part of developing many AI systems.

---

## 3. Algorithms

### 3.1 What Is an Algorithm?

An **algorithm** is a defined set of instructions or steps used to solve a problem or complete a task.

Algorithms are used in many areas of computing, not only in AI. For example, a calculator follows algorithms to perform mathematical operations.

In AI, an algorithm may be used to find patterns in data, adjust a model during training, or generate predictions.

### 3.2 Simple Example of an Algorithm

Imagine that you want to organise students according to their test scores.

A simple algorithm could follow these steps:

1. Receive the students' test scores.
2. Compare the scores.
3. Arrange the scores from highest to lowest.
4. Display the organised results.

This is a basic example of an algorithm because it follows a defined sequence of instructions.

An AI learning algorithm can be more complex because it may adjust a model's internal parameters to improve its performance on a particular task.

### 3.3 Algorithm vs. Model

An algorithm and a model are related, but they are not the same.

| Concept | Meaning | Example |
|---|---|---|
| Algorithm | A procedure or method used to perform a task | A learning method that adjusts model parameters |
| Model | A system that has been developed or configured to produce outputs from inputs | A trained model that predicts whether an email is spam |

A useful way to remember the difference is that **the algorithm describes a method, while the model is the system produced or configured through that process**.

The exact relationship depends on the type of AI system being used.

---

## 4. AI Models

### 4.1 What Is an AI Model?

An **AI model** is a computational system that processes inputs and produces outputs according to patterns, rules, or relationships represented within it.

In machine learning, a model typically contains adjustable values called **parameters**. These parameters can be adjusted during training so that the model performs a task more effectively.

For example, an email classification model may use patterns in email text to estimate whether a message is spam.

Other AI models can perform tasks such as:

- Recognising objects in images.
- Predicting product demand.
- Translating languages.
- Generating text or images.

### 4.2 How Does a Model Use Information?

A model receives an input and processes it to produce an output.

For example:

- **Input:** An email message.
- **Model task:** Estimate whether the email is spam.
- **Output:** A prediction such as "spam" or "not spam".

The output depends on the model's design, the information it receives, and how it was developed or trained.

### 4.3 What Are Model Parameters?

**Parameters** are internal values that a model uses when processing information.

In many machine learning systems, training adjusts these values to improve the model's performance.

Beginners do not need to calculate these values manually. It is enough to understand that parameters help determine how a trained model responds to different inputs.

---

## 5. Training and Predictions

### 5.1 What Is Training?

**Training** is the process of developing a machine learning model by using data to adjust its internal parameters or otherwise improve its ability to perform a task.

During a typical supervised machine learning process, a model is given examples with known answers. Its outputs are compared with the expected answers, and a learning algorithm adjusts the model to reduce errors.

For example, a spam detection model may be trained using emails labelled as spam or not spam.

Training is not the same as manually programming every possible answer. Instead, the learning process helps the model identify patterns in the examples it receives.

### 5.2 What Is a Prediction?

A **prediction** is an output produced by a model when it processes an input.

A prediction does not always refer to a future event. It can also be a classification, an estimate, or another type of output.

Examples include:

- Predicting whether an email is spam.
- Estimating tomorrow's temperature.
- Classifying an image as containing a cat or a dog.
- Estimating the likelihood that a customer will purchase a product.

Predictions can be incorrect. Therefore, the output of an AI model should not automatically be treated as a confirmed fact.

### 5.3 Training vs. Prediction

| Training | Prediction |
|---|---|
| Uses data to develop or adjust a model | Uses a model to produce an output |
| May compare outputs with known answers | Usually processes a new input to generate a result |
| Aims to improve the model's performance | Applies what the model has learned or represented |
| Example: Learning from labelled emails | Example: Classifying a new email |

In many systems, training takes place before a model is used to make predictions. Some systems can also be updated or trained further after deployment.

---

## 6. How the Concepts Work Together

The concepts introduced in this section are connected. In a typical supervised machine learning workflow, data is used to train a model, and the trained model can then make predictions about new inputs.

### 6.1 Basic AI Workflow

```text
        Collect Data
             |
             v
       Prepare Data
             |
             v
    Choose a Learning Method
             |
             v
     Train the Model
             |
             v
      Evaluate the Model
             |
             v
     Use the Trained Model
             |
             v
      Make Predictions
```

**How to read the diagram:**

1. **Collect data:** Gather examples relevant to the task.
2. **Prepare data:** Organise the data and correct problems where possible.
3. **Choose a learning method:** Select an appropriate algorithm.
4. **Train the model:** Use the training data to develop or adjust the model.
5. **Evaluate the model:** Test how well it performs using suitable data.
6. **Use the trained model:** Provide new inputs to the model.
7. **Make predictions:** Receive outputs that can be checked and interpreted.

This diagram represents a simplified machine learning workflow. Not every AI system follows exactly these steps. For example, a rule-based system may use predefined instructions rather than learning from training data.

### 6.2 Key Relationships

| Concept | Main Role | Key Question |
|---|---|---|
| Data | Provides information and examples | What information is available? |
| Algorithm | Defines a method or procedure | How is the task performed or the model trained? |
| Model | Processes inputs to produce outputs | What system performs the task? |
| Training | Develops or adjusts the model | How is the model prepared to perform its task? |
| Prediction | Provides an output for an input | What result does the model produce? |

Understanding these relationships makes it easier to explain how many AI applications work.

---

## 7. Worked Example: An AI Spam Detector

### Scenario

An email service wants to develop an AI system that identifies spam messages.

The goal is to classify incoming emails as either **spam** or **not spam**.

### Step 1: Collect the Data

The developers collect example emails and label them.

| Email | Example | Correct label |
|---|---|---|
| A | "Your school timetable is attached." | Not spam |
| B | "Claim your free prize today!" | Spam |
| C | "The team meeting is at 3 PM." | Not spam |
| D | "Congratulations! You have won a reward!" | Spam |

These examples form a small dataset.

### Step 2: Select an Algorithm

The developers choose a machine learning algorithm that can learn patterns from labelled examples.

The algorithm provides the learning method used to develop the model.

### Step 3: Train the Model

The model is trained using the labelled emails. It may learn that certain words or combinations of features are associated with spam messages.

However, no single word guarantees that an email is spam. For example, a legitimate school email might also contain the word "prize" when discussing a competition.

### Step 4: Evaluate the Model

The developers test the model using additional emails that were not used for training.

This helps them determine whether the model can classify new messages correctly rather than simply memorising its training examples.

### Step 5: Make a Prediction

The email service receives a new message:

> "Congratulations! You have been selected for a special reward."

The trained model processes the message and produces a prediction:

**Predicted category: Spam**

This is a prediction, not a guarantee. The model may still make mistakes, so the email service should be evaluated and improved when necessary.

### What Have We Learned?

The spam detector demonstrates how the concepts work together:

- **Data:** The example emails and their labels.
- **Algorithm:** The method used to learn from the examples.
- **Model:** The trained system that classifies emails.
- **Training:** The process used to develop the model.
- **Prediction:** The model's classification of a new email.

This example illustrates a common supervised machine learning process in a simplified way.

---

## 8. Learner Activity: Match the AI Terms

### Instructions

Match each term in Column A with the correct definition in Column B.

| Column A: Term | Column B: Definition |
|---|---|
| 1. Data | A. The output produced by a model for a particular input |
| 2. Algorithm | B. The process of developing or adjusting a machine learning model using data |
| 3. Model | C. Information collected and used for a task |
| 4. Training | D. A method or set of steps for performing a task |
| 5. Prediction | E. A computational system that processes inputs and produces outputs |

Write your answers in the following format:

- 1 → ___
- 2 → ___
- 3 → ___
- 4 → ___
- 5 → ___

### Application Question

A student wants to create a simple AI system that predicts whether a photograph contains a cat or a dog.

Answer the following questions:

1. What type of data could the student collect?
2. What is the purpose of the algorithm?
3. What happens during training?
4. What would the model's prediction look like when a new photograph is provided?
5. Why should the student test the model using photographs that were not used during training?

---

## 9. Answers and Expected Outcomes

### 9.1 Matching Activity Answer Key

| Question | Correct Answer | Explanation |
|---|---|---|
| 1. Data | C | Data consists of information collected for a task. |
| 2. Algorithm | D | An algorithm describes a method or sequence of steps. |
| 3. Model | E | A model processes inputs to produce outputs. |
| 4. Training | B | Training develops or adjusts a machine learning model. |
| 5. Prediction | A | A prediction is the output produced for an input. |

### 9.2 Application Question: Expected Answers

**1. What type of data could the student collect?**

The student could collect photographs of cats and dogs, with each photograph labelled with the correct animal category.

**2. What is the purpose of the algorithm?**

The algorithm provides a method for learning patterns from the labelled photographs and developing the model.

**3. What happens during training?**

The model uses the training examples to learn patterns that may help distinguish cats from dogs.

**4. What would the model's prediction look like?**

The model might output "cat" or "dog" for a new photograph. It could also provide scores or probabilities for the categories, depending on how the system is designed.

**5. Why should the student test the model using photographs that were not used during training?**

Testing with separate photographs helps determine whether the model can recognise patterns in new examples. It also helps reveal errors and problems with generalisation.

---

## 10. Key Takeaways

- **Data** provides the information used by an AI system.
- **Algorithms** describe methods for performing tasks or learning from data.
- **Models** process inputs and produce outputs.
- **Training** develops or adjusts a machine learning model.
- **Predictions** are outputs that a model produces for particular inputs.
- These concepts are connected in many machine learning workflows.
- AI predictions can be wrong and should be evaluated using appropriate evidence and testing.

The most important idea is that an AI system does not automatically produce correct answers. Understanding its data, learning method, model, and outputs helps us evaluate what it can and cannot do.

---

## 11. References

The following resources provide further explanations of AI and machine learning concepts.

1. Google for Developers. *Machine Learning Crash Course.*
   https://developers.google.com/machine-learning/crash-course

2. IBM. *What Is Artificial Intelligence (AI)?*
   https://www.ibm.com/think/topics/artificial-intelligence

3. National Institute of Standards and Technology (NIST). *Artificial Intelligence.*
   https://www.nist.gov/artificial-intelligence

These resources should be consulted when reviewing the material and developing further examples. The explanations in this section have been simplified for beginner learners.
