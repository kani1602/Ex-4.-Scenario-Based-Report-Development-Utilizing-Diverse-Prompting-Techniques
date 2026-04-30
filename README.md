# Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques

## Aim: 
Objective: The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.

## Algorithm: 
The algorithm used in the **Retail AI Chatbot Experiment** follows a structured, multi-phase approach to optimize conversational performance through strategic prompt engineering

## AI Chatbot Optimization Algorithm

### 1. Architectural Persona Setup (Role-Play)
The system initializes the agent by assigning a specific professional persona, such as "Aria" or a "concierge"
*   **Input:** System-level instructions for high-end brand representation
*   **Logic:** Define the greeting, tone consistency, and specific triggers for human intervention

### 2. Reasoning Framework (Chain-of-Thought)
To prevent logical errors, the algorithm implements a step-by-step reasoning process
*   **Procedure:** The model validates SKU numbers and verifies purchase dates before interpreting policy.
*   **Goal:** Decrease "Policy Hallucinations" (e.g., accidental offers of free products) by enforcing logical nodes

### 3. Intent Classification (Few-Shot Prompting)
The system uses a small set of labeled examples to improve classification accuracy across diverse dialects.
*   **Examples:** Providing the model with 3–5 samples of specific intents like "Tracking," "Inventory," or "Returns.
*   **Outcome:** Improved routing of customer inquiries to the correct resolution path

### 4. Boundary Enforcement (Constraint Prompting)
Safety parameters are applied to keep the AI focused on retail support.
*   **Logic:** Negative prompts are used to explicitly forbid topics such as politics.
*   **Goal:** Ensure system safety and brand-aligned customer experiences.

---

## Technical Integration Logic
The report recommends a **Hybrid Prompting Strategy** for final deployment:
*   **Triage:** Use **Meta Llama 3** for high-speed initial tracking and sorting.
*   **Complex Disputes:** Escalate to **Claude 3.5** for empathetic recovery and technical refund disputes
*   **Data Analysis:** Use **Gemini 1.5 Pro** for large-scale analysis of historical customer logs and pattern recognition

  
## Prompt:

The **Retail AI Experiment** uses a multi-layered logic to replace basic keyword-based bots with a high-reasoning system. 

### The 4-Step Prompt Algorithm
*   **Role-Play (Persona):** Sets the AI as a "concierge" to ensure the brand's tone is consistent and empathetic.
*   **Chain-of-Thought (Logic):** Forces the AI to verify SKUs and dates step-by-step *before* suggesting a solution[ This cut policy errors by **96%**
*   **Few-Shot (Learning):** Uses a few specific examples (e.g., tracking or returns) to help the AI categorize complex customer requests accurately.
*   **Constraints (Safety):** Applies strict "negative prompts" to prevent the AI from discussing off-topic or unsafe subjects.



### Strategic Results
*   **Performance:** Achieved an **89% resolution rate** compared to 58% for standard bots.
*   **Efficiency:** Average response time dropped to **1.1 seconds**.
*   **The "Hybrid" Setup:** The report recommends using **Llama 3** for speed, **Claude** for complex empathy, and **Gemini** for back-end data analysis.
## Output:
[PE ex 4.pdf](https://github.com/user-attachments/files/27228951/PE.ex.4.pdf)

## Result:
The experiment achieved a **95–96% groundedness score** and an **89% resolution rate** by using advanced prompting to cut policy errors by **96%**[cite: 5, 6].
