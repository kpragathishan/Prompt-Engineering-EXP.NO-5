# Ex.No.5 – Comparative Analysis of Different Types of Prompting Patterns and Explain with Various Test Scenarios

## AIM

To study and analyze different types of prompting patterns used in Prompt Engineering and evaluate their behavior using various test scenarios and use cases.

---

# 1. Zero-Shot Prompting

## Definition

Zero-shot prompting is a prompting technique where the AI model performs a task without any prior examples. The instruction alone is provided.

---

## Scenario 1 – Text Summarization

### Prompt:

“Summarize the importance of renewable energy in 50 words.”

### Output:

Renewable energy helps reduce pollution, conserve natural resources, and minimize global warming. Sources like solar and wind energy provide sustainable power for future generations while reducing dependence on fossil fuels.

---

## Scenario 2 – Code Generation

### Prompt:

“Write a C program to check whether a number is prime.”

### Output:

```c
#include<stdio.h>

int main() {
    int n, i, flag = 0;

    printf("Enter a number: ");
    scanf("%d", &n);

    if(n <= 1)
        flag = 1;

    for(i = 2; i <= n/2; i++) {
        if(n % i == 0) {
            flag = 1;
            break;
        }
    }

    if(flag == 0)
        printf("Prime Number");
    else
        printf("Not Prime");

    return 0;
}
```

---

# 2. Few-Shot Prompting

## Definition

Few-shot prompting provides a few examples before asking the AI to perform a similar task.

---

## Scenario 1 – Sentiment Classification

### Prompt:

Positive: “The movie was amazing.”
Negative: “The food was terrible.”
Classify: “The phone battery life is excellent.”

### Output:

Positive

---

## Scenario 2 – Language Translation

### Prompt:

English: Hello → Tamil: வணக்கம்
English: Thank You → Tamil: நன்றி
English: Good Morning → Tamil: காலை வணக்கம்

### Output:

Tamil: காலை வணக்கம்

---

# 3. Chain-of-Thought Prompting

## Definition

Chain-of-Thought prompting encourages the AI to explain intermediate reasoning steps before giving the final answer.

---

## Scenario 1 – Mathematical Problem

### Prompt:

“A train travels 60 km in 1 hour. How far will it travel in 5 hours? Explain step-by-step.”

### Output:

Speed of train = 60 km/hour
Time = 5 hours

Distance = Speed × Time

Distance = 60 × 5 = 300 km

---

## Scenario 2 – Logical Reasoning

### Prompt:

“If all fruits are healthy and apples are fruits, are apples healthy? Explain.”

### Output:

All fruits are considered healthy.
Apples belong to the category of fruits.
Therefore, apples are healthy.

---

# 4. Role-Based Prompting

## Definition

Role-based prompting assigns a specific role or identity to the AI before asking a question.

---

## Scenario 1 – Teacher Perspective

### Prompt:

“You are a mathematics teacher. Explain Pythagoras theorem to a school student.”

### Output:

Pythagoras theorem states that in a right-angled triangle, the square of the hypotenuse is equal to the sum of the squares of the other two sides.

a² + b² = c²

This theorem is useful in geometry and distance calculations.

---

## Scenario 2 – Career Advisor

### Prompt:

“You are a career advisor. Suggest skills for first-year EEE students.”

### Output:

First-year EEE students should learn:

* Basic C programming
* Electrical circuit fundamentals
* Communication skills
* MATLAB basics
* Embedded systems introduction
* Problem-solving techniques

---

# 5. Comparative Analysis Prompting

## Definition

Comparative Analysis prompting compares two or more systems, technologies, or products based on features and performance.

---

## Scenario 1 – AI Chatbots

### Prompt:

“Compare ChatGPT, Gemini, and Claude based on accuracy, simplicity, and response quality.”

### Output:

| AI Platform | Accuracy  | Simplicity | Response Quality |
| ----------- | --------- | ---------- | ---------------- |
| ChatGPT     | High      | Very Easy  | Excellent        |
| Gemini      | High      | Easy       | Very Good        |
| Claude      | Very High | Moderate   | Good             |

---

## Scenario 2 – Programming Languages

### Prompt:

“Compare C and Python for beginners.”

### Output:

| Feature        | C                  | Python               |
| -------------- | ------------------ | -------------------- |
| Syntax         | Complex            | Simple               |
| Speed          | Faster             | Moderate             |
| Learning Curve | Medium             | Easy                 |
| Usage          | System Programming | AI & Web Development |

---

# 6. Instruction-Based Prompting

## Definition

Instruction-based prompting gives direct and clear instructions to perform a task.

---

## Scenario 1 – Email Writing

### Prompt:

“Write a professional leave letter for two days.”

### Output:

Subject: Leave Request

Respected Sir/Madam,

I request leave for two days due to personal reasons. Kindly grant me permission.

Thank you.

---

## Scenario 2 – Essay Writing

### Prompt:

“Write a short essay on Artificial Intelligence in 100 words.”

### Output:

Artificial Intelligence is a modern technology that enables machines to perform tasks intelligently. AI is used in healthcare, education, banking, and entertainment. It improves automation, decision-making, and user experience. Technologies like chatbots, recommendation systems, and self-driving cars are examples of AI applications. AI helps reduce human effort and increases productivity. However, ethical concerns and job replacement issues should also be considered while developing AI systems responsibly.

---

# SUMMARY TABLE

| Prompting Pattern              | Purpose                          | Example Use Case    | Advantage                    |
| ------------------------------ | -------------------------------- | ------------------- | ---------------------------- |
| Zero-Shot Prompting            | Perform task without examples    | Text summarization  | Fast and simple              |
| Few-Shot Prompting             | Learn from examples              | Sentiment analysis  | Better accuracy              |
| Chain-of-Thought Prompting     | Step-by-step reasoning           | Mathematics         | Improves logical explanation |
| Role-Based Prompting           | Generate role-specific responses | Teacher or advisor  | Context-aware answers        |
| Comparative Analysis Prompting | Compare systems/products         | AI tools comparison | Detailed evaluation          |
| Instruction-Based Prompting    | Execute direct commands          | Letter writing      | Clear and precise output     |

---

# COMPARISON TABLE

| Prompt Type                    | Accuracy | Coherence | Simplicity | Reasoning Ability | User Experience |
| ------------------------------ | -------- | --------- | ---------- | ----------------- | --------------- |
| Zero-Shot Prompting            | 4/5      | 4/5       | 5/5        | 3/5               | Very Good       |
| Few-Shot Prompting             | 5/5      | 5/5       | 4/5        | 4/5               | Excellent       |
| Chain-of-Thought Prompting     | 5/5      | 5/5       | 3/5        | 5/5               | Excellent       |
| Role-Based Prompting           | 4/5      | 5/5       | 5/5        | 4/5               | Very Good       |
| Comparative Analysis Prompting | 5/5      | 4/5       | 4/5        | 4/5               | Excellent       |
| Instruction-Based Prompting    | 4/5      | 5/5       | 5/5        | 3/5               | Very Good       |

---

# RESULT

Thus, the different types of prompting patterns such as Zero-Shot Prompting, Few-Shot Prompting, Chain-of-Thought Prompting, Role-Based Prompting, Comparative Analysis Prompting, and Instruction-Based Prompting were successfully analyzed and explained using various test scenarios and use cases.
