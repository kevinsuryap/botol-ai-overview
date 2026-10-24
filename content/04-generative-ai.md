# Lesson 3: Understanding Generative AI

## 1. Overview

Generative Artificial Intelligence (Generative AI or GenAI) is a type of AI that can create new content, such as text, images, music, audio, videos, and computer code. It is used in education, creative work, software development, and many other fields.

Unlike systems designed mainly to classify information or make predictions, Generative AI focuses on producing content based on patterns learned during training. However, its outputs are not always accurate, original in every respect, or suitable for the intended purpose.

This lesson introduces the basic concepts behind Generative AI, explains how it works, explores its applications, and teaches learners how to write effective prompts.

### Learning Objectives

By the end of this lesson, learners should be able to:

- Define Generative AI and explain how it differs from other AI applications.
- Describe the basic process used to generate content.
- Identify common types of Generative AI tools and their applications.
- Apply basic prompt engineering principles.
- Recognise the limitations of generated content and explain why human review is important.

### Prerequisites

Learners should have a basic understanding of Artificial Intelligence and the differences between common AI approaches.

## 2. What Is Generative AI?

Generative AI is a category of AI designed to produce new content by learning patterns and relationships from training data.

Depending on the model, Generative AI can produce:

- **Text:** Stories, summaries, explanations, and drafts.
- **Images:** Illustrations, designs, and visual concepts.
- **Audio and music:** Speech, sound effects, and musical compositions.
- **Video:** Short video clips and animated scenes.
- **Computer code:** Code examples, explanations, and suggested corrections.

For example, a student could ask a generative AI assistant to draft a presentation outline about renewable energy. The assistant generates a response based on the prompt and patterns learned during training.

Generative AI does not simply retrieve a complete answer that someone has previously written. Many generative models construct outputs using learned patterns. Nevertheless, some applications also use search engines, databases, or supplied documents to provide additional information.

### Generative AI vs. Other AI Applications

| Feature | Analytical or Predictive AI | Generative AI |
|---|---|---|
| Main purpose | Classifies information or predicts outcomes | Produces new content |
| Example task | Identifying unwanted emails | Drafting an email |
| Typical output | A category, score, or prediction | Text, images, audio, or other content |
| Important limitation | May classify or predict incorrectly | May generate inaccurate or misleading content |

These categories can overlap. A single application may analyse information and then use Generative AI to produce a written explanation of its findings.

## 3. How Does Generative AI Work?

Generative AI models learn patterns from training data and use those patterns to produce outputs. The exact process depends on the type of model, but a simplified explanation involves three stages.

### Stage 1: Training

During training, a model processes examples from a dataset and adjusts its internal parameters to learn patterns and relationships.

For example, a language model may learn relationships between words, sentence structures, and different ways of expressing ideas.

The model does not necessarily store or understand every example in the same way a human would. Its behaviour depends on its architecture, training process, and data.

### Stage 2: Receiving a Prompt

A user provides an instruction or input, known as a *prompt*. The prompt tells the model what kind of output is requested.

For example:

> Write a short paragraph explaining how solar panels generate electricity for a beginner.

The model uses this input to guide the response it generates.

### Stage 3: Generating Content

The model produces an output using the patterns it learned during training. Different types of models generate content in different ways.

Two important examples are:

- **Large Language Models (LLMs):** Models that process and generate language, often by predicting tokens based on the surrounding context.
- **Diffusion models:** Models commonly used for image generation that learn to produce data by reversing a process that gradually adds noise during training.

A token is a unit of text processed by a language model. It may be a word, part of a word, punctuation, or another piece of text.

**Important:** Generative AI does not think or understand the world in exactly the same way humans do. Its outputs can sound convincing while still containing mistakes.

## 4. Types of Generative AI Tools and Their Applications

Generative AI tools are designed for different tasks. Some focus on one type of content, while others support several types.

