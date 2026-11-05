# 8. Using What We Learned About AI

## Learning Objectives

By the end of this section, you will be able to:

1.  Explain the key ideas from Sections 1--7 in your own words and match
    them to correct definitions.
2.  Explain why an AI answer can sound confident and still be wrong,
    biased, or unsafe to use.
3.  Apply a four-question check to an AI answer and decide whether to
    accept, verify, revise, or reject it.
4.  Make responsible choices about AI use in everyday situations such as
    school, health, work, and creative projects.
5.  Distinguish AI-based systems from ordinary rule-based automation.

------------------------------------------------------------------------

## 8.1 Review: The Big Ideas in Plain Language

You have now seen what AI is, how it works, where it is used, and where
it can go wrong. Here is a quick recap. New or technical words appear in
**bold** with a short definition the first time they are used.

  -----------------------------------------------------------------------
  Section                 The idea in one or two  Everyday example
                          sentences               
  ----------------------- ----------------------- -----------------------
  1\. Introduction to AI  **Artificial            Voice assistants, spam
                          intelligence (AI)**     filters, map apps
                          means computer systems  
                          designed to do tasks    
                          that usually need human 
                          thinking, such as       
                          understanding speech,   
                          recognizing images, or  
                          making recommendations. 
                          The term appeared in    
                          the title of a 1955     
                          research proposal for a 
                          summer workshop held at 
                          Dartmouth College in    
                          1956 (McCarthy et al.,  
                          2006).                  

  2\. Basic AI Concepts   **Data** is the         A photo app learns from
                          information a system    many labeled pictures,
                          learns from. An         then predicts "this is
                          **algorithm** is a      a cat" for a new photo.
                          step-by-step set of     
                          instructions a computer 
                          follows. **Training**   
                          is showing an algorithm 
                          many examples so it can 
                          find patterns. The      
                          result is a **model**:  
                          the learned system used 
                          to make a               
                          **prediction**, which   
                          is its best estimate    
                          about something new.    

  3\. Different           **Symbolic AI** uses    A rule-based tax
  Approaches to AI        rules and symbols       checker (symbolic); a
                          written by people.      face-recognition system
                          **Connectionist AI**    (connectionist); a
                          learns patterns from    robot vacuum that turns
                          data using networks of  when it bumps a wall
                          simple connected units  (behavior-based).
                          (neural networks).      
                          **Behavior-based AI**   
                          builds intelligent      
                          behavior from simple    
                          actions that react to   
                          the environment.        

  4\. Generative AI       **Generative AI**       Asking a chatbot to
                          creates new content     draft an email or
                          such as text or images. summarize an article.
                          A **large language      
                          model (LLM)** is a      
                          large AI model trained  
                          on text to generate     
                          language. A **prompt**  
                          is the instruction or   
                          question you give to    
                          the tool.               

  5\. Applications of AI  AI is used in           Tutoring tools, medical
                          education, healthcare,  image support, customer
                          business, science, and  service, research
                          creative work, usually  analysis, design.
                          to assist people rather 
                          than replace them.      

  6\. Limitations and     AI makes errors. A      A chatbot invents a
  Risks                   **hallucination** is an book title; a tool
                          AI output that sounds   treats one group less
                          fluent and confident    fairly; a user pastes a
                          but is false or made    customer's phone number
                          up; NIST uses the term  into a public tool.
                          *confabulation* for a   
                          related generative-AI   
                          risk (Autio et al.,     
                          2024). **Bias** is a    
                          pattern of unfair or    
                          skewed results, often   
                          linked to skewed data   
                          or assumptions.         
                          **Privacy** risks arise 
                          when **personal data**  
                          (information that       
                          identifies a person) is 
                          shared or revealed.     

  7\. Responsible Use of  Use AI with             Checking a fact before
  AI                      **verification**        sharing it; telling
                          (checking claims        your instructor how you
                          against trusted         used AI.
                          sources), privacy       
                          protection,             
                          **transparency** (being 
                          open about when and how 
                          you used AI),           
                          **academic integrity**  
                          (doing honest work and  
                          giving credit), and     
                          **human judgment**      
                          (people stay            
                          responsible for         
                          decisions). UNESCO's    
                          global ethics           
                          recommendation also     
                          stresses human          
                          oversight (UNESCO,      
                          2021).                  
  -----------------------------------------------------------------------

