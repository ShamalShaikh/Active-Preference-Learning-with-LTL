# Active-Preference-Learning-with-LTL
Description: An active preference learning framework that translates human preferences into LTL formulas for formal validation before execution.


## Overview:
This project explores Active Preference Learning combined with Linear Temporal Logic (LTL) to enable robots to learn, generalize, and verify human-like preferences in dynamic environments. By leveraging Büchi Automata, Product MDPs, and value iteration, the system ensures that autonomous agents execute tasks safely, efficiently, and in compliance with learned constraints.


## Key Features:
Active Learning for Preferences: Uses counterfactual reasoning to iteratively refine user preferences through interactive queries.
LTL-Based Formal Verification: Translates learned preferences into LTL formulas, ensuring task safety and correctness.
Trajectory Optimization: Computes optimal paths using Product MDPs and value iteration, integrating preference constraints.
Real-World Simulations: Tested in PyBullet and OpenStreetMap, evaluating generalization under constraints like traffic and elevation.
Scalable & Adaptive: Enables robots to dynamically adjust to new environments while ensuring compliance with user-defined constraints.


## Tech Stack:
PyBullet | OSMnx | OpenStreetMap API | Reinforcement Learning | LTL | Büchi Automata | Product MDP | Value Iteration | LLM-based Specification Learning | Model Checking


## How It Works:
Environment Setup: Simulates navigation tasks with static/dynamic obstacles.
Active Learning: Queries users for trajectory preferences and encodes them as LTL rules.
Planning & Verification: Converts LTL formulas into Büchi Automata, integrates them into Product MDPs, and computes optimal trajectories.
Feedback Loop: Refines learned preferences based on user input and execution results.
Evaluation: Tests generalization across diverse, ambiguous environments.


## Results & Future Work:
Benchmarked against state-of-the-art preference learning models for efficiency and generalization.
Future plans include expanding to multi-task environments (e.g., AI2-THOR) and benchmarking real-world robotics applications.

## Why It Matters:
This project enables AI-powered human-aligned decision-making for autonomous systems, making them safer, more interpretable, and adaptable in robotics, autonomous navigation, and assistive technologies.
