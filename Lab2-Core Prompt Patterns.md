# 🧪 Hands-On Lab: Core Prompt Patterns

---

## Objective
Learn how prompt patterns bring structure, consistency, and reliability to LLM outputs by applying common patterns such as Persona, Question Refinement, Reasoning Checks, and Output Adaptation in real tasks.

---

## Prerequisites
- Access to an LLM (ChatGPT / Gemini / Claude / etc.)
- Completion of “Foundations of Prompt Engineering” (recommended)

---

## Part 1: Introduction to Prompt Patterns

### Exercise 1: Why Patterns Improve Consistency

#### Step 1: Use an unstructured prompt
Give advice on improving team productivity.

Run this prompt twice.

#### Step 2: Use a patterned prompt
Act as an organizational productivity expert.  
Provide 5 practical strategies to improve team productivity  
for a software development team.  
Present the output as numbered bullet points.

### Observe
- Variability between runs  
- Structure and clarity  
- Ease of reuse  

### Key Insight
Prompt patterns reduce randomness and guessing by the model.

---

## Part 2: Prompt Patterns as Templates

### Exercise 2: Reusability Through Templates

You will reuse the same structure with different inputs.

#### Template Prompt
Act as a [ROLE].  
Your task is to [TASK].  
The audience is [AUDIENCE].  
Provide the output in [FORMAT].

#### Fill it in (Example 1)
Act as a data analyst.  
Your task is to summarize the following report.  
The audience is business executives.  
Provide the output as 5 bullet points.

#### Fill it in (Example 2)
Act as a teacher.  
Your task is to explain climate change.  
The audience is middle school students.  
Provide the output in simple language.

### Takeaway
- Same pattern, different tasks  
- Minimal effort, consistent results  

---

## Part 3: Core Prompt Pattern – Persona Pattern

### Exercise 3: Applying the Persona Pattern

#### Prompt A (No persona)
Explain blockchain technology.

#### Prompt B (Persona applied)
Act as a financial technology expert.  
Explain blockchain technology to non-technical business leaders  
using simple language and one real-world example.

### Compare
- Tone  
- Depth  
- Relevance  

### When to Use Persona Pattern
- Domain-specific tasks  
- Tone control  
- Avoiding generic answers  

---

## Part 4: Core Prompt Pattern – Question Refinement Pattern

### Exercise 4: Refining a Vague Question

#### Step 1: Start with a vague question
How can AI help my company?

#### Step 2: Use question refinement
I want to ask a question about using AI in my organization.  
Rewrite my question to be more specific and actionable.  
Ask clarifying questions if needed before answering.

#### Step 3: Use the refined question
Use the AI’s improved question as your actual prompt.

### Observe
- How refining the question improves output quality  
- Reduced ambiguity  

### When to Use Question Refinement
- Early exploration  
- Poorly defined problems  
- Complex decision-making  

---

## Part 5: Core Prompt Pattern – Checking Reasoning

### Exercise 5: Reasoning and Logic Validation

#### Prompt without reasoning
Which is a better option: public cloud or on-premise servers?

#### Prompt with reasoning check
Compare public cloud and on-premise servers.  
Explain your reasoning step by step before giving a conclusion.

### Observe
- Transparency in decision-making  
- Logical flow  
- Reduced “guessy” answers  

### When to Use Reasoning Checks
- Decisions  
- Trade-off analysis  
- Planning and strategy  

---

## Part 6: Core Prompt Pattern – Output Adaptation

### Exercise 6: Same Content, Different Outputs

#### Step 1: Generate base content
Explain the benefits of remote work.

#### Step 2: Adapt output for different audiences

**For Executives**  
Adapt the previous explanation into a concise executive summary  
focused on business impact.

**For Employees**  
Adapt the explanation into a friendly internal announcement  
for employees.

**For HR Documentation**  
Adapt the explanation into formal HR policy language.

### Key Learning
- Output style is a controllable variable  
- Same
