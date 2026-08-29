# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

## Name: Sanjai L
## Register Number: 212223230184

## Aim

To test and compare how different prompting patterns respond to various prompts such as naïve prompts (broad or unstructured) and basic prompts (clear, refined, and structured) across multiple engineering problem-solving scenarios. Analyze the quality, accuracy, depth, clarity, feasibility, and usefulness of the generated responses.

---

## AI Tools Required

- ChatGPT

---

## Explanation

### Types of Prompting Patterns

### 1. Naïve Prompt

A naïve prompt is broad, simple, or unclear and provides very little context or instruction to the AI model.

### 2. Basic Prompt

A basic prompt is structured and refined. It clearly specifies:

- The task
- Expected output
- Format
- Context
- Constraints

Structured prompts help AI generate more accurate, relevant, and meaningful responses.

---

## Project Title

AI-Powered Security Vulnerability Scanner

---

## Problem Statement

Software developers may introduce security vulnerabilities into applications without identifying them before deployment. Manual security testing can be time-consuming and requires specialized knowledge.

The project aims to develop an AI-assisted security vulnerability scanner that analyzes source code, identifies potential security weaknesses, explains the vulnerabilities, and provides practical remediation suggestions.

---

## Test Scenarios

The following engineering scenarios were selected from the project:

1. Identifying Security Vulnerabilities
2. Explaining a Detected Vulnerability
3. Recommending Security Remediation
4. Prioritizing Security Vulnerabilities

For each scenario:

- A naïve prompt was tested.
- A basic prompt was tested.
- Responses were analyzed based on:
  - Quality
  - Accuracy
  - Depth
  - Clarity
  - Feasibility
  - Usefulness

---

# OUTPUT

## Scenario 1 - Identifying Security Vulnerabilities

| Prompt Type | Prompt | Output Summary |
|---|---|---|
| Naïve Prompt | Find security problems in this code. | Identified some possible security issues but provided limited reasoning and context. |
| Basic Prompt | Analyze the following Java code for security vulnerabilities. Identify each vulnerability, explain why it is dangerous, mention the affected code section, assign a severity level from Low to Critical, and suggest a secure alternative. Present the result in a table. | Generated a structured vulnerability analysis with explanations, severity levels, affected sections, and remediation suggestions. |

---

## Scenario 2 - Explaining a Detected Vulnerability

| Prompt Type | Prompt | Output Summary |
|---|---|---|
| Naïve Prompt | Explain SQL injection. | Provided a general explanation with limited project-specific context. |
| Basic Prompt | Explain SQL injection to a Java developer. Describe how it occurs when user input is directly included in SQL queries, provide a simple vulnerable example, explain the security impact, and show how PreparedStatement prevents the vulnerability. | Provided a clearer technical explanation with an example, security impact, and practical prevention method. |

---

## Scenario 3 - Recommending Security Remediation

| Prompt Type | Prompt | Output Summary |
|---|---|---|
| Naïve Prompt | How can I fix this security issue? | Provided general security recommendations with limited implementation details. |
| Basic Prompt | The scanner has detected a SQL injection vulnerability in a Java application. Explain the root cause, provide a secure Java implementation using PreparedStatement, identify why the original approach is unsafe, and list two additional preventive practices. | Generated a practical remediation approach with secure Java implementation and additional security practices. |

---

## Scenario 4 - Prioritizing Security Vulnerabilities

| Prompt Type | Prompt | Output Summary |
|---|---|---|
| Naïve Prompt | Which security issue should I fix first? | Provided a general recommendation based mainly on severity. |
| Basic Prompt | Prioritize the following vulnerabilities for a Java web application: SQL Injection, Cross-Site Scripting, Hardcoded Password, and Missing Input Validation. Rank them from highest to lowest priority using severity, exploitability, potential impact, and remediation urgency. Explain the reasoning for each ranking. | Produced a structured prioritization based on severity, exploitability, security impact, and remediation urgency. |

---

## Comparative Analysis Table