> **Quick self-check before moving on:** Can you explain "model" and
> "hallucination" to a friend without looking at the table? If not,
> re-read the rows for Sections 2 and 6.

### 8.1.1 AI vs. Ordinary Rule-Based Automation

Not every system that behaves automatically is an AI system. Some
computer systems simply follow rules written by programmers, while AI
systems may learn patterns from data and use those patterns to make
predictions or generate outputs.

**Ordinary rule-based automation** follows predefined instructions. It
performs an action when a specified condition is met. It does not need
to learn from examples.

**AI-based systems** may use trained models to identify patterns, make
predictions, classify information, or generate new content.

  -----------------------------------------------------------------------
  Example                 How it works            Classification
  ----------------------- ----------------------- -----------------------
  A calculator            Follows programmed      Ordinary automation
                          mathematical            
                          operations.             

  An automatic light      Turns on when its       Ordinary automation
                          motion sensor detects   
                          movement according to   
                          predefined rules.       

  An email spam filter    Learns patterns from    AI
  using a trained model   examples of spam and    
                          legitimate emails to    
                          classify new emails.    

  A chatbot               Uses a language model   AI
                          to generate responses   
                          based on the input      
                          prompt.                 

  A traditional           Activates when the      Ordinary automation
  temperature alarm       temperature exceeds a   
                          fixed threshold.        
  -----------------------------------------------------------------------

**Important distinction:** Some AI approaches, such as Symbolic AI, also
use explicit rules. However, a simple program does not automatically
become AI just because it uses conditions or makes decisions.

The important question is how the system works: Does it simply follow
fixed instructions, or does it use AI techniques such as learning
patterns, reasoning, or generating outputs?

**Remember:** Automation describes a system performing tasks
automatically. AI describes particular computational approaches that
enable systems to perform tasks associated with intelligence. They can
overlap, but they are not the same thing.

------------------------------------------------------------------------

## 8.2 Core Skill: Evaluating an AI Answer

Sections 6 and 7 gave you the risks and the responsible-use habits. This
part turns them into one repeatable skill you can use every time an AI
tool gives you an answer.

### 8.2.1 Why an AI Answer Can Sound Right but Be Wrong

An LLM generates text by predicting which words are likely to come next,
based on patterns it learned during training. It does not automatically
verify every statement against a trusted source. Because of this, it can
produce smooth, confident sentences that are false. Researchers have
studied this problem, called hallucination, across many kinds of
text-generation systems (Ji et al., 2023), and NIST identifies
confabulation as a risk of generative AI (Autio et al., 2024).

Three practical consequences:

-   **Confidence is not evidence.** A confident tone does not mean the
    answer is correct.
-   **The way you ask shapes the answer.** If your prompt pushes toward
    a conclusion ("prove that..."), the tool may follow your lead
    instead of giving a balanced answer.
-   **The tool does not know what is private to you.** Information you
    type may be processed or stored according to the tool's policies, so
    decide carefully what to share.

### 8.2.2 The Four-Question Check

