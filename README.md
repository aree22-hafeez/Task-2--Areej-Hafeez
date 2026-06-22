# Prompt Engineering Project 2 – Chain-of-Thought Reasoning & Self-Correction

## Overview

This project focuses on improving the reasoning ability of Large Language Models (LLMs) using Prompt Engineering techniques. The goal is to make the AI solve complex logic problems step by step instead of jumping directly to an answer.

The project uses Chain-of-Thought (CoT) prompting and a Self-Correction phase to improve accuracy, logical consistency, and reliability.

## Objectives

* Force the AI to think through problems step by step.
* Reduce incorrect answers caused by skipped reasoning.
* Add a self-review phase to detect and fix mistakes.
* Improve logical problem-solving performance.

## Key Concepts

### Chain-of-Thought (CoT) Reasoning

The model breaks a problem into smaller steps and solves it logically before giving the final answer.

### Self-Correction

Before generating the final answer, the model reviews its own reasoning, checks calculations, and verifies that all constraints are satisfied.

### Structured Output

The reasoning and final answer are separated using XML tags:

```xml
<reasoning>
Step-by-step solution
</reasoning>

<final_answer>
Final result
</final_answer>
```

## Project Workflow

### Phase 1: Extract Variables

* Identify important values, conditions, and constraints.

### Phase 2: Formulate Strategy

* Decide the best approach to solve the problem.

### Phase 3: Step-by-Step Computation

* Solve the problem in logical order.

### Phase 4: Verification

* Recheck calculations and reasoning for errors.

### Self-Correction Phase

* Review the entire solution.
* Detect mistakes or missing constraints.
* Correct errors before generating the final answer.

## Examples Used

* Bridge Crossing Puzzle
* Hat Color Logic Puzzle
* Cheryl's Birthday Problem

These examples were used to test the model's reasoning, deduction, and validation abilities.

## Results

The structured prompting approach helped the model:

* Solve logic problems more accurately.
* Reduce reasoning errors.
* Verify answers before responding.
* Produce more reliable outputs.

## Skills Demonstrated

* Chain-of-Thought Prompting
* Self-Correction Techniques
* Logical Reasoning
* Problem Solving
* Output Control
* AI Evaluation

