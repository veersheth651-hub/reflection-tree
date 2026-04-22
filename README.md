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

