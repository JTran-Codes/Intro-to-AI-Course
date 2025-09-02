# Chapter 1: AI Landscape & Key Terms

**After this chapter, you can:**
- Define AI, ML, DL, Generative AI, LLMs, and Chatbots
- Explain prompts, inputs, outputs, tokens, and context limits
- Visualize how these concepts nest together

---

## What is Artificial Intelligence (AI)?
AI is the science of making machines perform tasks that typically require human intelligence (understanding speech, recognizing images, making decisions).
> François Chollet: “AI is automating intellectual tasks normally performed by humans.”

**Examples:** Self-driving perception, Siri/Alexa, chess engines.

---

## What is Machine Learning (ML)?
A subset of AI where algorithms **learn from examples** to map **Input (A) → Output (B)** instead of following hard-coded rules.
> Arthur Samuel (1953): “Gives computers the ability to learn without being explicitly programmed.”

**Examples:** Netflix recommendations; email spam filters.

---

## What is Deep Learning (DL)?
A subset of ML using multi-layer **neural networks** that learn complex patterns from large data. DL powers recent breakthroughs in vision, speech, and language.

**Analogy:** If AI is all medicine and ML is cardiology, DL is a specialized surgical technique within cardiology.  
**Example:** Facial recognition trained on millions of images.

---

## What is Generative AI?
Models that **create new content**—text, images, audio, code—based on patterns learned from data. You provide a **prompt**; the system produces a novel output.

**Examples:**  
- “A purple robot eating ice cream in space” → an AI image  
- ChatGPT drafts an email from your instructions

---

## What are Large Language Models (LLMs)?
A type of generative AI focused on **language** (e.g., GPT-4, Claude, Gemini, LLaMA). Trained on huge text corpora with billions of parameters to predict the **next token** in context. They can summarize, translate, answer, write, and code.

**Chatbots** (like ChatGPT) are applications built on LLMs and fine-tuned (e.g., RLHF) to follow instructions safely and helpfully.

---

## Prompts, Inputs, Outputs
- **Prompt:** Your instruction (e.g., “List 3 ML benefits in healthcare.”)
- **Input:** Prompt **plus** any supplied context (docs, data, images)
- **Output:** The generated result (text, code, image, etc.)

**Tip:** Clear, specific prompts → better outputs.

---

## Tokens & Context Limits
Models process **tokens** (chunks of text). Each request has a **max token** window shared by input + output. Exceed it, and the model may drop early context or truncate responses. Larger models support bigger windows, but **conciseness** still helps quality and cost.

---

## ANI vs AGI (Preview)
- **Artificial Narrow Intelligence (ANI):** Excellent at one task/domain (today’s systems)
- **Artificial General Intelligence (AGI):** Hypothetical human-level, broad intelligence (does **not** exist today)

We go deeper in Chapter 2.

---

## Putting It Together (Hierarchy)
**AI** ⟶ **ML** (learning from data) ⟶ **DL** (neural networks).  
**Generative AI** often uses DL to synthesize new data.  
**LLMs** are DL models specializing in language.  
**Chatbots** are apps powered by LLMs.  
You interact using **prompts**, within **token** limits.

---

## Review
1) Define AI, ML, DL, Generative AI, LLMs, Chatbots in your own words.  
2) What’s the difference between a **prompt** and the **input**?  
3) What are **tokens** and **context limits** and why do they matter?

---

## Mini-Assignment: Prompt & Analyze
**Goal:** Design a prompt, inspect output, reflect on token use.

1. Pick a task (e.g., “Suggest 5 fun names for a chocolate-dessert café, each with a tagline.”)  
2. Submit your prompt to an LLM and save:
   - Your prompt (input)
   - The AI’s output
3. Analyze:
   - Approx. tokens used; was the output on-spec?
   - What was vague? What constraints were missing?
4. Revise your prompt to be clearer/shorter. Re-run and compare:
   - Output quality improved?
   - Fewer tokens? Better relevance?
5. Reflect: One sentence on what changed and why.

> Keep your work in a folder like: `/docs/assets/assignments/ch1/`