| Type | Common Applications | Example |
|---|---|---|
| Text generation | Drafting, summarising, explaining, and brainstorming | Creating a first draft of a report |
| Image generation | Illustrations, design concepts, and visual ideas | Creating a concept image for a poster |
| Audio generation | Speech synthesis, voice output, and sound creation | Generating spoken narration |
| Video generation | Creating or modifying video clips | Producing a short animated scene |
| Code generation | Writing code examples and explaining programming concepts | Drafting a simple calculator program |

### Real-World Applications

**Education:** Learners can request explanations at different levels of difficulty, generate practice questions, or receive feedback on a draft.

**Creative work:** Artists and designers can explore visual ideas, while writers and musicians can use AI to brainstorm possibilities.

**Business:** Organisations may use Generative AI to draft communications, summarise documents, and prepare initial versions of reports.

**Software development:** Developers can request code examples, explanations of errors, and suggestions for improving their programs.

**Research and analysis:** Generative AI can help summarise supplied information and organise ideas, but important facts and conclusions must still be checked.

These examples illustrate possible uses rather than guarantees of accuracy. The suitability of a tool depends on the task, the quality of its output, and how people review the results.

## 5. Basic Prompt Engineering

Prompt engineering is the practice of writing and refining instructions to guide an AI model toward a useful output.

A prompt does not need to follow a complicated formula. However, including the right details can make the intended task clearer.

### Principles of Effective Prompting

#### A. Be Clear and Specific

State exactly what you want the AI to do.

**Less effective prompt:**

> Explain AI.

**Improved prompt:**

> Explain Generative AI in three short paragraphs using simple English for a beginner.

The improved prompt specifies the topic, length, language level, and format.

#### B. Provide Relevant Context

Explain the background information that may affect the answer.

**Example:**

> I am preparing a school presentation about renewable energy for beginners. Explain how solar panels work without using complicated scientific terms.

The context helps the model tailor its response to the intended audience.

#### C. Specify the Output Format

Tell the AI how the response should be organised.

Possible instructions include:

- Use bullet points.
- Create a comparison table.
- Write one paragraph of approximately 100 words.
- Give three examples.
- Present the explanation as numbered steps.

#### D. Set Boundaries

State any important requirements or restrictions.

**Example:**

> Summarise the supplied article in five bullet points. Use only information from the article and identify any questions the article does not answer.

This helps clarify what the AI should and should not include.

#### E. Review and Refine

The first response may not fully meet your needs. Read the output and request a specific improvement.

For example:

1. Initial prompt: "Explain Generative AI."
2. Follow-up: "Use simpler language and include one everyday example."
3. Final check: "Check whether the explanation distinguishes Generative AI from ordinary classification systems."

Prompting is an iterative process. A clearer prompt may improve relevance, but it cannot guarantee a correct answer.

### Worked Example: Improving a Prompt

Suppose a student needs an explanation of Generative AI for a classroom presentation.

**Initial prompt:**

> Write about Generative AI.

This prompt is broad. It does not specify the audience, length, or required information.

**Improved prompt:**

> Explain Generative AI to a beginner in approximately 120 words. Include a simple definition, two everyday applications, and one limitation. Use clear English and organise the answer into short paragraphs.

The improved prompt gives the model a clearer goal and specific output requirements.

**Why is the improved prompt more useful?**

- It identifies the audience.
- It defines the expected length.
- It specifies the content to include.
- It requests a clear format.

The generated answer should still be reviewed for accuracy and relevance.

## 6. Limitations and Responsible Use

Generative AI can be useful, but it also has limitations that users should understand.

### Inaccurate Information

Generative AI may produce statements that sound correct but are false. Important information should be checked against reliable sources.

### Bias

If a model's training data contains biases, its outputs may reflect or reproduce them. Users should consider whether an answer is fair and appropriate.

### Privacy

Users should avoid entering passwords, private personal details, confidential school records, or other sensitive information into AI tools unless the tool and its approved use explicitly permit it.

### Copyright and Ownership

Generated content may raise questions about copyright, attribution, and permitted use. Users should follow applicable laws, school requirements, and the terms of the tool they are using.