| Scenario | Prompt Type | Quality (1-5) | Accuracy (1-5) | Depth (1-5) | Clarity (1-5) | Feasibility (1-5) | Usefulness (1-5) | Overall Score |
|---|---|---:|---:|---:|---:|---:|---:|---:|
| Identifying Security Vulnerabilities | Naïve Prompt | 3 | 3 | 2 | 3 | 3 | 2 | 16 |
| Identifying Security Vulnerabilities | Basic Prompt | 5 | 5 | 5 | 5 | 5 | 5 | 30 |
| Explaining a Detected Vulnerability | Naïve Prompt | 3 | 3 | 2 | 3 | 3 | 3 | 17 |
| Explaining a Detected Vulnerability | Basic Prompt | 5 | 5 | 5 | 5 | 5 | 5 | 30 |
| Recommending Security Remediation | Naïve Prompt | 2 | 3 | 2 | 3 | 2 | 2 | 14 |
| Recommending Security Remediation | Basic Prompt | 5 | 5 | 5 | 5 | 5 | 5 | 30 |
| Prioritizing Security Vulnerabilities | Naïve Prompt | 3 | 3 | 2 | 3 | 3 | 3 | 17 |
| Prioritizing Security Vulnerabilities | Basic Prompt | 5 | 5 | 5 | 5 | 5 | 5 | 30 |

---

## Overall Score Comparison

| Scenario | Naïve Prompt | Basic Prompt |
|---|---:|---:|
| Identifying Security Vulnerabilities | 16 | 30 |
| Explaining a Detected Vulnerability | 17 | 30 |
| Recommending Security Remediation | 14 | 30 |
| Prioritizing Security Vulnerabilities | 17 | 30 |

<img width="749" height="309" alt="visual" src="https://github.com/user-attachments/assets/b8bf7069-17ff-40db-b371-5d0069b6748c" />

---

## Impact of Prompt Clarity

<img width="785" height="314" alt="ChatGPT Image May 13, 2026, 10_55_07 AM" src="https://github.com/user-attachments/assets/310710d9-ea3f-41ba-b7ee-a3a636c2f114" />

Prompt clarity had a significant impact on the quality and usefulness of the generated responses.

### Naïve Prompts

- Produced broad responses.
- Provided less project-specific information.
- Often lacked structured reasoning.
- Required additional clarification.
- Were less useful for direct engineering implementation.

### Basic Prompts

- Provided more relevant technical information.
- Produced structured outputs.
- Improved explanation quality.
- Generated practical remediation strategies.
- Made the responses easier to evaluate and implement.

---

## Findings

- Basic prompts consistently generated better responses than naïve prompts.
- Structured prompts improved:
  - Quality
  - Accuracy
  - Depth
  - Clarity
  - Feasibility
  - Usefulness
- Providing project context improved the relevance of the responses.
- Specifying the expected output format improved clarity.
- Adding constraints reduced vague responses.
- Asking for technical reasoning improved the depth of the responses.
- Security-related prompts benefited from specifying the programming language and application context.
- Naïve prompts were sufficient for simple conceptual questions but were less effective for engineering problem-solving.
- Basic prompts produced more actionable recommendations.
- Prompt clarity directly influenced the usefulness of ChatGPT's responses.

---

## Final Selected Prompting Technique

The Basic Prompt technique was selected as the most effective prompting technique for the engineering scenarios tested.

It performed better because it combines:

- Context
- Specific task definition
- Constraints
- Expected output
- Evaluation criteria
- Technical requirements

---

## Refined/Final Prompt

> Analyze the given source code for potential security vulnerabilities in the context of a Java application.
>
> Identify each vulnerability and provide:
>
> 1. Vulnerability name
> 2. Affected code section
> 3. Root cause
> 4. Security impact
> 5. Severity level from Low to Critical
> 6. Exploitation risk
> 7. Recommended remediation
> 8. Secure code alternative where applicable
>
> Present the findings in a structured table. Avoid claiming that a vulnerability is confirmed when the available code only indicates a potential weakness. Clearly distinguish between confirmed issues and potential issues.

---

## Engineering Validation

The generated responses were evaluated against standard software security principles.

The following aspects were considered:

- Whether the identified vulnerability was technically plausible.
- Whether the explanation matched the behavior of the code.
- Whether the suggested remediation addressed the actual root cause.
- Whether the severity classification was reasonable.
- Whether the recommendation could be implemented in a Java application.
- Whether the AI distinguished between confirmed and potential vulnerabilities.

The AI-generated recommendations should be validated using static analysis tools, secure coding guidelines, testing, and manual code review before being used in a production environment.

---

## Result

The comparative analysis of different prompting patterns was executed successfully. The experiment demonstrated that structured and refined prompts produce significantly better outputs in terms of quality, accuracy, clarity, depth, feasibility, and usefulness compared to naïve prompts.
