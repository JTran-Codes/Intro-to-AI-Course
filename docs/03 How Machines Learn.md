# Chapter 3: How Machines Learn

**You’ll be able to:**
- Describe supervised learning as **A → B** mapping
- Outline the ML workflow end-to-end
- Recognize strengths and limits

## A → B Mapping (Supervised Learning)
- Train on pairs of **Input (A)** and **Output (B)** to predict B for new A.
- Examples:
  - Email: A = email text/meta → B = spam/not spam  
  - Speech: A = audio → B = transcript  
  - Vision: A = image → B = defect/no defect

## Why define A and B clearly?
“Garbage in, garbage out.” Poorly framed problems or mislabeled data poison learning.

## Typical Workflow
1. Define A & B  
2. Collect/label data  
3. Choose model  
4. Train (minimize loss)  
5. Validate on unseen data  
6. Deploy & monitor

## Strengths vs Weaknesses
- **Strengths:** learns complex patterns, scales, improves with more/better data
- **Limits:** needs data; can overfit; may inherit bias; struggles outside training distribution

## Review
- In your own words: What is supervised learning?  
- Why evaluate on data the model never saw?  
- Define **overfitting** with an example.

## Mini-Assignment: Flashcard Simulation
Create 10 examples (A,B) for a simple task (e.g., fruit type). Hide B, predict from A, then compare. Which features mattered? What new data would help?
