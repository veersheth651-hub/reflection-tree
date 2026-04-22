
Reflection Tree Assignment

 Overview
This project is a deterministic reflection tool using a decision tree.

It explores:
1. Locus of Control  
2. Contribution  
3. Scope of Impact  

Design

#Questions
The questions are designed to capture real behavior through structured choices instead of free text.

Logic
- Decision nodes route based on signals  
- Each axis produces a reflection  
- Same input always gives same output (deterministic)  

Psychology
- Locus of Control (Rotter)  
- Growth mindset  
- Self-transcendence (Maslow)
  
Improvements
- Add scoring system  
- Improve reflection depth  
- Build UI
- 
Diagram

```mermaid
graph TD
START --> Q1 --> Q2 --> Q3 --> D1
D1 --> R1_HIGH --> B1
D1 --> R1_LOW --> B1
B1 --> Q4 --> Q5 --> Q6 --> D2
D2 --> R2_HIGH --> B2
D2 --> R2_MID --> B2
D2 --> R2_LOW --> B2
B2 --> Q7 --> Q8 --> Q9 --> D3
D3 --> R3_HIGH --> SUMMARY
D3 --> R3_MID --> SUMMARY
D3 --> R3_LOW --> SUMMARY
SUMMARY --> END
```
