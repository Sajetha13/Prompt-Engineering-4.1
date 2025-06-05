# Prompt-Engineering 4.1  
## Experiment 4: Scenario-Based Report Development Utilizing Diverse Prompting Techniques  
### Lab Scenario: Smart Health Assistant System – *MediGuide*

**Name**: S Mohamed Ahsan  
**Register No**: 212223240089  

---

## Aim  
To design and train *MediGuide*, an AI-powered Smart Health Assistant system that assists elderly patients with chronic health conditions like diabetes, hypertension, and arthritis. The system should offer:

- Personalized health advice  
- Timely medication reminders  
- Daily well-being tips  
- Friendly emotional support  

MediGuide must understand natural language, adapt to user needs, and deliver safe, compassionate, and context-aware responses.

---

## Objective  
To demonstrate how diverse AI prompting techniques improve the conversational abilities of *MediGuide* across multiple health-related use cases.

---

## Prompting Techniques Used  
1. Zero-Shot Prompting  
2. Few-Shot Prompting  
3. Chain-of-Thought Prompting  
4. Role-Based Prompting  
5. Multi-Modal Prompting  

---

## Algorithm / Procedure  
1. **Identify Use Cases** – Understand common health-related queries from elderly users.  
2. **Select Prompting Techniques** – Match each scenario with an appropriate prompting strategy.  
3. **Design Prompts** – Create realistic and effective prompt examples.  
4. **Evaluate Outputs** – Analyze chatbot responses for clarity, empathy, and safety.  
5. **Refine Prompts** – Adjust phrasing and strategy based on feedback.  
6. **Document Findings** – Summarize insights from each technique.

---

## 1. Zero-Shot Prompting  
**Use Case**: Giving general health advice to diabetic patients.  
**Prompt**:  
> "Provide a health tip for an elderly diabetic patient."  

**Output**:  
> "Make sure to check your blood sugar levels regularly and avoid skipping meals. Include fiber-rich foods and stay hydrated."

**Explanation**:  
Zero-shot prompting helps test AI’s general understanding without any prior examples.

**Alternate Example**  
**Prompt**:  
> "List symptoms of high blood sugar."  

**Output**:  
> "Common symptoms of high blood sugar include increased thirst, frequent urination, fatigue, blurred vision, and slow-healing wounds."

---

## 2. Few-Shot Prompting  
**Use Case**: Responding to symptom-related questions.  
**Prompt**:
> 'I have a headache.' → 'Make sure you're well-hydrated and rest in a quiet, dark room. If it persists, consult your doctor.'
> 'My knee hurts.' → 'Try applying a warm compress and avoid putting too much pressure on it today.'
Now respond to: 'I feel dizzy in the morning.'

**Output**:  
> "Dizziness in the morning can be due to low blood pressure or dehydration. Try getting up slowly and drinking water. If it continues, consult a healthcare professional."

**Explanation**:  
Few-shot prompting improves accuracy by showing example interactions.

**Additional Example**  
**Prompt**:
Q: What is a good health tip for diabetes?
A: Stay hydrated and monitor your blood sugar regularly.

Q: Give me a daily diabetes tip.
A: Eat balanced meals with consistent carbohydrate intake.


**Output**:  
> "Remember to check your feet daily for any sores or changes, as diabetes can affect circulation."

---

## 3. Chain-of-Thought Prompting  
**Use Case**: Handling complex situations like missed medications.  
**Prompt**:  
> "A patient forgot to take their blood pressure medication this morning. Think step-by-step to decide what advice to give."

**Output**:
1. Identify how late the dose is.  
2. If only a few hours, it may be safe to take it now.  
3. If close to the next dose, it may be better to skip it.  
4. Recommend contacting their healthcare provider for confirmation.

**Explanation**:  
Chain-of-thought prompting enables stepwise, logical decision-making.

**Alternate Prompt**:  
> "Let's think through this step by step: High blood pressure often has no symptoms..."

**Output**:  
> "High blood pressure is known as the 'silent killer' because it may not cause noticeable symptoms. Even if you feel fine, untreated hypertension can lead to heart attacks, strokes, and kidney damage over time. That’s why it’s important to take your medication regularly."

---

## 4. Role-Based Prompting  
**Use Case**: Providing emotional support.  
**Prompt**:  
> "You are a kind and empathetic health assistant for elderly users. Respond to this: 'I feel lonely and tired today.'"

**Output**:  
> "I'm really sorry you're feeling this way. You’re not alone — I’m here to talk anytime. Maybe a short walk, some music, or calling a loved one could lift your mood a little. Would you like me to suggest a calming activity?"

**Explanation**:  
Role-based prompting enhances empathy and relatability in responses.

**Alternate Prompt**:  
> "You are a compassionate digital health coach. Provide emotional support and a simple pain management tip for arthritis."

**Output**:  
> "I understand how challenging arthritis can be. You're doing your best, and that matters. One tip that might help is applying a warm compress to sore joints—it can ease stiffness and improve flexibility."

---

## 5. Multi-Modal Prompting  
**Use Case**: Analyzing food or medication image inputs.  
**Prompt**:  
> *(Input: Image of a meal plate + Text: "Is this a good breakfast for a diabetic?")*

**Output**:  
> "This meal looks high in carbohydrates due to the white bread and fruit juice. For a diabetic-friendly breakfast, consider whole grain toast, a boiled egg, and unsweetened tea."

**Explanation**:  
Multi-modal prompting enables the assistant to respond based on visual data alongside text.

**Alternate Example**:  
**Prompt**:  
> *(Includes image of medication label + Text: "Can you tell me the dosage instructions on this label?")*

**Output**:  
> "This medication should be taken once daily with food. Be sure to follow your doctor’s instructions and not exceed the recommended dose."

---

## Output  
Each prompting technique was successfully applied to health support scenarios within the MediGuide system. The responses were context-aware, empathetic, and medically sound for managing chronic conditions.

---

## Result  
Using diverse prompting techniques significantly improves MediGuide's performance by enabling more relevant, accurate, and emotionally supportive responses tailored to elderly users' health needs. Each technique addresses different challenges—ranging from logical reasoning and context-awareness to emotional intelligence and visual understanding.