This check combines the Section 6 risks with the Section 7 habits. You
can use it alongside your own responsible-use checklist from Section 7.

  -----------------------------------------------------------------------
  \#                Question          What to look for  What to do
  ----------------- ----------------- ----------------- -----------------
  1                 **Is it true?**   Specific facts,   Check key claims
                                      dates, numbers,   in trusted
                                      names, and        sources such as
                                      sources; claims   official
                                      that are too      websites,
                                      certain           textbooks,
                                      ("always",        journals, or
                                      "proves",         reputable news
                                      "everyone         sources. Confirm
                                      agrees").         that any cited
                                                        source really
                                                        exists.

  2                 **Is it fair?**   One-sided         Ask for multiple
                                      statements,       perspectives,
                                      stereotypes,      rewrite a leading
                                      missing           prompt neutrally,
                                      viewpoints, or a  or reject the
                                      prompt that       output.
                                      pushes a          
                                      conclusion.       

  3                 **Is it safe to   Personal data in  Remove or
                    share?**          your prompt or in anonymize
                                      the answer, such  personal data;
                                      as names, ID      follow your
                                      numbers, contact  school's or
                                      details, or       workplace's rules
                                      health and        for AI tools.
                                      financial         
                                      details.          

  4                 **What will I     The stakes of the Choose
                    do?**             decision (low:    **accept**,
                                      brainstorming;    **verify more**,
                                      high: health,     **revise the
                                      money, grades, or prompt**, or
                                      legal matters).   **reject**. Use
                                                        human judgment,
                                                        and remember you
                                                        remain
                                                        responsible for
                                                        what you use or
                                                        share.
  -----------------------------------------------------------------------

### 8.2.3 The Four-Question Check as a Flow

``` mermaid
flowchart TD
    A["AI gives an answer"] --> B{"1. Is it true? Can I verify the facts and sources?"}
    B -- "No or cannot tell" --> V["Verify with a trusted source"]
    B -- "Yes" --> C{"2. Is it fair? Balanced, no stereotypes?"}
    V --> C
    C -- "No" --> R["Revise the prompt or reject the answer"]
    C -- "Yes" --> D{"3. Is it safe to share? Any personal data?"}
    D -- "No" --> P["Remove or protect the data"]
    D -- "Yes" --> E{"4. What will I do?"}
    P --> E
    R --> E
    E --> F["Accept, verify more, revise, or reject. You stay responsible."]
```

### 8.2.4 Worked Example: Checking a Flawed Answer, Step by Step

> *The answer below was written for teaching. It is deliberately
> flawed.*

**Prompt:** "Who invented the term 'artificial intelligence', and when?"

**AI answer (flawed):** "The term 'artificial intelligence' was invented
by Alan Turing in 1950 in his paper 'Computing Machinery and
Intelligence', which he presented at the Dartmouth conference. All
experts agree this paper founded the field."

**Step 1: Break the answer into checkable claims.**

  -----------------------------------------------------------------------
  Claim                               Type
  ----------------------------------- -----------------------------------
  A. Alan Turing invented the term    Fact (who)
  "artificial intelligence".          

  B. This happened in 1950.           Fact (when)

  C. The paper was presented at the   Fact (where)
  Dartmouth conference.               

  D. All experts agree the paper      Overgeneralization
  founded the field.                  
  -----------------------------------------------------------------------

**Step 2: Verify each claim against trusted sources (Question 1).**

  -----------------------------------------------------------------------
  Claim                   Verdict                 Evidence
  ----------------------- ----------------------- -----------------------
  A                       **Not supported**       The phrase "Artificial
                                                  Intelligence" appeared
                                                  in the title of a
                                                  proposal dated August
                                                  31, 1955, written by
                                                  John McCarthy, Marvin
                                                  Minsky, Nathaniel
                                                  Rochester, and Claude
                                                  Shannon, for a summer
                                                  study at Dartmouth
                                                  College (McCarthy et
                                                  al., 2006). John
                                                  McCarthy's biographical
                                                  memoir describes his
                                                  role in proposing the
                                                  name for the workshop
                                                  (National Academy of
                                                  Sciences, n.d.).

  B                       **Partly misleading**   1950 is correct for
                                                  Turing's paper, which
                                                  appeared in *Mind* in
                                                  October 1950 (Turing,
                                                  1950). The Dartmouth
                                                  proposal came in 1955
                                                  and the workshop took
                                                  place in 1956.

  C                       **False**               The paper was published
                                                  in a journal in 1950.
                                                  The Dartmouth workshop
                                                  took place in 1956, six
                                                  years later, so the
                                                  paper could not have
                                                  been presented there.
                                                  **A simple date check
                                                  exposes the error.**

  D                       **Overconfident**       Turing's paper is
                                                  widely regarded as a
                                                  landmark that asked
                                                  whether machines can
                                                  think and proposed the
                                                  "imitation game"
                                                  (Turing, 1950), but
                                                  "all experts agree" is
                                                  an unsupported
                                                  absolute.
  -----------------------------------------------------------------------

**Step 3: Fairness and privacy (Questions 2 and 3).** The answer is not
obviously stereotyped, and the prompt contains no personal data. The
main problem is accuracy and overconfidence.

**Step 4: Decide (Question 4).** This is a low-stakes question, but the
answer would spread a false fact if copied. Decision: **revise**. Ask
the tool for sources, then confirm them independently.

**Corrected summary the learner can safely use:**

"Alan Turing's 1950 paper 'Computing Machinery and Intelligence' asked
whether machines can think and is a landmark in the field. The phrase
'Artificial Intelligence' appeared in the 1955 proposal for the
Dartmouth summer workshop of 1956, written by McCarthy, Minsky,
Rochester, and Shannon."

**What this example shows:** The answer mixed true pieces (Turing, 1950,
Dartmouth) into a false story. That is why you check *each claim*, not
just the overall impression.

------------------------------------------------------------------------

## 8.3 Learner Activities

Complete the following activities using the concepts introduced in
Sections 1--7.

### General Instructions

Before beginning:

1.  Read the complete activity instructions.
2.  Review the relevant definitions and concepts from earlier sections
    when necessary.
3.  Answer each question using your own understanding.
4.  Provide explanations when requested instead of writing only a final
    decision.
5.  Do not include real personal information in any response.

**Submission Requirements:**

-   Activity 1: A list of 10 matching pairs.
-   Activity 2: A written evaluation containing five parts.
-   Activity 3: Four scenario responses, each containing 2--4 sentences.
-   Activity 4: A comparison table and a short explanation of AI versus
    ordinary automation.

**Responsible AI Reminder:** These activities do not require you to
submit personal information to an AI tool. If you choose to use an AI
tool for additional practice, do not enter real names, student
identification numbers, passwords, contact details, or other private
information. Follow your school's AI-use policies and independently
check information generated by an AI tool.

### Activity 1: Match the Terms

**Objective:** Demonstrate your understanding of the fundamental AI
terminology introduced in Sections 1--7.

**Instructions:**

1.  Read all 10 terms and definitions carefully.
2.  Match each numbered term with the correct letter.
3.  Use each definition only once.
4.  Write your answers in the format shown below.

**Expected output:** A list of 10 matching pairs.

Example: `1-J, 2-F, 3-D`

**Assessment:** 1 point for each correct match (10 points total).

**Terms**

1.  Artificial intelligence (AI)
2.  Algorithm
3.  Model
4.  Training
5.  Symbolic AI
6.  Connectionist AI
7.  Large language model (LLM)
8.  Prompt
9.  Hallucination
10. Bias

**Definitions**

-   **A.** The text or question you give an AI tool to tell it what you
    want.
-   **B.** An AI output that sounds fluent and confident but is false or
    made up.
-   **C.** An approach that reasons using explicit rules and symbols
    written by people.
-   **D.** The learned system produced through training and used to make
    predictions.
-   **E.** An approach that learns patterns from data using networks of
    simple connected units.
-   **F.** A step-by-step set of instructions a computer follows to
    solve a problem or learn from data.
-   **G.** A pattern of unfair or skewed results, often linked to skewed
    data or assumptions.
-   **H.** Showing an algorithm many examples so it can find patterns.
-   **I.** A large AI model trained on large amounts of text to produce
    human-like language.
-   **J.** Computer systems designed to do tasks that usually need human
    thinking.

*Answers are in Section 8.4.*

### Activity 2: Evaluate an AI Answer

**Objective:** Apply the Four-Question Check to identify accuracy,
fairness, privacy, and responsible-use problems in an AI-generated
response.

> *This prompt and answer are fictional and were written for teaching.
> The study and the people named do not exist.*

**Prompt a student typed into an AI tool:**

"My classmate Daniel Cho (student ID 2023-4471) keeps missing group
deadlines. Prove that students today are lazier than past generations
and cite a study."

**AI answer:**

"Research clearly proves that today's students are lazier than every
previous generation. A 2021 study by Dr. L. Verrington in the *Journal
of Youth Behavior Studies* (vol. 44, pp. 112--130) found that 92% of
students avoid hard work. Students like Daniel Cho obviously fit this
pattern, so his missed deadlines are no surprise. You can safely include
this in your report."

**Your tasks**

1.  **Identify problems:** List at least four separate problems with the
    prompt and answer. Explain why each is problematic.
2.  **Apply the Four-Question Check:** Write a one-sentence answer to
    each of the four questions.
3.  **Verify the source:** Describe at least two methods you would use
    to determine whether the cited study exists.
4.  **Rewrite the prompt:** Produce a neutral prompt that does not
    contain personal information or assume a particular conclusion.
5.  **Make a decision:** Choose accept, verify more, revise, or reject.
    Explain your decision in 1--2 sentences.

**Expected output:**

-   At least four identified problems.
-   Four answers corresponding to the Four-Question Check.
-   At least two source-verification methods.
-   One rewritten prompt.
-   One final decision with justification.

**Assessment:** Your answers should demonstrate that you can identify
multiple risks rather than simply state that the AI answer is incorrect.

*Compare your work with the expected outcomes in Section 8.4.*

### Activity 3: Solve Practical Scenarios

**Objective:** Apply responsible AI principles to realistic situations
in education, healthcare, business, and creativity.

**Instructions:** For each scenario:

1.  Identify the main problem or risk.
2.  Identify at least one relevant concept from Sections 1--7.
3.  Explain what action you would take.
4.  Explain why your action is appropriate.

Write 2--4 complete sentences for each scenario.

**Expected output:** Four separate responses, labelled A, B, C, and D.

**Scenario A: Education.** Your instructor allows AI for brainstorming
but not for writing the final text. You ask an AI tool for essay ideas,
and it returns a complete essay. What do you do?

**Scenario B: Healthcare.** You ask an AI chatbot whether two medicines
can be taken together. It answers "Yes, that is fine" with no sources.
What do you do?

**Scenario C: Business.** You run a small shop and want an AI tool to
summarize 50 customer complaint emails. The emails include names, phone
numbers, and home addresses. What do you do before using the tool?

**Scenario D: Creativity.** You use an AI image generator to make a
poster for a school event. The image looks great at first glance. What
do you check, and what do you tell others about how it was made?

**Assessment:** Each response should contain an appropriate action, a
relevant AI concept, and a reasonable explanation.

### Activity 4: AI or Ordinary Automation?

**Objective:** Distinguish AI-based systems from ordinary rule-based
automation and explain how their operating methods differ.

**Instructions:**

Examine the following examples:

1.  A calculator that performs mathematical operations using programmed
    instructions.
2.  An email filter that uses a trained model to identify spam based on
    patterns learned from previous examples.
3.  A motion-activated light that switches on when movement is detected.
4.  A chatbot that generates responses using a large language model.
5.  A traditional temperature alarm that activates when the temperature
    exceeds a fixed value.

For each example:

-   Classify it as AI or ordinary rule-based automation.
-   Explain briefly how it operates.
-   Identify whether it uses learned patterns or predefined
    instructions.

**Expected output:** A completed table containing five examples, their
classifications, and explanations.

  -----------------------------------------------------------------------
  System                  Classification          Explanation
  ----------------------- ----------------------- -----------------------
  Calculator              Ordinary automation     Performs programmed
                                                  mathematical
                                                  operations.

  Trained spam filter     AI                      Uses patterns learned
                                                  from training examples.

  Motion-activated light  Ordinary automation     Follows a predefined
                                                  condition to activate.

  LLM chatbot             AI                      Generates responses
                                                  using a trained
                                                  language model.

  Temperature alarm       Ordinary automation     Activates when a fixed
                                                  threshold is reached.
  -----------------------------------------------------------------------

**Follow-up question:** In 2--3 sentences, explain why not every
automated system should be considered AI.

**Assessment:** 1 point for each correct classification and 1 point for
each reasonable explanation (10 points total). The follow-up question is
used to assess deeper understanding.

**Important:** These examples are simplified for learning purposes. Some
real-world systems combine AI techniques with conventional automation.

------------------------------------------------------------------------

## 8.4 Answers and Expected Outcomes

### Activity 1 Answer Key

  Term                   Definition
  ---------------------- ------------
  1\. AI                 J
  2\. Algorithm          F
  3\. Model              D
  4\. Training           H
  5\. Symbolic AI        C
  6\. Connectionist AI   E
  7\. LLM                I
  8\. Prompt             A
  9\. Hallucination      B
  10\. Bias              G

**Check for understanding:** If a learner mixes up *algorithm* (F) and
*model* (D), remind them that an algorithm is a method or set of
instructions, while a model is the learned system produced through
training. If they mix up *symbolic* and *connectionist* AI, point to how
knowledge is represented: people write explicit rules in symbolic AI,
while connectionist AI learns patterns through networks of connected
units.

### Activity 2 Expected Outcomes

**1. Problems (any four or more earn full credit):**

-   **Privacy:** The prompt shares a classmate's name and student ID,
    which are personal data about a third party. The answer then repeats
    the name and judges the classmate.
-   **Leading prompt:** "Prove that..." pushes the tool toward one
    conclusion instead of asking what the evidence shows.
-   **Possibly invented source:** The citation looks precise but cannot
    be trusted until verified. This may be a hallucination.
-   **Overconfidence and absolutes:** "Clearly proves", "every previous
    generation", and "92%" are too certain and unsupported.
-   **Stereotype and unfairness:** It generalizes about a whole
    generation and labels a person based on one behavior.
-   **Encourages unverified use:** "You can safely include this" invites
    copying into a report without checking, which risks academic
    integrity problems.

**2. Four-Question Check (model answers):**

1.  **Is it true?** Not demonstrated; the claims are absolute and the
    study is unverified.
2.  **Is it fair?** No; it stereotypes a generation and an individual.
3.  **Is it safe to share?** No; a name and student ID were entered and
    repeated.
4.  **What will I do?** Reject the answer and revise the prompt without
    personal information.

**3. Checking the study:** Search for the journal and article title on
the journal's own website; search a library database or Google Scholar
by title and author; check that the volume and page numbers match; or
ask a librarian. If no trustworthy record exists, treat the citation as
unverified and do not use it as evidence.

**4. Model rewritten prompt:**

"What does research say about whether student work habits have changed
over time? Please include evidence on different sides and provide
sources I can check."

This version removes personal information and asks an open, neutral
question.

**5. Decision:** Reject the original answer, then revise the prompt and
verify any sources the tool returns before using them.

### Activity 3 Expected Outcomes

  -----------------------------------------------------------------------
  Scenario                Strong response         Ideas used
                          includes                
  ----------------------- ----------------------- -----------------------
  **A: Education**        Use the AI output only  Academic integrity,
                          in the ways the         transparency, human
                          instructor allows, such judgment
                          as brainstorming. Write 
                          the essay in your own   
                          words, do not submit    
                          the AI-written essay as 
                          your own, disclose AI   
                          use according to course 
                          rules, check any facts  
                          used, and ask the       
                          instructor if the rules 
                          are unclear.            

  **B: Healthcare**       Do not rely on the      Reliability,
                          answer. Check medicine  hallucination risk,
                          information with a      human judgment, high
                          pharmacist or doctor,   stakes
                          because an incorrect    
                          answer could cause      
                          harm. AI can help       
                          prepare questions to    
                          ask, but it should not  
                          make the decision. For  
                          urgent concerns,        
                          contact an appropriate  
                          medical service.        

  **C: Business**         Remove or anonymize     Privacy protection,
                          names, phone numbers,   verification
                          and addresses before    
                          using a tool, or use    
                          only a tool approved    
                          for customer data.      
                          Follow the business's   
                          privacy rules. After    
                          the summary is          
                          produced, spot-check it 
                          against the original    
                          emails.                 

  **D: Creativity**       Check the image for     Verification, bias,
                          visible mistakes, such  transparency
                          as garbled text or      
                          incorrect details;      
                          consider whether people 
                          are represented fairly; 
                          and check the tool's    
                          terms of use. Be open   
                          that AI helped create   
                          it, especially if the   
                          school or audience      
                          expects disclosure.     
  -----------------------------------------------------------------------

### Activity 4 Expected Outcomes

**1. System Classification**

  -----------------------------------------------------------------------
  System                  Correct classification  Explanation
  ----------------------- ----------------------- -----------------------
  Calculator              Ordinary automation     Executes mathematical
                                                  operations using
                                                  predefined
                                                  instructions.

  Trained spam filter     AI                      Uses patterns learned
                                                  from training examples
                                                  to classify emails.

  Motion-activated light  Ordinary automation     Responds to a
                                                  predefined condition
                                                  when movement is
                                                  detected.

  LLM chatbot             AI                      Uses a trained language
                                                  model to generate
                                                  responses based on
                                                  prompts.

  Temperature alarm       Ordinary automation     Activates when a
                                                  measured temperature
                                                  reaches a predefined
                                                  threshold.
  -----------------------------------------------------------------------

**2. Follow-up question:**

A strong response should explain that ordinary automation follows
predefined instructions, while AI systems may use techniques such as
learning patterns from data, making predictions, or generating content.
The presence of automatic decision-making alone does not mean a system
uses AI.

**Common misunderstanding:** A system does not become AI simply because
it can respond to inputs or perform tasks automatically. Learners should
examine the underlying method used by the system rather than its
appearance or function.

**Marking guidance:**

-   Correct classification: 1 point per example (5 points).
-   Reasonable explanation: 1 point per example (5 points).
-   Follow-up explanation: assess conceptual accuracy and clarity.

Total: 10 points for the table, with the follow-up question used to
assess deeper understanding.

### Self-Assessment Rubric (For Learners and Teachers)

  -----------------------------------------------------------------------
  Level             Understanding     Application       Responsible AI
                                                        Practice
  ----------------- ----------------- ----------------- -----------------
  **Secure**        Correctly         Completes         Identifies
                    explains key AI   activities        privacy,
                    concepts and      accurately and    fairness, and
                    terminology.      provides clear    reliability risks
                                      reasoning.        and proposes
                                                        appropriate
                                                        actions.

  **Developing**    Understands most  Completes most    Recognizes some
                    concepts but      activities but    risks but needs
                    occasionally      provides limited  guidance in
                    confuses related  explanations or   deciding how to
                    terms.            misses some       respond.
                                      details.          

  **Needs Review**  Frequently        Provides          Does not
                    confuses          incomplete        consistently
                    fundamental AI    answers or makes  recognize
                    concepts.         decisions without privacy,
                                      supporting        verification, or
                                      explanations.     fairness
                                                        concerns.
  -----------------------------------------------------------------------

**Recommended next steps:**

-   **Secure:** Proceed to the next learning module and apply the
    concepts to more complex examples.
-   **Developing:** Review the relevant sections and retry the
    activities where explanations were incomplete.
-   **Needs Review:** Revisit Sections 2, 3, 6, and 7 before attempting
    the activities again.

------------------------------------------------------------------------

## 8.5 Wrap-Up and Reflection

### Three Takeaways

1.  AI can be useful and still be wrong, so check claims instead of
    trusting the tone.
2.  Ask neutral questions and protect personal data.
3.  You are responsible for what you accept, share, or submit.

### Responsible AI Checklist

Before using an AI tool in your daily activities, ask yourself:

-   [ ] **Accuracy:** Have I checked important information against
    reliable sources?
-   [ ] **Fairness:** Could the output contain stereotypes, bias, or
    unfair assumptions?
-   [ ] **Privacy:** Have I avoided sharing personal or confidential
    information?
-   [ ] **Transparency:** Have I disclosed AI assistance when required?
-   [ ] **Academic Integrity:** Does my use of AI follow my instructor's
    rules?
-   [ ] **Human Judgment:** Have I made the final decision myself rather
    than blindly accepting the AI output?

**Remember:** AI is a tool to support human thinking, not a replacement
for personal responsibility. Always consider the consequences before
accepting, using, or sharing AI-generated information.

### Reflection Prompt

Write 3--5 sentences. Think of one way you use, or could use, AI this
week. Which question from the Four-Question Check would matter most
there, and what will you do differently?

------------------------------------------------------------------------

## References

Autio, C., Schwartz, R., Dunietz, J., Jain, S., Stanley, M., Tabassi,
E., Hall, P., & Roberts, K. (2024). *Artificial Intelligence Risk
Management Framework: Generative Artificial Intelligence Profile* (NIST
AI 600-1). National Institute of Standards and Technology.
https://doi.org/10.6028/NIST.AI.600-1

Ji, Z., Lee, N., Frieske, R., Yu, T., Su, D., Xu, Y., Ishii, E., Bang,
Y., Chen, D., Dai, W., Chan, H. S., Madotto, A., & Fung, P. (2023).
Survey of hallucination in natural language generation. *ACM Computing
Surveys, 55*(12), Article 248, 1--38. https://doi.org/10.1145/3571730

McCarthy, J., Minsky, M. L., Rochester, N., & Shannon, C. E. (2006). A
proposal for the Dartmouth Summer Research Project on Artificial
Intelligence, August 31, 1955. *AI Magazine, 27*(4), 12--14.
https://doi.org/10.1609/aimag.v27i4.1904

National Academy of Sciences. (n.d.). *John McCarthy* \[Biographical
memoir\].
https://www.nasonline.org/wp-content/uploads/2024/06/mccarthy-john.pdf

Turing, A. M. (1950). Computing machinery and intelligence. *Mind,
59*(236), 433--460. https://doi.org/10.1093/mind/LIX.236.433

UNESCO. (2021). *Recommendation on the Ethics of Artificial
Intelligence*. https://unesdoc.unesco.org/ark:/48223/pf0000381137

------------------------------------------------------------------------

**Note on original material:** The prompts, flawed AI answers, fictional
study, scenarios, activities, and the Four-Question Check are teaching
materials developed for this module. The Four-Question Check summarizes
the risks discussed in Section 6 and the responsible-use habits
discussed in Section 7, informed by the NIST and UNESCO documents above.
Keep the definitions in this section consistent with the wording used in
the corresponding Sections 1--7 of the study guide.

**Pre-submission check:** Test all reference links, confirm that any
external tools or supporting files required elsewhere in the module are
accessible, and preview the Markdown rendering in the team's GitHub
repository. The activities in this section are self-contained and do not
require an external dataset or AI account.
