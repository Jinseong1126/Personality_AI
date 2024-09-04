# Personality_AI: Injecting and Analyzing Personality in GPT Models

This repository contains code for injecting and analyzing personality traits in large language models (LLMs) like GPT-3.5, GPT-4, and GPT-4o. Using the **Machine Personality Inventory (MPI)** and **Chain of Thought (CoT)** prompting techniques, this project explores the injection of personality traits based on the OCEAN (Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism) model.

## Project Overview

With the rapid advancement of LLMs, AI systems are now able to interact with humans in a more personalized and natural way. This project aims to inject personalities into LLMs to enable them to establish more trustworthy interactions with users. Specifically, by using CoT techniques and different prompting methods, we evaluate the effectiveness of personality injection and assess the LLMs' behavior based on the OCEAN personality model.

## Key Features

1. **Personality Injection and Evaluation (MPI and CoT prompting techniques)**:
   - Personality traits are injected using Naive, Auto, and P2 (Chain of Thought) prompting methods.
   - The **Machine Personality Inventory (MPI)** is used to evaluate the injected personalities based on the OCEAN (Big Five) personality model.

2. **Research on Multiple Personality Injection and Negative Traits**:
   - Further studies include injecting multiple OCEAN traits simultaneously and injecting specific traits in negative forms. For example, Openness and Neuroticism were positively injected while Conscientiousness, Extraversion, and Agreeableness were negatively injected.
   - The results show significant differences in MPI scores compared to the pre-injection state, highlighting the effectiveness of these injection methods.

3. **Targeting Personality Scores**:
   - A novel approach to personality injection was explored using adverbs (e.g., often, sometimes, mostly) to control the degree of personality traits. This allows for a more fine-tuned injection of traits by targeting specific personality scores.

4. **Integration with Quadrupedal Robot Project**:
   - This research is connected with a quadrupedal robot project that utilizes Vision Language Models (VLM) and LLMs for natural language-based interaction. The robot can predict user personality traits and adjust its behavior accordingly to improve human-robot interaction.