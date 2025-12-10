# 🧪 Hands-On Lab: Structured, Reasoned & Action-Oriented Prompting

---

## Objective

Practice advanced prompting techniques that help LLMs handle complex tasks reliably, including:
- Example-driven and few-shot prompting  
- Step-by-step reasoning (Chain-of-Thought)  
- Reasoning combined with actions (ReAct)  

---

## Prerequisites

- Access to an LLM (ChatGPT / Claude / Gemini)
- Basic familiarity with prompts and persona patterns

---

## Part 1: Structured & Example-Driven Prompting

### Concept Recap

- LLMs learn patterns from text  
- Examples show the model:
  - Task expectations  
  - Output format  
  - Reasoning style  
- “Show → Then Ask” is more effective than instructions alone  

---

### Exercise 1: Instruction Only vs Example-Driven

#### Prompt A (Instruction Only)

Classify the sentiment of the following text as  
Positive, Negative, or Neutral.

Text:  
"The product works fine, but the battery life is disappointing."

---

#### Prompt B (Example-Driven)

Classify the sentiment of the text.

Example 1:  
Text: "I love this phone. The camera is amazing."  
Sentiment: Positive  

Example 2:  
Text: "The service was slow and unhelpful."  
Sentiment: Negative  

Now classify the following text:  
Text: "The product works fine, but the battery life is disappointing."  
Sentiment:

---

### ✅ Observe

- Accuracy  
- Confidence in classification  
- Output consistency  

### ✅ Key Insight

Examples remove ambiguity and anchor expectations.

---

## Part 2: Few-Shot Prompting

### Why Few-Shot Works

- Reinforces pattern recognition  
- Reduces reliance on vague task descriptions  
- Improves format and reasoning alignment  

---

### Exercise 2: Few-Shot Content Transformation

#### Prompt

Rewrite sentences to be more professional.

Example 1:  
Input: "This feature is kinda slow."  
Output: "This feature performs slower than expected."

Example 2:  
Input: "The app is broken after the update."  
Output: "The application experienced issues following the update."

Now rewrite:  
Input: "The UI looks bad and confuses users."  
Output:

---

### ✅ Try

- Adding a third example  
- Changing tone (formal → empathetic)  

---

### Exercise 3: Few-Shot with Intermediate Reasoning

Solve the problem by showing reasoning.

Example 1:  
Question: If a pencil costs $1, how much do 3 pencils cost?  
Reasoning: One pencil costs $1, so three pencils cost 3 × 1 = 3.  
Answer: $3  

Example 2:  
Question: A shirt costs $20 and has a 25% discount. What is the final price?  
Reasoning: 25% of 20 is 5. Subtract 5 from 20.  
Answer: $15  

Now solve:  
Question: A bag costs $50 and has a 10% discount.  
Reasoning:  
Answer:

---

### ✅ Observe

- Logical structure  
- Reduction in calculation errors  

---

### Tips for Writing Good Few-Shot Examples

- Keep examples correct and realistic  
- Maintain consistent format  
- Order examples from simple → complex  
- Avoid edge cases unless intentional  
- Match examples exactly to the final task  

---

## Part 3: Chain-of-Thought (CoT) Prompting

### Concept Recap

- CoT asks the model to think step by step  
- Improves performance on:
  - Math  
  - Logic  
  - Planning  
- Makes reasoning inspectable  

---

### Exercise 4: No CoT vs CoT

#### Prompt A (No CoT)

If a train travels 60 km per hour for 2.5 hours,  
how far does it travel?

#### Prompt B (With CoT)

If a train travels 60 km per hour for 2.5 hours,  
calculate the distance. Think step by step.

---

### ✅ Compare

- Accuracy  
- Explanation clarity  

---

### Exercise 5: Safe & Controlled CoT

#### Uncontrolled CoT

Solve the problem and explain everything in detail.

#### Controlled CoT

Solve the problem.  
Provide a short, numbered reasoning (max 3 steps),  
then give the final answer.

---

### ✅ Teaching Point

- More reasoning does not always mean better reasoning  
- Structure keeps reasoning reliable  

---

### Exercise 6: CoT for Planning

Plan a one-day technical workshop for beginners.  
Think step by step about:
1. Learning goals  
2. Session structure  
3. Time allocation  

---

### ✅ Observe

- Logical ordering  
- Missing vs complete steps  

---

## Part 4: ReAct Prompting (Reasoning + Action)

### Concept Recap

ReAct combines:
- Internal reasoning  
- External or simulated actions  

Pattern:  
**Reason → Act → Observe → Refine**

Ideal for:
- Multi-step tasks  
- Dynamic decision-making  

---

### Exercise 7: Basic ReAct Style Prompt

You are solving a problem using reasoning and actions.

Task: Decide the best laptop for a college student.

Steps:
1. Reason about key requirements  
2. Take an action by identifying possible options  
3. Evaluate the options  
4. Provide a final recommendation  

---

### ✅ Observe

- How reasoning evolves  
- How decisions depend on previous steps  

---

### Exercise 8: ReAct for Research-Like Tasks

You are an assistant performing step-by-step reasoning and actions.

Goal: Recommend the best programming language for a beginner.

Instructions:
- Reason about learning difficulty, job demand, and use cases  
- At each step, reassess before making a final decision  

---

### ✅ Why ReAct Shines

- Research  
- Tool-assisted workflows  
- Autonomous agents  
- Troubleshooting  

---

## Part 5: Integrated Hands-On Challenges

### Task 1: Example-Driven + Few-Shot

Provide three examples that demonstrate how to summarize  
technical text for non-technical users.  
Then summarize the given paragraph using the same style.

---

### Task 2: Few-Shot + Chain-of-Thought

Using provided examples with reasoning,  
solve the following multi-step word problem.  
Explain reasoning briefly before the answer.

---

### Task 3: ReAct Full Workflow

Act as a project planning assistant.

Steps:
1. Reason about the project requirements  
2. Identify actions needed to deliver the project  
3. Evaluate risks  
4. Refine the plan  
5. Present the final output as a checklist  

---

## Wrap-Up Reflection

- Which technique improved accuracy the most?  
- When did examples outperform instructions?  
- How did reasoning visibility affect trust?  
- Where would ReAct be useful in your work?  

---

## Learning Outcomes

After completing this lab, you can:
- ✅ Design effective example-driven prompts  
- ✅ Apply few-shot prompts with reasoning  
- ✅ Use Chain-of-Thought safely for complex problems  
- ✅ Apply ReAct prompts to real-world workflows  

---