### Overreliance

Depending entirely on AI can reduce opportunities to practise independent thinking and problem-solving. AI is best used as a support tool rather than an unquestioned authority.

### Human Review

Before using generated content, users should ask:

1. Is the information accurate?
2. Can important claims be verified?
3. Does the content answer the original question?
4. Is the content appropriate for the intended audience?
5. Does it follow relevant privacy, attribution, and academic-integrity requirements?

## 7. Learner Activity: Write a Better Prompt

### Part A: Identify the Problem

Consider this prompt:

> Make me something about climate change.

Answer the following questions:

1. What information is missing from the prompt?
2. Who is the intended audience?
3. What type of content should the AI create?
4. How could the prompt be made more specific?

### Part B: Rewrite the Prompt

Rewrite the original prompt so that it includes:

- A clear task.
- An intended audience.
- A required output format.
- At least one content requirement.

### Part C: Evaluate the Result

Imagine that the AI generates a response containing three statistics but does not provide any sources.

Discuss:

1. Should the statistics be accepted without checking?
2. How could you ask the AI to make the response more useful?
3. What steps could you take to verify the statistics?

## 8. Suggested Answers

### Part A

1. The prompt does not explain the audience, content type, length, or specific goal.
2. The intended audience is not stated.
3. The required output could be an essay, summary, presentation, poster, or another format.
4. The prompt should specify the task, audience, format, and required content.

### Part B

One possible improved prompt is:

> Create a five-slide presentation outline about climate change for secondary school students. Explain two causes, two impacts, and three possible ways to reduce greenhouse gas emissions. Use simple English and include suggestions for reliable sources to verify the main facts.

Other answers are acceptable if they make the task more specific.

### Part C

1. No. Statistics should be checked against reliable sources.
2. Ask the AI to identify sources for the claims and clearly distinguish verified information from claims that still need checking.
3. Consult trustworthy scientific organisations or official reports and confirm that the sources actually support the statistics.

The activity demonstrates that an effective prompt is only one part of using Generative AI responsibly. Users must also evaluate the output.

## 9. Discussion and Reflection

1. How is Generative AI different from an AI system that classifies emails?
2. Why does a generative model need training before it can produce useful content?
3. How can a clearer prompt improve the relevance of an AI-generated response?
4. What are two possible benefits and two limitations of Generative AI in education?
5. Why should users verify important information produced by AI?
6. In what situations should a person avoid entering information into an AI tool?
7. How can students use Generative AI to support learning without relying on it to do all their work?

## 10. Key Takeaways

- Generative AI creates content such as text, images, audio, video, and code.
- Generative models learn patterns from training data and use them to produce outputs.
- Large Language Models generate language, while diffusion models are commonly used for image generation.
- Prompt engineering involves writing and refining instructions to guide an AI model.
- Clear goals, relevant context, output requirements, and boundaries can improve the usefulness of a response.
- Generative AI can produce inaccurate or biased information, so important outputs should be checked.
- Responsible use includes protecting private information, following academic requirements, and applying independent judgement.

## 11. Further Reading

- OpenAI — [Prompt Engineering Best Practices](https://help.openai.com/en/articles/10032626)
- Google AI for Developers — [Prompting Strategies](https://ai.google.dev/gemini-api/docs/prompting-strategies)
- NIST — [Artificial Intelligence](https://www.nist.gov/artificial-intelligence)

These resources provide further information about prompting and AI. Follow your course's citation requirements when incorporating information from external sources.

## 12. Development Status

| Item | Status |
|---|---|
| Learning objectives and prerequisites | Drafted — review required |
| Generative AI concepts and working process | Drafted — review required |
| Tools and real-world applications | Drafted — review required |
| Prompt engineering examples | Drafted — review required |
| Learner activity and suggested answers | Drafted — review required |
| Responsible-use guidance | Drafted — review required |
| References and citations | Added — citation format to be checked |
| Final review | Pending |
